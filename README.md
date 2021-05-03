# IoT
For Raspberry Pi works with AWS IoT.
#### Change following parameters #### 
awshost = "xxx.iot.cn-northwest-1.amazonaws.com.cn"         # AWS IoT China Ningxia Endpoint
awsport = 8883                                              # Port no.   
clientId = "MyIotThing"                                     # Thing_Name
thingName = "MyIotThing"                                    # Thing_Name
caPath = "/home/pi/certs/AmazonRootCA1.pem"                 # Root_CA_Certificate_Name
certPath = "/home/pi/certs/certificate.pem.crt"             # <Thing_Name>.cert.pem
keyPath = "/home/pi/certs/private.pem.key"                  # <Thing_Name>.private.key
