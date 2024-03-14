Slack File Uploader

This is a simple Go program that allows you to upload files to a specific Slack channel using the Slack API. It demonstrates how to authenticate with the Slack API, retrieve the necessary credentials from environment variables, and upload a file to a designated channel.

Features:

•	Upload one or more files to a Slack channel

•	Specify the target channel using the channel ID

•	Authenticate with the Slack API using a bot token

•	Print the name and URL of the uploaded file(s)

•	Handle errors during the file upload process

Prerequisites:

•	Go programming language installed on your system

•	A Slack bot token with file upload permissions

•	The ID of the target Slack channel

Usage:

1.	Clone the repository to your local machine.

2.	Set the SLACK_BOT_TOKEN and CHANNEL_ID environment variables with your Slack bot token and the target channel ID, respectively.

3.	Update the fileArr slice in the main.go file with the name(s) of the file(s) you want to upload.

4.	Build and run the Go program.

Command 

go build ./slack-file-upload

The program will attempt to upload the specified file(s) to the designated Slack channel. If the upload is successful, it will print the name and URL of the uploaded file(s). If there's an error, it will print the error message.


![1](https://github.com/miteshgaonkar/slack-file-upload-bot/assets/56105301/c75f3187-4c2b-4e5d-b750-a528e6932314)

![2](https://github.com/miteshgaonkar/slack-file-upload-bot/assets/56105301/e385d5b9-1cbf-4835-a3f1-1f594a6abcf5)

![3](https://github.com/miteshgaonkar/slack-file-upload-bot/assets/56105301/ce3e71d1-6a02-4750-999c-aed8494c873e)



