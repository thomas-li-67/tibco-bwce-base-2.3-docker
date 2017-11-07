Scripts for customizing Docker images for TIBCO BusinessWorks™ Container Edition
=============================================================================
Use these scripts to generate a TIBCO BusinessWorks™ Container Edition (BWCE) 
2.x Docker Image using the BWCE runtime 
(available as bwce_cf.zip from edelivery.tibco.com) 

Prerequisite
=============================================================================
  * Access to https://edelivery.tibco.com.
  * Docker Installation (https://docs.docker.com/engine/installation/).
    
Download TIBCO BusinessWorks™ Container Edition Runtime
=============================================================================
Download TIBCO BusinessWorks™ Container Edition 2.x.x runtime file (bwce_cf.zip) 
from https://edelivery.tibco.com.
     
Create TIBCO BusinessWorks™ Container Edition Base Docker Image
=============================================================================
  * Copy bwce_cf.zip file to <BWCE-HOME>/docker/resources/bwce-runtime folder
  * On terminal, goto <BWCE-HOME>/docker and RUN: 'docker build -t <TAG-NAME> .'
  e.g. docker build -t tibco/bwce:latest .

Test TIBCO BusinessWorks™ Container Edition Base Docker Image
=============================================================================
  * Refer Sample documentation for Docker 

     
