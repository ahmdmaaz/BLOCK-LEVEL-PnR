# BLOCK-LEVEL-PnR-
TECHNOLOGY NODE = 28nm  / 32nm
FLOW OF PnR
  1.DIRECTORY STRUCTURE 
  2.CREATING SOFT LINK OF THE DESIGN INPUT FILES
  3.OPEN DESIGN INPUT FILES AND UNDERSTAND THEM
  4.
  5.
  6.FLOORPLAN
     1.CORE UTILIZATION =.7
     2.ASPECT RATIO = 1
     3.CORE OFFSET = 10
     4.SITE DEFINATION = UNIT 
     5.SITE ROW USE
     6.
  7.PORT PLACEMENT (USING ROUTING BLOCKAGE METHOD ALSO)
     1.INPUT PORTS 
        1.M5 M7 
        2.SIDE 1
        3.CORNER KEEPOUT = 100um
        4.PIN SPACING TRACK = 5 
        
     2.OUTPUT PORTS
        1.M5 M7
        2.SIDE 3
        3.PIN SPACING MIN TRACK = 5 um
        4.CORNER KEEPOUT = 100um
        
     3.CLOCK PORTS
        1.M4 M6
        2.SIDE 2
        3.PIN SPACING 5
        4.CORNER KEEPOUT = 100um
        
   8.VOLATGE PLANNING
          
   9.VOLTAGE AREA CREATION
      1. UTILIZATION = .75
      2.GUARD BAND = 5.016um
   
   10.MACROPLACEMENT
      1.KEEP OUT MARGIN 3
      2.BLOCKAGES
   
   11.PHYSICAL ONLY CELLS PLACEMENT  
   
   12.POWERPLANNING
   
   13.CLOCK INFORMATION
   
   14. SCAN CHAIN INFORMATION

   15.PLACEMENT
   
   16.CLOCK TREE SYNTHESIS ....... day 24 line 158
      1.M4 & M5
      
      
   17.  
      
   
     
