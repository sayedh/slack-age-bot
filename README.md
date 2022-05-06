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
os.Setenv("SLACK_BOT_TOKEN", "<insert here>")
os.Setenv("SLACK_APP_TOKEN", "<insert here>")

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
