# MS-Purview--Explore-the-capabilities-of-Copilot-in-Microsoft-Purview
Microsoft Security Copilot is accessible within Microsoft Purview data security and compliance solutions, including Data Loss Prevention (DLP), Insider Risk Management, Communication Compliance, and eDiscovery (Premium).  In this exercise, you explore the Copilot summarization capabilities available in each of these solutions.


**Task 1: Enable the Microsoft Purview plugin**

In this task, you enable the Microsoft Purview plugin. For this task, you work in the standalone experience.

1. Open the simulated environment by selecting this link: Microsoft Security Copilot. https://7lraebk5le-0de6q8m2yh.app.highlights.guide/

2. From the Microsoft Security Copilot landing page, select the Sources icon sources icon in the prompt bar.
![image](https://github.com/user-attachments/assets/ac339065-aa02-4536-a4a5-a46692d95f34)

A. From the manage sources window, under the Microsoft plugins, select Show 11 more.
B. Scroll down so that the Microsoft Purview plugin is visible.
![image](https://github.com/user-attachments/assets/026136b4-2a79-4a65-8239-0fe4f121f821)

C. Select the Information icon screenshot of the information icon. Note the instructions then close the plugins page by selecting the X on the top-right corner of the manage sources window.

3. Select the Home menu screenshot of the home menu icon, often referred to as the hamburger icon.

A. Select Owner settings.
B. Enable the toggle switch next to Allow Security Copilot to access data from your Microsoft 365 services.
![image](https://github.com/user-attachments/assets/017feba0-892c-45f5-a6b6-a6b3291d870a)


C. Return to the Copilot home page, by selecting Microsoft Security Copilot on the top-left of the page next to the home menu (hamburger) icon.

4. Now that you’ve enabled Copilot to access data from your Microsoft 365 services, return to the plugins page and enable the Microsoft Purview plugin.

A. From the promptbar, select the Sources icon.
B. From the manage sources window, under the Microsoft plugins, select Show 11 more.
C. Enable the toggle switch next to Microsoft Purview to enable the plugin.
![image](https://github.com/user-attachments/assets/d03a0b32-e941-4542-91df-cee8518aa455)

D. Close the manage sources window by selecting the X.

**Task 2: Gain a comprehensive summary of Insider Risk Management alerts**

For this and all subsequent tasks, you explore the Copilot functionality embedded in Microsoft Purview.

In this task, you explore the value Copilot provides in summarizing an Insider Risk Management alert. You start by first reviewing an alert, without Security Copilot. It can be challenging to know where to start your investigation when risky activities are detected over a long period of time. You'll then see how Copilot can address this same task with the click of a button.

Microsoft Copilot assumes the permissions of the user when it tries to access the data to answer queries. To access data associated with the Microsoft Purview Insider Risk Management solution, the Copilot user should have previously been assigned an appropriate role.

1. Open the environment by selecting this link: Microsoft Purview Portal.   https://in9pj0q7cg-n98gy3vils.app.highlights.guide/home?tid=536279f6-15cc-45f2-be2d-61e352b51eef
2. A pop-up window appears that says, "Welcome to the new Microsoft Purview portal!"

3. ![image](https://github.com/user-attachments/assets/027f3fc9-bc84-431a-8105-e07adedf0325)

A. Select the box where it says "This is a public preview. I agree to the terms of data flow disclosure, the preview section of the Product Terms, and Privacy Statements."
B. Select Try now.
C. You can close the Explore all solutions pop-up by selecting the X. Alternatively, you can select Next to go through the information. If you go through all six information windows, you'll need to scroll-up to get back to the top of the page, when you're done.


2. From the Microsoft Purview portal, select Insider Risk Management.

3. Select Alerts.
4. ![image](https://github.com/user-attachments/assets/e53e0c2c-082e-44b4-88c3-a5da2dbc9378)

5. Select the first alert on the list, alert ID: 86e52569.
![image](https://github.com/user-attachments/assets/e5ecaf2b-d447-4a2d-b138-b52551a9db26)

A. This alert is associated with the policy, 'Potential data theft - Employee Departure.' Under User details, you can gain more context on why the user was identified as a high impact user by selecting View all details. Review the user details then select the X to close the User details window.
B. The current page shows All risk factors. If you scroll down, there are even more details to consume.
C. Select the Activity explorer tab, to quickly review a timeline of potentially risky activity and filter for specific risk activities associated with the alert. Select, the first activity on the list, labeled Files accessed on SPO. Review the information provided then select X to close the window.
D. Select the User activity tab. Here you view a scatter plot, over a one month, three months, or six months timeline; alongside details of each event.


5. With Security Copilot, you can gain a comprehensive summary of an alert – in the single click of a button! From the top of the alert page, select Summarize.
![image](https://github.com/user-attachments/assets/dee21855-c05d-4590-9df7-3f7b54ab7dee)

A. This comprehensive summary provides key details, including alert severity, user details like their HR offboarding event and much more!
B. These summaries help accelerate investigations by helping you quickly gain context into user intent and timing of risky activities, enabling you to tailor your investigation with specific dates in mind and quickly pinpoint sensitive files at risk.


6. From the left navigation panel, select Home to return the Microsoft Purview portal. You'll return to this page in the next task.


**Task 3: Gain a comprehensive summary of Data Loss Prevention alerts.**

In this task, you explore the value Copilot provides in summarizing a Data loss prevention alert. As in the previous task, you start by first reviewing an alert, without Security Copilot. You then discover how Copilot can address this same task with the click of a button.

Microsoft Copilot assumes the permissions of the user when it tries to access the data to answer queries. To access data associated with the Microsoft Purview Data Loss Prevention solution, users should have previously been assigned an appropriate role.

1. Select Data loss prevention, then select Alerts
![image](https://github.com/user-attachments/assets/12e3c375-a781-48ef-a6df-bad858e6f331)

2. Investigating DLP alerts can be overwhelming due to the large number of sources to analyze, including apps, cloud services, email, endpoints and chat, and the varying rules and conditions of a policy.

3. Select the first alert from the list, labeled, DLP policy match for document cardholder transaction Log.xlsx in OneDrive.
![image](https://github.com/user-attachments/assets/35771302-1718-4426-93e3-0f10c5abac8e)

A. A side panel opens listing some details of this alert, including the alert status, severity, the DLP policy match, location, and user involved. From the bottom of the page, select View details. This opens a new browser tab.
B. Select the Events tab. For the selected event, you can view event details, impacted entities and more.
C. Select the Classifiers tab. Under classifiers, you can view the specific sensitive information types or trainable classifiers that were matched.
D. You can also select File Activity. There's much information to analyze.
E. Close this browser tab, but be sure to keep the 'Alerts|Microsoft Purview' tab open.


4. Now view the information that Copilot can generate with the click of a button.

A. From the Alerts|Microsoft Purview tab, which is showing the side panel with information about the alert, select Summarize with Copilot.
B. This comprehensive summary provides key details, including policy rules, source, files involved and more. Additionally, the summary pulls the user risk levels from Insider Risk Management, providing integrated insights across data security solutions. These summaries provide you with a better starting point for further investigation.

5. From the left navigation panel, select Home to return the Microsoft Purview portal. You'll return to this page in the next task.


**Task 4: Gain contextual summary of Communication Compliance policy matches**
In this task, you explore the capability of Copilot in Microsoft Purview Communication Compliance. Reviewing communication violations can be time-consuming, especially when reviewing lengthy content like meeting transcripts, email attachments, Teams attachments, or extensive text. Copilot can address this, and more, with the click of a button.

Microsoft Copilot assumes the permissions of the user when it tries to access the data to answer queries. To access data associated with the Microsoft Purview Communication Compliance solution, users should have previously been assigned an appropriate role.

1. From the New Microsoft Purview portal, select View all solutions, then select Communication Compliance, listed under Risk & Compliance.

2. Select Policies.

3. Select Regulatory compliance policy to identify potential regulatory compliance violations.

4. From the list of violations triggered by the policy, select the Teams communication with the subject Happy new year valued customers! to expand the list. Select the first item from the expanded view.

5. Communication Compliance is able to pinpoint the timestamps when a potential violation has occurred and highlight conditions matched, but there's still a good bit of text to read through.

A. With Security Copilot, you can gain a comprehensive summary of an alert in the single click of a button! Select Summarize.
B. You can also ask follow-up questions. Use copy/paste to enter Does this violation indicate unauthorized disclosure?

6. From the left navigation panel, select Home to return the Microsoft Purview portal. You'll return to this page in the next task.


**Task 5: Gain contextual summary of evidence collected in eDiscovery review sets (Preview)**

In this task, you explore the capability of Copilot to Microsoft Purview to gain a contextual summary of evidence collected in an eDiscovery review set.

Legal investigations can take hours, days, even weeks to sift through the list of evidence collected in review sets, requiring costly resources like outside council to manually go through each document to determine the relevancy to the case. Copilot can significantly reduce that burden by generating summaries of conversations in a variety of languages and the documents that may be included as attachments.

Microsoft Copilot assumes the permissions of the user when it tries to access the data to answer queries. To access data associated with the Microsoft Purview eDiscovery solution, users should have previously been assigned an appropriate role.

1. From the New Microsoft Purview portal, select View all solutions, then select eDiscovery, listed under Risk & Compliance.

2. For this simulation, you're taken directly to the page for cases. From the cases page, select Contoso stock manipulation, then select the tab Review sets.

3. From the review sets page, open the review set listed RS - Stock manipulation Teams conversation + cloud attachments

A. From the bottom of the Overview page, select Open review set.
B. Using the filter, filter for Teams conversations:
 - Filter - File class.
 - Select an operator - Equals any of.
 - Select Any - Conversation.

C. From the results, select the first item on the list #1.
1. Information about the conversation appears in the window to the right. Scroll to view the source history. There's quite a bit of text included in this teams conversation. It can be time-consuming to sift through the information.
2. With Security Copilot, you can gain a comprehensive summary of the conversation in the review set – in the single click of a button! Select Summarize. Copilot also provides prompt suggestions and the prompt bar for you to enter your own prompts in furtherance of the investigation. This helps you save time and conduct investigations more efficiently!

4. Refer back to the list of Teams conversations. This time, select the second item on the list select item #2 .

A. The subject is displayed in a non-English language. This is common challenge with multi-national corporation whose employees speak various languages. The window with the source conversations shows a conversation history with non-English language. Select Summarize to view a summary in English, which is my default language for Copilot.
B. Within Microsoft Teams, you can send cloud attachments, which are links to documents. Expand item #2 by selecting the >. The first subitem is a Word document. Select the **document** then select **Summarize** to have Copilot generate a summary.


5. From the left navigation panel, select **Home** to return the Microsoft Purview portal. You'll return to this page in the next task.


**Task 6: Create Keyword Query Language (KeyQL) queries using natural language to search in eDiscovery (Premium)**

In this task, you explore the capability of Copilot in Microsoft Purview eDiscovery (Premium) to create Keyword Query Language (KeyQL) queries using natural language. Users provide a prompt in natural language and Copilot generates a query in KeyQL language, making your search iterations faster and more accurate. This feature also enables analysts, at all levels, to conduct advanced investigations using KeyQL.

Microsoft Copilot assumes the permissions of the user when it tries to access the data to answer queries. To access data associated with the Microsoft Purview eDiscovery solution, users should have previously been assigned an appropriate role.

1. From the New Microsoft Purview portal, select **View all solutions**, then select** eDiscovery**, listed under **Risk & Compliance.**

2. For this simulation, you're taken directly to the page for cases.

3. Select **Fabrikam vs Contoso**.

4. Select Create a search.

A. Enter a search **name.**
B. Enter a** description**.
C. Select** Create**.

5. Add a data source

A. Select Add data **sources.**
B. In the search bar, enter **Sales.**
C. From the search results, select **Sales.**
D. From the bottom of the page, select **Save.**

6. Now use Copilot to draft a query in natural language. Select **Draft a query with Copilot**.

A. From the box labeled natural language prompt, select **View prompts**. This is a great starting point. You could look at suggested prompts to determine how to craft a natural language query for suggested prompts. For example, Find all emails containing the words budget and finance and have attachments.

B. For this example, however, you know what you are looking for. You’ve been told that you need to find all conversations related to a recent acquisition. Use copy/paste to enter **Find all conversations that contain the keywords; acquisition, stock, Bitdefender, Frostvision, offshore.**

C. When you enter your natural language prompt, you can have Copilot refine the query to ensure a more accurate query output. Select Refine then Accept.

D. Select Generate KeyQL. Security Copilot refines the prompt and then in a simple click, can generate the query within seconds!

E. The purpose of this exercise is to show how easily Copilot can generate the code for a query using natural language. In your production environment, to run the generated query copy the KeyQL code into the run box and select run

**Review**

With Copilot in Microsoft Purview, data security and compliance admins can use the power of AI to assess risk exposure more quickly than is otherwise possible, directly from within Microsoft Purview solutions.

In this exercise, you explored the powerful functionality of Copilot to aid in your compliance investigations with DLP, Insider Risk Management, Communication Compliance, and eDiscovery.


