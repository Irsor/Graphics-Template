# Шаблон проекта по компьютерной графике

Этот проект позволяет собрать приложения с использованием библиотек GLFW, GLAD, stb_image, Dear ImGui и GLM средствами CMake.

## Как добавить GLFW

### Добаление удаленного сервера GLFW

```bash
git remote add glfw https://github.com/glfw/glfw.git
```

### Добаление поддерева GLFW

```bash
git subtree add --prefix=external/glfw glfw master --squash
```

### Обновление GLFW

```bash
git subtree pull --prefix=external/glfw glfw master --squash
```