1. Add '127.0.0.1 db.int' to your hosts file
2. If you want to use xdebug with phpStorm add a server named '_', and map the project directory to '/app'
3. Set 'DATABASE_URL="postgresql://main:main@db.int:5432/main?serverVersion=13&charset=utf8"' in your .env file