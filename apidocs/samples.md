# Group 契約者

Resources related to samples in the API.

## Question Collection [/samples]

### API Sample [GET]
+ Response 200 (application/json)

        [
            {
                "question": "Favourite programming language?",
                "published_at": "2014-11-11T08:40:51.620Z",
                "url": "/samples/1",
                "choices": [
                    {
                        "choice": "Swift",
                        "url": "/samples/1/choices/1",
                        "votes": 2048
                    }, {
                        "choice": "Python",
                        "url": "/samples/1/choices/2",
                        "votes": 1024
                    }, {
                        "choice": "Objective-C",
                        "url": "/samples/1/choices/3",
                        "votes": 512
                    }, {
                        "choice": "Ruby",
                        "url": "/samples/1/choices/4",
                        "votes": 256
                    }
                ]
            }
        ]
