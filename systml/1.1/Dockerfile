FROM divkal/nvidia-pytorch:1.6

# Install personal packages
RUN pip install git+https://github.com/victor-estrade/datawarehouse.git && \
	pip install iminuit && \
    # clean up pip cache
    rm -rf /root/.cache/pip/* && \
	echo "END"

#sudo docker build -t estradevictorantoine/systml:1.1 ./