
![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


# App Name

description



## Demo

Insert gif or link to demo
## Usage/Examples

main.py
```python
import platform

class System_Info(RunnerView):
    template_name = "src/list.html"

    def get_response(**kwargs):
        """
        shows system info
        """
        return {
            "system": platform.system(),
            "node": platform.node(),
            "release": platform.release(),
            "version": platform.version(),
            "machine": platform.machine(),
            "processor": platform.processor(),
            "uptime": psutil.boot_time(),
            "cpu": psutil.cpu_percent(),
            "memory": psutil.virtual_memory(),
            "disk": psutil.disk_usage("/"),
        }
```


## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  pip3 install -r requirements.txt
```

Start the Excalibur Engine and then change src in auto-generated manifest.json file

Restart Server Again! Boom! working!

## Roadmap

- Updates LoL

## Tech Stack

**Client:** Bootstrap, Javascript, TailwindCSS

**Server:** Python, Django


## Optimizations

What optimizations did you make in your code? E.g. refactors, performance improvements, accessibility


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?


## Authors

- [@r4mbhardwaz](https://www.github.com/r4mbhardwaz)


## Used By

This project is used by the following companies:

- Company 1

## Feedback

If you have any feedback, please reach out to us at programmersidharth@gmail.com

