# Experiment 09: System Monitoring using Prometheus and Grafana

## Aim

To monitor system and application metrics by collecting them with Prometheus, visualizing them in Grafana, and configuring an alert.

## Technologies Used

* Docker
* Docker Compose
* Prometheus
* Grafana
* Node Exporter

## Project Description

This project provides a containerized monitoring setup using Prometheus and Grafana. Prometheus collects metrics from configured targets, while Grafana provides dashboards for visualizing the collected data.

## Project Files

* `docker-compose.yml` — Defines the monitoring services.
* `prometheus.yml` — Configures Prometheus metric collection.
* `alert.rules.yml` — Defines a CPU usage alert rule.
* `README.md` — Documents the project.

## Objectives

1. Configure Prometheus to collect metrics.
2. Monitor the health of configured targets.
3. Query metrics using PromQL.
4. Visualize metrics using Grafana.
5. Configure an alert for high CPU usage.

## Status

Configuration files prepared and uploaded to GitHub. Service startup, metric collection, dashboard configuration, and alert verification are pending execution.
