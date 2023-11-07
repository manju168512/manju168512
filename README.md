- 👋 Hi, I’m @manju168512
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
manju168512/manju168512 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#getting base image ubuntu
FROM ubuntu
MAINTAINER manjunath <manjshree001@gmail.com>
RUN apt-get update
CMD ["echo","hello world..! from my first docker image"]
