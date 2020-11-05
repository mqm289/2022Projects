### …或在命令行上创建新的存储库

```
echo "# MyProjects-" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mqm289/MyProjects-.git
git push -u origin main
                
```

### …或从命令行推送现有存储库

```
git remote add origin https://github.com/mqm289/MyProjects-.git
git branch -M main
git push -u origin main
```

https://github.com/mqm289/MyProjects-