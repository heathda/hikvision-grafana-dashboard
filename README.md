# hikvision-grafana-dashboard
Hikvision IP Camera Grafana Dashboard

This is a Grafana dashboard to display information about your Hikvision IP Cameras.  The Hikvision MIBs do not support a ton of useful information, but this dashboard does display the information I was looking to monitor.  

This dashboard works with a telegraf collector which can be found over here https://github.com/heathda/hikvision-telegraf-collector

## Statistics Displayed
- Manufacturer
- Device Model
- CPU Percentage
- Memory Percentage
- Static IP
- Video Encoding

![hikvision-dash-sm](https://user-images.githubusercontent.com/71768221/95099627-1fce3680-06fe-11eb-8d09-64a07aa40171.png)
