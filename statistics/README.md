# To generate on Corefacility:
```bash
curl 'http://192.168.0.1:8080/blazegraph/status?dumpJournal&dumpPages' -H 'Pragma: no-cache' -H 'Origin: http://192.168.5.19:8080' -H 'Accept-Encoding: gzip, deflate' -H 'Accept-Language: en-US,en;q=0.9,la;q=0.8' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36' -H 'Content-Type: application/x-www-form-urlencoded; charset=UTF-8' -H 'Accept: */*' -H 'Cache-Control: no-cache' -H 'X-Requested-With: XMLHttpRequest' -H 'Connection: keep-alive' -H 'Referer: http://192.168.0.1:8080/blazegraph/' -H 'DNT: 1' --compressed
```

# To generate on Cybera
```bash
curl -d 'dumpPages' -d 'dumpJournal' -H 'Connection: keep-alive' 'http://localhost:8080/bigdata/status' 
```
