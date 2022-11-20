FROM jupyter/minimal-notebook
WORKDIR /code
RUN pip install numpy
COPY . /code
ENTRYPOINT ["start.sh", "jupyter", "lab", "--LabApp.token=''"]