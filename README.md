# Minecraft Perfect-Scheduler

  If you play Singleplayer then you need to be running this service. It will backup your Minecraft "Saves" folder by the minute, hour, day, week, month, etc. Just configure to run however often you want.
  
  I got this code from the article below by SibeeshVenu and then modified it to backup my 'saves' folder. What I did was modify the code to backup every 5 minutes. Then I don't really need to push to the cloud every five minutes so for now I've turned off the Azure Blob Storage code with a "disabled" flag.
  
  Eventually I will want to push the weekly, and monthly zip files up to the cloud but the "Minutely" and "Daily" can stay local.
  
  Also, in the future I will add a variable to configure the time from 1 - 60 minutes. If you need more than that you can use the "Hourly" job schedule.

Daily, Weekly, Monthly. Please feel free to read this article here: https://sibeeshpassion.com/tag/quartz-scheduler/
