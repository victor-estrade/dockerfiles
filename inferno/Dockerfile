FROM divkal/nvidia-tensorflow:1.6

# FIXME : current tensorflow version is 1.13.0 while tensorflow probability requires >= 1.13.1

# Install personal packages
RUN pip install git+https://github.com/victor-estrade/datawarehouse.git && \
	pip install iminuit && \
	pip install corner && \
	pip install git+https://github.com/pablodecm/neyman.git && \
    # clean up pip cache
    rm -rf /root/.cache/pip/* && \
	echo "END"

#sudo docker build -t estradevictorantoine/inferno:1.2 ./