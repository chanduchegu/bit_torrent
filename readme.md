# assignment 3

## tracker

trackerCompilation:g++ tracker.cpp -lpthread -lcrypto -o tracker
trackerExecution:./tracker tracker_info.txt tracker_no

## client

- clientCompilation:g++ client.cpp -lpthread -lcrypto -o client2
- clientExecution:./pclient2 ip_address:port tracker_info.txt

## dataFiles contains:

- tracker_info.txt: ip and port of tracker
- userData contains files to make the peerData persistant even after logout
- fileDetails.txt,groupData.txt,tracker_info.txt,validationData.txt contains data to make the tracker persistant & synchronizes even after logout
