## Server architecture overview

HowChat always welcomes third-party servers to enter the entire HowChat system. It can be used as a load or forwarding server to get rewards, or as an independent third-party server to access HowChat. After accessing the third-party server, you can enjoy independent and controllable data storage, higher-speed intranet transmission and unlimited upload and download.

### Server type comparison table

|    Type/Project    | Is it officially provided | Data encryption processing | Official calculation processing | SLA online rate | Reward mechanism |       Data ownership       |
| :----------------: | :-----------------------: | :------------------------: | ------------------------------- | :-------------: | :--------------: | :------------------------: |
|  Official Server   |            Yes            |          Official          | All                             |     99.95%+     |        -         |          Official          |
|    Load server     |            No             |          Official          | Important data                  |      99%+       |       Yes        |          Official          |
| Forwarding server  |            No             |          Official          | Almost all                      |      90%+       |       Yes        |          Official          |
| Third-party server |            No             |          Optional          | Very few information            | Not guaranteed  |     Ignored      | Independently controllable |

### Server type detailed introduction:

#### Official server:

As the core of the entire HowChat system, the official server provides core functions such as data encryption and decryption, data forwarding, user login, password change and binding.

#### Load server:

The load server is a branch of the official server and is provided by a third party. HowChat official will provide reward support. The load server needs to guarantee SLA> 99%. The load server will be responsible for most of the data processing, and only a small part of the core content will be processed by the official server , The load server also needs to be online for a long time to ensure the normal operation of the business.

#### Forwarding server:

The forwarding server is a branch of the official server just like the load server. It is provided by a third party. The official HowChat will also provide reward support. The difference between the forwarding server and the load server is that the forwarding server does not need to guarantee SLA and does not need to be online for a long time. The requirement to require larger bandwidth for high-speed data forwarding services is also a major guarantee for the normal operation of HowChat.

#### Third-party server:

HowChat will not use the Overlord Clause to restrict users' use. Users will have most of the customizable permissions. We strive to create an instant chat software that belongs to users. We support users to access HowChat on their own servers and provide business support in HowChat. I'm sorry that we cannot provide reward support on third-party servers, but occasionally there will be activities to encourage users to build their own third-party servers. The purpose of the third-party server can be fast intranet transmission, help users build their own intranet chat system, or data privacy. The data of the third-party server will never be saved on the official server in any way. The support provided is only to provide data forwarding service (allow users who do not have public IP to continue to build a third-party server, this forwarding service can choose not to be required), all data is stored on a third-party server, HowChat officially encourages this kind of unfamiliar The act of contributing to the ecology.