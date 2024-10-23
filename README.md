This is an example of changing a specified locator via .fossa.yml where if the same project is scanned, FOSSA will produce a new project due to the change. This shows that you can continue to scan the same project but change it's id via a .fossa.yml to maintain the old project and continue to scan the same project under a different name.
From 

```
version: 3

project:
  locator: custom+43030/vmwoozies-fossa-type-license-test
  id: github.com/cmboling/vmwoozies-fossa-type-license-test
  name: vmwoozies-fossa-type-license-test
  labels:
    - cmboling-test
```

![vmwoozies-fossa-type-license-test](https://github.com/user-attachments/assets/c1ccfa8b-ea98-4a09-ab86-024db55673ff)


To

```version: 3

project:
  locator: custom+43030/marissa-fossa-type-license-test
  id: github.com/cmboling/marissa-fossa-type-license-test
  name: marissa-fossa-type-license-test
  labels:
    - cmboling-test
```

![Settings](https://github.com/user-attachments/assets/392bdf25-45ba-43a4-964a-b0a5b766d703)
