## Projects

### UR5E Robotic Arm

#### GIF
[Robot arm drawing my initials in space](https://github.com/Quasician/porfolioSite/blob/gh-pages/midterm.gif)

#### Code
Here is my code for my [robot arm](https://gitlab.oit.duke.edu/tpc14/tpc14_rosintro/-/blob/main/ur5e_robot/scripts/planning.py) writing my initials (TPC) in 3d space.
It uses poses and cartesian motion planning in ROS.

#### High-level Description
The problem was to write my initials (TPC) in space using the UR5e’s end effector. My approach was to have the robot move to three unique starting locations using pose goals and once at a starting location, execute a letter using waypoints (cartesian interpolation). I made sure the starting locations were close enough so that the robot would not throw any errors saying that it could not find a solution. Another important note was to make sure that the robot would be able to reach the starting position for the letter T from the finished execution position for C so that I could debug without any issues after running the code multiple times.

<!-- 
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Quasician/porfolioSite/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. -->
