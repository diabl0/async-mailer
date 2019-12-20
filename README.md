# Sending Messages Async with json serializer does not work

## Instalation

1. Clone repo (`git clone https://github.com/diabl0/async-mailer.git`)
2. start docker containers with MailCatcher and RabbitMQ `docker-compose up -d` 
3. run `symfony serve` to start local server
4. Click "send email" in browser
5. run `symfony console messenger:consume async` in console to see how consumer fails
git remote add origin git@github.com:diabl0/async-mailer.git
git push -u origin master