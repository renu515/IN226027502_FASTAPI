# FastAPI Internship Assignment

This repository contains the solution for **FastAPI Day 1 Assignment**.

## Folder Structure

IN226027502_FASTAPI  
└── ASSIGNMENT 1  
    ├── main.py  
    ├── Q1_Output.png  
    ├── Q2_Output.png  
    ├── Q3_Output.png  
    ├── Q4_Output.png  
    ├── Q5_Output.png  
    └── Q6_Output.png  

## How to Run

Install dependencies:

pip install fastapi uvicorn

Run the server:

uvicorn main:app --reload

Open in browser:

http://127.0.0.1:8000/docs

## Endpoints Implemented

- `/products`
- `/products/category/{category_name}`
- `/products/instock`
- `/store/summary`
- `/products/search/{keyword}`
- `/products/deals`
