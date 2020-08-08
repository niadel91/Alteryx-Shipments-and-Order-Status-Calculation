# Shipments and Order Status Calculation


We have 2 input files: Open Orders and Shipments.

Flag the records in the Shipments file that have fully shipped and those where the Order still has Lines to ship.  Also, flag Lines as complete or partially shipped.

An Order can have more than one Line, and a Line can be partially shipped on more than one Shipment.  If an Order exists in the Open Orders file, then the Order has one or more Lines that still have quantity to ship.  

The Shipments file includes the number of shipped quantities (Qty) for each Order and Line number. 
