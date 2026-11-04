# JSON2Table

A simple and dynamic application that converts JSON data into a clean and easy-to-read table format.

## 📌 About the Project

JSON responses are commonly used when working with APIs and AI applications. However, reading large JSON objects manually can sometimes be difficult because the data is displayed as multiple key-value pairs.

**JSON2Table** solves this problem by taking JSON data as input and dynamically displaying it in a structured table format.

Instead of viewing data like this:

```json
{
  "ui": "hello",
  "name": "Ritam",
  "status": "success"
}
```

The application converts it into a clean table:

| Key | Value |
|-----|-------|
| ui | hello |
| name | Ritam |
| status | success |

## ✨ What the Application Does

- Accepts JSON data as input.
- Dynamically reads the JSON structure.
- Detects JSON keys and their corresponding values.
- Converts the data into a clean table format.
- Displays the result in an easy-to-read user interface.
- Works dynamically without hardcoding specific JSON keys.

## 🔄 How It Works

```text
JSON Input
    ↓
Read JSON Data
    ↓
Detect Keys and Values
    ↓
Process Data Dynamically
    ↓
Display in Table Format
```

## 💡 Example

### JSON Input

```json
{
  "ui": "hello",
  "name": "John",
  "age": 22,
  "status": "active"
}
```

### Table Output

| Key | Value |
|-----|-------|
| ui | hello |
| name | John |
| age | 22 |
| status | active |

## 🎯 Purpose

The main goal of this project is to make JSON data easier to understand and visualize.

Instead of manually checking JSON key-value pairs, users can quickly view the data in a structured and readable table.

This can be useful when testing:

- API responses
- AI-generated JSON responses
- Application data
- JSON objects
- Dynamic key-value data

## 🚀 Key Feature

The application is **dynamic**.

You do not need to define the JSON keys manually in the code.

For example, if the input changes from:

```json
{
  "name": "John"
}
```

to:

```json
{
  "product": "Laptop",
  "price": 50000,
  "available": true
}
```

The application will automatically display the new keys and values in the table.

## 📋 Project Flow

```text
User Provides JSON
        ↓
Application Parses JSON
        ↓
Application Dynamically Reads Keys
        ↓
Application Reads Corresponding Values
        ↓
Application Generates Table Rows
        ↓
Clean Table Displayed to User
```

## 🛠️ Future Improvements

Possible features that can be added in the future:

- Support for nested JSON objects.
- Support for JSON arrays.
- JSON validation.
- Error handling for invalid JSON.
- Copy table data.
- Download table data.
- Dark mode.
- Search and filter functionality.
- Export data to CSV or Excel.

## 📖 Summary

**JSON2Table** is a simple JSON visualization application that transforms JSON key-value data into a clean, dynamic, and readable table.

The goal is simple:

> **Provide JSON → Get a Clean Table**

This makes JSON responses easier to read, understand, and analyze.
