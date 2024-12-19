## 配置信息:
- Redis:
    - https://console.upstash.com/redis/773473b1-369d-4196-872a-deb6a7128641?teamid=0
- Email:
    - https://resend.com/onboarding
- sanity无头CMS:
    - https://www.sanity.io/manage/personal/project/jrdwogmo/datasets?name=wenhaofree-blog
- 登录认证clerk:
    - https://dashboard.clerk.com/apps/app_2qR5nwiHtqalOoYLOyKy9h7dsCq/instances/ins_2qR5nyjaRazuQniqX5fjtzNbqsl
- 数据库Neon:
    - https://console.neon.tech/app/projects/raspy-poetry-81279255/branches/br-bitter-heart-a13z6tx6/tables?database=neondb

## 本地启动顺序:
1. 确认所有配置正确
2. pnpm install
3. pnpm run db:generate
4. pnpm run db:push
5. pnpm dev
6. 访问http://localhost:3000


