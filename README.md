# Atlan-Backened-Challenge

## Task1:
One of our clients wanted to search for slangs (in local language) for an answer to a text question on the basis of cities (which was the answer to a different MCQ question)

- Approach: 
I use language detection library called langdetect that supports 55 languages.This helps me to find out the result with language code.

## Task2:
A market research agency wanted to validate responses coming in against a set of business rules (eg. monthly savings cannot be more than monthly income) and send the response back to the data collector to fix it when the rules generate a flag

- Approach:
I created one excel file and check the conditions that market research agency wanted  and send back the responses .

## Task3:
A very common need for organizations is wanting all their data onto Google Sheets, wherein they could connect their CRM, and also generate graphs and charts offered by Sheets out of the box. In such cases, each response to the form becomes a row in the sheet, and questions in the form become columns. 

- Approach:
I used xlwt library it helps to create spreadsheets files compatible with MS-Excel versions 95 to 2003. I added a sheet to write the data in that sheet

## Task4:
A recent client partner wanted us to send an SMS to the customer whose details are collected in the response as soon as the ingestion was complete reliably. The content of the SMS consists of details of the customer, which were a part of the answers in the response. This customer was supposed to use this as a “receipt” for them having participated in the exercise.

- Approach:
I created a database named clien_data and  give some data,here in task i use two libraries SMTP,SSL.
Simple Mail Transfer Protocol(SMTP) is used  SMTP client session object that can be used to send mail to any internet machine with an SMTP .
Secure Sockets Layer  module provides access to Transport Layer Security encryption and peer authentication facilities for network sockets, both client-side and server-side. This module uses the OpenSSL library. It is available on all modern Unix systems, Windows, macOS, and probably additional platforms, as long as OpenSSL is installed on that platform.
