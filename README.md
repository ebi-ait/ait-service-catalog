# AIT Service Catalog
This screen contains all the AIT applications with respect to their teams.

# Webin and ENA Web services and command line tools

| Service|Description|Application URL|Github|Developed using|Swagger API
|---|---|---|---|---|---|
| Webin Authentication | Webin submitter authentication and submission account admnistration web API. | https://www.ebi.ac.uk/ena/submit/webin/auth |  https://github.com/enasequence/webin-auth | Java, Spring-boot-2.3.1.RELEASE |  :heavy_check_mark: |
| Webin REST | Webin submissions web API.| https://www.ebi.ac.uk/ena/submit/drop-box/ |  https://github.com/enasequence/sub-sra    | Java, Spring-boot-2.2.0.RELEASE| :heavy_check_mark:  |
| Webin Portal | Webin submission and reports service web UI. | https://www.ebi.ac.uk/ena/submit/webin/ |  https://github.com/enasequence/sub-ang    | Angular-8.2.14|  |
| Webin Reports | Webin reports web API. | https://www.ebi.ac.uk/ena/submit/report/ |  https://github.com/enasequence/webin-reports| Java, Spring-boot-1.5.7.RELEASE| :heavy_check_mark: |
| ENA Reports | ENA internal processing reports web UI. | https://www.ebi.ac.uk/ena/reports/ |  https://github.com/enasequence/ena-reports | Java| |
| Webin CLI  | Webin command line interface submission tool | | https://github.com/enasequence/webin-cli | Java, Spring-boot-2.1.1.RELEASE| |
| Checklist editor | Webin sample checklist editor web UI. | https://www.ebi.ac.uk/ena/checklist-editor/ |  https://github.com/enasequence/sub-checklist-editor | Java, Spring-Boot-1.5.6.RELEASE| |
| Webin file uploader | Webin (FTP) file uploader Java web start application. | https://www.ebi.ac.uk/ena/upload/WebinUploader.jnlp |  https://github.com/enasequence/sub-file-uploader | Java|  |
| CRAM reference registry | CRAM reference registry web API. | https://www.ebi.ac.uk/ena/cram |  https://github.com/enasequence/ena-cram-reference-registry |Java, Spring-boot-2.1.6.RELEASE| :heavy_check_mark: |
| ENA firestarter | ENA FIRE 3 file archival web API. |  http://ves-hx-5a:8436/firestarter | https://github.com/enasequence/ena-firestarter |Java, Speing-boot-2.3.5.RELEASE| :heavy_check_mark: |
| Webin ENA Database | Webin internal ENA* oracle database web API. |  https://wwwint.ebi.ac.uk/webin/ena/service/ | https://github.com/enasequence/webin-ena-service |Java, 2.4.3.RELEASE| :heavy_check_mark: |
| Webin ERA Database | Webin internal ERA* oracle database web API. |  https://wwwint.ebi.ac.uk/webin/era/service/ | https://github.com/enasequence/webin-era-service |Java, 2.4.3.RELEASE| :heavy_check_mark: |
| Webin ECA Database | Webin ECA* oracle database web API  https://wwwint.ebi.ac.uk/webin/era/service/ | https://github.com/enasequence/webin-era-service |Java, 2.4.3.RELEASE| :heavy_check_mark: |
| Webin Interactive | Old Webin submission and reports service web UI (will be deprecated end of 2021)  | https://www.ebi.ac.uk/ena/submit/sra/ |  https://github.com/enasequence/sub-sra-gwt| Java, GWT| |
| Old Webin authentication (with sessions) | Old Webin Session based authentication(will be deprecated end of 2021) | http://ves-hx-5a:8120/ena/authentication/ |  https://github.com/enasequence/ena-authentication| Java| |
| Old Webin authentication (without sessions) | Old Webin Sessionless based authentication(will be deprecated end of 2021) | https://www.ebi.ac.uk/ena/auth/ |  https://github.com/enasequence/ena-authentication| Java|  |
| Old Webin account administration | Old Webin account administration (will be deprecated end of 2021) | http://ves-hx-5a:8120/ena/account/admin/ |  https://github.com/enasequence/ena-account-admin | Java|  |
| Webin Interactive sequence template validator | Old Webin Interactive template sequence template validator (will be deprecated end of 2021) | https://www.ebi.ac.uk/ena/validator/ |  https://github.com/enasequence/ena-validator | Java| |


# Biosample Web services
| Service                     | Description                  | Application URL             | Github       | Developed using
|  ---------------------------|----------------------------- | ------------------------------- | ----------------------------------------------------------- |--------------------------|
| webapps-core  | EBI BioSamples database | https://www.ebi.ac.uk/biosamples/ | https://github.com/EBIBioSamples/biosamples-v4/tree/dev/webapps/core | Java, Spring |
| rabbitmq  | | http://wp-p2m-40.ebi.ac.uk:15672/ (Runs on 4 VM's [wp-p2m-40, wp-p2m-41, wp-p1m-40 and wp-p1m-41] with shovel plugin to central queue in wp-p2m-40) | | |
| solr  | | http://wp-p2m-42.ebi.ac.uk:8983/ and http://wp-p1m-42.ebi.ac.uk:8983/  | | |
| MongoDB | | mongodb-hhvm-008, mongodb-hxvm-009 (no HTTP access)  | | |
| neo4j | | http://biosamples-neo4j:7474/ | | |
| graylog | | http://biosamples-ops:9000/ | | |
| spring-boot-admin | | http://biosamples-ops:9010/ | | |  