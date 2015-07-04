# sencom

The 'sencom' adds encoding options of your editor when you edit a commit message.

(sencom = Set ENcoding options for git COmmit Message)

## Usage

1. Configure editor and option in the sencom.

    ```bash
    # Set your favorite editor with options except an encoding option.
    git_core_editor="vim --nofork +1"
    # Set an encoding option of your editor.
    commitmsg_specific_opt="-c 'set fenc=utf-8'"
    ```

2. Modify your git `core.editor` option.

    ```bash
    git config --global core.editor 'path/to/sencom'
    ```
