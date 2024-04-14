# YOUTUBE-DATA-HARVESTING-AND-WAREHOUSING using Python, SQL , Pandas and Streamlit

Introduction

YouTube Data Harvesting and Warehousing is a project that aims to allow users to access and analyze data from multiple YouTube channels. The project utilizes SQL, Pandas and Streamlit to create a user-friendly application that allows users to retrieve, store, and query YouTube channel and video data.

Project Overview:The YouTube Data Harvesting and Warehousing project consists of the following components:

Streamlit Application: A user-friendly UI built using Streamlit library, allowing users to interact with the application and perform data retrieval and analysis tasks.

YouTube API Integration: Integration with the YouTube API to fetch channel and video data based on the provided channel ID.

SQL Data : Migration of data from the data lake to a SQL database, allowing for efficient querying and analysis using SQL queries.

Technologies Used

The following technologies are used in this project:

Python: The programming language used for building the applications.

Streamlit: A Python library used for creating interactive web applications .

YouTube API: Google API is used to retrieve channel and video data from YouTube.

SQL (MySQL): A relational database used as a data warehouse for storing migrated YouTube data.

TOOLS AND LIBRARIES USED:

This project requires the following components:

PYTHON: Python is a powerful programming language renowned for being easy to learn and understand. Python is the primary language employed in this project for the development of the complete application, including data retrieval, processing, analysis.

STREAMLIT: Streamlit library was used to create a user-friendly UI that enables users to interact with the programme and carry out data retrieval and analysis operations.

GOOGLE API CLIENT: The googleapiclient library in Python facilitates the communication with different Google APIs. Its primary purpose in this project is to interact with YouTube's Data API v3, allowing the retrieval of essential information like channel details, video specifics, and comments. By utilizing googleapiclient, developers can easily access and manipulate YouTube's extensive data resources through code.

MySQL: MySQL is an open-source, advanced, and highly scalable database management system (DBMS) known for its reliability and extensive features. It provides a platform for storing and managing structured data, offering support for various data types and advanced SQL capabilities.

REQUIRED LIBRARIES:

1.googleapiclient.discovery
2.streamlit
3.Mysql
4.pandas

Installation and Setup

To run the YouTube Data Harvesting and Warehousing project, follow these steps:

Install Python: Install the Python programming language on your machine.

Install Required Libraries: Install the necessary Python libraries using pip or conda package manager. Required libraries include Streamlit, MongoDB driver, SQLAlchemy, Pandas, and Matplotlib.

Set Up Google API: Set up a Google API project and obtain the necessary API credentials for accessing the YouTube API.

Configure Database: Set up a  SQL database (MySQL) for storing the data.

Configure Application: Update the configuration file or environment variables with the necessary API credentials and database connection details.

Run the Application: Launch the Streamlit application using the command-line interface

Features

The YouTube Data Harvesting and Warehousing application offers the following features:

Retrieval of channel and video data from YouTube using the YouTube API.
Storage of data in a SQL database as a data lake.
Migration of data from the data lake to a SQL database for efficient querying and analysis.
Search and retrieval of data from the SQL database using different search options, including joining tables.
Support for handling multiple YouTube channels and managing their data.

Conclusion

The YouTube Data Harvesting and Warehousing project provides a powerful tool for retrieving, storing, and analyzing YouTube channel and video data. By leveraging Python, SQL, and Streamlit, users can easily access and manipulate YouTube data in a user-friendly interface. The project offers flexibility, scalability empowering users to gain insights from the vast amount of YouTube data available
