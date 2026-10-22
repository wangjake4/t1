代发 wailian999

[U89] JS：数组去重
来源：http://dali.birdmap.top/Article/details/gt2cttxvupd.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2kysgfmva.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gt2wlndoito.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2tylaflmb.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gt2ksmjqrtr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuanzx.com/Article/details/gt2bwmvnbgo.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2hpqipqjk.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ugehewtf.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2yaaybehx.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gt2vmhejhsc.html

[U94] JS：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gt2dmsrxdlk.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gt2lgfxbdgi.html

[U95] JS：Promise 包装
来源：http://dali.gaohongyu789.top/Article/details/gt2qojzywaz.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gt2xcgqxopq.html

[U96] JS：async/await 与异常
来源：http://dali.andypj.xyz/Article/details/gt2qpzqrwhu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcoikndv.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gt2smsqdshd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2pmvjbqwa.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gt2ngjabesj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gt2bebiuupx.html

[U99] JS：事件监听
来源：http://dali.jqgfzy.top/Article/details/gt2spxbhvfq.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gt2hofoigen.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gt2riewfdhy.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gt2snsmrtby.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gt2lihhjezo.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gt2khemhyvc.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gt2gdgpwfvk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnqzz.top/Article/details/gt2nimfpxku.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gt2kuifsnkt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shuidangran.top/Article/details/gt2gdimjmkl.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gt2rtckjdfx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2qxzyotzr.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gt2phlymgyu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gt2djglbepf.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2cuxcnmwj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gt2unbkzvfr.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gt2pvzoisfj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2aeskyqqy.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gt2wvalkwgy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2niijgovv.html

[U109] JS：数组分组
来源：http://dali.yueranfly.top/Article/details/gt2zqeisxyh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2gigqjyht.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gt2dnkuvans.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gt2fyhwheku.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gt2eptvenau.html

new Map(Object.entries(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2jlzcvgvd.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gt2unelwsrz.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2mkuwjfli.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gt2haghxqth.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2husogese.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gt2nagqldxv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2ppaqbdad.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxxgjvdl.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2szvtoafj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gt2uebmevld.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gt2jrokxyvk.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gt2rdwuioit.html

npm i -D vitest;  npx vitest
来源：http://dali.daxiang520.top/Article/details/gt2odjvlrvu.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gt2ocdkklqk.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gt2pjkzgzyg.html

[U119] JS：生产构建
来源：http://dali.aibaodan.cn/Article/details/gt2kygpkmyb.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gt2wvzgcepj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gt2qxvnutvt.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gt2cimqpopa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qmysabxc.html

统计汇总
来源：http://dali.sweek.top/Article/details/gt2cvovuodh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2oqffjmgj.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gt2mxhsnrez.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gt2rbnovzrl.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gt2qfapmwzf.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gt2vzplbfim.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gt2bpiqepjd.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gt2jzcfxrpj.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gt2roangnax.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2xewlbvsi.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gt2pmtcfbnp.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gt2ajphzrmu.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gt2qtcomomh.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjhaepxt.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gt2zaqbapfw.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtetrzkn.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gt2xgdnqxgy.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gt2hgzgmwpv.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gt2yjjerpeu.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gt2mmciumsa.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2zfhfmftc.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gt2kqqzises.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gt2gzprfktm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gt2qkpvplxp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gt2ytktsdnk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2goqxecdg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhshzqfd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangdashe.top/Article/details/gt2vmkeuven.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gt2foeluodo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gt2idptdrom.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2wvpebmol.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2zekwvqud.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2dewfgehb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2bqgekydq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2venripkn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2ldsflzmj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gt2royyqrst.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hongshengwenyu.top/Article/details/gt2jievsbqn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2mxkyfghc.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gt2slrujvvu.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gt2mhsztrrc.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gt2clilpvqp.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2kxyrpffb.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2usfkpoqz.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2lcpbzolo.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gt2qoocaulw.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2vwdrsegb.html

使用提醒
来源：http://dali.feifeiyinyue.top/Article/details/gt2snoekymd.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2yjlayqyf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gt2yckpgapa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gt2xcgpuxik.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnqzz.top/Article/details/gt2xeeklfjs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gt2aaeqhxzb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuetiantiany.cn/Article/details/gt2koeutjxe.html

—— 文件结束 ——
来源：http://dali.yueranfly.top/Article/details/gt2wzjydhbh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2skhwdsdz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gt2rvulunar.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gt2zeyskphf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ejhzjmsn.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gt2grhbxoya.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gt2rbyhpdoo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gzhubu.top/Article/details/gt2wglqnqbm.html

SQL · Bash · C · C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufmnirqg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigfzy.top/Article/details/gt2kzqcelkj.html

【使用说明】
来源：http://dali.zdqjudy.top/Article/details/gt2xawwusrz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gt2wlrahpki.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gt2uphfbfmr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ommclqyr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2stkdnkbb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hnxiangtu.top/Article/details/gt2tolzigfb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gt2daxpoipi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gt2deytieri.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dianchejie.cn/Article/details/gt2vctgenak.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gt2exphmnts.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gt2rwbrgunb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cdnleiting.top/Article/details/gt2gfuiqqsf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gt2wchzxypl.html

【文件统计】
来源：http://dali.zhengqikj.top/Article/details/gt2xckjhjsb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fzhhl.top/Article/details/gt2kzphhrvp.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2yxayjgoa.html

目  录
来源：http://dali.cucudq.cn/Article/details/gt2rjmpvgeg.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kexaxdwu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gt2qlvdczlv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gt2vydpiqyd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2xdzjsxlq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gt2epecyvzz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyfxomjb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2gbpigvcf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jovadnkx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2irgarwmr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhwabqoh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gt2uhfdgnuq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2zonvvisq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2ovmmaaqd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2atohmgcf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gt2qaemdvsf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gt2jwvseypl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gt2ikreyqot.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2khqikoon.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2meoiibny.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.svipenyu.cn/Article/details/gt2mizwwbgc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2obwamwpy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2zftshvnb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qowgmfns.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gt2lznqecpu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2usmgthhr.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2llgmwutd.html

Py:   print("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gt2vrpmjeux.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gt2pqfhjudp.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2wwapiycb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gt2ptkzwlat.html

Java: System.out.println("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clqqoexl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gt2jmuoscwm.html

Ruby: puts "Hello, World!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2vocgzeep.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2nhyaewpu.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezgabzon.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2dvbxulsj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yvedp.cn/Article/details/gt2vajeuypr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2paflrjca.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gt2acxqdall.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2xpksefhz.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gt2imwobatp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gt2dbxmappq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2atscbubf.html

[A03] 常量定义
来源：http://dali.xylfe.cn/Article/details/gt2gegngjie.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukqdevjt.html

PHP:  const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2qgvqiphy.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2lcolrbgi.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2lwoqwohi.html

Java: static final double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2qyttxdan.html

Go:   const PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gt2upymzuyw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoktqto.html

C#:   const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2wpnkgvgv.html

[A04] 判断变量类型
来源：http://dali.wangdashe.top/Article/details/gt2imokmvnd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjxzjegk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.mhx1999.top/Article/details/gt2xqiywgmj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnbxtzxn.html

TS:   typeof x; x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gt2ahsocvob.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gt2smibtasp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gt2ztrzuxkv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigufen.top/Article/details/gt2drcvdewn.html

C#:   x.GetType().Name; x is int
来源：http://dali.gaohongyu789.top/Article/details/gt2nbqgcwqf.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gt2sudhhmgn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.havefunace.top/Article/details/gt2iuowxgsy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2ikkuuvub.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2ymerzgto.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2pnlxwhki.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2xoxsxdgx.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2ckyxapkm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2lzkozwuh.html

C#:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2whbvbrca.html

[A06] 字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2hsdpshlr.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmjccvyh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dashuyun.cn/Article/details/gt2alfagkii.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gt2jouiwykr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gt2qwosizlb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gt2slgczqea.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yangfankeji.com/Article/details/gt2tusjuthj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gt2vaoijbop.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2bsblrmxs.html

[A07] 数字转字符串
来源：http://dali.havefunace.top/Article/details/gt2rsnwhrbo.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gt2rtnmhkuh.html

PHP:  (string) 42; strval(42)
来源：http://dali.yonumen.top/Article/details/gt2ruoxdrno.html

JS:   String(42); (42).toString()
来源：http://dali.dashuyun.cn/Article/details/gt2bawqxiwq.html

TS:   String(42)
来源：http://dali.aibaodan.cn/Article/details/gt2mcizlzwa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gt2lmnpxbwc.html

Go:   strconv.Itoa(42)
来源：http://dali.yvedp.cn/Article/details/gt2bmgrylmf.html

Ruby: 42.to_s
来源：http://dali.hnqzz.top/Article/details/gt2yenqfbhr.html

C#:   42.ToString()
来源：http://dali.cheryme.top/Article/details/gt2rudwijoq.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gt2vjzpgjun.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2isjepcdc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgufenzy.top/Article/details/gt2vrzamkgs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2hldfnqna.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cheryme.top/Article/details/gt2sntoorsk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2ijiymzng.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2legrapyq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dashuyun.cn/Article/details/gt2nxvtzhkx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2dkdsiavx.html

[A09] 绝对值与最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gt2iswgbbpz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2xxrkfmml.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2sypdbows.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2afkhhzya.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2aafrsqnd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2gfeyipxs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjjrrijl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhixingplan.top/Article/details/gt2sluvbnlu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2lsflazko.html

[A10] 生成随机数
来源：http://dali.shzxlz.cn/Article/details/gt2etzpgesk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icduzfoz.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gt2yyawtqeg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.0kj1m.cn/Article/details/gt2tpoudnlt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gt2nsfljegw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jyoumei.cn/Article/details/gt2lwpdhhoi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj202588.top/Article/details/gt2teolotlz.html

Ruby: rand(1..100)
来源：http://dali.bjfxy.top/Article/details/gt2ttmwkqqz.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258.top/Article/details/gt2ykyiajip.html

[A11] 条件表达式（三元）
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyrrunnd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nwbrower.top/Article/details/gt2dsskkwvz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gt2xgkbutpw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2murpxwch.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2nnwuranr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrzdrwip.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yanxiufei.cn/Article/details/gt2wtrdmgvh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2iepavxhi.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvwqrxdb.html

[A12] 字符串插值 / 格式化
来源：http://dali.hysaishi.cn/Article/details/gt2rjhnifve.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.haohaochexian.top/Article/details/gt2gbdxyeye.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.snrcjt.cn/Article/details/gt2lowbzgzl.html

JS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gt2ewcrimmy.html

TS:   `Hello, ${name}!`
来源：http://dali.kuanghao11.cn/Article/details/gt2retuqooz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsjqgjix.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yongpay.top/Article/details/gt2mgjpzmwm.html

Ruby: "Hello, #{name}!"
来源：http://dali.jyoumei.cn/Article/details/gt2bbnzcric.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gt2assujgkh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.aibaodan.cn/Article/details/gt2akfravzv.html

Py:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2rqmfkeeu.html

PHP:  "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2jvypphjg.html

JS:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inrvglql.html

TS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2sckzbsme.html

Java: "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2xmwnsyja.html

Go:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2tnthnhqp.html

Ruby: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2jweowqms.html

C#:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffriblad.html

[A14] 注释写法
来源：http://dali.hnqzz.top/Article/details/gt2hhmkpsyx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gt2ygerpxkv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gt2nkltemwo.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2gcxlbgla.html

TS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gt2rsfvlscf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuanzhike.top/Article/details/gt2uvmiknpb.html

Go:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2eomgzigj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gogol.net.cn/Article/details/gt2anrafxwl.html

C#:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gt2urdlgqmy.html

[A15] 空值判断与默认值
来源：http://dali.birdmap.top/Article/details/gt2zubsjblq.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdazexiw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gt2pnklrcpi.html


<!-- 参考信息 -->