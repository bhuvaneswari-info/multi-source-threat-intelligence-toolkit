# Multi-Source Threat Intelligence Toolkit

## Overview
This project is a Python-based Threat Intelligence Toolkit designed to analyze suspicious IP addresses, domains, URLs, and file hashes by aggregating data from multiple threat intelligence platforms.

## Objective
- Understand threat intelligence aggregation
- Perform indicator reputation analysis
- Gain SOC Level 1 practical exposure

## Technologies Used
- Python
- Flask
- VirusTotal API
- AbuseIPDB API
- AlienVault OTX
- REST APIs

## Features
- IP reputation checking
- Domain and URL analysis
- File hash reputation lookup
- Multi-source result aggregation
- Basic input validation

## Project Structure
- Backend: Flask-based REST API
- Frontend: Simple HTTP server
- Secure API key handling using environment variables

## How to Run
1. Clone the repository
2. Create a virtual environment
3. Install dependencies using `requirements.txt`
4. Configure API keys in `.env`
5. Run `run.sh`

## Security Note
API keys are not included in this repository. Users must provide their own keys via environment variables.

## Author
Bhuvaneswari N  
MSc Cyber Security Student
