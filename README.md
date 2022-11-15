# turnover-employees-forecast
Marcos Vinicius Martins de Menezes - mvmenezesadm@gmail.com

Uncover the factors that lead to employee turnover and explore important questions. 

The objective of this project is to statistically analyze what are the possible reasons for spontaneous turnover and create an algorithm able to detect which professionals can rotate. With such information, a company has the possibility of understanding the reasons for the dismissal rates, and it is then possible to create actions to prevent unwanted cases.

This project will be divided into two parts, the first one referring to the exploratory analysis of the data, in which hypotheses will be raised that will be statistically tested. The second part will be the creation of the machine learning model to predict employees with positive turnover. The analysis will be done in the python language.

The data were obtained through internet dataset.

Developed using:

    Python;

How to execute:

    Open terminal on root directory and run: nohup php -q socket_server.php "port" >/dev/null &
    Launch the web-server application (example: wamp, xampp, etc);
    Open Browser (see this link for Websocket API browser compatibility);
    Open the link: localhost/"project-folder"/socket_client.html;
    Choose the port and click on 'Go' button (same port used on terminal command);
    Use command navigate "folder" (example: /test)
    Websocket status: 0 - connecting; 1 - open; 2 - closing; 3 - closed;


Others:

    test.php used for terminal argv tests and folder list tests;
    log.txt file contains the log for server connections and infos;
    license MIT
