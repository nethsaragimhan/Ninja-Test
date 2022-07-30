FROM nethsaragimhan/ninja:latest

RUN git clone https://github.com/nethsaragimhan/Ninja-Test /skl/Raganork
WORKDIR /skl/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
