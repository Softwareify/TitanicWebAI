FROM jupyter/minimal-notebook
WORKDIR /code
RUN pip install numpy pandas scikit-learn seaborn
COPY . /code
ENTRYPOINT ["start.sh", "jupyter", "lab", "--LabApp.token=''"]