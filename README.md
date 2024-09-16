# DBMS_Property_Finder 🏠

Welcome to the DBMS_Property_Finder project! This system provides a comprehensive database model to manage property-related information, including ownership, client reviews, and transactions. With a focus on strong entities and their interactions, this project ensures an efficient way to handle property data.

## Overview 🌟

The database model features the following key components:
- **Entities:**
  - **Owner:** Represents individuals or organizations that own properties.
  - **Client:** Represents individuals who review properties and engage in transactions.
  - **Property:** Represents real estate units available in the system.
  - **Location:** Represents the geographical location where properties are situated.

- **Relationships:**
  - **Owns:** Connects Owners to their Properties.
  - **Makes:** Connects Clients to their Reviews of Properties.
  - **Transacts:** Connects Clients to Transactions with Owners.
  - **Has:** Links Properties to their Location.

## Assumptions 📝

- Each Client can provide only one review per Property.
- Each Property is uniquely associated with a detailed Address through the Location entity.
- Owners and Clients transact based on individual preferences or circumstances.

## Project Components 🔍

1. **Database Schema:**
   - The schema defines the structure of the database, including tables, relationships, and constraints.

2. **SQL Code:**
   - Contains SQL scripts for creating tables, relationships, and sample data.

3. **Oracle Forms Builder (FMB) File:**
   - Includes the `.fmb` file used to design and manage database forms.

## Getting Started 🚀

1. **Set Up the Database:**
   - Use the provided SQL code to create the database schema and populate it with initial data.
   - Ensure all relationships and constraints are correctly implemented.

2. **Use Oracle Forms Builder:**
   - Open the `.fmb` file in Oracle Forms Builder to access and modify the forms.
   - Customize the forms according to your needs and preferences.

3. **Explore and Test:**
   - Use the database schema and forms to manage properties, clients, and transactions.
   - Test the functionality to ensure all interactions and relationships are correctly handled.
