# Ziggurat

This is a personal solution to a problem I've encountered working with energy consumption inside a factory.

This script is to process a data batch from SMART32 software. This software is a management software responsible to receive data from demand controllers installed in electrical substations. The problem is to make the data batch something that give to us information about the behavior of every circuit and then, use this processed data batch to reach some conclusions about the machines and what the teams have to do (action plans to reduce energy consumption). 

SMART32 give to the user a batch of txt files of every circuit configurated previously there. The Ziggurat script is to process the data batch to show the hourly consumption in kWh by each factory circuit. 

Some measures in this data batch are not direcltly receveived by the controllers itself. So, in this case, I need some math to calculate the virtual measure of some circuits there, based in the electrical structure. 
