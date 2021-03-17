# Helix.Skeleton.Example
Example project setup structure for Helix.Skeleton (https://github.com/trnktms/Helix.Skeleton)

# Demo
[![Helix.Skeleton demo with Helix.Skeleton.Example](https://img.youtube.com/vi/t6iSng6nXaQ/0.jpg)](https://www.youtube.com/watch?v=t6iSng6nXaQ)

# Clone
```
git clone https://github.com/trnktms/Helix.Skeleton.Example.git && cd Helix.Skeleton.Example && git submodule init && git submodule update && cd Helix.Skeleton && git submodule init && cd .. && git submodule update --recursive
```

# Available commands
- `.\Helix.Skeleton\sk-base\sk-scripts\init.ps1 -toRoot 1 -templateName default`
- `.\Helix.Skeleton\sk-base\sk-scripts\add-project.ps1 -toRoot 1 -templateName feature -subProjectName Navigation`
- `.\Helix.Skeleton\sk-base\sk-scripts\add-project.ps1 -toRoot 1 -templateName foundation -subProjectName Search`
- `.\Helix.Skeleton\sk-base\sk-scripts\add-module.ps1 -toRoot 1 -templateName feature -subProjectName Navigation -moduleName Footer`

`Navigation`, `Search` and `Footer`can be replaced with your own values, they are just examples!
