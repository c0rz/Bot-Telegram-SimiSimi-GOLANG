# Bot Telegram SimiSimi with Golang programming language
[![GoDoc](https://godoc.org/github.com/go-telegram-bot-api/telegram-bot-api?status.svg)](http://godoc.org/github.com/go-telegram-bot-api/telegram-bot-api)

<!-- ABOUT THE PROJECT -->
## About The Project

A Telegram Bot with automatic chat with its users (Indonesian *) via the API provided.<br/>
WARNING: Please change your country in the following url
```sh
https://api.simsimi.net/v1/?lang=CHANGE HERE&cf=%5BChatfuel%5D&text=" + strings.ReplaceAll(pesan, " ", "%20"
```
### Built With
* Go

### Installation

1. Clone the repo
```sh
git clone https://github.com/c0rz/bot-telegram-simi-simi.git
```
2. Install the support library
``` 
go get
```
3. Run File index.go
``` 
go run index.go
```

<!-- CONTRIBUTING -->
## Contributing
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b <add-your-new-branch-name>`)
3. Commit your Changes (`git commit -m 'commit message'`)
4. Push to the Branch (`git push origin <add-your-branch-name>`)
5. Open a Pull Request
