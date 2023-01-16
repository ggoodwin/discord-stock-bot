<div align="center">
	<h1><img alt="Stock logo" src="https://github.com/octodiscord/stock-bot/blob/main/stock.png" height="300" /><br />
		Discord Crypto Bot
	</h1>

[![Go Reference](https://pkg.go.dev/badge/octodiscord/stock-bot.svg)](https://pkg.go.dev/github.com/octodiscord/stock-bot) [![Go Version](https://img.shields.io/github/go-mod/go-version/octodiscord/stock-bot)](https://go.dev/) [![GoReportCard](https://goreportcard.com/badge/github.com/octodiscord/stock-bot)](https://goreportcard.com/report/github.com/octodiscord/stock-bot) [![CodeFactor](https://www.codefactor.io/repository/github/octodiscord/stock-bot/badge)](https://www.codefactor.io/repository/github/octodiscord/stock-bot) [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/octodiscord/stock-bot/.github/workflows/go.yml)](https://github.com/octodiscord/stock-bot/blob/main/.github/workflows/go.yml) ![Size](https://img.shields.io/github/languages/code-size/octodiscord/stock-bot) [![Last Commit](https://img.shields.io/github/last-commit/octodiscord/stock-bot)](https://github.com/octodiscord/stock-bot/commits/main) [![License](https://img.shields.io/github/license/octodiscord/stock-bot)](https://github.com/octodiscord/stock-bot/blob/main/LICENSE)

</div>
<hr/>

## 🌟 How it works

We use the [`Yahoo!`](https://finance.yahoo.com/most-active) API to gather real time stock data.

## 📦 Installation and Usage

### Config File

Rename the `config.json.example` file to `config.json` and add your `Discord Token` and `Stock Ticker` to the file.

```json
{
	"DiscordToken": "Your Token Key",
	"CryptoTicker": "TSLA"
}
```

[Where to search for Stock Tickers](https://finance.yahoo.com/most-active)

### Go

Make sure you have `Go` installed on your machine.

You can check by running the following command in the `console`

```plain
go version
```

If you don't have `Go` installed, you can download it from [here](https://go.dev/dl/).

### Project setup

Run the following command in the `console`, in the `project directory`

Run the following command to install the dependencies

```plain
go get
```

Then run the following command to tidy the dependencies

```plain
go mod tidy
```

Then run the following command to build the bot

```plain
go build
```

### Project run

Run the following command to run the bot

```plain
./stock-bot
```

## 💻 Dependencies

- [bwmarrin's `DiscordGo`](https://github.com/bwmarrin/discordgo)
- [OctoLibs `Stocks`](https://github.com/octolibs/stocks)

## 🙇‍♂️ Issues and Contributing

If you find an issue with this library, please report an issue. If you'd
like, we welcome any contributions. Fork this library and submit a pull
request.

## ⚖️ License

This project is under the MIT License. See the [LICENSE](https://github.com/octodiscord/stock-bot/blob/main/LICENSE) file for the full license text.

## 📜 Changes

Check out our [CHANGELOG](https://github.com/octodiscord/stock-bot/blob/main/CHANGELOG.md)
