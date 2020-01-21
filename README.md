# LibCal: A simple chatbot designed for NYU Dibner Library
Course project: Human-Computer Interaction

The project task was to design a front-end UI for a chatbot. I chose to implement one in context to NYU's Engineering Library. All the UI code has been <b> written from scratch without using external frameworks and tools </b> like bootstrap. The project relies heavily on Javascript, HTML and CSS. Since the project had to be completely front-end, I used <i>Rivescript.js</i> to implement the <i> brain </i> of the chatbot.

Additional features: The chatbot can read out its responses. This was implemented using <i> responsivevoice.js </i> and can be switched off if the user doesn't need it. 


## Exploring the UI

![Floating icon](https://github.com/harmanchawla/LibCal/blob/master/Report/UI%20Explained/Image%201.png)
Floating icon on the bottom-right of the page. Note how the chat window has resized with the inspection window and screen size. 


![Hover over the icon](https://github.com/harmanchawla/LibCal/blob/master/Report/UI%20Explained/Image%202.png)
Hovering over the icon reveals hidden icons giving the user an option to talk to a bot of a librarian if the librarian is available.


![Initial chat](https://github.com/harmanchawla/LibCal/blob/master/Report/UI%20Explained/Image%203.png)
The chat window is displayed as a sidebar over the webpage and the rest of the page gets faded. The top-bar clearly indicates that the chat is online. The icon next to the message reflects the sender of the message for clarity. Each text comes with bold, easy to read text and a timestamp. 


![Sample chat](https://github.com/harmanchawla/LibCal/blob/master/Report/UI%20Explained/Image%204.png)
I don't expect the user to type complete sentences. The bot is designed to <b> pick up keywords from the user inputs and generate an appropriate response </b>. If the bot is uncertain, it will redirect the user to the Ask Librarian forum, a human chat assistant or ask the user to wait while someone comes online to help. 

Furthermore, long responses tend to disinterest the user. Therefore, <b>long responses are avoided</b>. If that is not feasible, <b>the response is broken down into multiple replies</b>. Notice how there is an appropriate spacing between the two responses. 


![Attention to detail](https://github.com/harmanchawla/LibCal/blob/master/Report/UI%20Explained/Image%205.png)
Attention to detail. Notice the white shadow casted on the chat area by the top bar to avoid confusion between blue top-bar and blue responses. Also notice the small divider between the text box and the send button at the bottom. Hovering over the Send button reveals makes it move left and reveals to arrows indicating the action. The messages can also be sent using the Enter key. <b>NOTE: The send button was later removed from Desktop version as the Enter key was more intuitive. </b>



![Demo](https://github.com/harmanchawla/LibCal/blob/master/Report/UI%20Explained/UI-Vocal.gif)

Here is the chatbot working with the speech functionality added. The toogle switch on the top allows the user to stop or enable the audio response. 

