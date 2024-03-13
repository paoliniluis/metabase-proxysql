# Project Name

Metabase + ProxySQL + MySQL

## Description

Metabase connecting to ProxySQL acting as a proxy of MySQL

## Prerequisites

Docker

## Installation

1. Clone the repository.
2. Install the necessary dependencies.
3. `docker compose up`

## Usage

Just go to localhost:3000 after it starts

## Considerations

If you're using a Mac with ARM architecture then you might probably face some errors. Simply bundle the Metabase application inside a debian container to make it work (check the Metabase repo)