<p align="center"><a target="_blank" rel="noopener noreferrer" href="https://docker.com"><img src="https://www.docker.com/sites/default/files/d8/styles/role_icon/public/2019-07/horizontal-logo-monochromatic-white.png" data-canonical-src="https://www.docker.com/sites/default/files/d8/styles/role_icon/public/2019-07/horizontal-logo-monochromatic-white.png" style="max-width:50%;"></a></p>
<p align="center"><a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/5ceadc94fd40688144b193fd8ece2b805d79ca9b/68747470733a2f2f6c61726176656c2e636f6d2f6173736574732f696d672f636f6d706f6e656e74732f6c6f676f2d6c61726176656c2e737667"><img src="https://camo.githubusercontent.com/5ceadc94fd40688144b193fd8ece2b805d79ca9b/68747470733a2f2f6c61726176656c2e636f6d2f6173736574732f696d672f636f6d706f6e656e74732f6c6f676f2d6c61726176656c2e737667" data-canonical-src="https://laravel.com/assets/img/components/logo-laravel.svg" style="max-width:100%;"></a></p>

## Laravel applications with Docker

This repo contains a Laravel installation setup to use Docker to create a development environment. This repo can be used as a starting point for developing Laravel apps with Docker.

You can check this medium post out for more information.

This setup contains;





<ul>
<li>PHP-FPM (PHP 7)</li>
<li>Nginx web server</li>
<li>Redis</li>
<li>MySQL database</li>
</ul>


[Laravel documentation](https://laravel.com/docs/contributions).

## Run

Make sure your have [Composer](https://getcomposer.org) and [Docker](https://docker.com) installed

Clone the image in Docker Hub
<pre>
    <code>docker push fabiovalencio/laravel-optmized:latest</code>
</pre>

Build and run the Docker containers
<pre>
    <code>docker-compose up -d</code>
</pre>



## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
<p>Code and documentation copyright 2017 Docker, inc, released under the Apache 2.0 license.</p>
