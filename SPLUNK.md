

## 1. Understand the architecture of Splunk and the installation process. Setup collector and forwarder,then ensure the logs are accumulated in Splunk. Familiarize yourself with the dashboard fields.
- Data collection: Splunk can collect data from a variety of sources such as servers, network devices, applications, sensors, and more. It uses agents and connectors to collect data and send it to the Splunk server.
- Data indexing: The collected data is indexed and stored in Splunk's proprietary format, which is optimized for searching and querying. The indexing process involves breaking the data into events, extracting fields from the events, and creating an index for each field.
- Search and analysis: Splunk provides a powerful search and analysis engine that allows users to query the indexed data using a search language called SPL (Splunk Processing Language). Users can create ad-hoc searches or save them as dashboards and alerts for later use.
- Visualization: Splunk provides a range of visualization options such as charts, graphs, and tables to help users understand and analyze their data. Users can customize the visualization options to suit their needs.
- Deployment options: Splunk can be deployed on-premises, in the cloud, or as a hybrid deployment. Splunk Enterprise can be deployed as a single instance or as a distributed environment with multiple indexers, search heads, and forwarders.
## Installation of Splunk Forwarder in kali
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/57853e1d-a5c1-4a92-bd7a-4496d8a8acb2)

## Splunk Forwarding Configuration
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/2db3f527-8cbc-4208-b361-8c288ef124f7)
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/5bb98818-a86a-4bd5-a0b7-ec0e9c97a958)
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/0e2a3218-32e7-4219-b05d-606503e2693b)
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/7ecc2480-e8db-4c44-b06c-550fc05521b2)
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/2e16465b-df8b-4b0f-a9c8-5887bb6674d3)

## 2.Run Splunk >> Forwarder can be in the same system or another system (user’s convenience) >>Make sure the logs are indexing in the Splunk enterprise.
- Run any network and port scanning commands from the host to the target machine. Run at least 5 to 8 commands. (If required, any tools can also be used).
- Use the search section in Splunk to analyze the firewall logs to find the log of the above process and the exact IP from where the scan was performed. HINT: Use the “stats” command.
- Analyze the log file and create an alert for any further similar activities.
- Performing nmap-scan and save it as a log fle which can send the nmap logs
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/b5ef4a34-d3a8-4cb2-8824-d111ab08489b)
- We can also use command 'scan' in enterprise splunk to find the logs.
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/cce64a2c-ae06-419a-a96a-f9876df0ddeb)

## 3. Run Splunk
- Forwarder can be in the same system or another system(user’s convenience) 
- Make sure the logs are indexing in the Splunk enterprise.


## 4. 
![image](https://github.com/s-sparshika/CyberSecurity/assets/68326118/02babed6-24fa-4b3b-ae77-90a849fb042f)
