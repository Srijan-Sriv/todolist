# Minimalist TodoList


This is a project made entirely on React.js and is exactly what it sounds like. It has a basic UI in order to save any hassle and just focus on your tasks.

---
To contribute or undertand the code you may contact me personally, since I probably wont be fixated on this particular code.

This is the [site](https://srijansriv.github.io/react-test/).

---
Apparently, as of 15.05.2021 this doesn't work as only the body (with its css done) is the only thing that shows up. So I will explain everything I did uptil this date.

---
I followed [this](https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f) blog to deploy my react app. The `git init` says its Reinitializing the empty commit but happily takes the remote origin. One difference that the react.js [documentation](https://create-react-app.dev/docs/deployment/#github-pages) says is to replace `"deploy": "gh-pages -d build"` with `"deploy": "gh-pages -b master -d build"` if deploying on a user page. This simply creates the only branch to be **master** instead of **gh-pages**. This however only uploads the build folder present in any react app. Hence, I (felt like I) need to perform the optional step given in the blog above.

This posed another problem, I need to pull the origin because apparently my local device doesn't contain the work on it(?). I had to `--allow-unrelated-histories` in a second pul too because the first pull messed the timelines. This finally allowed me to `git push origin master`. The pulls are the reason all the build folder content are spilled in the code.

Still, the depolyment doesn't for some reason display the .jsx elements. From this point on I'm frustrated. This project was made in order to practice React, but not onlyl did the css took me more time that the jsx itself, it has now become a project to practice git too. I would love some help. The node and git commands are (mostly) archived with me.
