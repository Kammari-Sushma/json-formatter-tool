# JSON Formatter & Validator  

Format, minify, and validate JSON instantly in your browser. Clean UI, dark mode, zero dependencies.  

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1a104e9e-065c-4de3-97b1-973d9c8baf7c" />  

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/974b9507-5d77-4e7c-864c-65c93279aecf" />  


## Features  

- **Format JSON**: Pretty-print with 4-space indentation  
- **Minify JSON**: Compress to single line for APIs or storage  
- **Live Validation**: Instant syntax checking with detailed error messages  
- **Dark/Light Mode**: Auto-detects system theme + manual toggle, saved to localStorage  
- **Responsive UI**: Works on mobile + desktop  
- **Zero Dependencies**: Pure HTML/CSS/JS, runs offline  


## Usage

1. Paste your JSON into the textarea  
2. Click `Format JSON` to pretty-print with indentation  
3. Click `Minify` to compress it   
4. Click `Clear` to reset  
5. Invalid JSON shows error details with the exact issue  

## Tech Stack  

- **Frontend**: HTML5, CSS3 with CSS variables  
- **Logic**: Vanilla JavaScript + `JSON.parse`/`JSON.stringify`  
- **Font**: Inter for UI, Fira Code for JSON editor  

## Local Setup  

No build step needed.  

```bash
git clone <your-repo-url>
cd json-formatter-tool
open index.html
