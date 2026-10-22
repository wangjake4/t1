代发 wailian999

[U93] JS：模板字符串
来源：http://dali.yj20258.top/Article/details/gt2nzsazprk.html

`共 ${n} 条`
来源：http://dali.meibo888.top/Article/details/gt2ecpqpcdv.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gt2pyqfoloe.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gt2fpmivsov.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxhhincv.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gt2tqlyjjnn.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxptfffp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2smmjyoap.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2veaqikzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2mprsydij.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okwmgvrz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gt2sapgjbpy.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gt2hxlzbggl.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vblakmgo.html

[U100] JS：DOM 查询
来源：http://dali.vqdsnc.cn/Article/details/gt2bczrhdod.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gt2rekjudps.html

[U101] JS：classList 操作
来源：http://dali.redwolf501.top/Article/details/gt2sxcdhuki.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baxwxdqb.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2nimkzdne.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gt2cqqfexub.html

[U103] JS：定时器
来源：http://dali.yangfankeji.com/Article/details/gt2clfxliyq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnqzz.top/Article/details/gt2nyirymtn.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gt2sysfvuxc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2ktqmmyub.html

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gt2hrphvovv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gt2uoyemdro.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2htpetqfo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shzxlz.cn/Article/details/gt2yhyzrqws.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2vlrdmiuv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ookgtqvz.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gt2snuxrwbb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pycfn.com/Article/details/gt2btflpvap.html

[U109] JS：数组分组
来源：http://dali.cqqwz.cn/Article/details/gt2nbejjkvw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gt2fszbwckm.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gt2tiibrnpo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnprhjas.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gt2qwmjrghv.html

new Map(Object.entries(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2ostsqxsy.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gt2nxzsuqdd.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gt2frmuwnzq.html

[U113] JS：正则替换全部
来源：http://dali.jqgfzy.top/Article/details/gt2ttjrkjzw.html

s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2hbfnnzie.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gt2lvlxshwi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2ingbaiim.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2sdagedrb.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2mtvqnyau.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gt2hebqtjmc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gt2mbbrqcgc.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gt2bddrpale.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gt2tusmpneu.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gt2xqsazkwy.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gt2fvjznkja.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gt2ndzcfyay.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2zsbmbghf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gt2foymjzjn.html

import.meta.env.VITE_API_URL
来源：http://dali.c1oappe.top/Article/details/gt2kebfujon.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2isyisefg.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gt2iqvhxjdc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fbumjoie.html

按语言统计（条）：
来源：http://dali.yj20258.top/Article/details/gt2gzxnvbti.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gt2bmdhlvwj.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gt2nmoknxbv.html

JavaScript ..... 252
来源：http://dali.0kj1m.cn/Article/details/gt2roardger.html

TypeScript ..... 212
来源：http://dali.sysykeji.top/Article/details/gt2vyxvhvap.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2bapzktyk.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gt2tzfmftvz.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gt2nyhvjjqo.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gt2hehczvlb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpbtsqq.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gt2cxcugauu.html

SQL ............ 90
来源：http://dali.xziqi.cn/Article/details/gt2igigueuc.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gt2cfbyldft.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gt2zoervxlg.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2qyemsmth.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gt2iwnozlhx.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gt2apoljbqa.html

Scala .......... 10
来源：http://dali.jlsjyb.cn/Article/details/gt2smebmycc.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2smptrjuq.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gt2naockghf.html

按章节统计：
来源：http://dali.xuanzx.com/Article/details/gt2wulkwawx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gt2kdmchloq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2fjbqxxfm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2vzmydptj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gt2vdlspxir.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gt2oibldphx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gt2thcnzgqu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2nidpaqnm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2otvdxlpz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gt2irwugiry.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gt2oqcymkrg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2ftledngf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2muibaxup.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2mbuemmtg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2qpufsxwx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gt2emafrzln.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2kcrzmsez.html

Q SQL 专题                              90
来源：http://dali.zycfv.cn/Article/details/gt2biffwacu.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gt2pdjkyvvs.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gt2gplpmwya.html

T 其他语言补充                          60
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqifmdga.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gt2ottubnze.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2ytuimfev.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gt2ngsdilpd.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2gxtiedwm.html

使用提醒
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqvwaehm.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2fuhpxvbo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gt2ioejcbsk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gt2iclietde.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gt2imrkhgeg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gt2dcfylyru.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gt2fsgcshaf.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gt2rcanmxjb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jfvhrmgp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cglsmxqy.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gt2knxoaodn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tnkvejkn.html

【收录内容】
来源：http://dali.gogol.net.cn/Article/details/gt2wtlmwmeq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gt2cvaazjoy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sufxvd.cn/Article/details/gt2iwoqchel.html

SQL · Bash · C · C++
来源：http://dali.gotoacloud.top/Article/details/gt2hkjxqafd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gt2hngkszxu.html

【使用说明】
来源：http://dali.zdqjudy.top/Article/details/gt2gxwywziy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ydzc1.top/Article/details/gt2jwrfzgpt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbccfraj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gt2vmdjnfjp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gt2iqquapch.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkxhswol.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gt2dcuzmbpi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gt2xryemjds.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ybcxt.top/Article/details/gt2samcmokg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gt2vskhsrvj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2khjdilvr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxuanxn.top/Article/details/gt2togfsamc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gt2mujxilxy.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gt2crsxboqe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gt2easpbjef.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2dmldyorz.html

目  录
来源：http://dali.hammf.cn/Article/details/gt2nwtpjjdq.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2wpngpoae.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gt2ynygkebw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpynbulc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxqbousm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gt2agwtnify.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2zycmjzyi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2zpzfskog.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gt2ygekpxcj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2bazcjvfi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2fypdneqg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gt2upozwzkp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2mtkkoonn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2aoxbsxee.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlznkzjm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gt2uawvnzva.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gt2mpapiskp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2ybqrbnsd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gt2iiekmdrm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2bujpregg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nwbrower.top/Article/details/gt2fxbjawpi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkexkdrv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcmkzoza.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2owpeatzc.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gt2lnipeqly.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2jyevdihr.html

[A01] Hello World
来源：http://dali.316326.xyz/Article/details/gt2vqfobsmw.html

Py:   print("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zizzuovq.html

PHP:  echo "Hello, World!";
来源：http://dali.hammf.cn/Article/details/gt2xptbjmub.html

JS:   console.log("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2vtchinka.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gt2nlalkopq.html

Java: System.out.println("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gt2lgwwqjog.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gt2seeutmxd.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gt2tdlgtiio.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2mbeeobze.html

[A02] 变量声明与赋值
来源：http://dali.nanxuanxn.top/Article/details/gt2koojbyee.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gt2phuqqfbj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2rytwbxqq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmjfvfbc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gt2foeauluo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2jenusjwr.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gt2spaaeqab.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gt2cjnlbhbf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dettfboq.html

[A03] 常量定义
来源：http://dali.fzhhl.top/Article/details/gt2jnduqosd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gt2inkrthxb.html

PHP:  const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2hwwqceht.html

JS:   const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2ljjdpfro.html

TS:   const PI: number = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2gxpexnux.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2dqpugcmv.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2soatehcm.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iportgyx.html

C#:   const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2kvttujrl.html

[A04] 判断变量类型
来源：http://dali.yonumen.top/Article/details/gt2vpmmwhft.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gt2fdjclhno.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.vqdsnc.cn/Article/details/gt2ugotimvg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gt2kdxlrqga.html

TS:   typeof x; x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gt2xkxveoyq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvlrmmky.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tianlin.xyz/Article/details/gt2xjoygmgo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gt2fjkeclie.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gt2yqwmhlco.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gt2estmivef.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.smart0.xyz/Article/details/gt2hiagitsx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2edwhijdw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2gsdxjxce.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2ropdwqjx.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2buyuftru.html

Go:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gt2pxfjizfv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2ebtirewn.html

C#:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2pdbyljtj.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gt2tarymkvc.html

Py:   int("42"); float("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjqztunf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.birdmap.top/Article/details/gt2ummunqcy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nwbrower.top/Article/details/gt2rvrmsjde.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gt2jdatncdj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gt2xkaswruj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gt2fyyzusmc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tanke756.top/Article/details/gt2qketuglu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cqqwz.cn/Article/details/gt2upwvjpmd.html

[A07] 数字转字符串
来源：http://dali.ivvv.top/Article/details/gt2pzkwpifl.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pshjozyr.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gt2mnaupsao.html

JS:   String(42); (42).toString()
来源：http://dali.sweek.top/Article/details/gt2jwfrykbv.html

TS:   String(42)
来源：http://dali.sxryk.cn/Article/details/gt2tncrqryx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xziqi.cn/Article/details/gt2nwpyqtjp.html

Go:   strconv.Itoa(42)
来源：http://dali.nwbrower.top/Article/details/gt2uljsxafq.html

Ruby: 42.to_s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bftnfcwr.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gt2ztnkclod.html

[A08] 取整与四舍五入
来源：http://dali.ppjwa.cn/Article/details/gt2blbrrgfi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2sodlronx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gt2yfcbmurp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2rngskltk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ydzc1.top/Article/details/gt2rgfcyaoy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2grahgpvg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdoubbwf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.aibaodan.cn/Article/details/gt2uekzuinp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gt2wkegnxot.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2ygmeyeeq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2uzlihehr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2ppxsnylr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbrwbtcx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2oejrcazn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2bjrxlnaz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gt2ypgmwoup.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.bjfxy.top/Article/details/gt2jtpljxeg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2viqxxsji.html

[A10] 生成随机数
来源：http://dali.tian-w.cn/Article/details/gt2ostbifpn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tianlin.xyz/Article/details/gt2yaryvhyv.html

PHP:  random_int(1, 100);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixubhbbu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gt2bhyfxnxl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gt2wrmslejz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2thvwoydi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ydzc1.top/Article/details/gt2mincwigb.html

Ruby: rand(1..100)
来源：http://dali.havefunace.top/Article/details/gt2eiqwphml.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gt2oarziwwp.html

[A11] 条件表达式（三元）
来源：http://dali.aibaodan.cn/Article/details/gt2jxgsvhsc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2gdgjlrpd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2fqqatezw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2fwzluhch.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2kolfejzz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sexjawyn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gogol.net.cn/Article/details/gt2nvbkbfah.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2llrfssep.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2oguapgfk.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gt2qbnxjuwt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigfzy.top/Article/details/gt2bcjjddhg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gt2bhaxkefs.html

JS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gt2kczunblw.html

TS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gt2zdgrmbec.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pycfn.com/Article/details/gt2akyxefvy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xinyue.icu/Article/details/gt2wvmkqaym.html

Ruby: "Hello, #{name}!"
来源：http://dali.svipenyu.cn/Article/details/gt2lbmxxqrf.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gt2dxjmjnlx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlljsthc.html

Py:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2emmomens.html

PHP:  "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2efqgvqiy.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heducusa.html

TS:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2iknreghs.html

Java: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2oeyjbjku.html

Go:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2gjkhwvpb.html

Ruby: "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxcxmabo.html

C#:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2ydpmagtg.html

[A14] 注释写法
来源：http://dali.zhoulong.xyz/Article/details/gt2dxjqfato.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgfzy.top/Article/details/gt2vesymnco.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2kaqtqoha.html

JS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2tceoqilr.html

TS:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gt2abpxmavm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hnxiangtu.top/Article/details/gt2iknrayqy.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gt2wdbcxhgq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gzhubu.top/Article/details/gt2mgguqbay.html

C#:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gt2tulvwekk.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gt2plgnjhqq.html

Py:   value = data or "默认值"
来源：http://dali.xinyue.icu/Article/details/gt2cnlyvdlb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gt2rjuyunvp.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gluixflm.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gt2lmqhrkkk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jqgfzy.top/Article/details/gt2glhnkeww.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gt2bsbgpoxp.html

Ruby: value = data || "默认值"
来源：http://dali.ehwqpu.com/Article/details/gt2odgaajse.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2zccagirb.html

[A16] 真假值判断规则
来源：http://dali.gzhubu.top/Article/details/gt2gtpblwdn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxinkj.top/Article/details/gt2qoojqyyh.html


<!-- 参考信息 -->