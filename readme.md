Getting tired of Dockerize all around?
Irritated by stack mass memory consumption?
Spending hours and hours on repair environment just simply stopped to work?

I did.

So I take a parts, mixed them up, and it is result.

Simply as possible, NGINX + PHP (with different version embedd) + COMPOSER.

Bind "bin" do your PATH.
Run:
    service nginx start
    service fpm start
    service redis start

Stick your project to "sites-enabled" folder.

Voila.