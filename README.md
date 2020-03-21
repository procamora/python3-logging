# python3-logging


Library to run the logging library with colors according to the type of log.


# Installation

Installation can be done through the _pip3_ command:



```bash
pip3 install procamora-logging --user
```


You can also update the library with:



```bash
python3 -m pip install --user --upgrade procamora-logging
```



# Basic Usage


To use this class the first thing to do is import the library:


```python
from procamora_logging.logging import get_logging
```




```python
logger: logging = get_logging(verbose=False, name='sqlite')

logger.debug(msg)
logger.info(msg)
logger.warning(msg)
logger.error(msg)
logger.critical(msg)
```



