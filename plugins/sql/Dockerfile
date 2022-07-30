FROM quay.io/souravkl11/raganork:multidevice

RUN git clone https://github.com/nethsaragimhan/Ninja-Test /skl/Ninja-Test
WORKDIR /skl/Ninja-Test
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
