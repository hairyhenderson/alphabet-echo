# alphabet-echo 

A silly tool that echos a message with all the characters replaced with Slack's
new alphabet emoji.

## Running 

Docker: 

```
docker run --rm rfratto/alphabet-echo hello world!
```

Copy and paste the resulting text into Slack.

Or install from source (Go >=1.15 required):

```
GO111MODULE=on go get github.com/rfratto/alphabet-echo@main
```

And then run with:

```
alphabet-echo hello world!
```
