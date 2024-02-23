# Use-case Diagram

<code-block lang="plantuml">
    <![CDATA[
    @startuml
        User << Human >>
        :Main Database: as MySql << Application >>
        (Start) << One Shot >>
        (Use the application) as (Use) << Main >>
        User -> (Start)
        User --> (Use)
        MySql --> (Use)
    @enduml
    ]]>
</code-block>

