# LLM Security Detection

This repository contains a project aimed at detecting sensitive personal information in user prompts to large language models (LLMs). The goal is to enhance the security and privacy of users interacting with LLMs by identifying potential security vulnerabilities.

## Project Overview

The project focuses on using regular expressions (regex) to detect various types of sensitive information in user inputs. The system will identify information such as:

- Credit Card Numbers
- Cryptocurrency Addresses
- Email Addresses
- IBAN Codes
- IP Addresses
- Personal Names
- Phone Numbers
- Social Security Numbers (SSNs)
- Bank Account Numbers
- UUIDs

## Features

- **Regex-based Detection**: Uses regex patterns to identify sensitive information.
- **Django Web Application**: A web-based interface to interact with a chatbot, integrated with the security detection system.
- **Real-time Monitoring**: Checks user inputs in real-time before sending them to the LLM.

## Installation

### Prerequisites

- Python 3.7+
- Django 3.1+
- Git

### Clone the Repository

```bash
git clone https://github.com/yourusername/LLM-Security-Detection.git
cd LLM-Security-Detection
