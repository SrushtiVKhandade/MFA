### MFA user 
ADDING NEW USER IN IAM AND ENABLING MFA AUTHENTICATION
open iam
create user
give name and allow access
custom password
uncheck user must create new passwd
next
attach policies directly
Allow s3 full access
download .csv file
login as user 
check you can access only things that root user have permitted you to
### PROVIDING MFA AUTHETICATION
Open IAM Dashboard go to users
create access key and download .csv file
go to security credentials > assign MFA device
select authentication app
scan QR through google authenticator and enter codes
login with user credentials and mfa code
