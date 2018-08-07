Standard Protocol collection
============================

### In order to create a new protocol:

  1. copy the protocol template sp0001_standardtemplate.md

  2. file name format [`sp000_title.md`](sp0000_title.md)

      - `sp` is lowercase
      - replace `0000` by the next available number; use leading zeros
      - append `_` and a very short title or acronym in lowercase letters
      - append file ending `.md` (indicating markdown format)

  3. Edit the file, adapting title, description and procedure as indicated in
  the template

  4. Add and commit the file to the repository. E.g. using `git`, the following
  commands work (repeat as you make changes, adapt the file name):

      ```sh
      git add sp0000_title.md
      git commit -m 'initial commit protocol sp0000'
      ```

  5. Once finalized, push the new version to the central repository on github:

      ```sh
      git pull
      git push
      ```




