
# Lab: Explore the Microsoft 365 Defender portal

## Lab scenario
In this lab you will explore the Microsoft 365 Defender portal by walking through the content displayed on the landing page. You will also explore the options on the navigation panel which provide quick access to functionality that is part of Microsoft’s Extended Detection and Response (XDR) solution: Microsoft Defender for Endpoints, and Microsoft Defender for Office 365 (email and collaboration).  Lastly you will also explore how Microsoft Secure Score can help an organization improve its security posture.


**Estimated Time**: 10-15 minutes

#### Task 1:  Explore the Microsoft 365 Defender landing page.


1. Open Microsoft Edge. In the address bar enter **admin.microsoft.com**.

2. Sign in with your admin credentials.

    1. In the Sign in window enter **odl_user_XXXXXX@cloudlabsai.com** (where XXXXXX is your unique ID provided on the lab environment page) then select **Next**.
    2. Enter the admin password which should be provided on the lab environment page. Select **Sign in**.
    3. When prompted to stay signed-in, select **Yes**. This takes you to the Microsoft 365 admin center page.

3. From the left navigation pane of the Microsoft 365 admin center, select **Show all**.


4. Under Admin centers, select **Security**.  A new browser page opens to the welcome page of the Microsoft 365 Defender portal.  

    ![alt text](https://raw.githubusercontent.com/Ritu786/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals/stag/Instructions/Images/8-1.png)
  

5. If this is the first time you visit the Microsoft 365 Defender portal, you may get a pop-up window to take a quick tour.  It is recommended that you complete the tour.  Select **Take a quick tour**.  Read the description provided in each pop-up window, then select **Next**. Continue through the tour until you get to the end, then select **Done**.

6. The left navigation panel provides links/access to information that are part of Microsoft’s Extended Detection and Response (XDR solution) which includes incidents & alerts, threat analytics, Hunting and much more.  It also includes quick access to Microsoft Defender for Endpoint (the links listed under Endpoints) and Defender for Office for 365 (links listed under Email and Collaboration).  Explore these options by selecting some of the links.   To return to the home page of the Microsoft 365 Defender portal, select **Home** on the left navigation panel.  Note: you may not see much information listed in these tabs as their are no devices attached and may not have any active threats or alerts.

7. The welcome page of the Microsoft 365 Defender portal, shows many of the common cards that security teams need. The composition of cards and data is dependent on the user role. Scroll through the page to view the default set of cards for your role as global admin.

8. The cards displayed can be customized to your preference.  Select **+ Add cards**. A Window opens indicating that you already have all the cards on your home page.  Close the window by select the **X** on top-right corner of the window.

9. Selecting the ellipses on the top-right of any card will provide more actions you can take.  

10. You can also move the cards around. Hover your mouse cursor over the title bar of any card,  when you will get a cross shaped cursor select the card and move it to your desired location.

11. Selecting the title of a card will take you to additional information for that topic. You will explore this in the next task.  Keep the browser window open.

#### Task 2: In this task you will explore how Microsoft Secure Score can help an organization improve its security posture.

1. In the address bar enter **security.microsoft.com**. It takes you to the Microsoft 365 Defender Portal.e

2. From the Welcome page of the Microsoft 365 Defender portal, select **Microsoft Secure Score**, from the title bar of the card (the text will turn blue).  Alternatively, you can select **Secure score** from the left navigation panel.

3. The Microsoft Secure Score page opens to the Overview tab.  Microsoft Secure Score is a measurement of an organization's security posture Your organization’s secure score is shown as a percentage, along with the number of points you've achieved out of the total possible points and broken down by category. Select **Include**, next to where it says Your secure score. you can choose for the view of your score to include the achievable score, Planned score, and Current license score.

    ![alty text](https://raw.githubusercontent.com/Ritu786/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals/stag/Instructions/Images/9-1.png)

1. The overview page also includes top improvement actions, comparison score, history, and additional resources.

1. Select **Improvement actions** from the top of the page.  Notice the information available in the table, for each item, which includes score impact and points achieved.  

1. Selecting an item from the list provided detailed information.  Select **Require MFA for Administrative roles**.  Note how you can update the status of the action plan and the detailed information for implementation of the action.

    ![alt text](https://raw.githubusercontent.com/Ritu786/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals/stag/Instructions/Images/9-2.png)

1. From the down left of the page select **Manage in Microsoft Azure**.  A new browser tab opens and takes you directly to the Conditional Access Policies page.  If you completed the Conditional access lab exercise you should see the policy listed or you can add the **New Policy** from the portal itself.   Return to Microsoft secure score tab on your browser to return to the improvement action page for requiring MFA for administrative roles. From the top right corner of the window, select the **X** to close this window and return the improvement actions page.

    ![alt text](https://raw.githubusercontent.com/Ritu786/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals/stag/Instructions/Images/9-3.png)

1. Select the **History** tab from the top of the page.  Some activities may show negative points.  As described in the activity field this may be because an item was removed because it was no longer relevant.  Select an item form the history table.  On the top-right of the details page, under History, select **X events** (where X is a number).  The action history window opens and provide more information.  Select **Close** on the bottom of the page, then select the **X** on the top-right corner of the details page to return to the History page.

    ![alt text](https://raw.githubusercontent.com/Ritu786/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals/stag/Instructions/Images/9-4.png)

1. From the top of the page, select **Metrics & trends**.  Note the available information.  From the top-right corner of the page, select the **calendar icon**.  You can narrow down the view to a custom date range.  Selecting **filter icon**, allows you to filter the view by Identity, Devices, and/or apps.  Close the window and select **Home** from the left navigation panel to return to the Microsoft 365 Defender home page.

    ![alt text](https://raw.githubusercontent.com/Ritu786/SC-900-Microsoft-Security-Compliance-and-Identity-Fundamentals/stag/Instructions/Images/9-5.png)

1. Close the browser page.

#### Review
In this lab you explored the Microsoft 365 Defender portal by walking through the content displayed on the landing page, you explored the options on the navigation panel which provides quick access to functionality that is part of Microsoft’s Extended Detection and Response (XDR) solution, Microsoft Defender for Endpoints, and Microsoft Defender for Office 365 (email and collaboration).  Lastly you explored how Microsoft Secure Score can help an organization improve its security posture.
