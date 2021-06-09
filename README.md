# AWS-SNS-SMS with NodeJS

A quick example of sending an SMS with AWS SNS and NodeJS

.env file , add the aws credential
`AWS_ACCESS_KEY_ID=<> AWS_SECRET_ACCESS_KEY=<> AWS_REGION=<>`

Create a specific AWS IAM user and add to group 'AmazonSNSFullAccess'

`$ npm start`

Open browser and visit something like,

`http://localhost:3000/?message=[The Message]&number=[The Number]&subject=[The Subject]`

Remove the + character from mobile number country code

Then Visit

`http://localhost:3000/?message=my message&number=918899889988&subject=Sample subject`
