# ticketsonlinecfg
Configuration repository for the ticketsonlinemicrosvcs' configuration service.
At the moment Configuration Server requires that the master branch exist (or else a not very informative 404 comes).

In case of :

  http://localhost:8761/config/eventservice/default/

following will be returned :

name	"eventservice"
profiles	
0	"default"
label	null
version	"7b2bd9b18f14ee99abb7840582a1df934bb2e9a4"
state	null
propertySources	
0	
name	"/home/tamas/projektek/TicketsOnline/ticketsonlinecfg/eventservice-default.properties"
source	
parameter	"eventservice parameter value"
1	
name	"/home/tamas/projektek/TicketsOnline/ticketsonlinecfg/eventservice-default.yml"
source	
parameter	"eventservice parameter value"
2	
name	"/home/tamas/projektek/TicketsOnline/ticketsonlinecfg/eventservice.properties"
source	
parameter	"eventservice parameter value"
3	
name	"/home/tamas/projektek/TicketsOnline/ticketsonlinecfg/eventservice.yml"
source	
parameter	"eventservice parameter value"

