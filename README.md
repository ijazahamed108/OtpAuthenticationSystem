# OtpAuthenticationSystem

# OtpAuthenticationSystem

 NOTE: -  This is only a backend Flow.
  you can integrate this with client and send payload from userForm.
  
to start the project run npm start command from project folder

inside userController  use your own sms API to trigger sms 
once the App is started use post man to hit POST request

signUp :   localhost:3001//api/user/signup
           payload : {
                number : number
           }
           
verifyOtp: localhost:3001//api/user/signup/verify
           payload : {
                number : number,
                otp:otp
           }
           
           
 create a .env file and add follwing in it
MONGODB_URL_LOCAL=   use your connection string here
PORT =3001
JWT_SECRET_KEY=HJDUDHSIDejhfefHEjk
