# send-digital-greetings-backend

This is a web application developed fornt-end using ReactJS and back-end using NodeJS and Express.<br>
The application's purpose is to allow sending email to multiple emails addresses using mailjet service.

### For Installation and Running
```sh
npm i
npm start
```

### `npm start`

Runs the back-end on port 9000.<br>
Open [http://localhost:9000](http://localhost:9000) to view it in the browser.

### `Deployed Herouko link`
https://send-digital-greetings-bend.herokuapp.com/

### API
`/email`  Post ( `{ recipients : arr[ { email: "str"} ] ,message: "str",subject: "str",}` )
