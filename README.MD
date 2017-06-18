# thinkphp的扩展库-json trace

thinkphp内置的trace只有html跟console，本库是增加json的扩展。

## 1、安装

```
composer require c7/tp_ext_json_trace
```

## 2、使用

在配置文件中增加配置：

*application/config.php*

```
'trace'                  => [
        //开启Json的trace扩展
        'type' => 'Json',
    ]
```

同时需要开启trace:`'app_trace' => true,`

## 3、enjoy

