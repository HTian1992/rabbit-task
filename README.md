# rabbit-task
springboot rabbitMq
 * 主要通过自定义的MessageListenerAdapter来分发不同的任务到不同的队列中，并根据配置选择相应的TaskRunner去执行队列任务
