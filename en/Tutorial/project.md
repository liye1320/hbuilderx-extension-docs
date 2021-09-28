# Project

With HBuilderX, let's start by creating a project.

The following will introduce project create, import, close, create alias, remove, rename project, redetect project type, rebuild project index, etc.

## Import project/directory

Click the top menu [File - Import], or click the menu [Open Directory] to import the project to HBuilderX.

HBuilderX, supports importing projects from `svn`, `Git`, and `local`.

To import projects into svn and git, you need to install the svn and git plugins first.

<img src="/static/snapshots/tutorial/project/project_import_en.png" style="zoom: 45%; border-radius: 20px;" />

## Project Create

HBuilderX supports a variety of project types, mainly: web projects, 5+App projects, uni-app projects, WeChat mini program, QuickApp, wap2app, etc.[Details](/Tutorial/Other/ProjectType)    

- Welcome page, click on `New Project`
- Toolbar, The first icon
- Top menu [File -> New -> Project]

<img src="/static/snapshots/tutorial/project/project_new_en.png" style="zoom: 40%; border: 1px solid #eee;" />

## Project Closed

When there are too many projects in the project manager, you can `close project`;

In the project manager, select the project, right-click the menu, and click [Close Project] to move the project to the list of [Closed Projects].

Of course, you can also open the required project from the [Closed Project] and move it to the project manager.

<img src="/static/snapshots/tutorial/project/project_close.png" style="zoom: 85%;" />

## Porject Alias

HBuilderX，Support setting alias name for projects 

In the project manager, select the project, right-click the menu, and click [Setting Alias Name] to create an alias.

<img src="/static/snapshots/tutorial/project/project_alias_en.png" style="zoom: 45%;border: 1px solid #eee;border-radius: 25px;" />

## Other

**Remove Project**：You can remove the project from the project manager, or move it to the recycle bin.

**Redetect Project Type**：In some cases, HBuilderX does not correctly identify the project type (for example, uniapp project, the run menu cannot be displayed), causing the relevant menu to fail to be displayed correctly, which can be solved by re-identifying the project type.[Details](/Tutorial/ProjectType)

**Rebuild Project Index**：In some cases, the code prompt is abnormal (for example, the image path cannot be prompt), It can be solved by `Rebuild Project Index`.