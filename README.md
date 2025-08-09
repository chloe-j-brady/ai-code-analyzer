# ai-code-analyzer

This is a simple practice run to see how ChatGPT (AI) can take an old array-based C++ assignment and make it more efficient, readable, and aligned with modern best practices.

## Overview
The project started with a basic C++ program using a raw array and manual bubble sort. The goal was to have ChatGPT analyze the code and suggest improvements for:

- Readability 
- Performance 
- Best Practices

## Process
1. Provided a sample C++ file: AI_code.cpp  
2. Prompted ChatGPT:  
    *"Can you analyze this C++ code and suggest improvements for readability, performance, and best practices?”*  
3. Received multiple improved versions of the code.  
4. Tested each version to ensure compatibility with my C++ setup and compared readability.  
5. Selected the final version based on clarity, maintainability, and modern C++ conventions.

## Why the Final Version is Better
1. Uses standard containers (std::array) – safer than raw arrays and automatically knows its size.  
2. Uses std::sort – faster (*O(n log n)*) and less error-prone than manual bubble sort.  
3. Avoids using namespace std;  – prevents name conflicts and keeps code clear.  
4.Clean, short, and reusable – easy to read, works for any type, and simple to modify.  

## Files
- AI_code.cpp 
   -  Original C++ code provided for analysis.  
- analysis_report.md 
    - Contains ChatGPT’s suggestions and reasoning for the improvements.  

