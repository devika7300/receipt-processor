# Receipt Processor

## Overview
The Receipt Processor is a simple web service designed to process receipts and calculate points based on specific business rules. This project is implemented using Go and can be run within a Docker container.

## Features
- Process receipt data via a REST API.
- Calculate points based on the receipt contents.
- Store receipt data in-memory (no persistent storage).

## Prerequisites
- Docker
- Go (optional for local development without Docker)

## Installation

### With Docker
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/receipt-processor.git
   cd receipt-processor

2. Build the Docker image:
    docker build -t receipt-processor .

3. Run the Docker container:
    docker run -d -p 8080:8080 receipt-processor

### Without Docker
    go run main.go


