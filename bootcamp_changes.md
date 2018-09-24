# Notes to make PictureBot labs work
09/24/2018  

The Bot Builder V4 SDK for .NET went GA today! We're working on updating the labs to incorporate the changes between Preview and GA, so check back soon for an update. In the meantime, we added some notes for you to follow if you still want to complete the labs.  


## Lab 2.2
 [1_Dialogs_and_Regex.md](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.2-building_bots/1_Dialogs_and_Regex.md)
* At the beginning of Lab 1.1 Setting up for bot development, follow the instructions to Download the Bot Emulator.
* Next, **read only** Lab 1.2 Creating a simple bot and running it, **until** the line "Get stuck? You can find the solution for the lab up until this point under [resources/code/PictureBot-FinishedSolution-Part0](https://github.com/Azure/LearnAI-Bootcamp/tree/master/lab02.2-building_bots/resources/code/PictureBot-FinishedSolution-Part0/PictureBot)." Open the solution under "PictureBot-FinishedSolution-Part0", which should already be on your local drive if you completed the previous labs, and start the lab from there.
* Do not update any packages!!  

[4_Publish_and_Register](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.2-building_bots/4_Publish_and_Register.md)
* When you publish the bot, select SDKv3 C# Basic, we will overwrite it later


## Lab 2.4
[2_Direct_Line](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.4-testing_bots/2_Direct_Line.md)
* May need to update the three instances of "Activity" with "Microsoft.Bot.Connector.DirectLine.Activity"
* May need to run "Install-Package Microsoft.Rest.ClientRuntime -Version 2.3.2" in the Package Manager Console if you get an exception when running the app.  


> Thank you for your patience. If you find any additional errors, please create an issue in the LearnAI-Bootcamp repository.
