# WhereIs
didn't want to open a browser and use ipgeolocation.io so I wrote a script to do it for me instead.
## client for IPgeo API
this script does nothing else other than communicating with the API and present specific results that might help SOC analysts.
## customize it as you like!
the API provides more data but I choose the country name and ISP. If you wish to veiw more of the data you can edit the script to your liking, here is the [documentaion](https://ipgeolocation.io/documentation/ip-geolocation-api.html) to assist you.
### usage:
after adding your key in the script code, you can use it like this
```
python3 Whereis.py 8.8.8.8
```

#### TODO
I believe that things are built by many people are better by the ones that are built by one thus I have left this for anyone who share the same vision.
  1. tell the user when the request limit has been reached.
  2. handle internet connection errors.
  3. left for your creativity.
