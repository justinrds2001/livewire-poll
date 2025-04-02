# Polls App

## Overview

This is a simple Poll API application built as part of a Udemy course. The app allows users to create polls and vote on them. The app is built with Laravel and Livewire.

## Features

- Create polls with options
- Vote on polls

## Tech Stack

- **Laravel** - Main framework for backend and business logic
- **LiveWire** - Library on top on lavaral making dynamic page updates possible without writing JavaScript
- **Docker Compose** - Containerized development environment

## Installation

### Prerequisites

- Docker & Docker Compose for database & db client
- PHP ^8.2 installed on your machine (or with docker)
- Composer installed on your machine (or with docker)

### Steps

1. Clone this repository:
   ```sh
   git clone git@github.com:{github_username}/event-management.git
   cd event-management
   ```
2. Copy the environment file:
   ```sh
   cp .env.example .env
   ```
3. Install dependencies
   ```
   composer install
   ```
4. Generate app key
   ```
   php artisan key:generate --ansi
   ```
5. Start the database server using Docker Compose:
   ```sh
   docker-compose up -d
   ```
6. Run Laravel migrations and seed database (if needed):
   ```sh
   php artisan migrate --seed
   ```

## Usage

- Add new tasks through the UI
- Mark tasks as completed/incomplete
- Delete tasks when no longer needed

## Development

To start a development environment:

```sh
   php artisan serve
```
