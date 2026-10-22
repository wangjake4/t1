代发 wailian999

[U89] JS：数组去重
来源：http://dali.ivvv.top/Article/details/gt2dlkhzncj.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2jofgqjek.html

[U90] JS：数字数组排序
来源：http://dali.ppjwa.cn/Article/details/gt2qkskrtrw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2ivvralgt.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gt2tknjhyyc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gt2qmeciaoq.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2sdefbovm.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2bzburunk.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxjombxs.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gt2zskwsisu.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2xiovoayw.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gt2grlxtkme.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlpegbkg.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gt2yhmucqfh.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gt2ukgdlmde.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yaiagmrw.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gt2kyimqoms.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2bzqlrqbm.html

[U98] JS：fetch 带 JSON
来源：http://dali.cashguo.top/Article/details/gt2phctrvwl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gt2qilkvdic.html

[U99] JS：事件监听
来源：http://dali.gogol.net.cn/Article/details/gt2inksukxu.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2qatcplnr.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkdwlvwn.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gt2nedigvqa.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gt2wajgtmwr.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gt2hwmoydyv.html

[U102] JS：本地存储
来源：http://dali.dashuyun.cn/Article/details/gt2ldovnwns.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdskzxow.html

[U103] JS：定时器
来源：http://dali.nwbrower.top/Article/details/gt2bjksclwu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gt2vswcbjwh.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gt2xbnbzzri.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2slcbcdqy.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gt2cjsgvjul.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gogol.net.cn/Article/details/gt2lrjgkwox.html

[U106] JS：日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2tewqzado.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2icwxlwzy.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2gbxpttgb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2axvjpjkb.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gt2lpsxpnib.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gt2ncvptygg.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gt2igrqkani.html

Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2wvoimtpw.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gt2xbwfylhe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gt2dwdkfpnm.html

[U111] JS：对象转 Map
来源：http://dali.9152youxi.cn/Article/details/gt2ytoaemmv.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gt2rjsoklrd.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvobljcs.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gt2tobrmkzs.html

[U113] JS：正则替换全部
来源：http://dali.xinyue.icu/Article/details/gt2phccncbg.html

s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2tvuzkwre.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gt2kbuecmga.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2fibovmcg.html

[U115] JS：生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2txpdgezc.html

crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2otrgaotv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gt2qhneesgl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2pxfiixdv.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gt2ckbzensu.html

npm i -D vitest;  npx vitest
来源：http://dali.gotoacloud.top/Article/details/gt2wutbvhvl.html

[U118] JS：开发服务器
来源：http://dali.xinyue.icu/Article/details/gt2povjhbim.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gt2jfcbhawn.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2mgunyvsw.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gt2kvnppuwu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxgluzey.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gt2xegwklqf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pgbuzcjm.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gt2mvcgfggb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nhatakcg.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gt2jwkeqlcr.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gt2exbseazd.html

PHP ............ 252
来源：http://dali.vqdsnc.cn/Article/details/gt2gnlxmqmd.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gt2tpfweiaz.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gt2ehhnxslm.html

Java ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2kgvpuksb.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2uvfhodmh.html

Ruby ........... 212
来源：http://dali.9152youxi.cn/Article/details/gt2npcqgspk.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2sofueazt.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gt2kjvspdre.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gt2belfkeok.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gt2avdekfub.html

Bash ........... 80
来源：http://dali.redwolf501.top/Article/details/gt2zibfolku.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gt2lcxjwhes.html

Swift .......... 15
来源：http://dali.fengsongda.top/Article/details/gt2bwwsrapz.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gt2cxexrmih.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gt2gdwiundj.html

Scala .......... 10
来源：http://dali.cheryme.top/Article/details/gt2mcdnmvdv.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2rvkjzkol.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gt2aipwotpw.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gt2qltwpllr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gt2fxtoafza.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gt2ebgbvqhy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmpewygu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gt2sozkfvqc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigufen.top/Article/details/gt2bszbjqeu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2amgrqilr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2cxwfuwcg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gt2uzoqiaku.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2kudbxcqv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gt2vhlqlgbx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2xkwsnnrs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2lczbafwt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2lhcxpawa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gt2obzpxtlo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gt2ydbcxbmv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2ocwlnmug.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gt2evflcgbz.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkuiwlhv.html

S C / C++ 专题                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2octpjquc.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gt2dihuzqrw.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gt2tuipjtll.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2ckuiuqwn.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gt2xzrhqgeq.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2kejrjgru.html

使用提醒
来源：http://dali.yonumen.top/Article/details/gt2dpfbkwmp.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2zzzuycmg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gt2ykmuhuka.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gt2pvclxuwy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cheryme.top/Article/details/gt2xbmyijwh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.quarkkingdee.top/Article/details/gt2cwcijdbl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gt2glazeswe.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gt2drotohaq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2nwuirlmf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gt2lsyemcwi.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gt2bwuddcxb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2femzsmle.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gt2vmbyicbk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbvslswh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gt2yzoqfqpg.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gt2hbpdojgv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gt2iyreldpk.html

【使用说明】
来源：http://dali.chenzaomai.com/Article/details/gt2zdywsmhi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aibaodan.cn/Article/details/gt2agmtkqce.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.redwolf501.top/Article/details/gt2igugfakk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.haohaochexian.top/Article/details/gt2uibtnira.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenlongwang.top/Article/details/gt2zwwfjtsv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.smart0.xyz/Article/details/gt2ceucocjd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgfzy.top/Article/details/gt2iyfrlcbb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daxiang520.top/Article/details/gt2wghyyszj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pycfn.com/Article/details/gt2vimbdyco.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuanzhike.top/Article/details/gt2jmfdsttm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gt2txlrkpim.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gt2rokxvigm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sysykeji.top/Article/details/gt2hpskkcnv.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlnxtxbj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gt2bltuypwh.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyctgvem.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gt2czrpqgpl.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2jztlrxhf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gt2rtsicuok.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2ehszntfp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2wqxmmnzb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gt2wrwydhpg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guowangkeji.top/Article/details/gt2caygtkxu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gt2naztkknp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2duefkoyz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gt2mpbissra.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gt2ucarrszb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2ndhafzzs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2tqqowrda.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2eiymjpny.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2meznnexw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gt2sehsmbdu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2xjmpreuj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rfhnimgl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvdbswzg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2glmfawfw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhengqikj.top/Article/details/gt2usrhdtds.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2wqtvrgtr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmuqpsdf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jnlreazt.html

A. 基础语法与类型
来源：http://dali.pycfn.com/Article/details/gt2ibiuoftr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrzoknai.html

[A01] Hello World
来源：http://dali.iojbl.cn/Article/details/gt2cmqqoqqf.html

Py:   print("Hello, World!")
来源：http://dali.cqqwz.cn/Article/details/gt2lscqtoxz.html

PHP:  echo "Hello, World!";
来源：http://dali.guannengcc.top/Article/details/gt2innyrapl.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gt2niurzdmh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgfzy.top/Article/details/gt2jwkgirdg.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2nrxpsyxf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gt2cncrcfbi.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2qyjuscuc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2odfiqzce.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gt2qmfqrozx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zdqjudy.top/Article/details/gt2kdavglav.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.aibaodan.cn/Article/details/gt2iwawwjte.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2guklorqe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gemhulkt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2nohxagme.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gt2ymerpihr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbkfsata.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2endyouiy.html

[A03] 常量定义
来源：http://dali.ivvv.top/Article/details/gt2iomoredd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.svipenyu.cn/Article/details/gt2gervpwsb.html

PHP:  const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2rkozvurp.html

JS:   const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2dsvffkpv.html

TS:   const PI: number = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2sfkqvpyc.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2tsqkglwa.html

Go:   const PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gt2gfqwloxt.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gt2jpvgjxrh.html

C#:   const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2ttetiwii.html

[A04] 判断变量类型
来源：http://dali.tanke756.top/Article/details/gt2jqpsifxm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2jfzhslqb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gt2gegbebxo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gt2zqeuhtfp.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gt2ifkftnnf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gt2titpcazu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gt2lysvwajp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkjxwyvc.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gt2vhwomrll.html

[A05] 整数除法与取模
来源：http://dali.chenlongwang.top/Article/details/gt2ybbpmokr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvmaboyl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2miynruty.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2kqshxozq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2nzwolgrf.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2jhutffit.html

Go:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2nytozmfo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2qdfrcaka.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2awgtencx.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2nulqedlm.html

Py:   int("42"); float("3.14")
来源：http://dali.andypj.xyz/Article/details/gt2bkydmiwd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.iojbl.cn/Article/details/gt2wzsrkvln.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2xbfghgpc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gt2mnewztrx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hprzwusi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gt2drxqcjen.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ybcxt.top/Article/details/gt2eobndwea.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gt2rhxwtljp.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2hevmyiiq.html

Py:   str(42)
来源：http://dali.hnqzz.top/Article/details/gt2qxlzwlvf.html

PHP:  (string) 42; strval(42)
来源：http://dali.havefunace.top/Article/details/gt2reejpfdd.html

JS:   String(42); (42).toString()
来源：http://dali.svipenyu.cn/Article/details/gt2lpfsqavt.html

TS:   String(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2hduphlkz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuanzhike.top/Article/details/gt2ffbvpwwu.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gt2prnhxyfp.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gt2rarrgvxc.html

C#:   42.ToString()
来源：http://dali.yuxming.cn/Article/details/gt2kfzwkhme.html

[A08] 取整与四舍五入
来源：http://dali.ehwqpu.com/Article/details/gt2dpadktnf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mavkmaub.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.0kj1m.cn/Article/details/gt2qphngrku.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2cuvsujub.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gt2odqwvtkj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2crvlmnlw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2hrkiyeyv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tian-w.cn/Article/details/gt2oncbufsh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxufhnug.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gt2adquvpwi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2xsojjaod.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2qjrwdqvy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2rmwsjamc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2utxrgywc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2irvdajmi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hfpthk.cn/Article/details/gt2wmorqxvm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnxiangtu.top/Article/details/gt2rhctqflz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2xjuqfnnr.html

[A10] 生成随机数
来源：http://dali.yueranfly.top/Article/details/gt2ffelhggo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxuanxn.top/Article/details/gt2rcfasatz.html

PHP:  random_int(1, 100);
来源：http://dali.meibo888.top/Article/details/gt2ikxkunql.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xlutsxet.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjeinsoe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.smart0.xyz/Article/details/gt2auqrahyd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gt2rknyiziz.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdpuekzq.html

C#:   new Random().Next(1, 101)
来源：http://dali.cheryme.top/Article/details/gt2fduvgdvd.html

[A11] 条件表达式（三元）
来源：http://dali.svipenyu.cn/Article/details/gt2gyqsvgez.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jyoumei.cn/Article/details/gt2phcxigjc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2delxmyte.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gt2bsmkmhhm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylyliark.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gt2eagibkqw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.dianchejie.cn/Article/details/gt2gbidcvvv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2dunmsieo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2dyeqasrp.html

[A12] 字符串插值 / 格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2jnkdjspc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.redwolf501.top/Article/details/gt2mxcgxvba.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pczyleue.html

JS:   `Hello, ${name}!`
来源：http://dali.sxryk.cn/Article/details/gt2ezroichv.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gt2vzkgnhkr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2yvpofkxl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkagultj.html

Ruby: "Hello, #{name}!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbkhnwbr.html

C#:   $"Hello, {name}!"
来源：http://dali.jiagoushi.top/Article/details/gt2dvwvregs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gt2bsztupwf.html

Py:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2izjmfzea.html

PHP:  "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2quccaofi.html

JS:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2axevihqs.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2poanskin.html

Java: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2pjtjfxjl.html

Go:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2zbfvissc.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2hjushgpm.html

C#:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2wcwoxywq.html

[A14] 注释写法
来源：http://dali.ybcxt.top/Article/details/gt2qmjdcnpf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.vqdsnc.cn/Article/details/gt2tohcmfhi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2mhbwgkuz.html

JS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2bszlhekd.html

TS:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gt2aluyqnzq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sweek.top/Article/details/gt2eoxbmijz.html

Go:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gt2ulvhnoge.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xziqi.cn/Article/details/gt2rwudlbot.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2ysynrspa.html

[A15] 空值判断与默认值
来源：http://dali.yonumen.top/Article/details/gt2unhwvoku.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2rkigfgaw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpklywzy.html


<!-- 参考信息 -->