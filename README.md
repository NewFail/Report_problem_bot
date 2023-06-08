# Report_problem_bot
 Telegram bot for collecting problems with equipment from users.
 The bot sends user requests to the bot administrator, and saves them to the Google table.


 The bot token, the id of the bot administrator, the name of the Google table where the requests are saved, the path to the json file are in the file: ...\Report_problem_bot\dist\config\bot.ini


 To start the bot, you need to run the file ...\Report_problem_bot\dist\run_bot.exe .*
 
 An internet connection is required for the bot to work


 To create the bot, the python programming language and libraries were used: aiogramm, pandas, gspread.


 Instructions for using the bot:

 1. Launch the bot and do not close the window that opens.*

 2. Log into Telegram to chat with the bot.

 3. Enter the command "/start".

 4. Use the "Сообщить о проблеме" button.

 5. Write your full name.

 6. Describe your problem.

 7. Check your message, if everything is fine, click the "Всё в порядке" button, if something is wrong, click the "Изменить" button and repeat steps 5-7.

 8. Your request has been sent to the bot administrator and saved in Google tables, if new problems occur, repeat steps 4-7.

Warning! To enter data about problems in the table, you need to create a service account and give him the opportunity to edit the table. You can find out more here: https://www.youtube.com/watch?v=aruInGd-m40 (section "Enable application and upload credentials")

\* - for the computer that is the server.
