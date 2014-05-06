title: "Open API: Emergence, Origination and Situation"
date: 2008-07-10 14:33
---
# OpenAPI出现、起源与现状

_按：本文原发于《程序员》杂志2008.7月刊。此处所发为底稿。_

## 碎片化的互联网

在早年刚刚上网的时候，经常感觉到互联网上内容的缺乏，很多想要的都没有。随着网站的逐步增多，崛起了以yahoo为代表的门户，典型的特点就是分类导航，现在中国的hao123和265还在继续扛这面大旗。那个时候，流行的词汇就是“冲浪”，从一个网站链接到另外一个网站，网站与网站之间的关系就靠那个链接维系。其随着互联网的内容增加更多，我们发现导航和冲浪解决不了我们的问题，我们想要找到一个东西变得日益艰难，在这个时候搜索应运而生，google也借助搜索形成对yahoo的巨大挑战。在搜索的时代，搜索将各个网站上的内容以搜索词为中心进行重组，网站与网站之间的简单链接关系被打破，内容的关联性成为网站间关系的主要表现，而在这个时候，网站也可以通过投放搜索广告的方式去获得一定的收入。

搜索模式与导航模式的相比，适应了信息爆炸时代我们精准定位找到自己想要的东西的目的，离我们的需求更进一步。但是目前的搜索距离我们真正想要的还是有很长一段距离，比如网上有很多信息与地理位置有关，但是我们却在地图上不能直观的看到这些信息。很多信息彼此之间具有某种关系，但是并不一定是按某个关键词的方式连接在一起的，在这个时候，搜索失去了它的既有的威力。这种有关系的信息缺乏连接，就像一个个碎片，散落在各处，并不能很好的为我们所用。Web2.0的应用的兴起，使得我们可以更为方便的交互，我们也越来越多的在网上拥有自己或者与自己相关的数据。但是这些数据很可能是存在不同的网站上，比如我们的blog在某个网站上，我们的miniblog可能在另外的网站上，而我们照片又在其他的网站上。这些林林种种的表现带来的问题就是：

1、 碎片化的信息。信息与信息之间缺乏关联组织；

2、 碎片化的应用。我们所使用的各种应用在不同的网站上，我们需要跑来跑去，应用之间缺乏关联；

3、 碎片化的关系。我们需要在不同的网站上注册ID，在不同的互联网应用上拥有相同或者不同的关系；

4、 碎片化的人。一个人在网上体现为与此相关的信息、应用和关系，因为信息、应用、关系的分裂，让人也呈现为碎片化的特点。

面对这些问题，有什么方法可以解决，让互联网更为接近我们的理想吗？
<!-- more -->

## google maps openAPI带来开放潮流

API的全称是应用编程接口（Application Programming Interface），这并不是一个新概念，在计算机操作系统出现的早期就已经存在了。在互联网时代，把网站的服务封装成一系列计算机易识别的数据接口开放出去，供第三方开发者使用，这种行为就叫做开放网站的API，与之对应的，所开放的API就被称作openAPI。

使用API构建业务是实现开放式业务结构的关键技术，也是下一代网络区别于传统电信网的主要特点之一。目前，关于下一代网络的开放式业务API标准主要包括：由Parlay组织、3GPP和ETSI SPAN共同制定的Parlay/OSA API以及由SUN公司在Java平台上推出的JAIN API。

在google开放API之前，已经有amazon和ebay等公司开放API，但是对应的数据集中在商品上，与人们的日常互联网应用有一定的距离。真正推动整个互联网开放的发端，应该算是google在2005年开放google maps的API，由此涌现出众多的web2.0应用，也推动Yahoo! Maps开放API。Google的开放触动了微软，在2005年9月，微软推出其“Web 平台”（Web Platform）策略，策略中包括公开MSN Search等一些公共Web网站的API、发布更好的开发工具等措施。微软的目标是采用Web 2.0或可编程Web的新兴模式，基于这些已经存在的、公开的Web网站而建立新的应用。在这种模式下，互联网公司不仅仅能提供对Web网页的简单访问，还可以将它们的Web网站转换为与操作系统等价的开发平台。三大巨头的参与，使得开放大潮风起云涌。

在开放API的环境下，我们就可以对原有的一些碎片化的数据进行重组，使其变得更有有关联。这时候出现了叫做mashup的东西。mashup又叫做web应用混搭技术，指的是利用其他网站的openAPI提供的内容进行重新搭配，从而制作出独特的、具有新价值的web应用的一种技术。其中最具代表性的当属运用google maps提供的开放地理信息而创作出的令人眼花缭乱、极具创意的mashup应用，比如：housingmap（http://www.housingmaps.com/）是一个非常cool的mashup应用。它利用了craigslist（http://www.craigslist.org）和Google Maps（http://maps.google.com/）的openAPI，把它们巧妙的组合起来，让租房的信息有机的组织和直观的显示在google maps提供的地图之上；twittervision（http://twittervision.com/）是把twitter（http://twitter.com/）和google maps的openapi进行mashup而形成的一个非常有趣的应用。进入twittervision网站，你会看到一个世界地图，地图上会不断冒出一些消息气泡，气泡里的内容就是某个人在twitter上喊话的内容了，而气泡的位置则是根据喊话人的地理位置信息而标记在了google maps上，当然它现在已经融合了更多网站的内容。

google在开放API方面的确称得上是开拓者和领导者（http://code.google.com/），不仅拥有search API, chart API, map api, opens ocial API等一系列还在不断增长的API列表，更在开放平台方面发力，推出开放的手机平台android和云计算平台appengine。在google、yahoo、微软的带动下，flickr、youtube等一系列网站也都纷纷对自己的服务提供了API供第三方开发者使用。

## openAPI的分类

openAPI按照制定者与遵循者的关系可以简单划分成两个大类：

1、专有

一个API制定出来主要是为了制定者本身提供应用开发接口的目的，这样的API就叫做专有API，例如facebook的API。大部分的API制定之初都是专有API，极特别的情况除外（例如google的open social，制定出来是给其他网站用，形成一种标准）。

2、标准

一个API称之为标准API，或者是制定者并不提供该API所定义的服务，例如google opensocial——此时它必须为成为业界标准而努力；或者是该API被业内很多服务提供者所遵循，例如RSS——要么是因为业内形成事实标准，要么是已经被标准化组织采纳。

openAPI按照提供的服务内容进行分类大概可以划分成下面几类：

1、搜索类

搜索类的API主要由搜索引擎提供商提供，主要可用来为你的网站添加搜索功能，或者利用其搜索结果进行组装。典型的例子如google search API, yahoo search API等。

运用搜索API进行mashup，可以做出像这个URL（http://www.langreiter.com/exec/yahoo-vs-google.html，对比两个搜索引擎的搜索结果）这样好玩的应用。

2、文字资讯类

不可否认，RSS接口可以成为几乎所有文字资讯类服务，如资讯类网站、博客、论坛的标准API。也因此，google reader（http://reader.google.com/）、抓虾（http://www.zhuaxia.com/）、鲜果（http://www.xianguo.com/）等阅读器才能够轻松我们的阅读生活。

而在此之外，还有许多专有的API提供这专有的文字资讯类服务，例如twitter的API、craigslist的API、豆瓣（http://www.douban.com/）的API等。

3、多媒体类（图片、视频等）

flickr（http://www.flickr.com/）是雅虎旗下的著名图片分享网站，flickr开放了API接口，所以才有第三方fans为它开发各种操作系统下的五花八门的工具（http://www.flickr.com/services/）。

google旗下的视频网站youtube（http://www.youtube.com/）也是同样因开放API而受益匪浅（http://code.google.com/apis/youtube/casestudies/）。

4、地理信息类

如前所述，地图API应该算得上是最有趣的API之一了，因为它为一维的文字信息提供了一个二维的载体，此外，互联网上的信息7、80%与地理位置有关也是重要的原因。所以google、yahoo纷纷开放了自己的地图API。google更是搞到了地球的卫星图片，做了三维的地理信息服务及开放接口，那就是著名的谷歌地球google earth（http://earth.google.com/）及其API（http://code.google.com/apis/earth/）。有人用google earth做了个游戏（http://www.gewar.net/），可以去玩玩。

5、用户及关系类

在社交网站风靡的今天，用户关系信息也成为一大类重要的数据。这方面的杰出代表就是facebook（http://www.facebook.com/），它通过开放API使得大量的第三方开发者可以在其社会化网络平台上开发出成千上百的应用，从而极大丰富了其平台自身的功用和乐趣。

而google也不甘寂寞，2007年11月1日，Google宣布了自己的社会关系平台标准Open Social。并且与facebook把接口专有的做法不同，google致力于推广这套API，力图使得全世界的社交网站都遵循这个标准API开放它们的数据。凭借google在互联网界的强大号召力， 参与此一开放平台的，除了MySpace外，还包括Engage.com、Friendster、hi5、Hyves、 imeem、LinkedIn、Ning、Oracle、Orkut、Plaxo、Salesforce.com、Six Apart、Tianji、Viadeo、XING等等网站。

在google大力推广Open Social这个开放平台标准的压力下，在今年6月，Facebook 把旗下的 F8 完全转变为开放源代码的平台，这无意给社交网络开放平台的标准之争增加了更多变数。

6、电子商务类

电子商务类网站提供的服务主要是围绕企业信息、商品信息展开的，此类网站开放API的主要目的是吸引第三方开发者开发各种附加功能，提高访问量、成交量或者用户粘性，从而提高网站自身的盈利水平，同时，将提高的部分盈利与第三方开发者利益分摊，吸引开发者持续开发和运营。典型的代表如amazon。据悉国内的C2C网站淘宝（http://www.taobao.com/）也即将开放API。

7、注册类

最后，还有一类不太引人注意的API，那就是注册类的API。几乎所有的网站在开放接口的时候都会同时提供一套供用户认证身份的专有API。但是openID（http://openid.net/）这个项目却是在致力于提供一个标准的、通用的注册API，如果所有网站都遵守了openID规范，那么我们就不用为每个网站记住一套用户名和密码了。

## 走向开放平台

通过开放API的方式，我们可以对众多的信息和应用进行再加工，使得之间的关联得以显现。但是用户通常还是需要在各个不同的地方跑来跑去。在2007年5月24日，Facebook推出开放平台，利用这个框架，第三方软件开发者可以开发与Facebook核心功能集成的应用程序。Facebook的做法，让整个openAPI前进了一大步，由此也带动互联网走向平台争战的新格局。Facebook创始人Mark Zuckerberg在接受Fortune杂志访问的时候，毫不讳言的说：“We want to make Facebook into something of an operating system so you can run full applications”。开放平台（open platform）由此作为一个新名词跃入人们的眼帘。

所谓开放平台，就是首先提供一个基本的服务，然后通过开放自身的接口，使得第三方开发者得以通过运用和组装其接口以及其他第三方服务接口产生新的应用，并且使得该应用能够统一运行在这个平台之上，我们把这样的一种网络服务模式叫做开放平台。这个基本的服务可以是已有的，例如门户、博客，也可以是新创的，例如用户关系。无论是那一种，开放平台模式成功的要点在于，通过自身服务和第三方应用的互利互惠，提高用户对平台网站的粘性和使用程度，进而提高获利，同时，通过利益分摊，达到平台自身和第三方应用循环刺激而产生的滚雪球式的增长。

基于类似于Facebook这样的开放平台，我们可以发现我们在前面所提到的碎片化的互联网里面遇到的种种问题，都有解决的可能，在未来将会在开放平台的基础上诞生个人的web操作系统。在开放平台时代，整个互联网的生产方式也发生了变革，从原来的一个个独立网站这样子的小作坊生产走向基于开放平台的大规模协作生产，网站与网站之间从数据层进行连接，变得更为紧密，而互惠方式也从单一的广告走向多样化的模式。

开放平台按照平台自身是否提供一个有显著应用模式的服务可以划分为两类：

1、应用型开放平台

应用型开放平台的特点是自身依赖一个基础的应用模式（例如用户关系、博客等），然后开放平台供第三方开发者扩展，这一种的开放平台大致有以下几类：

A、基于用户关系的

例如facebook。

B、基于个人门户的

例如myyahoo,igoogle和netvibes。

C、基于博客的

例如sohu blog。

是否每一种基础应用模式开放出去都能最终建立起平台-第三方应用-用户的循环刺激，从而带来整个开放系统的良性循环发展，答案明显是否定的。就上述几种开放平台而言，只有类似于Facebook这样的基于用户关系的开放平台很好的解决了我们在碎片化的互联网时代遇到的大多问题，而基于个人门户和基于博客的开放平台，只是停留在简单的应用组装层面，难以让用户很好的控制不同的数据，在应用推广上，也由于缺乏基于用户关系的链式传播路径，带来很多问题。

2. 服务型开放平台

服务型开放平台常常不会太引人注意，因为它们往往是躲在幕后的角色。这类平台本身并没有一个基础的应用模式，而是把计算资源作为一种服务，通过开放API提供给开发者，让开发者能够以极为低廉的服务费拥有大量、稳定的计算或存储资源。这类开放平台有一个热门的昵称，“云计算”。这方面的代表有amazon S3（http://aws.amazon.com/s3），google  appengine（http://code.google.com/appengine/）。

这两类开放平台并不矛盾，反而相得益彰。第三方开发者通过运用服务型开放平台提供的计算和存储服务，可以不再为机器、软件的运维所烦扰，融合各类openAPI，专心做好应用的业务逻辑和界面逻辑，然后部署到应用型开放平台中去，以及其低廉的成本快速开发和部署了绚丽的应用，服务于应用型开放平台中的大量用户，进而为整个平台和自己都创造了极佳的前景。

## 中国开放平台现状

在国外互联网的带动下，中国互联网也正走向开放平台时代。

**中国开放平台竞争格局**

(image lost)

继搜狐blog在今年1月推出开放平台之后，4月份myspace中国（聚友）宣布开放。6月13日，Google中国正式发布了其“开放平台战略”，将其OpenSocial标准在中国广泛推广。而且继商务社交平台天际网作为中国第一个社区加入OpenSocial联盟后，天涯、海内、校内网、豆瓣、聚友、51等十家社区网站正式投入到Google的怀抱。

在中国开放平台的竞争中，目前Open Social系占据主导力量，其中校内和51将在稍后的时间里正式开放，这两家大量的用户和用户数据都让开发者充满期待。据了解校内网已经做好开放的准备工作，蓄势待发，目前想要围绕校内开发应用的开发者现在已经可以添加这个叫做developer的APP。Facebook开源F8之后，中国的其他平台是否会采用Facebook的标准，现在加入Open Social阵营的社区网站是否会采用兼容的模式甚至直接跳到F8的阵营，还要拭目以待，但在可预见的未来，Facebook肯定会进军中国市场。以康盛的ucenter home为代表的蚂蚁雄兵，则通过提供SNS网站程序的方式，在大的开放平台之外诞生了众多的小蚂蚁。如何将蚂蚁聚集在一起，形成雄兵，路数尚不知晓，康盛在未来是否会采用ning的模式也值得观察，但康盛在可预见的未来必定会考虑打通各个SNS网站，并构建自己的开放平台。雅虎中国（雅虎口碑）的站长天下和一起网显然是想以开放平台的模式来运作，但未来走向扑朔迷离。值得特别关注的是淘宝的开放，代表了中国电子商务应用的开放平台模式，而ebay则在近日公布了Project Echo计划，显然也是想走开放的模式，ebay中国也将有所动作。

在未来的格局中值得期待，也将给中国的开放平台竞争带来诸多变数的是两家中国互联网的领军企业：百度和腾讯。腾讯CEO马化腾在一次接受采访中表示，腾讯将在年内开放，具体时间和如何开放目前尚不明了。百度虽然目前未有明确表示开放的战略，但可以预见，在竞争的推动下，百度也将逐步走向开放。

2008将作为中国互联网的开放年留在人们的记忆中，中国互联网已经走上平台争战的道路，互联网的格局或许将因此而改变。


作者：

谭晨辉：www.sociappy.com（专业社会化应用服务提供商）创始人。

刘青焱：www.oplatform.org （开放平台实验室）联合创始人。