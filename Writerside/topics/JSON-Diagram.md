# JSON Diagram

<code-block lang="plantuml">
    @startjson
    {
        "fruit":"Apple",
        "size":"Large",
        "color": ["Red", "Green"],
        "key": {
            "sub_key1": 1234,    
            "sub_key2": 1234,
            "sub_key3": {"name":"anon", "age":999},
            "sub_key4": [1, "2", null, "another", "array"]
        }
    }
    @endjson
</code-block>


