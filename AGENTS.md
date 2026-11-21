# Shop All - Monorepo
Stack: React ở /frontend, PHP Laravel ở /backend, DB MySQL
Chạy frontend: cd frontend && bun dev - port 5173
Chạy backend: cd backend && php artisan serve - port 8000
API base: http://localhost:8000/api
Cấu trúc:
- /frontend: React, chỉ Dev Frontend sửa
- /backend: Laravel, chỉ Dev Backend sửa
- /docs/API.md: Contract API, PM + Tech Lead viết
Luật:
- Không sửa trên main, luôn làm trong worktree
- Feature cần cả FE + BE: viết API.md trước, rồi mới code
- Skill: frontend-react cho /frontend, backend-php cho /backend
- QA phải test trước khi merge