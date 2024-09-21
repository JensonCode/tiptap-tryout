# Tiptap Integration in a Next.js Application

## Overview

This project is a demonstration of using **Tiptap** in a Next.js application. The goal is to build a fully functional article form with rich text editing capabilities, utilizing **shadcn-ui** components and Next.js features.

## Scope

- Implement an article creation form in **Next.js**.
- Utilize **shadcn-ui** components for the UI.
- Integrate a **Rich Text Editor** using **Tiptap**.
- Enable server-side rendering (SSR) for SEO optimization and performance.

## Goal

The primary goal is to allow content editing with **custom JSX elements** and ensure the articles are server-side rendered for improved SEO. This creates a functional and interactive blog solution.

## Why Tiptap?

**Tiptap** is a widely-used choice for rich text editing due to its ease of setup and extensive customization options. It supports adding custom JSX elements through its content extensions, making it highly flexible for dynamic applications.

## Thought Process

1. **Define the Schema**:
   - Use **TypeScript interfaces** and **Zod** schemas for type safety and validation.
   
2. **Create Forms**:
   - Develop forms for creating and updating articles.
   
3. **Mock Data**:
   - Incorporate mock data for testing and development purposes.
   
4. **Render Articles**:
   - Style and display articles using the appropriate components and SSR for performance.
