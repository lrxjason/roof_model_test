# roof_model_test

python setup.py sdist bdist_wheel

python -m twine upload --skip-existing --repository pypi dist/*

from ruixu_model import predict

predict.run()
predict.mask()
predict.help()
