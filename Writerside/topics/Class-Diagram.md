# Class Diagram

<code-block lang="plantuml">
    <![CDATA[
    @startuml
        left to right direction
        enum User {
            id : int32
            ..
            other_id : uint16
            yet_another_id : uchar
        }
        struct AL {
            ..
            likes
            ==
            this
            --
            software
            ..
        }
        class Email {
            id : INTEGER
            ..
            user_id : INTEGER
            address : INTEGER
        }
        User::id *-- Email::user_id
        AL *-> User
    @enduml
    ]]>
</code-block>

