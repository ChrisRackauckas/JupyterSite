

```python
from traitlets.config.manager import BaseJSONConfigManager
path = "/home/crackauc/.jupyter/nbconfig"
cm = BaseJSONConfigManager(config_dir=path)
cm.update('livereveal', {
              'theme': 'sky',
              'transition': 'fade',
              'start_slideshow_at': 'selected',
                'width' : 1600,
                'height': 900,
                'scroll': True,
                'slideNumber': False,
})

#
#from notebook.services.config import ConfigManager
#cm = ConfigManager()
#cm.update('livereveal', {
#        'width': 1600,
#        'height': 800,
#        'scroll': True,
#})




#
#from notebook.services.config import ConfigManager
#cm = ConfigManager()
#cm.update('livereveal', {
#        'width': 1600,
#        'height': 800,
#        'scroll': True,
#})

#
#from notebook.services.config import ConfigManager
#cm = ConfigManager()
#cm.update('livereveal', {
#        'width': 1600,
#        'height': 800,
#        'scroll': True,
#})

```




    {u'height': 900,
     u'scroll': True,
     u'slideNumber': False,
     u'start_slideshow_at': 'selected',
     u'theme': 'sky',
     u'transition': 'fade',
     u'width': 1600}


