代发 wailian999

[U85] JS：可选链
来源：http://dali.hammf.cn/Article/details/gt2lojtmnmj.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gt2kwaelhns.html

[U86] JS：空值合并
来源：http://dali.vqdsnc.cn/Article/details/gt2zjfqkyqq.html

a ?? b
来源：http://dali.zhongyouzk.top/Article/details/gt2xghxytom.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gt2pqdszljn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euglnhwj.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gt2miyxnuud.html

{ ...a, ...b }
来源：http://dali.316326.xyz/Article/details/gt2cmwbwpif.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gt2bsoqegwk.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2hcpqrvee.html

[U90] JS：数字数组排序
来源：http://dali.zhoulong.xyz/Article/details/gt2jpmaccow.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2ycipkjan.html

[U91] JS：对象键值遍历
来源：http://dali.hnqzz.top/Article/details/gt2ncxaully.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gt2xawbjvfl.html

[U92] JS：深拷贝
来源：http://dali.fengsongda.top/Article/details/gt2rioqcvqh.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2egpyhiey.html

[U93] JS：模板字符串
来源：http://dali.sufxvd.cn/Article/details/gt2esybuvht.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2yksfojdb.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gt2jbssstwm.html

const double = x => x * 2;
来源：http://dali.cucudq.cn/Article/details/gt2zkgrbohs.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gt2kgwqepnq.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gt2hyeuqrwp.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emamrced.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2ahpozlhj.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gt2ihttawnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmaqugrx.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenlongwang.top/Article/details/gt2szogprji.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gt2qonzxklo.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtzsioej.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpikdqns.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2osazcyot.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gt2jfutrxax.html

[U101] JS：classList 操作
来源：http://dali.9152youxi.cn/Article/details/gt2hgxqmpjc.html

el.classList.toggle("active")
来源：http://dali.pengpengdd.cyou/Article/details/gt2thghkjcs.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gt2bwscdysv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tianlin.xyz/Article/details/gt2dqczstak.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gt2uduztflq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yueranfly.top/Article/details/gt2cqqjkogo.html

[U104] JS：防抖
来源：http://dali.daxiang520.top/Article/details/gt2gnfplerd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2rendrqkh.html

[U105] JS：节流
来源：http://dali.shuidangran.top/Article/details/gt2xjppzyuz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gt2upbptpfh.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gt2kfkzzwks.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgvwvztb.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gt2sjfdrrqd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2buotogfn.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gt2wfvxdwvr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hfpthk.cn/Article/details/gt2pxjtsxcy.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfpfuyqv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2aresnvso.html

[U110] JS：数组分块
来源：http://dali.cqqwz.cn/Article/details/gt2wjylluyx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jlsjyb.cn/Article/details/gt2vmbbmfmn.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gt2evfjpkvf.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gt2jawwapct.html

[U112] JS：字符串补位
来源：http://dali.bjfxy.top/Article/details/gt2enqsrrmy.html

"7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjetacqg.html

[U113] JS：正则替换全部
来源：http://dali.tanke756.top/Article/details/gt2cgppztdb.html

s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2tleeiyjo.html

[U114] JS：JSON 深比较
来源：http://dali.yonumen.top/Article/details/gt2tvlukcqe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2ffsgpnmg.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2fqnbvxqh.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2hswvtcld.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gt2qwvrfywh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kerzbiqb.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gt2xvfctpfo.html

npm i -D vitest;  npx vitest
来源：http://dali.pycfn.com/Article/details/gt2yvkcfdob.html

[U118] JS：开发服务器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzilqotn.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gt2efteqmhc.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gt2mxqdtmfp.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gt2ljqlefuu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.bjfxy.top/Article/details/gt2apbcsrxs.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gt2jrairwth.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2bmdckizo.html

统计汇总
来源：http://dali.dashuyun.cn/Article/details/gt2hwqxsvqy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xlszttxt.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gt2lcyuvvvu.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gt2tjonsmox.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gt2gzopxdmc.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gt2erfjjnjs.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gt2uvrfoedi.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2kkpddzop.html

Go ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2qhtbxsud.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2tiihzcpc.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2fzdcugxo.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gt2izneqhpp.html

C++ ............ 30
来源：http://dali.tian-w.cn/Article/details/gt2afzhycul.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gt2sxsufqzd.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gt2bzmndswn.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gt2eqqevbbb.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gt2hcwniwdo.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gt2jawivjcu.html

Perl ........... 10
来源：http://dali.gotoacloud.top/Article/details/gt2kvpgtbku.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gt2tnyrqnnp.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2kwgwpqda.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gt2qgvxevgg.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gt2bgojpxsa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2ukxhwvqo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2blyuxrzq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2pimfpiah.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gt2tdxantcu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.quarkkingdee.top/Article/details/gt2yiozlike.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2lpfuduyz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2msbqkyti.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gt2xxzxaknj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2iuqexfvs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gt2lkralpix.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2qunomhsf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2ypprzulc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2srmutvue.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gt2rrhlzfok.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gt2gxctuacp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2bodhcity.html

Q SQL 专题                              90
来源：http://dali.zhongyouzk.top/Article/details/gt2wjwjzfee.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gt2asdjjxio.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gt2qgvbqfts.html

T 其他语言补充                          60
来源：http://dali.tanke756.top/Article/details/gt2cvgretaa.html

U 高频实用片段                         120
来源：http://dali.gogol.net.cn/Article/details/gt2hhofhgei.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2bwyfuvcv.html

合计                                  2106 条
来源：http://dali.hnqzz.top/Article/details/gt2wnvxxynn.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcomulwo.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gt2cnadhbad.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2usrcface.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gt2vjeoqaqa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqtuszhi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gt2weyfelev.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwydeswo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yonumen.top/Article/details/gt2hibsqpks.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gt2xbmlkodv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2segxtqub.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqiclpuo.html

Common Programming Examples Cheat Book
来源：http://dali.quarkkingdee.top/Article/details/gt2hhvwxwew.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2azcjtkyh.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gt2gsbbpgdq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nwbrower.top/Article/details/gt2hihqeptx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fleehnjr.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gt2ldmyifrg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jianghu66.top/Article/details/gt2ezdqzyml.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gt2huhtcujl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmljeati.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gt2dptskbuf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fengsongda.top/Article/details/gt2xnufbvew.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.smart0.xyz/Article/details/gt2ilrcgntf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhixingplan.top/Article/details/gt2jvftrkfx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jyoumei.cn/Article/details/gt2yhqyofab.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.c1oappe.top/Article/details/gt2mftxhrpd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gotoacloud.top/Article/details/gt2mfcncekn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gt2nhjvmfkj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlciuydi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ydzc1.top/Article/details/gt2klcyftjp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gogol.net.cn/Article/details/gt2tdzsraei.html

【文件统计】
来源：http://dali.nwbrower.top/Article/details/gt2flfyflqt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gt2jfeyeuvp.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2ocyjcawd.html

目  录
来源：http://dali.zhengqikj.top/Article/details/gt2xweuuers.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2ixxzeryp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2ealcaign.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gt2bghthitn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2vemgmvzk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gt2wcjnwyvb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gt2gfbjeqii.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gt2pjoqidqt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ghtmruuq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gt2kwzvxzek.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2oaicezik.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2gzfxznrm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2akxhtvor.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2ejpsltlh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2cjsfocyx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgpgceal.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwpyzjms.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2znvvyfga.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gt2sczhjfyq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gt2hchvzqms.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2wofrvwdm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2enqoudoa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2tkffoymn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2iszqqeeg.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gt2slpihagb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2licsypea.html

[A01] Hello World
来源：http://dali.pycfn.com/Article/details/gt2qxkwpwcd.html

Py:   print("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gt2otbmlttb.html

PHP:  echo "Hello, World!";
来源：http://dali.pycfn.com/Article/details/gt2briyneam.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2abxiydny.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gt2kxuvmcii.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gt2avkiydgu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwvuycdk.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gt2knddtsbc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2yrntoauj.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqwhmjla.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xylfe.cn/Article/details/gt2ochmeqmr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2ygfzzwkq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gt2boazawbb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2slbtrava.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gt2ofmyfnel.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gt2wsijyurl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dashuyun.cn/Article/details/gt2cifoelpz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2upimgltg.html

[A03] 常量定义
来源：http://dali.ehwqpu.com/Article/details/gt2fsprfnfb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.kuanghao11.cn/Article/details/gt2hckhfeor.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2osieopyz.html

JS:   const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2uoaysdrj.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2hqhrwshn.html

Java: static final double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2vldyoisd.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gt2cgzcqnvf.html

Ruby: PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gt2djxbclvl.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2rjcljkcd.html

[A04] 判断变量类型
来源：http://dali.daria6918.cn/Article/details/gt2ehdwkdkn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmstdsoy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.9152youxi.cn/Article/details/gt2flehrshm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gt2ivbgdndk.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gt2akxivbal.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj202588.top/Article/details/gt2yvkmgydh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gt2flvliitv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnxiangtu.top/Article/details/gt2nnrbqqvr.html

C#:   x.GetType().Name; x is int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2byfvxghk.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gt2yzknqwcw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sxryk.cn/Article/details/gt2ptrmqkxg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2rgjwfnko.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2emwsjbdc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuppfrsg.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2pkdrmwhn.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fydqhfmb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2ispxfglk.html

C#:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2agrfmgja.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2uiydcdko.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2hwjfyeww.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gt2kxsioofq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gt2ihhqqbtc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gt2rimpxobs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenlongwang.top/Article/details/gt2cbpichck.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvncxeab.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gt2eiaryszl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shuidangran.top/Article/details/gt2naozxhli.html

[A07] 数字转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2cdobqsxi.html

Py:   str(42)
来源：http://dali.haohaochexian.top/Article/details/gt2atuerduz.html

PHP:  (string) 42; strval(42)
来源：http://dali.316326.xyz/Article/details/gt2kxhyitrb.html

JS:   String(42); (42).toString()
来源：http://dali.guowangkeji.top/Article/details/gt2eeyyqbmh.html

TS:   String(42)
来源：http://dali.tianlin.xyz/Article/details/gt2rdwumwvl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.meibo888.top/Article/details/gt2lzmykvje.html

Go:   strconv.Itoa(42)
来源：http://dali.sweek.top/Article/details/gt2rytbkled.html

Ruby: 42.to_s
来源：http://dali.havefunace.top/Article/details/gt2mnudobwe.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iveablzs.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gt2brgiqmgs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2ukhslfej.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenzaomai.com/Article/details/gt2tfgavmfg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gt2chuxcdyi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvsrfanv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2aihgvlkm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2ywntqdwx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hammf.cn/Article/details/gt2kyxiaggh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2rmqvcdgi.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2nnxjxiuj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2hvsbvhfz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2ygwzgqqf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dehrsqgs.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2dvyunisi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2oqpfqiwn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgouhlwy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dznjquix.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2egnhmxjn.html

[A10] 生成随机数
来源：http://dali.jlsjyb.cn/Article/details/gt2gvfuzara.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daxiang520.top/Article/details/gt2yuycqjyg.html

PHP:  random_int(1, 100);
来源：http://dali.dashuyun.cn/Article/details/gt2fkwixzin.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gt2euazsmpm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gt2ihchiukk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2suzekqvp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ivvv.top/Article/details/gt2qjeibbwt.html

Ruby: rand(1..100)
来源：http://dali.jyoumei.cn/Article/details/gt2oggglihl.html

C#:   new Random().Next(1, 101)
来源：http://dali.pycfn.com/Article/details/gt2tgltumxh.html

[A11] 条件表达式（三元）
来源：http://dali.birdmap.top/Article/details/gt2npwaqzks.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj20258888.top/Article/details/gt2nxcbsttg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2edsquahl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2jmtfcjrq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsyppyae.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gt2otijkpek.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.316326.xyz/Article/details/gt2wxvqsxhd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gt2ehfxrsfe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2bdfwdqfl.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzfnxqpb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvsnzepi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gt2eqbwknyp.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgfzy.top/Article/details/gt2oqsqurdu.html

TS:   `Hello, ${name}!`
来源：http://dali.jianghu66.top/Article/details/gt2mbduojry.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2onvlyjne.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenzaomai.com/Article/details/gt2uvyuxqnt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zycfv.cn/Article/details/gt2onmsiyac.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gt2jvgdjrhl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tianlin.xyz/Article/details/gt2nzvxljri.html

Py:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2jiwcceuy.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2mrtykwmz.html

JS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2pmxowhew.html

TS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2eyonsbnk.html

Java: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2bfghmjnt.html

Go:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2naeunilw.html

Ruby: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2qjgsdlfz.html

C#:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2zosknvar.html

[A14] 注释写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2slmbnoec.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esqyrmih.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gt2njfbvqsi.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gt2hmdqgprw.html


<!-- 参考信息 -->