
![图片](https://p0-xtjj-private.juejin.cn/tos-cn-i-73owjymdk6/94ea6794127944d9af43b4f487653555~tplv-73owjymdk6-jj-mark-v1:0:0:0:0:5o6Y6YeR5oqA5pyv56S-5Yy6IEAg6L2v5Lu25rWL6K-V5ZCb:q75.awebp?policy=eyJ2bSI6MywidWlkIjoiMzU0MDkwMTExMjMxNzIyNCJ9&rk3s=f64ab15b&x-orig-authkey=f32326d3454f2ac7e96d3d06cdbb035152127018&x-orig-expires=1732743035&x-orig-sign=HvIKlBAdr0MUvBDZQX2Ou9gvvQk%3D)


可以说现在的工作已经完全离不开AI了，它的强大影响了各个领域。尤其在互联网领域，不少人心里直犯嘀咕：这AI大模型都这么厉害了，那测试开发和自动化测试这些岗位，是不是就快没活儿干，要被淘汰啦？


其实呀，这里面的门道可多着呢，且听我细细道来。


### AI在测试工作中的表现究竟咋样？


#### 功能测试方面的功与过


AI大模型在功能测试这块儿，一开始还真能让人眼前一亮。它就像是个聪明的小助手，能根据软件功能的描述呀，还有那些文档资料，嗖嗖地就生成一堆测试用例来。比如说咱平常常用的办公软件，像处理文字的软件里设置字体、排版段落、保存文档这些个功能，AI大模型生成的测试用例那是相当全面，正常咋操作的，还有那些可能会出错的情况，比如输错数据格式啦，操作不合规啦，它都能考虑到。


但它也没那么神，一旦碰到那种专业性特别强的软件，AI大模型可就有点懵圈了。就拿医疗影像分析软件来说吧，这里头全是专业的医学术语，还有复杂得让人头疼的影像分析算法，再加上严格的医疗规范要求。AI大模型呢，它对这些专业知识也就是一知半解的程度，所以生成的测试用例常常会漏掉一些关键的小细节，没办法把软件在实际医疗场景下的功能完完整整、准准确确地检测出来，甚至还瞎编乱造，搞不好就把一些隐藏的细节功能问题给忽略掉了，这可就有点麻烦啦。


#### 性能测试领域的喜与忧


在性能测试方面，AI大模型也有它的本事。它能模拟不少用户同时访问软件的情况呢。比如说测个在线视频平台软件吧，它能模拟好多人同时在那看视频、切换视频、发弹幕啥的，然后看看系统的响应时间、吞吐量这些个性能指标表现得咋样。


但咱得知道，真实世界里用户用软件可没那么规规矩矩的呀。就拿看视频来说吧，有的人看着看着突然就暂停了，然后不停地快进、倒退，还会因为网络环境变来变去就不断切换视频清晰度。这些个复杂多变的用户行为，AI大模型想要精准模拟出来可就太难啦。所以要是光靠AI大模型来做性能测试，很可能就会漏掉一些只有在真实使用场景下才会冒出来的性能瓶颈问题，那软件的性能到底咋样可真就不好说喽。


#### 安全测试角度的强与弱


说到安全测试，AI大模型也能起点作用。它能根据自己学到的那些安全漏洞模式，再加上大量的数据，对软件进行初步的漏洞扫描。像常见的SQL注入、跨站脚本攻击（XSS、这些个安全漏洞，它能发现一部分呢。


不过呢，现在网络安全形势那叫一个严峻啊，新型的安全漏洞就跟雨后春笋似的，不停地冒出来。有些攻击者可狡猾啦，想出的攻击手段又隐蔽又巧妙，比如利用新的技术手段生成的恶意代码，或者针对特定软件架构设计的零日漏洞。AI大模型呢，因为它数据更新和学习机制有点局限，它还没学习到，所以往往很难及时察觉到这些新型安全威胁。而且对于软件内部那些复杂的安全机制，比如多因素身份验证系统里不同认证方式的协同安全性，AI大模型也分析不透，搞不好就会漏掉一些潜在的安全隐患，这可关乎软件的安全命脉呀。


#### 兼容性测试方面的得与失


AI大模型在兼容性测试上也能出点力。它可以模拟不同的操作系统、浏览器、设备等环境，对软件进行兼容性检测。就拿手机应用来说吧，它能看看在不同品牌手机、不同安卓或iOS版本，以及各类主流浏览器上，软件的界面显示、功能交互是不是正常。


可是现实中啊，有好多那种小众的、特定行业专用的设备和软件组合，它们的兼容性要求可特殊啦。比如工业控制软件，得和特定型号的传感器、控制器以及工业网络协议配合得好好的才能正常工作。AI大模型对这些特殊情况了解不多，可能就无法准确检测出在这些特定环境下软件的兼容性问题，这要是在实际应用中必然会出岔子，那影响可就大啦。


### 测开和自动化测试的独特魅力


#### 测试开发岗位的核心价值


测试开发岗位那可是相当重要呀。测试开发人员要干的事儿就是开发各种各样的测试工具、框架和脚本，目的就是为了让测试工作更高效、更有效果。他们对软件的架构和技术栈那是了如指掌，能根据项目的具体需求，专门定制开发出合适的测试工具。


比如说吧，要是碰到那种复杂的分布式系统，测试开发人员就能开发出专门用来模拟分布式环境下各种故障场景的测试工具，这事儿你让AI大模型可就干不了。而且测试开发人员还能把自动化测试框架和持续集成/持续交付（CI/CD、流程紧密结合起来，确保每次代码提交后都能自动触发一系列测试，这样就能及时发现代码变更可能引入的问题。


你让AI大模型来干，不定给你整成啥样，还得靠人为去干预矫正。


所以，在优化测试脚本性能、提高测试覆盖率以及解决测试环境搭建中的复杂技术问题等方面，测试开发人员都有着不可替代的作用，他们就是软件测试的坚实后盾。


#### 自动化测试岗位的关键作用


自动化测试岗位也有它的独特作用。自动化测试人员主要就是把手动测试用例转化为自动化脚本然后去执行。他们对各种自动化测试工具和技术那是相当熟悉，能根据软件的功能特性和业务流程设计出高效的自动化测试方案。


就拿电商平台来说吧，每次功能升级后，自动化测试就能迅速对商品浏览、下单、支付、物流查询等核心功能进行全面测试，确保新功能的引入没有破坏原有功能的正常运行。而且自动化测试人员还能对自动化测试结果进行深入分析，及时发现测试脚本中的问题并进行优化，保证自动化测试的稳定性和可靠性。通过持续优化自动化测试流程和脚本，自动化测试人员不断提升软件测试的效率和质量，为软件产品的快速迭代提供了有力保障。


你让AI大模型去理解吃透业务，生成用例，再搞成脚本，这生成那玩意，有谱嘛!


### AI大模型与测试的携手共进


其实呀，AI大模型和测试开发、自动化测试岗位并不是谁要取代谁的关系，而是可以携手共进、优势互补的好伙伴。


AI大模型可以利用它强大的数据处理能力和快速生成测试资源的优势，为测试开发人员提供大量的基础测试素材，比如初步的测试用例、性能模拟数据等，这样就能大大提高测试工作的效率。同时，AI大模型也可以为自动化测试人员提供自动化测试脚本的模板或示例，加快自动化测试脚本的开发速度。


而测试开发人员呢，可以通过开发适配程序和接口，将AI大模型更好地集成到现有的测试工具和框架中。比如开发一个接口将AI大模型生成的测试用例自动导入到自动化测试框架中，实现无缝对接。自动化测试人员则可以利用AI大模型对测试结果进行初步分析和筛选，快速定位可能存在问题的测试区域，然后再凭借自身的专业技能进行深入的缺陷分析和定位。


另外，测试开发和自动化测试人员在日常工作中积累的大量实际测试数据和经验，可以反馈给AI大模型，帮助其不断优化算法和模型，提高其在测试工作中的准确性和有效性。就像把实际测试中发现的新型安全漏洞案例反馈给AI大模型，使其能够学习并更新安全漏洞检测模式，增强对新型安全威胁的识别能力。


可以说体力活，它都能帮你干了。


### 总结


虽然，AI 大模型在日常工作中独占鳌头了，但。它毛病也不少。


咱搞技术的，对软件架构、业务流程心里有数，专业测试技术和工具开发能力也不差，在工作里那也是至关重要。


要我说，还是得保持独立思考和 AI 大模型搞好分工，让二者相辅相成。这样软件测试才能又快又准，软件质量才有底，软件行业那些五花八门的需求也才能对付得了。你觉得呢？


### 往期阅读


[**测试工程师的苦水与解药：别让这些问题毁了你的职业生涯！**](https://github.com)\*\*\*\*


[**技术前沿：AI大模型在自动化测试中的应用实例**](https://github.com):[飞数机场](https://ze16.com)\*\*\*\*


[**38 岁测试工程师：跳出 “简历黑洞”，逆袭高薪 offer 的秘籍大揭秘！**](https://github.com)


