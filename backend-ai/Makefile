.PHONY: deploy

deploy:
	git pull origin main && docker compose down && docker compose up -d --build && docker image prune --force