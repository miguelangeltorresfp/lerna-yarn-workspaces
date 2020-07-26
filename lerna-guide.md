# LERNA GUIDE

* Ejecutar solo en un paquete con scope:
  `lerna run test --scope=@walnut/common`
  `lerna run test --scope={@walnut/common,@walnut/server}`

* versioning
  `"new-version": "lerna version --conventional-commits --yes"`