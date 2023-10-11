## IBM Cloud Code Engine

ibmcloud ce project current
theia@theiadocker-muabbasa8:/home/project$ ibmcloud ce project current
Getting the current project context...
OK

Name:       Code Engine - sn-labs-muabbasa8  
ID:         f74cead6-9255-4f37-89b1-3b2d262fdadc  
Subdomain:  18dz7epj37wr  
Domain:     us-south.codeengine.appdomain.cloud  
Region:     us-south  

Kubernetes Config:    
Context:               18dz7epj37wr  
Environment Variable:  export KUBECONFIG="/home/theia/.bluemix/plugins/code-engine/Code Engine - sn-labs-muabbasa8-f74cead6-9255-4f37-89b1-3b2d262fdadc.yaml"  
theia@theiadocker-muabbasa8:/home/project$ ibmcloud code-engine application list
Listing all applications...
OK

Name  Status  URL  Latest  Age  Conditions  Reason  
theia@theiadocker-muabbasa8:/home/project$ ibmcloud ce app list
Listing all applications...
OK

Name  Status  URL  Latest  Age  Conditions  Reason  
theia@theiadocker-muabbasa8:/home/project$ ibmcloud ce app create --name helloworld --image docker.io/ibmcom/helloworld
Creating application 'helloworld'...
The Route is still working to reflect the latest desired specification.
Configuration 'helloworld' is waiting for a Revision to become ready.
Ingress has not yet been reconciled.
Waiting for load balancer to be ready.
Run 'ibmcloud ce application get -n helloworld' to check the application status.
OK

https://helloworld.18dz7epj37wr.us-south.codeengine.appdomain.cloud
theia@theiadocker-muabbasa8:/home/project$ ibmcloud ce app get --name helloworld
For troubleshooting information visit: https://cloud.ibm.com/docs/codeengine?topic=codeengine-troubleshoot-apps.
Run 'ibmcloud ce application events -n helloworld' to get the system events of the application instances.
Run 'ibmcloud ce application logs -f -n helloworld' to follow the logs of the application instances.
OK

Name:               helloworld  
ID:                 6fe4cf5d-da8a-454e-94af-62d052085da9  
Project Name:       Code Engine - sn-labs-muabbasa8  
Project ID:         f74cead6-9255-4f37-89b1-3b2d262fdadc  
Age:                61s  
Created:            2023-10-11T04:11:12-04:00  
URL:                https://helloworld.18dz7epj37wr.us-south.codeengine.appdomain.cloud  
Cluster Local URL:  http://helloworld.18dz7epj37wr.svc.cluster.local  
Console URL:        https://cloud.ibm.com/codeengine/project/us-south/f74cead6-9255-4f37-89b1-3b2d262fdadc/application/helloworld/configuration  
Status Summary:     Application deployed successfully  

Environment Variables:    
  Type     Name          Value  
  Literal  CE_APP        helloworld  
  Literal  CE_DOMAIN     us-south.codeengine.appdomain.cloud  
  Literal  CE_SUBDOMAIN  18dz7epj37wr  
Image:                  docker.io/ibmcom/helloworld  
Resource Allocation:      
  CPU:                1  
  Ephemeral Storage:  400M  
  Memory:             4G  

Revisions:     
  helloworld-00001:    
    Age:                61s  
    Latest:             true  
    Traffic:            100%  
    Image:              docker.io/ibmcom/helloworld (pinned to 250026)  
    Running Instances:  1  

Runtime:       
  Concurrency:    100  
  Maximum Scale:  10  
  Minimum Scale:  0  
  Timeout:        300  

Conditions:    
  Type                 OK    Age  Reason  
  ConfigurationsReady  true  43s    
  Ready                true  30s    
  RoutesReady          true  30s    


Hello World from:
. ___  __  ____  ____
./ __)/  \(    \(  __)
( (__(  O )) D ( ) _)
.\___)\__/(____/(____)
.____  __ _   ___  __  __ _  ____
(  __)(  ( \ / __)(  )(  ( \(  __)
.) _) /    /( (_ \ )( /    / ) _)
(____)\_)__) \___/(__)\_)__)(____)

Some Env Vars:
--------------
CE_APP=helloworld
CE_DOMAIN=us-south.codeengine.appdomain.cloud
CE_SUBDOMAIN=18dz7epj37wr
HOME=/root
HOSTNAME=helloworld-00001-deployment-77945d9b7f-wnhnr
K_REVISION=helloworld-00001
PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
PORT=8080
PWD=/
SHLVL=1
z=Set env var 'SHOW' to see all variables

Events:        
  Type    Reason   Age  Source              Messages  
  Normal  Created  62s  service-controller  Created Configuration "helloworld"  
  Normal  Created  62s  service-controller  Created Route "helloworld"  

Instances:     
  Name                                          Revision          Running  Status   Restarts  Age  
  helloworld-00001-deployment-77945d9b7f-xldgr  helloworld-00001  3/3      Running  0         61s  
