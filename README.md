Think of this project like an HR chatbot for company data.

A user simply types a question in normal English, just like chatting with a bot. They don’t need to know SQL, databases, or anything technical. The system reads the question and understands what information the user is looking for.

Before answering, the chatbot checks the user’s role and permissions. This is role-based access control. If the user is allowed to see that data, the system continues. If not, it politely says no and stops there. This yes-or-no policy check keeps all sensitive data safe.

Once access is approved, the AI understands the question and fetches the correct information using approved data and rules. It does not guess or make things up. Everything is controlled and logged so the company knows who accessed what.

In simple terms, it’s a smart, secure chatbot that lets employees get answers easily about them as well as the company while making sure the right people see the right data. For a clearer picture of how this flows step by step, the architecture diagram explains it much better.

Architecture Diagram:
<img width="559" height="1011" alt="HrChatBot" src="https://github.com/user-attachments/assets/ca158e8d-e200-4017-9657-22e574b2da4d" />
