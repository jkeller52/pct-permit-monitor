# pct-permit-monitor
This program monitors the Pacific Crest Trail Association permit availability website for any changes. 

After missing the first permit release in November 2022, I found myself frequently checking the permit portal to see if any permits had freed up. Upon learning that you could view permit availability without having to login and verify through email verification, I realized it would be easy to automate this process and snd myself notifications about updates to permit availability using Python. 

This code adapts Paul Bitutsky's [tutorial on Medium](https://medium.com/swlh/tutorial-creating-a-webpage-monitor-using-python-and-running-it-on-a-raspberry-pi-df763c142dac#:~:text=Checking%20to%20see%20if%20the%20webpage%20was%20changed&text=The%20function%20website_was_changed()%20will,request%20to%20a%20specified%20URL.) for monitoring websites using a Raspberry Pi. I highly recommend reading this tutorial for background. He covers text and email notifications.