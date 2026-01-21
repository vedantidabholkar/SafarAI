# SafarAI

✈️ AI-Powered Travel Planner
An end-to-end AI-powered travel planning system that allows users to search for flights, find hotels, and generate personalized travel itineraries using Agentic AI.

This project demonstrates how to build a real-world GenAI application using FastAPI, Streamlit, CrewAI, and Large Language Models (LLMs), integrated with real-time travel data from SerpAPI.

🚀 Features
🔍 Real-time flight search using Google Flights (via SerpAPI)
🏨 Real-time hotel search using Google Hotels (via SerpAPI)
🤖 AI-powered recommendations for best flights and hotels
🧠 Agentic AI architecture using CrewAI
📅 AI-generated day-by-day travel itinerary
⚡ Async FastAPI backend for performance
🖥️ Interactive Streamlit frontend
📥 Downloadable itinerary (Markdown)


🏗️ System Architecture
Flow Overview:

User enters travel details via Streamlit UI
Streamlit sends requests to FastAPI backend
FastAPI fetches real-time data from SerpAPI
CrewAI agents analyze flight & hotel options
AI recommends best options
LLM generates a complete travel itinerary
Results are returned and displayed in the UI


🧠 Agentic AI Design
This system uses multiple AI agents, each with a specific role:

✈️ Flight Analyst Agent
Evaluates price, duration, stops, and comfort
🏨 Hotel Analyst Agent
Analyzes price, rating, location, and amenities
📅 Travel Planner Agent
Generates a structured day-by-day itinerary
Agents collaborate using CrewAI and are powered by LLMs.

🛠️ Tech Stack
Backend
FastAPI
Python (Async / asyncio)
Pydantic
CrewAI
OpenAI / LLMs
SerpAPI
Frontend
Streamlit
Other Tools
dotenv (Environment variables)
Uvicorn (ASGI server)
Logging

