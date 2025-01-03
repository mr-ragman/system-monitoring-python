# Toy App - System Monitoring With Python

Let's toy around by building a simple python based app to monitor your system.

## Install Required Libraries

We need to install the following Python packages:

- **dash**: Web framework for building dashboards.
- **plotly**: Used to create graphs and charts - works well with dash.
- **psutil**: For monitoring system resources.

## More about psutil

The psutil library provides cross-platform access to system monitoring information (ram, cpu and disk). It works on Windows, Linux, and macOS. On MacOs, disk metric may need slight adjustment on mounting the root folder. (TODO!)

## Run the App

```python

# all metrics on one chart
python app.py one

# each metric on separate chart
python app.py multiple

```

## Thanks

[Py-Core Python Programming](https://medium.com/@ccpythonprogramming) for inspiration!
