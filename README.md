## Add a submodule

```bash
git submodule add <remote-url> <path/name>
```

## What happens to the submodule container after submodule update?

-   `git diff` result
    ![](images/2022-10-25-20-03-00.png)

-   the link point to the submodule changed
    -   before module commit ![](images/2022-10-25-20-06-03.png)
    -   after module commit ![](images/2022-10-25-20-07-01.png)
