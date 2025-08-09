# ai-code-analyzer
A simple practice run to see how chatgpt (AI) sued old array assignemtment and make them more efficient  


## How It Worked
- A sample C++ file is provided (AI_codee.cpp)
- Promted chatGPT " Can you analyze this C++ code and suggest improvements for readability, performance, and best practices?”
- Gave me multiple options that looked through to see which one worked with my C++ version and had the best readabilty 
- chatGPT said it was better because:
    1. Uses standard containers (std::array) – safer than raw arrays, automatically knows its size.
    2. Uses std::sort – faster (O(n log n)) and less error-prone than manual bubble sort.
    3. Avoids using namespace std; – prevents name conflicts and keeps code clear.
    4. Clean, short, and reusable – easy to read, works for any type, and simple to modify.
       
- Suggestions are saved in `analysis_report.md`
