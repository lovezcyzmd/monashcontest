# monashcontest
To run this project, please follow this flow:
Step1: install an application called UiPath under Windows System, the Uipath website is www.uipath.com. Please install a community edition. Please use Uipath Studio edition.

Step2: Download my project files using the Github link: https://github.com/lovezcyzmd/monashcontest, unzip the depedance.zip. Make the directory arange like this:
       https://github.com/lovezcyzmd/monashcontest/blob/main/pic/diretory.png
       
Step3: Change the config file(config.xlsx) in the project folder. There is two option to set. 

 1、working path. The project will download related files in this path and put the result.xlsx file to this path. You need to ensure the working path exists in your computer.
 
 2、working mode. If you put this to 0, the project will run one test mode, else it will be on normal mode. In test mode, the project will only run at a small sample. The small
 sample file is in my project folder called data_test.xlsx
 
 After change these option, put the config.xlsx under folder "C:\Users\"
 
step4:Open my project files using UiPath. To do this, just use Uipath “open” menu to open the file project.json in my project folder.

Step5: Execute run. Then the project will execute the whole flow and work out the final result.

