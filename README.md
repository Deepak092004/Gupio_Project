# Inventory Backend -> Task Tracker Backend

This backend provides a simple Task Tracker REST API using Node.js, Express and MongoDB.

Endpoints:

- `GET /api/tasks` - list tasks (query: `assigneeId`, `status`)
- `POST /api/tasks` - create task { title, description, assigneeId, dueDate }
- `GET /api/tasks/:id` - get task
- `PATCH /api/tasks/:id` - update task fields
- `DELETE /api/tasks/:id` - delete task
- `GET /api/users` - list users
- `POST /api/users` - create user { name, email }

Run:

1. Create `.env` with `MONGO_URI` or use local MongoDB (default: `mongodb://127.0.0.1:27017/tasktracker`).
2. `npm install` in `inventory-backend`.
3. `npm run dev` (or `npm start`). 
