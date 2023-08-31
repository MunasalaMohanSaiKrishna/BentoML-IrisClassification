BentoML is a framework for building reliable, scalable, and cost-efficient AI applications. It comes with everything you need for model serving, application packaging, and production deployment.
Visit https://www.bentoml.com/

Steps:
1. pip install -r requirements.txt
2. python train.py
3. bentoml models list
4. python test.py
5. bentoml serve service.py:svc --reload
6. create a file bentoml.yaml and run 'bentoml build'
7. Possible next steps:

 * Containerize your Bento with `bentoml containerize`:
    $ bentoml containerize iris_classifier:tw5iahkh46r6fzcu  [or bentoml build --containerize]

 * Push to BentoCloud with `bentoml push`:
    $ bentoml push iris_classifier:tw5iahkh46r6fzcu [or bentoml build --push]
