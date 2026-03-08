# SchemeSense AI

SchemeSense AI is a prototype system that helps citizens quickly identify government welfare schemes they are eligible for.

The system analyzes user inputs such as age, income, and state, and recommends suitable government schemes with clear explanations.

## Problem

Many citizens are unaware of government schemes they qualify for because eligibility conditions are complex and information is scattered across multiple portals.

## Solution

SchemeSense AI simplifies this process by providing:

- Scheme eligibility analysis
- AI-style reasoning explanation
- Recommended government schemes
- Direct application links

## Features

- Voice and text input
- Multilingual interface (English, Telugu, Hindi)
- Eligibility reasoning engine
- Recommended scheme ranking
- Simple and accessible user interface

## Architecture

Frontend → API Gateway → AWS Lambda → DynamoDB → AI reasoning layer

The architecture is designed for integration with Amazon Bedrock for large-scale AI reasoning.

## Prototype

Users enter:

- Age
- Income
- State

The system evaluates scheme conditions and returns recommended schemes with explanations.

## Technology Stack

Frontend: HTML, CSS, JavaScript  
Backend: AWS Lambda  
API Layer: Amazon API Gateway  
Database: Amazon DynamoDB  
Voice Input: Web Speech API

## Demo

Live prototype:  
https://rohi-nagedram.github.io/schemesense/

## Impact

SchemeSense AI helps citizens easily discover welfare schemes they qualify for, improving access to government benefits and reducing application confusion.
