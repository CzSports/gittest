debug: true
server:
  port: 24543
spring:
  cloud:
    consul:
      host: 127.0.0.1
      port: 8500
      discovery:
        register: true
        hostname: 10.9.10.215
