# INFLUENCIO

INFLUENCIO is an AI-powered influencer marketing platform that leverages data scraping and natural language processing to identify the most relevant influencers for brand campaigns. The platform automatically matches clients with the best influencers to promote their services or products.

## Project Overview

This project consists of a full-stack application that:
- **Scrapes social media data** using APIs from Instagram and TikTok
- **Processes and prepares** the collected data using natural language processing
- **Stores influencer profiles** in a structured database
- **Matches clients with influencers** based on service/product descriptions and uploaded images
- **Provides automated recommendations** for optimal influencer partnerships

## How It Works

1. **Data Collection**: The system continuously scrapes influencer data from Instagram and TikTok using their respective APIs
2. **Data Processing**: Raw social media data is cleaned, analyzed, and processed using NLP techniques to extract meaningful insights
3. **Database Storage**: Processed influencer profiles are stored in a structured database for quick retrieval
4. **Client Input**: Users can describe their service or product and optionally upload images
5. **AI Matching**: The system automatically analyzes the client's requirements and matches them with the most suitable influencers
6. **Recommendations**: Clients receive a curated list of influencers optimized for their specific campaign needs

## Project Structure

- `client/`: Next.js frontend application
- `server/`: Spring Boot backend application with API integration and AI processing

## Technology Stack

### Frontend
- **Next.js**: Modern React framework for the user interface
- **Image Upload**: Support for product/service image uploads

### Backend
- **Spring Boot**: Robust Java backend framework
- **Social Media APIs**: Integration with Instagram and TikTok APIs
- **Natural Language Processing**: AI-powered text analysis and matching
- **Database**: Structured storage for influencer profiles and client data

## Getting Started

### Frontend
Navigate to the `client` directory and follow the instructions in `client/README.md`.

### Backend
Navigate to the `server` directory and follow the instructions in `server/README.md`.

## Features

- 🔍 **Smart Data Scraping**: Automated collection from Instagram and TikTok
- 🧠 **AI-Powered Matching**: Intelligent influencer-client pairing
- 📊 **Data Processing**: Advanced NLP for profile analysis
- 🖼️ **Visual Recognition**: Support for image-based product matching
- 📈 **Campaign Optimization**: Data-driven influencer recommendations

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## License

This project is part of an AI-powered influencer marketing platform development initiative.
