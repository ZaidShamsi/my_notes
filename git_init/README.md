# git init

## Useful reads

- [git init | Atlassian git tutorial](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-init#:~:text=The%20git%20init%20command%20creates,run%20in%20a%20new%20project.)
- [Git - git-init Documentation](https://git-scm.com/docs/git-init)

## Purpose

I would like to answer the question, '**What happens when I do git init in an empty New Folder?**'

## Findings

- `git init` creates a .git folder in the New Folder.
- The contents of the .git folder are as follows:
    - hooks folder
        - 13 SAMPLE files
    - info folder
        - exclude file
    - objects folder
        - info folder
        - packs folder
    - refs folder
        - heads folder
        - tags folder
    - config file
    - description file
    - HEAD file

### .git folder

![git_init_creates_git_folder](https://github.com/ZaidShamsi/my_notes/assets/103277308/92ea2eba-24aa-4cf6-b230-de21a6b9f9cb)

### contents of the .git folder

![contents_of_the_git_folder](https://github.com/ZaidShamsi/my_notes/assets/103277308/a3f83be3-065d-4990-b0a9-84e6d763e4c6)

#### contents of the hooks folder

![contents_of_hooks_folder](https://github.com/ZaidShamsi/my_notes/assets/103277308/46564687-8608-45bf-9c59-a9a37366ff07)

##### contents of the applypatch-msg.sample file

![contents_of_the_applypatch-msg_sample_file](https://github.com/ZaidShamsi/my_notes/assets/103277308/c4c08e1f-5760-493e-8e65-37cac373adfd)

#### contents of the info folder

![contents_of_info_folder](https://github.com/ZaidShamsi/my_notes/assets/103277308/4933edc2-5466-4fd4-8bfc-08c9cc0e1f64)

##### contents of the exclude file

![contents_of_the_exclude_file](https://github.com/ZaidShamsi/my_notes/assets/103277308/1ffe1efe-8878-4d57-9bd7-e934910c0142)

#### contents of the objects folder
Both subfolders are empty

![contents_of_objects_folder](https://github.com/ZaidShamsi/my_notes/assets/103277308/f3bdb1ca-f2fc-436c-9086-44e2c79359ce)

#### contents of the refs folder
Both subfolders are empty

![contents_of_refs_folder](https://github.com/ZaidShamsi/my_notes/assets/103277308/49321511-bd94-4a47-8b16-79463c9debee)

#### contents of the config file

![contents_of_the_config_file](https://github.com/ZaidShamsi/my_notes/assets/103277308/1af5ab93-44b4-4808-900f-44c08c7d6aeb)

#### contents of the directory file

![contents_of_the_directory_file](https://github.com/ZaidShamsi/my_notes/assets/103277308/5d6511ce-113d-44ce-8d30-9dccf9cf86e9)

#### contents of the HEAD file

![contents_of_the_HEAD_file](https://github.com/ZaidShamsi/my_notes/assets/103277308/876ce481-ae1f-4641-917e-d189e6145250)
