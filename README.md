# 说明
覆盖 Home Assistant 地图面板的同名文件，适用版本 0.58.0 。

由于 0.58.0 版本引入 ES6，因此请按需选择路径：

## 启用 ES6 
如果你是通过虚拟环境安装 HA 的，如 All-in-one，那么路径为：

```
/srv/homeassistant/homeassistant_venv/lib/python3.5/site-packages/hass_frontend/panels
```

之后，替换上级文件夹

```
/srv/homeassistant/homeassistant_venv/lib/python3.5/site-packages/hass_frontend
```

文件 `__init__.py` 内 `map` 项的 `md5` 值。

**注意路径中 python 3.x 为所安装的 python 版本号，请自行填写选择 3.5 或 3.6。**
***
## 继续使用 ES5

如果你是通过虚拟环境安装 HA 的，如 All-in-one，那么路径为：

```
/srv/homeassistant/homeassistant_venv/lib/python3.5/site-packages/hass_frontend_es5/panels
```

之后，替换上级文件夹

```
/srv/homeassistant/homeassistant_venv/lib/python3.5/site-packages/hass_frontend_es5
```

文件 `__init__.py` 内 `map` 项的 `md5` 值。

**注意路径中 python 3.x 为所安装的 python 版本号，请自行填写选择 3.5 或 3.6。**

***

更多 Home Assistant 的教程和经验欢迎浏览我的博客：

[http://cxlwill.cn](http://cxlwill.cn)

    

