# Steps

Steps to get you page and PDF done:

 - Create a new repo from the [base template](https://github.com/avdata99/test-mkdocs)
 - Modify ``index.md`` at ``docs`` and ``docs-es``
 - Create new md files at ``docs`` and ``docs-es`` folders
    - Include them at ``nav`` section at ``mkdocs-en.yml`` and ``mkdocs-es.yml``
 - Put static content at the ``assets`` folder (images, css, js, etc).  
 - Replace mkdocs files: test-mkdocs -> testing-mkdocs-multilang-template **TODO**
 - Enable the ``gh-pages`` branch to be published as GitHub Pages
 - Push! (all languages will be built automatically)

## TODOs

Requirements or possible new features:
 
 - Include a PDF link in the header
 - FIX: The edit icon for each page point always to english version
 - Add a step to update github URL and repo name in mkdoc files
 - Allow add or remove languages
 - Check style for es language
 - Allow define all setting in a custom file and build automatically all required mkdocs-LANG files
