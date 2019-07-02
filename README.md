# PROS V5 Template
This is a template repository for the PROS V5 Environment.

To use this template, click the green "Use this template" button on the
far right, to the left of "Clone or download" near the top of
[the repository page](https://github.com/IrvingtonRobotics/pros-v5-template).

Then set a new name and deal with other details on the page until you
are done and hit the "Create repository from template" button.

If you're still confused, please consult
https://help.github.com/en/articles/creating-a-repository-from-a-template.

After copying the template:

1. follow along with the TODO directions by searching for `%TODO` and
making edits (In Atom, press <kbd>ctrl</kbd> + <kbd>shift</kbd> +
<kbd>F</kbd> to search in project).

2. Download [firmware/okapilib.a](https://github.com/IrvingtonRobotics/pros-v5-template/raw/master/firmware/okapilib.a)
from the template repository, then copy the file into your new repository.
For some reason, this is necessary because the template leaves out this one
file.

Most of your work will be in the `src/` directory, but you may want to
edit `include/main.h` to include libraries such as Okapi or edit
`Makefile` to enable hot/cold linking for wireless upload.

----------------------------------------------------------------------

%TODO: Delete everything above this line ^ %

%TODO: Rename title%
# VEX Tower Takeover Code
%TODO: Change team letter%
**Team 44730A Bluescreens**

## Controls

### Primary Controller
| Position | Description |
|----------|-------------|
| Left Y | Left drive control |
| Right Y | Right drive control |

## Wiring

### Motors
| Motor Port | Function |
|------------|----------|
| 1 | Left drive motor |
| 10 | Right drive motor |
