# Jotform Frontend Hackathon: Submissions Dashboard

Welcome to the Jotform Frontend Hackathon! 

In this challenge, you will build a **Submissions Dashboard**, a core part of the Jotform product experience. Users need to be able to see their forms, view the data submitted to those forms, and easily find specific information.

We are looking for a complete, well-structured frontend application. You should aim to build a fully functional product experience, focusing on clean architecture, component reusability, and a seamless user interface.

## 🎯 The Challenge

You are provided with two main data entities:
1.  **Forms:** The templates created by users.
2.  **Submissions:** The actual data entries filled out by respondents for specific forms.

Your task is to build a React application that fetches this data and presents it in a clear, navigable, and highly usable dashboard.

## ✅ Core Requirements

1.  **Data Fetching & State:**
    * Fetch the `forms` and `submissions` data. (You can mock an API call using `setTimeout` and the provided JSON, or use `json-server`).
    * Handle loading states gracefully (e.g., skeletons or spinners).
    * Handle potential error states.

2.  **Form Listing:**
    * Display a list or grid of all forms.
    * Show key details: Title, Status (Active/Archived), and Submission Count.

3.  **Exploring Relationships (The Detail View):**
    * When a user clicks on a specific Form, display a detailed view showing all `submissions` associated with that `formId`.
    * The submissions should be displayed in a tabular format or an organized list.

4.  **Search & Filtering:**
    * Implement a search bar to filter forms by title.
    * *Bonus:* Allow searching within the submissions of a selected form (e.g., searching for a specific respondent's name).

5.  **Submission Inspection:**
    * Provide a way to click on a specific submission row to view a "Details Modal" or a "Side Panel" showing the complete raw answers (the `answers` object) and metadata (IP address, submission date).

## 🛠️ Technical Constraints & Freedoms

* **Framework:** React (Vite, Next.js, or CRA are all acceptable).
* **Styling:** You have complete freedom. CSS Modules, Tailwind CSS, Styled Components, or raw CSS. Focus on a clean, professional "Jotform-like" aesthetic. 
* **Libraries:** You may use standard libraries for routing (e.g., React Router) and icons (e.g., Lucide React, React Icons). 

## 📝 Evaluation Criteria

* **Product Thinking:** Is the hierarchy of information clear? Is it easy to switch between forms and view their data?
* **Code Quality:** Are your components appropriately sized? Is your state management logical?
* **UI/UX:** Does the application look and feel like a finished product rather than a rough sketch? Are loading and empty states considered?

## ⏱️ Timeline Reminder

* **10m:** Bootstrap project (React setup, Tailwind/CSS config).
* **10m:** Read this document, plan state structure.
* **2h 25m:** Build the solution (Routing, Fetching, UI Components).
* **15m:** Cleanup, add comments, commit, and push.

Good luck!
