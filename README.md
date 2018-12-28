# base-symfony-project
Symfony skeleton with my minimal bundle

This project will be updated with symfony release.

Following bundle has been added to Symfony/skeleton :

* symfony/Server       (alias : server)
* symfony/debug-pack   (alias : debug)
* symfony/maker-bundle (alias : make)

More bundle could be added in future but they probably would only concerned developpement, the goal is to have a basic project without any specific bundle.

## How to use

First of all, clone the project:

```bash
$> git clone https://github.com/JeremLa/base-symfony-project.git
```
`cd` on project directory


Create `.env` file base on `.env.dist`

```bash
$> cp .env.dist .env
```
customise `.env` at your convenience

Install dependency

```bash
$> composer install
```
