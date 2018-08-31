# Lutece docker demo site : Transparency

This site presents the plugin transparency that publish public appointments of elected officials and lobbies. The french Lobby list is automatically provided.
The users can have delegations to add appointments for an elected official.


## build the image

`docker build -t site-demo-transparency .`

All Lutece images are available at https://hub.docker.com/u/lutece/

## Launch the server


`docker run -p 80:8080 lutece/transparency`

## Connect to the server to see the service

'http://localhost/transparency'

## Add appointments
go to : http://localhost/transparency/jsp/site/Portal.jsp?page=meeting

and connect with login/pwd : test_user/test_user

## Back office management

http://localhost/tools/jsp/admin/AdminLogin.jsp

Connect to the back office with login/pwd : admin/transparency
