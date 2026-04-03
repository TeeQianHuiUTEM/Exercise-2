
[
    {
        "id": "4a1a874ca23617f7",
        "type": "tab",
        "label": "Flow 1",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "5f1793b67a1a32c8",
        "type": "tab",
        "label": "Flow 2",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "59cd30595df3892c",
        "type": "http in",
        "z": "4a1a874ca23617f7",
        "name": " Receive Telemetry",
        "url": "/api/sensor",
        "method": "post",
        "upload": false,
        "skipBodyParsing": false,
        "swaggerDoc": "",
        "x": 310,
        "y": 260,
        "wires": [
            [
                "1a2a82536fb62662",
                "90d5e907b9d06e55"
            ]
        ]
    },
    {
        "id": "1a2a82536fb62662",
        "type": "http response",
        "z": "4a1a874ca23617f7",
        "name": " Response",
        "statusCode": "200",
        "headers": {},
        "x": 760,
        "y": 260,
        "wires": []
    },
    {
        "id": "90d5e907b9d06e55",
        "type": "debug",
        "z": "4a1a874ca23617f7",
        "name": "debug 1",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "true",
        "targetType": "full",
        "statusVal": "",
        "statusType": "auto",
        "x": 760,
        "y": 340,
        "wires": []
    },
    {
        "id": "569825cc7ebddad0",
        "type": "http in",
        "z": "5f1793b67a1a32c8",
        "name": " Receive Telemetry",
        "url": "/api/sensor",
        "method": "get",
        "upload": false,
        "skipBodyParsing": false,
        "swaggerDoc": "",
        "x": 210,
        "y": 180,
        "wires": [
            [
                "20ec8eaad6afdd6b",
                "32a24ca928130450"
            ]
        ]
    },
    {
        "id": "32a24ca928130450",
        "type": "function",
        "z": "5f1793b67a1a32c8",
        "name": "function 1",
        "func": "msg.payload = {\n    sensor_id: \"ESP32_01\",\n    temperature: 24.5,\n    humidity: 60\n};\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 480,
        "y": 180,
        "wires": [
            [
                "3601b6cffc95db4b"
            ]
        ]
    },
    {
        "id": "3601b6cffc95db4b",
        "type": "http response",
        "z": "5f1793b67a1a32c8",
        "name": " Response",
        "statusCode": "200",
        "headers": {},
        "x": 740,
        "y": 180,
        "wires": []
    },
    {
        "id": "20ec8eaad6afdd6b",
        "type": "debug",
        "z": "5f1793b67a1a32c8",
        "name": "debug 2",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "true",
        "targetType": "full",
        "statusVal": "",
        "statusType": "auto",
        "x": 740,
        "y": 320,
        "wires": []
    }
]
