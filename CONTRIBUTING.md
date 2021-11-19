<p align="center">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/anytype-docs-logo.svg" alt="Docs-Logo" width="180px" height="50px">
    </a>
</p>

## Table of Contents

- [**Contributing**](#contributing)
- [**File Structure**](#file-structure)
- [**Conventions**](#conventions)
  - [**Text Formats**](#text-formats)
  - [**Lists**](#lists)
  - [**Blocks**](#blocks)

## Contributing

> ℹ️ We ask that all users read our [Code of Conduct](https://github.com/anytypeio/community/blob/main/README.md#code-of-conduct) and [Gitbook Conventions](#conventions) before contributing to the documentation.
> Anytype welcomes all contributions and corrections. Please follow the steps below in order to contribute. If you're new to \_git\* and/or _GitHub_, we suggest you go through [the GitHub Guides](https://guides.github.com/introduction/flow/).

1. Fork this repository
2. (Optional) Clone the fork
   - Using SSH
     ```shell
     git clone --filter=tree:0 git@github.com:anytypeio/community.git
     ```
   - Using HTTPS
     ```shell
     git clone --filter=tree:0 https://github.com/anytypeio/community.git
     ```
   - Using GitHub CLI
     ```shell
     gh repo clone anytypeio/community -- --filter=tree:0
     ```
3. Create a new branch from the latest `main`
4. Make your changes on the new branch
5. Commit and push to the new branch
6. Make a pull request
7. Assign [Vladimir](https://github.com/d1eselboy), [Divyanshu](https://github.com/div3xi) or [Enda](https://github.com/endac) as the PR reviewer

## File Structure

* Any Page that has been added or removed from the documentation needs to be added to the **Table Of Contents** in the file [SUMMARY.md](https://github.com/anytypeio/docs/blob/main/SUMMARY.md)
  * Indentation is used to signify nesting of pages
  * Pages are linked using markdown URL's eg:
    ```
    [Navigation](https://github.com/anytypeio/docs/blob/main/features/navigation.md)
    ```
* All files are saved as **Markdown .md**
* For nesting pages they need to be placed in the category folder if it does not exist then you can create the folder
* To use images they must all be placed inside the [.gitbook/assets](https://github.com/anytypeio/docs/tree/main/.gitbook/assets) folder and then referenced from that folder

## Conventions

> These are the rules that Gitbook follows while creating documentation from markdown. Please follow them while making any changes

### Text Formats

- # Heading 1
  ```
  # Heading 1
  ```
  
- ## Heading 2
  ```
  ## Heading 2
  ```
  
- ### Heading 3
  ```
  ### Heading 3
  ```
  
- **Bold**
  ```
  **Bold Text**
  ```
  
- *Italics*
  ```
  _Italics Text_
  ```
  
- ~~Strikethrough~~
  ```
  ~Strikethrough Text~
  ```
  
- Horizontal Rule
  ```
  ---
  ```
  
- [URL](#)
  ```
  [URL Name](https://example.com)
  ```
 
- ![Image](#)
  ```
  ![Image](http://url/a.png)
  ```
 
- `Inline Code`
  ```
  `Inline Code`
  ```
 
### Lists

- **Un-Ordered List**
  ```
  * Item 1
  * Item 2
  * Item 3
      or
  - Item 1
  - Item 2
  - Item 3
  ```

- **Ordered List**
  ```
  1. Item 1
  2. Item 2
  3. Item 3
  ```

- **Task List**
  ```
  * [ ] Un-checked Task
  * [x] Checked Task
  ```
  
### Blocks

- **Code Blocks**
```
``` creates a new code block.
```py creates a new code block with Python syntax highlighting.
```

- **Quotes**
  ```
  Use > to start a quote block
  ```

- **Information Hint Block**
  ```
  {% hint style="info" %} Information Hint Block {% endhint %}
  ```
  <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/info-hints-block.png" alt="info-hints">
    </a>
  </p>
  
- **Warning Hint Block**
  ```
  {% hint style="warning" %} Warning Hint Block {% endhint %}
  ```
    <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/warning-hints-block.png" alt="warning-hints">
    </a>
  </p>
  
- **Success Hint Block**
  ```
  {% hint style="success" %} Success Hint Block {% endhint %}
  ```
    <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/success-hints-block.png" alt="success-hints">
    </a>
  </p>
  
- **Danger Hint Block**
  ```
  {% hint style="danger" %} Success Hint Block {% endhint %}
  ```
    <p align="left">
    <a href="https://doc.anytype.io">
        <img src="https://raw.githubusercontent.com/anytypeio/community/main/assets/danger-hint-block.png" alt="danger-hints">
    </a>
  </p>