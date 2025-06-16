# Jokes-by-API-Ninjas MCP Server

Welcome to the Jokes-by-API-Ninjas MCP Server! This server is designed to provide you with an endless stream of laughter by delivering a wide range of jokes sourced from the internet. Whether you're interested in pop culture, science, history, or other fascinating topics, this server has something to tickle your funny bone.

## Overview

The Jokes-by-API-Ninjas MCP Server offers an efficient and reliable service with the following attributes:

- **Popularity:** 9.7
- **Service Level:** 100%
- **Latency:** 220ms

## Features

### Large Collection of Jokes

Access a comprehensive collection of jokes from various genres. The server ensures you get a mix of humor from different areas, keeping your content fresh and engaging. Note that while most jokes are light-hearted and fun, some may contain content that could be deemed inappropriate or offensive.

### Easy Integration

The server is designed for seamless integration, allowing you to incorporate it into your projects with minimal effort. You can experiment with different endpoints and see the results immediately, making it easy to adapt the service to your needs.

## Tool List

The server includes the following tools to help you access and manage jokes effectively:

- **Endpoint Group:** `/v1/jokes`
  - **Function Name:** `/v1/jokes`
  - **Description:** This is the primary endpoint of the Jokes-by-API-Ninjas server, providing access to the jokes collection.

## Tool Declarations

The server provides a structured way to query jokes with specific parameters:

- **Function:** `v1_jokes`
  - **Description:** Access the endpoint for retrieving jokes.
  - **Parameters:**
    - **Name:** `limit`
    - **Optional:** Yes
    - **Type:** String
    - **Description:** Specifies the number of jokes to return. Must be between 1 and 30, with a default value of 1.

## Usage

To get started with the Jokes-by-API-Ninjas MCP Server, simply use the `/v1/jokes` function to retrieve a selection of jokes. Adjust the `limit` parameter according to your needs to control the number of jokes returned in a single request.

Dive into the world of humor and discover what the Jokes-by-API-Ninjas MCP Server can do for you today!