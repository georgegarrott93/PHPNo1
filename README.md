# PHPNo1
PHP Repository

George Garrott, Giedrius Dzinga and Chetan Gohel

Objective - The EE SMS server accepts SMS/GPRS messages and stores them in XML format. The EE
M2M Connect web-service makes these stored messages available to be downloaded via the
EE SOAP server. Once a message has been downloaded by a SOAP client it can be parsed
and the embedded data extracted, sanitised, validated and stored in a local database. After
the data has been downloaded and stored, then web-page reports can be prepared on demand
by a user.

Once an initial web-report has been created and displayed on a user’s browser, AJAX or
JSON could be used to dynamically update the reporting web-page when subsequent
messages are downloaded and processed. Emails or SMS messages could notify users of the
arrival of a message; numerical data such as temperatures could be displayed as a chart, SMS
messages could be used to update the status of the circuit board (this will be a simulation).

The server that downloads and processes the SMS messages (and subsequently makes the
data available to clients) will be implemented in Object Oriented PHP with MySQL as the
database server. You also have to publish your finished application on the public facing PHP
and MySQL servers. Be careful to remove any code you have written for debugging purposes
before uploading your application.

NB a Rich Internet Application (RIA) is not required – the majority of all processing will be
achieved via PHP on the server.
