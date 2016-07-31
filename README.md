# Github-Essentials
Essential knowledge and files for Github.

For a good Unity3d project with Git(hub), follow the following steps:

- Create a git repository online (eg. github.com).
- Save your Unity project on your local filesystem.
- Enable External option in Unity → Preferences → Packages → Repository (only if Unity ver < 4.5).
- Switch to "Visible Meta Files" in Edit → Project Settings → Editor → Version Control Mode.
- Switch to "Force Text" in Edit → Project Settings → Editor → Asset Serialization Mode.
- Save scene and project from the "File" menu.
- Quit Unity and then delete the Library and Temp directory in the project directory*1.
- Delete everything but the Assets and ProjectSettings directory*1.
- Create a .gitignore file using the text in the .gitignore file from this repository.
- Make your first commit in Git(hub).

Make sure to add a GNU V3 license to the repository.

*1: Not necessary, but saves space and errors.
