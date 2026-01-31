# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Initialization & Configuration**
  Initialize a new TanStack Start project. Configure Tailwind CSS for styling and set up the basic folder structure. verify the development server runs successfully.

- [ ] ⏳ **Database Setup & Schema Definition**
  Set up Drizzle ORM with a local SQLite database. Define the schema for 'issues', 'users' (mock), and 'comments'. Run the initial migration to create the database file.

- [ ] ⏳ **App Shell & Navigation Layout**
  Create the root layout component using TanStack Router. Implement a responsive sidebar navigation and a top header. Include placeholder links for Dashboard, Issues, and Settings.

## Phase 2

- [ ] ⏳ **Issue List View with Server Loader**
  Implement the '/issues' route. Create a Server Function (loader) to fetch all issues from Drizzle. Render the data in a clean data table or list view. Handle the 'loading' state.

- [ ] ⏳ **Create Issue Mutation**
  Create a 'New Issue' modal or page. Implement a Server Function to handle form submission and insert a new issue into the DB. Use TanStack Query's invalidation to refresh the list automatically upon success.

- [ ] ⏳ **Issue Detail View (Dynamic Route)**
  Implement the '/issues/$issueId' route. Create a loader to fetch a single issue by ID. Display the title, description, status, and priority. Handle 404s if the issue doesn't exist.

- [ ] ⏳ **Status & Priority Updates**
  Add dropdowns to the Issue Detail view to change Status and Priority. Implement the Server Function for the update. CRITICAL: Implement optimistic updates so the UI reflects the change immediately before the server responds.

## Phase 3

- [ ] ⏳ **Comments System Backend & UI**
  Add a comments section to the Issue Detail view. Create a server function to post a comment and a loader to fetch comments for the issue. Display them in a chronological list.

- [ ] ⏳ **Dashboard Metrics**
  Implement the home dashboard. Create a loader that performs aggregation queries (count of open bugs, distribution by priority) and render summary cards/charts.

- [ ] ⏳ **URL-Based Filtering**
  Enhance the Issue List (Task 4) to support filtering by status and priority using URL search parameters. Ensure the loader reads these params to filter the DB query efficiently.

## Phase 4

- [ ] ⏳ **UI Polish & Error Boundaries**
  Add a global error boundary for graceful failure handling. Polish the UI with consistent spacing, typography, and empty states for lists. Add loading skeletons.

---

_Last updated by dev0 automation_
