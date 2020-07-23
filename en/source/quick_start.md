# Cloud Server Quick Start

[简体中文](https://heltec-automation.readthedocs.io/zh_CN/latest/quick_start.html)

## Summary

Cloud Server is a simple and fully functional LoRa cloud server. This page shows how to use this cloud server quickly.

## Create Base Configuration

### Login/Register

Open the  ``Browser``, enter the URL  [http://cloud.heltec.org](http://cloud.heltc.org)，you will see the following interface，click ``Register/Login`` 。

![](img/quick_start/01.png)

If you already have a [heltec.org](https://heltec.org) account, you can enter the correct user name and password directly and click ``LOG IN`` . If you don't have an account, you need to reister first. Enter the user name, email address and password. Click ``REGISTER``  to complete the registration，and you can log in successfully.

![](./img/quick_start/02.png)

![](./img/quick_start/03.png)

### Select Frequency Band

After entering the paltform, select the regional frequency band you need, such as ``AS923`` .

![](./img/quick_start/04.png)

### Create Gateway

Click ``Gateways``->``GatewaysCreate`` ，Select the ``GENERAL`` menu and fill in the corresponding information. The following three options are required and the remaining options are optional. Finally, slide to the bottom of the page and click  ``CREATE GATEWAY`` to complete the gateway creation. Here is an example.

![](./img/quick_start/05.png)

![](./img/quick_start/06.png)

![](./img/quick_start/07.png)



### Create Application

Click ``Apps``->``AppsCreate`` ， fill in the corresponding information. The following two options are required and the remaining options are optional. Click ``CREATE APPLICATION`` to complete creation. Here is an example.

![](./img/quick_start/09.png)

![](./img/quick_start/11.png)

### Create Device

Click ``Apps``->``AppsList`` ，You will see the application we created before (the ``AppName`` in the example)，and click it.

![](./img/quick_start/12.png)

![](./img/quick_start/13.png)

Select ``DEVICES`` menu，Click ``CREATE`` to create device.

![](./img/quick_start/14.png)

Select ``GENERAL``  menu， fill in the corresponding information，The following four options are required and the remaining options are optional. Click ``CREATE DEVICE`` 。

![](./img/quick_start/15.png)



Fill in the required ``Key`` or ``LoRa Protocol`` information according to the selected  ``Device-profile`` option. For example, in this example, select ``Device-profile`` as ``OTAA/CLASS-A`` , as shown below：

![](./img/quick_start/17.png)
