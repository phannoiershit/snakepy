# How to make custom speed file
First: make a file called customspeed.txt
Secondly: put JSON data to it
Example: 
```json
[
    {
        "label": "Easy Reimagined",
        "speed": 2,
        "color": [0, 255, 0] 
    },
    {
        "label": "Medium",
        "speed": 5,
        "color": [255, 165, 0] 
    },
    {
        "label": "Hard Reimagined",
        "speed": 10,
        "color": [255, 0, 0] 
    }
]
```
"label" : speed name

"speed": speed

"color" : speed color (array)

Thirdly : encode the JSON data into base64

Finally : put the encoded data into customspeed.txt and put it on the game folder

Then you are done!
