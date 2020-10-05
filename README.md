# hikvision-grafana-dashboard
Hikvision IP Camera Grafana Dashboard

This is a Grafana dashboard to display information about your Hikvision IP Cameras.  The Hikvision MIBs do not support a ton of useful information, but this dashboard does display the information I was looking to monitor.  

This dashboard works with a telegraf collector which can be found over here https://github.com/heathda/hikvision-telegraf-collector

### Statistics Displayed
- Manufacturer
- Device Model
- CPU Percentage
- Memory Percentage
- Static IP
- Video Encoding

![graf-sm](https://user-images.githubusercontent.com/71768221/95124108-f2df4b00-0720-11eb-93e8-211e0a8ca831.png)
