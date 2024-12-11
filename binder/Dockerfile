# Use the Firedrake base image
FROM firedrakeproject/firedrake:latest

# Install additional Python dependencies
RUN pip install numpy matplotlib

# Expose port for Jupyter Notebook
EXPOSE 8888

# Start Jupyter Notebook
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--no-browser", "--allow-root"]
