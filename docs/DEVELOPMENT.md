# Development configuration

This is an academic prototype, not a deployment-ready compliance service.

Set a new, local `JWT_SECRET` before using authentication. The current fallback is an explicit development placeholder. The inherited public history includes two historical JWT signing-default examples; never reuse them for a real service. The environment example also contains local Airflow demonstration credentials. These examples do not establish a secure hosted configuration.

Start infrastructure with `docker compose -f docker/docker-compose.yml up --build` after reviewing the Compose file and its environment requirements. Full-pipeline checks require Docker, models, local data and the configured services; a frontend build alone does not verify the OCR or Airflow pipeline.

Screenshots use six synthetic document records. Confidence percentages are illustrative UI fixtures, not measured model accuracy. Original technical documentation is retained as historical project documentation; its feature-state labels are not fresh verification results.
