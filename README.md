# Fake Server in Python

A simple fake server built using Python to simulate server responses for testing and development purposes.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This Python-based fake server is designed to simulate various server responses. It is useful for developers who need to test client-side applications or integrations without relying on a live server.

The server allows you to set up different endpoints and customize responses such as status codes, headers, and payloads.

## Features
- Easily set up multiple endpoints.
- Customize HTTP response codes.
- Serve static and dynamic content.
- Simulate various delay times for response.
- JSON and text-based response support.
- Lightweight and easy to configure.

## Installation

### Prerequisites
Ensure you have the following installed:
- [Python 3.x](https://www.python.org/)
- [pip](https://pip.pypa.io/en/stable/)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/vishuchauhan27/HTTP_redirect.py
   cd fake-server-python
{
  "/api/test": {
    "status": 200,
    "content-type": "application/json",
    "response": {
      "message": "This is a fake response"
    }
  }
}

{
  "/api/users": {
    "status": 200,
    "content-type": "application/json",
    "response": {
      "users": ["user1", "user2", "user3"]
    }
  },
  "/api/error": {
    "status": 500,
    "content-type": "application/json",
    "response": {
      "error": "Internal Server Error"
    }
  }
}
