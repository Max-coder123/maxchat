# maxchat

Command line streaming AI chat with conversation history.

### Usage

```none
cp .env.sample .env # and fill in your OpenAI key
pip install -r requirements.txt
python chat.py
```

### Example Conversation

```none
 ____    ____                _           ______  __              _
|_   \  /   _|              | |        .' ___  |[  |            / |_
  |   \/   |   ,--.   _   __\_|.--.   / .'   \_| | |--.   ,--. `| |-'
  | |\  /| |  `'_\ : [ \ [  ] ( (`\]  | |        | .-. | `'_\ : | |
 _| |_\/_| |_ // | |, > '  <   `'.'.  \ `.___.'\ | | | | // | |,| |,
|_____||_____|\'-;__/[__]`\_] [\__) )  `.____ .'[___]|__]\'-;__/\__/


> hello
Hello! How can I assist you today?
> what's 3+5?
3 + 5 equals 8.
> add 9 more
Adding 9 more to 8 gives you 17.
> what'd i just ask?
You asked to add 9 more to the result of 3 + 5, which was 8.
> thanks
You're welcome! If you have any more questions, feel free to ask.
```
