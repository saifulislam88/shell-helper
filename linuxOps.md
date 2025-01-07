[Text editing](#Text-editing)



#### Text editing
- 1. adding sequential numbers to the names of directories in a specific directory starting from 1

```sh
i=0; for dir in *; do mv "$dir" "$((++i)).$dir"; done
```
