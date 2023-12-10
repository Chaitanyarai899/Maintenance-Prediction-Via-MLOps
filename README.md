# Deploying an end-to-end ml/dl model (for predicting maintaince for aircrafts by using dataset provided by NASA) into cloud server using Flask and Docker with CI/CD pipeline

This project promulgates a `pipeline` that `trains` an end-to-end keyword spotting model using input audio files, `tracks` experiments by logging the model artifacts, parameters and metrics, `build` them as a web application followed by `dockerizing` them into a container and deploys the application containing trained model artifacts as a docker container into the cloud server with `CI/CD` integration, automated tests and releases.


## Languages and Tools

<div align="">
<a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/></a>
<a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/></a>
<a href="https://flask.palletsprojects.com/en/2.2.x/" target="_blank" rel="noreferrer"> <img src="https://banner2.cleanpng.com/20180704/sv/kisspng-flask-python-web-framework-bottle-microframework-django-5b3d0ba62504c0.3512153115307273341516.jpg" alt="flask" width="95" height="43"/></a>
<a href="https://github.com/features/actions" target="_blank" rel="noreferrer"> <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--2mFgk66y--/c_limit,f_auto,fl_progressive,q_80,w_375/https://dev-to-uploads.s3.amazonaws.com/uploads/badge/badge_image/78/github-actions-runner-up-badge.png" alt="actions" width="52" height="49"/></a>
<a href="https://python-poetry.org/" target="_blank" rel="noreferrer"> <img src="https://www.yuyagishita.com/img/poetry.png" alt="poetry" width="95" height="43"/></a> 
<a href="https://hydra.cc/docs/intro/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/facebookresearch/hydra/master/website/static/img/Hydra-Readme-logo2.svg" alt="hydra" width="98" height="37"/></a>
<a href="https://www.mlflow.org/docs/latest/python_api/mlflow.html" target="_blank" rel="noreferrer"> <img src="https://www.mlflow.org/docs/latest/_static/MLflow-logo-final-black.png" alt="mlflow" width="98" height="44"/></a>
<a href="https://www.heroku.com/platform" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Heroku_logo.svg/2560px-Heroku_logo.svg.png" alt="heroku" width="107" height="43"/></a> 
<a href="https://docs.pytest.org/en/7.1.x/" target="_blank" rel="noreferrer"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/ba/Pytest_logo.svg/2048px-Pytest_logo.svg.png" alt="pytest" width="55" height="50"/></a> 
</div>
 
<br>
