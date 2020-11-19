#Use Python Image

# Install apt dependencies
 
# Copy contents into image
 
# run pip dependencies
 
# Expose correct port

# Create an entrypoint
FROM python:3.7
COPY . .
RUN pip3 install flask flask-sqlalchemy PyMySQL cryptography
EXPOSE 5000
ENTRYPOINT ["python3", "app.py"]

