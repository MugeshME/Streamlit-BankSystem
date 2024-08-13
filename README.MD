OVERVIEW: The Banking Services program is developed using Streamlit for the front-end interface and MongoDB for the database. The program allows users to perform various banking activities, including opening accounts, viewing account details, depositing money, withdrawing money, and checking balances. This document outlines the tools used and topics covered in the program. TOOLS USED:

Streamlit: A Python library used for creating interactive web applications. In this program, Streamlit is used to create the user interface, enabling users to interact with the system through forms and buttons.
MongoDB: A NoSQL database used to store user information and transaction records. The pymongo library is utilized to interact with the MongoDB database.
PIL (Python Imaging Library): A library for opening, manipulating, and saving image files. It is used to handle user-uploaded images for account creation.
Base64: A method for encoding binary data (like images) into ASCII text. This is used to store images in the MongoDB database.
IO (Input/Output): A core Python module used for managing streams, in this case, to handle image data. TOPICS COVERED: Opening an Account:
