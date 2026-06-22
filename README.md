# JSON Validator

This is a Java project that implements a JSON parser and validator from scratch. It uses custom-built lexical analysis and parsing logic instead of relying on external libraries.

## What it does
- Breaks JSON input into tokens using a custom lexer  
- Parses JSON structures including objects, arrays, and primitive values  
- Handles nested JSON formats correctly  
- Detects and reports syntax errors in invalid JSON  
- Includes unit tests written with JUnit

## Tech Stack
- Java  
- JUnit

## Project Structure
src/main/
├── JSONLexer.java
├── JSONParser.java
├── Main.java
└── Token.java

src/test/
└── JSONValidatorTest.java

## Example

Valid JSON:
{
  "city": "London"
}

Invalid JSON:
{
  "city": "London",
}
