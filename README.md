## Command

```bash
git clone git@github.com:1Rhino/docker_ruby.git
docker compose build
docker compose up -d
```

## Command to update docker

```bash
git pull origin main
docker compose build
docker compose down
docker compose up -d
```

### Command to run app

```bash
docker compose exec app irb
docker compose exec app ruby hello_world.rb
```
