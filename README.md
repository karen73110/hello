echo "# hello" >> README.md
git init
git add README.md
git commit .m "first commit"
git remote add origin http://github.com/bpy28/hello.git
gitpush -u origin master
