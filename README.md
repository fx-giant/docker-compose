# giant v2 java services  docker compose files
use for hold all giant v2 java docker compose



# how to use
1. down load all the docker yml files.
2. open NotePad++.
3. replace all the fellow fields with your value.

   ```
   _docker_hub_iamge_url *url to your docker hub or docker registery
   _image_version *iamge tag 
   _log_service_ip * ip/host name no need port
   _data_service_ip * ip/host name no need port
   _redis_ip *ip/host name no need port
   _postgres_ip *ip/host name no need port 
   _postgres_user_name 
   _postgres_password
   _postgres_port
   _semantic_service_ip *ip/host name no need port
   _giant_service_ip *format http://[ip]/[subpath]/GiantService
   _dm_service_ip *ip/host name no need port
   _mission_control_service_ip * format http://[ip]/WebAPIs/MissionControl/api/Settings/[defaultregion]/Computed
   _region1 *default region code 
   _jobServiceUrl  *ip/host name no need port 
   _rabbitmp_ip *ip/host name no need port 
   _rabbitmp_user_name
   _rabbitmp_password
   _data_search_ip *ip/host name no need port 
   _index_elastic_host *ip/host name no need port 
   _logging_elastic_host *ip/host name no need port 
   _applicationWebRootPath *http://[ip]/website/
   _orientdb_host *ip/host name no need port 
   _orientdb_user_name
   _orientdb_password
   _message_service_ip *ip/host name no need port 
   _email_host  * email 
   _email_sender *email 
   _email_password
   _mongodb_connectionstring *mongo://[ip]:[port]
   _recipient_email1 *email
   _audit_log_ip *ip
   ```
   
4. now can use the file as compose-up already
