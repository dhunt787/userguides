# How to setup the PSF autoforward rule effectively.

In order to setup the PSF autoforward rule effectively, you need to use Office365 portal.

* _Please do not use the outlook application to setup the rule, because that relies on your laptop being left on and outlook open while you are on leave._

To access the menu where you setup the OOO auto-forward, log into the single sign on portal here - [https://glg.galaxy.it](https://glg.galaxy.it)

Launch the office365 app, by clicking on the app button.

 It looks like this.({{ site.baseurl }}/images/office365/office365_outlook.png "Outlook App Button"))

Once the app launches, look over to the right hand side of the window. Beside your name you will see a cog icon, that look like this - ({{ site.baseurl }}/images/office365/settings_cog.png)

Click on that and a menu will pop out from the right hand side of the screen, like this. ({{ site.baseurl }}/images/office365/Settings_Menu.png)

At the bottom of the sidebar, there is a section called "Your app settings". Click on the 'Mail' option in that section.

An options menu will pop out from the left hand side of the window - see below.

({{ site.baseurl }}/images/office365/Mail_Function_Menu.png)

Under the section "Automatic processing", look for "Inbox and sweep rules"

The resulting screen will look like this.

({{ site.baseurl }}/images/office365/Inbox_Rules_Menu.png)

To create the rule, click on the '+' button to start creating a new rule.

Give the rule a name. I suggest you call it 'PSF autoforwarding rule'.

Now you need to set the conditions of the rule. To do that, follow the instrucions below:

    Select the 'When the message arrives, and it matches all of these conditions' option.

     Followed by

    'It includes these words -> in the sender's address'

    Then click on the text 'Add Words"

    That will cause a window like this to pop up.

    ({{ site.baseurl }}/images/office365/Enter_Words_Menu.png)

    Now add the first domain address of the client whose emails you want to foward to a colleague. 
    
    E.G. If it is Bain emails you wish to forward add '@bain.com'- See below for an example.

    Click on the '+' button to add that address.

    Repeat the above process until all client domains are added.

    Once complete, press the 'Okay' button to exit that menu.

    That will bring you back to the previous menu where you create the rule.

    Under the section 'Do all of the following', select the following conditions

    'Forward, redirect, or send -> Forward the message to'

    When you select those conditions, a new window will open where you need to search for the person are you forwarding the client emails to. Find their email address and add it as a recipent email address.

Once complete, press the 'Save' button.

Tick the option 'Stop processing more rules' and press okay.

The rule is now setup.

**Please add all client domains seperatly in the 'Enter Words' menu .**

*Please remember when you are not OOO, to disable this rule by unticking the 'On' checkbox next to the rule.*