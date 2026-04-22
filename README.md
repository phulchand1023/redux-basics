This is a simple Todo Application built while learning the fundamentals of Redux Toolkit and React.

The project focuses on understanding how global state management works using Redux, including creating slices, dispatching actions, and accessing state with hooks.

🚀 Features
➕ Add a new todo
❌ Delete a todo
🔄 Toggle todo completion
📦 Centralized state management using Redux
🧠 What I Learned

While building this project, I practiced:

Setting up a Redux store using configureStore
Creating slices using createSlice
Writing reducers for state updates
Using useSelector to read state
Using useDispatch to trigger actions
Understanding the difference between:
Named exports vs default exports
Mutation vs immutable updates (handled internally by Immer)
📂 Project Structure
src/
│
├── app/
│   └── store.js          # Redux store configuration
│
├── features/
│   └── todoSlice.js      # Slice with reducers & actions
│
├── App.jsx               # Main UI logic
├── main.jsx              # Entry point with Provider
⚙️ Tech Stack
React
Redux Toolkit
React Redux
▶️ Getting Started
npm install
npm run dev
⚠️ Note

Currently, todos are stored in-memory (Redux store only).
This means data will be lost on page refresh.

🔮 Future Improvements
Persist todos using localStorage
Add edit functionality
Filter todos (All / Completed / Pending)
Improve UI/UX
📌 Purpose

This project was built as part of learning the basics of Redux and state management, focusing more on concepts than production-level features.