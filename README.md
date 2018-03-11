![Nebu Data Hub](https://www.nebu.com/hs-fs/hubfs/Nebu-2016/images/Nebu.png)

# Purpose of this repository
This repository was made for the Professional Days of the University of Debrecen to demonstrate the power of CSS Frameworks. In this HTML file the [Bulma](https://bulma.io) CSS Framework is presented.

# Using git
## Download the source
1. [Get a git client](https://git-scm.com/download), if you don't have one yet
2. Open git bash in a folder you want to download it to
3. Clone the project with this command
```bash
git clone https://github.com/NebuBV/Szakmai2018Tavasz.git
```

## Check changes (commits)
You can check the evolution of the code via the gitk command
```bash
gitk
```
In every commit there is a message which describes what happened there.

## Check out different stages
Via `gitk`, you select a commit that you want to restore. Every commit has a hash code but some of them have a name. (In this case the **_initial_** and the **_final_** stages have dedicated names.)
```bash
git checkout hashcode1234
```
For example if you want to check out the initial stage of the presentation then use the following command:
```
git checkout initial
```
If you want to get the final stage:
```
git checkout final
```

# Homework :)
Try to design this site from the initial stage by yourself with another CSS Framework. For example: [Bootstrap](http://getbootstrap.com/).  
Note: Possibly you have to modify the structure of the HTML code as well.