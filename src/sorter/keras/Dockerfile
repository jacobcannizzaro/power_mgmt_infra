# specify base image
FROM jupyter/tensorflow-notebook:dd2087c75645

# to run in complete isolation
# COPY . .

# install dependencies
RUN pip3 install keras && \
    pip3 install git+https://github.com/voins/google-images-download.git@patch-1 && \
    pip3 install seaborn
