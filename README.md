# hive-python-geoip-geolite2

to update the underlying database powering geolite2 lookups

1) download the most recent "GeoLite2 City" version on this page: https://www.maxmind.com/en/accounts/791098/geoip/downloads
2) extract the downloaded gzip/etc as needed
3) find the `GeoLite2-City.mmdb` file in the unzipped folder
4) replace the `GeoLite2-City.mmdb` file in this repo with the new version
5) commit + push
6) then update our entry in requirements.txt HiveHQ/tickets to your commit's hash!
