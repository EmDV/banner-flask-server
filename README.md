# banner-flask-server
Translation server: DXM controller API protocol to Exosite's Device API proto. 

## Introduction

This should be a relatively tiny flask server that takes the cyclical data pushes made by a DXM 100 and writes the appropriate data into Exosite. This should like translating a loaded GET request into a proper HTTP POST request to Exosite's device API.

I haven't decided how I will handle provisioning. My guess is that I will hard-code a device token for starters.