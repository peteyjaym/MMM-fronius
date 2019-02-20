# MMM-Fronius
A MagicMirror module that displays information from a fronius solar inverter, 
Tested with a fronius Symo inverter, 
This module shows solar output,  grid draw and total load,

Module is a quick and dirty modified version of MMM-json-feed by Amcolash,   all credit for the main code goes to him. 

This module works for me but may have many MANY bugs and errors, 

## Install
`cd MagicMirror/modules`
`git clone https://github.com/peteyjaym/MMM-fronius'

## Update
`cd MagicMirror/modules/MMM-fronius`
`git pull`

## Configuration
just add the inverter ip as shown below:

 {
    module: 'MMM-fronius',	
    position: 'top_center',	
    config: {
		
      ipaddfr:[
                'xx.xx.xx.xx', //inverter ip
        ],
}

no configuration is required as all values are hard coded into the main file,   just add your inverter ip.


NOTE:   This is a quick and dirty implimentation and is in no way optimised,  
i have no intention of performing any major updates/adding features but you never know 

