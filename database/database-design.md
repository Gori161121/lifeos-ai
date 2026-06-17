# Database Design

## Main Entities

### Users

- user_id
- full_name
- email
- created_date

---

### Goals

- goal_id
- user_id
- title
- category
- target_date
- status

---

### Projects

- project_id
- user_id
- title
- category
- status

---

### Tasks

- task_id
- project_id
- priority
- due_date
- status

---

### Habits

- habit_id
- user_id
- frequency
- tracking_status

---

### Notes

- note_id
- user_id
- title
- category
- content

---

### Decisions

- decision_id
- user_id
- decision_title
- context
- outcome

---

### AI Insights

- insight_id
- user_id
- generated_date
- recommendation
- confidence_score

---

## Technologies

- PostgreSQL
- Supabase
- Vector Database

---

## Future Expansion

- personal knowledge graph
- semantic search
- memory engine
- personal forecasting
- behavioral intelligence
