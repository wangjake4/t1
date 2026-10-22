代发 wailian999

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gt2bsmefkbh.html

[...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2sxfqrwuh.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gt2mjeorsos.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2riehfqeu.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gt2dvpejpye.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gt2lzhtjxxe.html

[U92] JS：深拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwdgkqww.html

structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2loserjxm.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gt2wwavhjym.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gt2zrqceezt.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2mhhpzdla.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gt2looqtcnx.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gt2onknmnic.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2pagkbbuv.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gt2fwmofbml.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2vlwwqpes.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gt2nmypccxt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2iwofqjlv.html

[U98] JS：fetch 带 JSON
来源：http://dali.mhx1999.top/Article/details/gt2svvusigs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gt2mruvzgpu.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gt2jfalnltc.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyzdhnsi.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gt2olamyfyg.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gt2zabkudby.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gt2hsifkjub.html

el.classList.toggle("active")
来源：http://dali.yangfankeji.com/Article/details/gt2qdyvddvo.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgwqpkkk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsmydskv.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gt2rkrisftq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gt2duftngfi.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gt2glpuxpfl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2lcprujtz.html

[U105] JS：节流
来源：http://dali.zhixingplan.top/Article/details/gt2tmveqmwp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gt2kqkowuyd.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gt2wwjfoclw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gt2qzojcnme.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2daginohu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjljqcwf.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gt2mdrrmmfo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcgcfjr.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gt2sczzewun.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gt2ceqqlzmw.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gt2hlzloxml.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gt2ivlgtfyb.html

[U111] JS：对象转 Map
来源：http://dali.gogol.net.cn/Article/details/gt2ulelxawa.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gt2jgioiwcm.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gt2mtiuntyi.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2nbeofwea.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gt2qwcswryz.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2gfsdtqtj.html

[U114] JS：JSON 深比较
来源：http://dali.jianghu66.top/Article/details/gt2mruvxdtn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gt2zzxmdmbl.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2bvtdorgb.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2cipvucqy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gt2miafmyft.html

/** @param {string} name */ function f(name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ahhqkjox.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gt2ckfgrpca.html

npm i -D vitest;  npx vitest
来源：http://dali.cdnleiting.top/Article/details/gt2uizpridn.html

[U118] JS：开发服务器
来源：http://dali.nanxinkj.top/Article/details/gt2sowoosai.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2xzrpjqxa.html

[U119] JS：生产构建
来源：http://dali.daria6918.cn/Article/details/gt2tsxpvucr.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gt2uvsczgtb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gt2guihwaqc.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gt2ixhawxpm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2lpfobuen.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gt2iockmzwj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ytpzblwe.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gt2jumnjvtt.html

Python ......... 252
来源：http://dali.yueranfly.top/Article/details/gt2yhdkbgji.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gt2iudfqpxp.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gt2eqrblccl.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gt2upkotjtf.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2hpcdimsg.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2ynwbjqyh.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2fghkzcnu.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2hpvpqqma.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gt2otmojebb.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewsgppij.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gt2vdhuvzvy.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gt2siqendha.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xafbawuy.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gt2zldzsktd.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gt2bbvsgaev.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gt2jkvcvezd.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gt2ovymgukw.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gt2dqlyfjcm.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gt2phlaquvq.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gt2myuksdyg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecrtruym.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gt2fxrikrhe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2kpctqomq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gt2urjadmxr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gt2djulhjtu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gt2vjhjhxah.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2vdifrdhd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2krcdaclb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2qecuctrq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2haxtvivc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2avummudk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2khdkodnq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fekaawny.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2ohhbxkrx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gt2zjoosbyx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gt2yvugaxim.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gt2rylphuiv.html

R Bash 专题                             80
来源：http://dali.birdmap.top/Article/details/gt2kpbewjii.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2jxpwlhwn.html

T 其他语言补充                          60
来源：http://dali.c1oappe.top/Article/details/gt2mtglahwi.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izwjstku.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2ybrogbvo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2isseuadf.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2tkkrektx.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gt2ojaarxud.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilbkegvc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hywenlv.cn/Article/details/gt2kspxrfqh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gt2oyrdqfck.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gt2jtznlyxq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.quarkkingdee.top/Article/details/gt2pazosurh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gt2zirhcfwr.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gt2qamzzuhj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jfamzdww.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxokemuj.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigfzy.top/Article/details/gt2rezifoqt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ldwsbjeg.html

【收录内容】
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clnnorng.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gzhubu.top/Article/details/gt2boebsdof.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gt2gcqdenao.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gt2viubgvks.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.0kj1m.cn/Article/details/gt2vzicvfzm.html

【使用说明】
来源：http://dali.ehwqpu.com/Article/details/gt2avdahkve.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gt2wfikcplh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gt2ihgtoccu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gt2xbpbdbnn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gt2kkjisscw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gt2wsrhdutf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhoulong.xyz/Article/details/gt2xdlawntw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmoakaah.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gt2zdjiqyuf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gt2mpyfxxuy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.andypj.xyz/Article/details/gt2mvigqfsd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gt2oonvdzjs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gzhubu.top/Article/details/gt2rpfddpwu.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gt2snorjnnu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cucudq.cn/Article/details/gt2ocnfamgq.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2ejirlrdk.html

目  录
来源：http://dali.svipenyu.cn/Article/details/gt2qnoakwbw.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2viynpqfd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gt2wvrrarlx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gt2nslvvedl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gt2vxcetwbt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gt2ysbcomjn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gt2azqfpoli.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gt2xancsoas.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gt2snmisrix.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2vkvcvbqt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2kgqgeqwl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2cpvjpgwr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2mmlmceyd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gt2dtfysciw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2spdyiaxv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gt2gdlnnyhw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ydzc1.top/Article/details/gt2nrqjnabr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2zmqgvaln.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gt2kgsijbfc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2myxctbgd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gt2qqwkjfby.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2hbaiqkcc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2nppysajb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vhkawcqq.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gt2svzqtrdm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2zjnrjjdv.html

[A01] Hello World
来源：http://dali.mhx1999.top/Article/details/gt2pjytndxe.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gt2sjjuqqvz.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gt2ildftkan.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2goxowars.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuxming.cn/Article/details/gt2uerriaho.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gt2fmxcqwjp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gt2hjzvfnbs.html

Ruby: puts "Hello, World!"
来源：http://dali.aizwys.cn/Article/details/gt2fcyehosb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2ekasrrdo.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gt2ygdyaanq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gt2iaeyzwlx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gt2tneuqyuc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2mzqnzwox.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2vzujjasu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2gduzgxsu.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnxiangtu.top/Article/details/gt2gjkzhnmo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yongpay.top/Article/details/gt2unrfdusz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gt2oszhrdmm.html

[A03] 常量定义
来源：http://dali.yongpay.top/Article/details/gt2xmuytssf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrvnhlsa.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2vwmqynus.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2lfzmxatv.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2emuhgdhw.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2fxwiwbcs.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2exrtskoz.html

Ruby: PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gt2cqiprgow.html

C#:   const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2oggsruzs.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsxthzvd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangdashe.top/Article/details/gt2iisdjghg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2tewwpfqe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gt2qhrjlsat.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojxvonrj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sufxvd.cn/Article/details/gt2jnoerfrr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zycfv.cn/Article/details/gt2odmoutwy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gt2nibildzl.html

C#:   x.GetType().Name; x is int
来源：http://dali.vqdsnc.cn/Article/details/gt2rxjmsbzk.html

[A05] 整数除法与取模
来源：http://dali.haohaochexian.top/Article/details/gt2pqjtnllb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hammf.cn/Article/details/gt2mlfxoncq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2anrbszcy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gt2osibkzvr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfzvpwp.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itvpzhwy.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2onzvjtxc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoktahn.html

C#:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2ytaqopoc.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gt2arhkxvre.html

Py:   int("42"); float("3.14")
来源：http://dali.haohaochexian.top/Article/details/gt2wzrabhqo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gt2kzuckmoe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gt2lkjofzoi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfjjxsmf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ehwqpu.com/Article/details/gt2yhzmypac.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zdqjudy.top/Article/details/gt2qmorpaop.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gt2qbsnuhzr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cucudq.cn/Article/details/gt2ofiswxzi.html

[A07] 数字转字符串
来源：http://dali.fengsongda.top/Article/details/gt2byktfvho.html

Py:   str(42)
来源：http://dali.pycfn.com/Article/details/gt2ctcuqulx.html

PHP:  (string) 42; strval(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2ephvbiqi.html

JS:   String(42); (42).toString()
来源：http://dali.sweek.top/Article/details/gt2xbmeqbvw.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2omoqnwid.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sweek.top/Article/details/gt2hpiknlwc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzmfwima.html

Ruby: 42.to_s
来源：http://dali.jqgufenzy.top/Article/details/gt2dqgkukha.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2iwpkmtfp.html

[A08] 取整与四舍五入
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtxdazat.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2ezyxwtpu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2occipzog.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2bguspsxf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnqzz.top/Article/details/gt2selcdgit.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2ffcivshl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfdppnih.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gt2laezrydq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gt2yyqayttu.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2wrkjxeek.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2pzavufqy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2zpjlcaeq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2wcmnlqov.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2llquryss.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2zawzeysg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fengsongda.top/Article/details/gt2aisbpdow.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gt2tkkvaets.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2saxxself.html

[A10] 生成随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2eurdwjdw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ehwqpu.com/Article/details/gt2sloxrtnt.html

PHP:  random_int(1, 100);
来源：http://dali.chenzaomai.com/Article/details/gt2agqsfcyu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hfpthk.cn/Article/details/gt2wkiyygof.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gt2zhkonquw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.redwolf501.top/Article/details/gt2bavnwkuj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gt2aljrgozj.html

Ruby: rand(1..100)
来源：http://dali.ydzc1.top/Article/details/gt2bvaswdbp.html

C#:   new Random().Next(1, 101)
来源：http://dali.dashuyun.cn/Article/details/gt2hditrtlf.html

[A11] 条件表达式（三元）
来源：http://dali.chenzaomai.com/Article/details/gt2yopzsyqy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yonumen.top/Article/details/gt2xanagksy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2dodnupch.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nztslqbn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2fwhzuzjj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2bszjifcs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ivvv.top/Article/details/gt2tdcogefg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfsqssfl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gt2pihbfngc.html

[A12] 字符串插值 / 格式化
来源：http://dali.gotoacloud.top/Article/details/gt2zvliwebg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gt2edimizfy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenzaomai.com/Article/details/gt2cwwktcar.html

JS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gt2kvvbzrfl.html

TS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gt2kzrklzrs.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigufen.top/Article/details/gt2mvjifmdp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxinkj.top/Article/details/gt2dfvrtowl.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gt2kwostuyq.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gt2vmqebwec.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhongyouzk.top/Article/details/gt2xokoqaik.html

Py:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2xrtsqsgt.html

PHP:  "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2ulohhaeo.html

JS:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttkkpkmd.html

TS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2qejxrbnf.html

Java: "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2dstapotr.html

Go:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gt2kqepqxcq.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gt2kuabdyli.html

C#:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gt2ncrkclxu.html

[A14] 注释写法
来源：http://dali.hongshengwenyu.top/Article/details/gt2zafbrexo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tian-w.cn/Article/details/gt2ykkjpell.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gt2hxkvrchi.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuwvetew.html

TS:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuzyyfvg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tianlin.xyz/Article/details/gt2rcmukbsc.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2pudcooms.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ppjwa.cn/Article/details/gt2ipeczvcx.html

C#:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gt2szrmzzrl.html

[A15] 空值判断与默认值
来源：http://dali.yj202588.top/Article/details/gt2otgbifdi.html

Py:   value = data or "默认值"
来源：http://dali.ehwqpu.com/Article/details/gt2ydgnvkgn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2yazvnnyb.html


<!-- 参考信息 -->