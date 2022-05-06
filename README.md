# Slack Age Calculator Bot
This is a project built with Golang. A simple api bot where one can slack message your birth year and the bot will calculate the age.


## Technologies Used
* Golang
* Slack


## Dependencies
* Install Go - https://go.dev/doc/install
* Install Slack - https://slack.com/

## Executing program
* Download the repository to your computer and go to project file
```
git clone https://github.com/sayedh/slack-age-bot
cd slack-age-bot
go mod init github.com/sayedh/slack-age-bot
go get "github.com/shomali11/slacker"
go mod tidy
code .
```
* Add your Bot Token and App Token into the main.go code
```
os.Setenv("SLACK_BOT_TOKEN", "xoxb-3471069331845-3486497002963-aFjL4NuK8ySEVBZr7rxJ4fGB")
os.Setenv("SLACK_APP_TOKEN", "xapp-1-A03F06X7PME-3486482695394-423d26ab1df055e3bf7f9333a84231a3c8e652ccc79a89519bd2d565365e5dc3")

```
* Add your Bot to your channel in slack

* Run the code
```
go run main.go
```

* Ask the Bot in Slack
```
Sayed Haque
@age-bot my yob is 1994


age-bot APP
age is 27

```
