# giant v2 java services  docker compose files
use for hold all giant v2 java docker compose



# how to use
1. down load all the docker yml files.
2. open NotePad++.
3. replace all the fellow fields with your value.

   ```
    _docker_hub_iamge_url			sample: docker.io
   _image_version                sample:last
   _mission_control_service_url		formmat: http://x.x.x.x/MissionControl/api/settings/region/SG/Computed/
   _mission_control_account_url		format: http://x.x.x.x:80/WebAPIs/MissionControl/api/ConnectionSource/Account/Default
   _data_search_ip				sample: x.x.x.x
   _semantic_service_ip			sample: x.x.x.x		
   _index_elastic_host			sample: x.x.x.x
   _applicationWebRootPath			sample: https://x.x.x.x.com/analytics		
   _orientdb_host				   sample: x.x.x.x					
   _orientdb_user_name			
   _orientdb_password			
   _data_service_ip			sample: x.x.x.x			
   _log_service_ip			sample: x.x.x.x
   _region1				      SG
   _logging_elastic_host			sample: x.x.x.x
   _email_sender				 sample: xxx@google.com			
   _recipient_email1			sample: yyyy@baidu.com
   ```
   
4. now can use the file as compose-up already


