.PHONY: up down

COMPOSE_DIR := directus-promoter
SOURCE_COMPOSE := $(COMPOSE_DIR)/docker-compose-source.yml
TARGET_COMPOSE := $(COMPOSE_DIR)/docker-compose-target.yml

up:
	docker compose -f $(SOURCE_COMPOSE) up -d
	docker compose -f $(TARGET_COMPOSE) up -d

down:
	docker compose -f $(SOURCE_COMPOSE) down
	docker compose -f $(TARGET_COMPOSE) down
