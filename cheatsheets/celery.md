# Celery

### Celery example setup

```python
app = Celery('project_name', backend='redis://localhost', broker='amqp://')
```

### Start all needed services

start Redis

`redis-server`

start RabbitMQ

`rabbitmq-server`

start Celery

`celery -A project_name worker -l info`

Django

`./manage.py runserver`
