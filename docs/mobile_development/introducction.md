# Introducction 

Nowadays mobiles are not only telephones, they are the most useful and used tool. The mobile development evolution is consequently very fast and the market is very changeable.

## Glossary

### Acronyms

- **App**: Application.
- **GPS**: Global Positioning System.
- **OS**: Operating System. 
- **SMS**: Short Message/Messaging Service.
- **STK**: SIM Application Toolkit.
- **USSD**: Unstructured Supplementary Service Data.

## Mobile _Apps_

One of the most **important decisions** when developing a mobile _app_ is to decide whether it will be **native or web _app_**. Each of these options has its pros and cons.

### Native _apps_

Native _apps_ run directly on the mobile. 

#### Pros and cons

**Pros**: Efficiency. 
  
- **Maximum** software and hardware **utilization**: _GPS_, accelerometers, touchscreen, etc. 
- More efficient _apps_.
- Allows **privacy**, as there is no need to send data over the network.. 
**Cons**: Expensive development.
  
- A **different executable** for each _OS_ and hardware platform.  
- Usually a different _app_ for each _OS_.
- Need to be **uploading new versions** to the _app_ store.

#### Recommended usage

Native _apps_ are suitable for:

- _Apps_ that need to **interact** with the device's **hardware**, **memory** or **_OS_**.
- _Apps_ running **locally** without network access.
- _Apps_ that need **privacy**.

Some native _apps_ examples: camera, file manager, gallery, calculator, blog of notes, etc.

### Web _apps_

Web _apps_ run on a server, providing service throught a browser.

#### Pros and cons

**Pros**: Simple development.  

- **Only one _app_** needs to be developed.
- **Maintainability**. Updated directly on the server, not for each mobile.

**Cons**: Low efficiency. 

- **Unable** to make proper **use** of the device's **hardware** and **software**.
- Is highly **dependent on network** technology.
- Usually slower responses.

#### Recommended usage

Web _apps_ are suitable for:

- _Apps_ with a **small budget**.
- **Service based** _Apps_ (no need of device access).
- _Apps_ with centralised **database** access requirements.
- _Apps_ whose content is **constantly updated**.

Some web _apps_ examples: Streaming (as [YouTube](https://www.youtube.com/)), news (as [NBC News](https://www.nbcnews.com)), repositories (as [GitHub](https://github.com)), online services (as [ILovePDF](https://www.ilovepdf.com)), etc.

### Hybrid _apps_

Many _apps_ **require some features from native** _apps_ and **some from web _apps_**. So why not make a hybrid _app_?

Hybrid _apps_ seek to benefit from the **best features of both paradigms**. So they develop **part** of the _app_ in a **native** way and another **part** in a **web** way, **integrating both parts** in a **single _app_**.

#### Recommended usage 

whenever native and web features are necessary.

Some hybrid examples:

- **Social network / chat / mail / cloud storage _apps_**: Usually needs access to _DB_ (web feature) but also access to hardware and memory---i.e. camera, gallery or file manager---(native feature). As [Twitter](https://twitter.com), [Whatsapp](https://www.whatsapp.com), [Gmail](https://mail.google.com) or [Drive](https://drive.google.com), respectively.
- **Localization / Maps _apps_**: Usually needs acces to the map (web feature), but also so the _GPS_ location (native feature). As [Google Maps](https://www.google.com/maps) or [Uber](https://www.uber.com).

### Message-based _apps_ 

The not-so-well-known message-based _apps_, become important in regions with little network technology.

The message-based _apps_ are supported by messaging _APIs_ like _SMS_, _USSD_ or _STK_. See [glossary](#glossary).  

## Mobile _OS_

Nowadays the main two _OS_ are [Android](https://www.android.com) (open-source) an [iOS](https://en.wikipedia.org/wiki/IOS), but it has not always been like this. 

There have been many other OS for mobiles throughout history:

- [Windows Phone](https://en.wikipedia.org/wiki/Windows_Phone) (Microsoft)  
- [Blackberry 10](https://en.wikipedia.org/wiki/BlackBerry_10) (Blackberry)
- [AliOS](https://en.wikipedia.org/wiki/AliOS) (Alibaba) 
- [Symbian](https://en.wikipedia.org/wiki/Symbian) (Nokia)
- [Bada](https://en.wikipedia.org/wiki/Bada) (Samsung)
- [Firefox OS](https://en.wikipedia.org/wiki/Firefox_OS) (Mozilla)
- [Mer](https://en.wikipedia.org/wiki/Mer_(software_distribution)) (Sailfish)
- [Ubuntu Touch](https://en.wikipedia.org/wiki/Ubuntu_Touch) (Ubuntu) 
- [Tizen](https://en.wikipedia.org/wiki/Tizen) (Samsung) 

All of them have passed into history except for Tizen (used for werables).

## Topics about mobile development 

- Architecture and _OS_ of mobiles.
- Software and technologies for mobile _apps_ development.
- Mobile _apps_ development for [Android](https://developer.android.com/studio). 
