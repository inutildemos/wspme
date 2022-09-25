# Whatsapp Me

Is a simple button to be added to your website to allow the sytem to send you whatsapps.
Please note that this won't ask the visitor to log his/her whatsapp as other services would do.
This will just use your personal whatsapp to send you -in this example- whatever text the visitor wants to share.

# Setup

## 1.- Register on whin free tier service through rapidapi.com page. 

## 2.- Copy your RapidApiKey

## 3.- Insert the following line in your page:

 <script src="https://api.inutil.info/wh2/js?rapidapikey=<your_RapidApiKey" async defer type="text/javascript"></script>
 
## 4.- Add a form or input button to your page:

      <form>  
         <input type = "button" value = "WhatsappMe" onclick = "sendWhatsapp();" /> 
      </form>
      
## 5.- You're all set. You should receive a whatsapp anytime submits something.

