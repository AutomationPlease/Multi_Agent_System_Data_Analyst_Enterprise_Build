

## Home page, blank chat displayed with side panel hidden
  - Chat Statistics show total message count (User Questions + Agent Responses) to help user identify when chat is becoming to lengthy and needing to start new chat (showing 0's because blank conversation)
  - Conversation timeline which shows the user prompts, and if clicked will open up to give the agent responses to that prompt (not showing anything because blank conversation).
  - Under the conversation timeline is a export chat function to export the full chat into the file type of choice (this will only appear once conversation begins).


![app home page no side panel](../Screenshots/Streamlit_App/home_page_blank_chat.png)


## Home page, blank chat displayed with side panel showing
  - Shows User Name, User Role, Services Status.
  - Logout, self explanatory.
  - Dashboard, goes to analytical dashboards page for given data sets in system.
  - Best Practices, goes to page to help train user with guidance around how to use chat, how to interact with agents, and other tips/tricks/techniques to improve user session effectiveness.
  - Data Tables, goes to page to view tables for data in system.
  - Admin, only visible to users with admin role, goes to admin page for system and user governance.
  - New Chat, starts blank new chat.
  - As a user creates more and more chats they will each be adding to the conversations container starting below the New Chat button, and will be sorted in Descending order, so newest to oldest.
    - New chats get added as "new conversation". The user has the ability to edit the chat name, or delete the chat. As the users performs these interactions the API endpoint will simultaneously update the respective data tables for these changes in Postgres.
    - There is no limit to the number of chats a user may have stored (active or not). The conversations container has a separate scroll bar that would allow a user to pick out a specific chat for review, analysis or continuation of previous session.
  - Panel Sizes, can be adjusted by the user or reset back to normal.
    - These adjustments can only be made to the chat box, and conversation timeline.
  - The home page side panel may be hidden by the user by clicking the double arrow in the top left corner of the screen at the top of the home page.
    - The side panel is only visible to users while on the home page. If user is within any other page then they will only have a Return to Home button where the double arrow button would normally be.


![app home page with side panel upper](../Screenshots/Streamlit_App/side_panel_upper_home_page_blank_chat.png)


![app home page with side panel lower](../Screenshots/Streamlit_App/side_panel_lower_home_page_blank_chat.png)


<table>
  <tr>
    <td width="50%" valign="top" align="left">
      <img src="../Screenshots/Streamlit_App/side_panel_chat_edit.png" width="400" alt="rename" />
      <br />Showing conversation rename
    </td>
    <td width="50%" valign="bottom" align="left">
      <img src="../Screenshots/Streamlit_App/side_panel_chat_delete.png" width="400" alt="deleted" />
      <br />Showing conversation deleted
    </td>
  </tr>
</table>
