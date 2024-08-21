# Ashish's Blog

// add link to subscribe the blog

## How to Setup Your Own Blog Like This

Motivation : https://guzey.com/personal/why-have-a-blog/
Make a new, empty github repo called blog.

```
git clone https://github.com/ashpect/blog
cd blog
git checkout 1dfed56d9f20e11c3614ffb328e6b5001b59c485
git set-url origin git@github.com:<YOUR_USERNAME>/blog.git
git checkout main
git reset --hard 1dfed56d9f20e11c3614ffb328e6b5001b59c485
git push origin main
```

Now, you can do `hugo serve` on the command line which will generate a /build folder. Making a project on [render.com](https://render.com) and pointing it to your repo should just work.
