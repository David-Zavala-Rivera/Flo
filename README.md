# Flow1
Creacion de flow 1 en NodeRED



[
    {
        "id": "f3bdc12314678684",
        "type": "tab",
        "label": "Flow 1",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "d357471f58a7b107",
        "type": "inject",
        "z": "f3bdc12314678684",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 140,
        "y": 120,
        "wires": [
            [
                "7a70e7b16da7333d"
            ]
        ]
    },
    {
        "id": "7a70e7b16da7333d",
        "type": "debug",
        "z": "f3bdc12314678684",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 350,
        "y": 120,
        "wires": []
    }
]
