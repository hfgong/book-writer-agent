# Book Writer Agent Guide

This repository contains documentation and guidelines for AI agents collaborating on book writing projects using LaTeX and TikZ.

## Overview

The `AGENTS.md` file provides comprehensive instructions for AI agents working on technical book authoring. It serves as a persistent knowledge base to ensure consistency and quality across multiple writing sessions that may span months or years.

## Key Features

### 📚 Structured Workflow
- Guidelines for resuming work across multiple sessions
- Systematic approach to understanding project status and next steps
- Support for long-term book development projects

### 🏗️ LaTeX/TikZ Architecture
- Three-level organization: part/chapter/section
- Modular compilation system using Makefiles
- Standalone figure compilation for efficient processing
- Bibliography management for academic references

### 🎨 Technical Diagrams
- Best practices for TikZ diagram creation
- Common pitfalls and solutions for figure compilation
- Consistency guidelines for visual elements

### 🔬 Research-First Approach
- Emphasis on literature research before writing
- Structured outlining at multiple levels
- Diagram/table/formula-driven writing methodology

## Usage

### With Claude CLI

1. Copy `AGENTS.md` to the root directory of your book project repository
2. Optionally rename to `CLAUDE.md` for automatic detection by Claude CLI
3. Start Claude CLI in your book project directory:
   ```bash
   claude
   ```
4. Claude will automatically read the instructions and follow the guidelines when working on your book

### With Gemini CLI

1. Copy `AGENTS.md` to the root directory of your book project repository
2. You may need to rename the file to `GEMINI.md` based on Gemini CLI's configuration requirements
3. Start Gemini CLI in your book project directory and reference the instructions file
4. The agent will use these guidelines to maintain consistency across writing sessions

### General Setup

- Place the file at the top level of your book project repository
- Ensure the file is accessible to the AI agent during sessions
- The agent will automatically reference these guidelines when resuming work
- Consider creating a `handover.md` file at the end of each session for continuity

## Requirements

- LaTeX distribution (preferably with LuaLaTeX)
- TikZ package for technical diagrams
- Make utility for build automation
- Bibliography management tools (BibTeX/BibLaTeX)

## Contributing

When working on the book project, agents should:
- Review existing materials before making changes
- Follow the established directory structure
- Maintain consistency in writing style and technical implementation
- Update handover notes for the next session

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
