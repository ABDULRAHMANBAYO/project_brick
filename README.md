# Jeetar bricks

This is my Jeetar Technology collection of bricks

## 🧱 Bricks

| Brick                                        | Description                                                            |
| -------------------------------------------- | ---------------------------------------------------------------------- |
| [`starter_setup`](./bricks/starter_setup/)   | The whole starter template for a new project                           |
| [`module_feature`](./bricks/module_feature/) | folder structure and files for a new feature. e.g signIn, signUp e.t.c |

## 🛠️ Installation Steps

Install [mason_cli](https://pub.dev/packages/mason_cli)

```sh
dart pub global activate mason_cli
```

Bricks can be installed from this repository.

Install a brick

```sh
## Install Starter Setup brick
mason add -g starter_setup --git-url https://github.com/DAMMAK/brick_jeetar --git-path bricks/starter_setup

## To use Starter Setup brick
mason make starter_setup

NB: Follow the prompt
```

```sh
## Install Module feature brick
mason add -g starter_setup --git-url https://github.com/DAMMAK/brick_jeetar --git-path bricks/module_feature

## To use Starter Setup brick
mason make module_feature

NB: Follow the prompt
```
