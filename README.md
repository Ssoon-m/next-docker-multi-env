# next-docker-multi-env

## 로컬 실행

```bash
pnpm install
pnpm dev
```

## 도커로 실행 (Makefile이용)

### 개발 환경

```
make build-development
make start-development
```

Open <http://localhost:3001>

### 프로덕션 환경

```
make build-production
make start-production
```

Open <http://localhost:3003>
