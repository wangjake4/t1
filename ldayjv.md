代发 wailian999

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gt2fztmmzkp.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gt2pdbqyqmz.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gt2fodolyng.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gt2tggnzzgt.html

[U95] JS：Promise 包装
来源：http://dali.dashuyun.cn/Article/details/gt2nqncrilh.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gt2zrktvprm.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gt2jrqqqlow.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2cjkivkrb.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gt2tbsskxks.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2uudnjmia.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2wvbqrtyw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2fhnopjsy.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2vdmdcpeu.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2wirtfaii.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gt2zqhooitw.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gt2pnsnzuyg.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2fplylwnc.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gt2ninngymf.html

[U102] JS：本地存储
来源：http://dali.chenjidiqi.icu/Article/details/gt2aytdasrc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gt2twgwkocb.html

[U103] JS：定时器
来源：http://dali.jqgfzy.top/Article/details/gt2fbmpfixr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gt2acriwsyu.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gt2llxxqzof.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2ocobtwtd.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gt2ugympeff.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtsphqqa.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gt2mmoahjdr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2utmlhumo.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gt2oytfrehs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gt2mrguidmj.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwdrhdys.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gt2dhqyghix.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gt2zdopglnu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2xgyicjeh.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtenwfwg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gt2stbzbzvg.html

[U111] JS：对象转 Map
来源：http://dali.jqgfzy.top/Article/details/gt2vsfquetl.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gt2ouzpwooj.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gt2tjvghczk.html

"7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2latpndvk.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gt2tqvidlsa.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2muabzrhj.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gt2tindudrb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iasalews.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gt2hqrdasnv.html

crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2cjjivyup.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gt2aaeiibeq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2skheincb.html

[U117] JS：单元测试
来源：http://dali.0kj1m.cn/Article/details/gt2wxtbwond.html

npm i -D vitest;  npx vitest
来源：http://dali.sweek.top/Article/details/gt2oiplcmum.html

[U118] JS：开发服务器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gesbrupp.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gt2acoadezl.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gt2qyxfyoai.html

npx vite build
来源：http://dali.wangdashe.top/Article/details/gt2xqxgqtzt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gt2bosccvty.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gt2ceupcuoa.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jagjchvp.html

统计汇总
来源：http://dali.nwbrower.top/Article/details/gt2hdkbbvne.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbxsdqsu.html

按语言统计（条）：
来源：http://dali.xuetiantiany.cn/Article/details/gt2ondboxlk.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gt2yjhghfkr.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gt2ovkcfjrz.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gt2wyprglmv.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gt2drojjyzu.html

Java ........... 212
来源：http://dali.smart0.xyz/Article/details/gt2aycouwrr.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2pcddxdef.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gt2aeavhgqw.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2fwbbdtur.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gt2efaihhmb.html

C++ ............ 30
来源：http://dali.smart0.xyz/Article/details/gt2efnpuzcb.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gt2kgdagxjv.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gt2ioszfmfb.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gt2zwrrqkto.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2oruioaip.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gt2eckscytj.html

Perl ........... 10
来源：http://dali.iojbl.cn/Article/details/gt2yxvfpfwp.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gt2adgfakam.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2ppmqcnsy.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gt2ccnazydc.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gt2opuohaha.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2fpnygvrm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gt2rhpjvwgt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gt2qyxjxwjt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gt2eksmreys.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gt2ftzshyci.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2rihvitvp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2harybely.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2uxiuqpze.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2ukfmpzpy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gt2zfrhpyyp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2cscbztow.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkjeaspj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gt2gzhlekxs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gt2kwhvmthp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awzysqqd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2rlfqmpcf.html

Q SQL 专题                              90
来源：http://dali.9152youxi.cn/Article/details/gt2hxakajpy.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gt2iintysnh.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gt2tghpdbpb.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gt2amrbnafw.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqtxawnt.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxoubzbt.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aliwbroq.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2pqirrrzx.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gt2yqfkgomz.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2zmepejds.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guannengcc.top/Article/details/gt2ukdsfmmn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gt2jesjwuuh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cheryme.top/Article/details/gt2ggmdoxma.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gt2ggsbjnza.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gt2nfkhsuuf.html

—— 文件结束 ——
来源：http://dali.yongpay.top/Article/details/gt2lmwtksfe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hirqaujh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dianchejie.cn/Article/details/gt2focxtxcr.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gt2kdvalptu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuubezys.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gt2ahxpudps.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gt2hjbrnsxk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gt2isgyewal.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gt2txnfeezk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jiagoushi.top/Article/details/gt2hglzedfb.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gt2gsrgrdwd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gt2mtoajndn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gt2yxmdzozo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gt2isbeuejg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.9152youxi.cn/Article/details/gt2veyvancg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gt2nmecxfqp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gaohongyu789.top/Article/details/gt2epnyujig.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gt2tltmuutu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwqgfeer.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gt2arjuuzfu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gt2notpfaxi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohpldmnn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhongyouzk.top/Article/details/gt2xhhnamqg.html

【文件统计】
来源：http://dali.jyoumei.cn/Article/details/gt2wthiywzz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gt2owvvsdzz.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2rtifyrqa.html

目  录
来源：http://dali.ydzc1.top/Article/details/gt2llmamxsn.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2wbhkhlam.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gt2hunwqehq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gt2vghigvtp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2sixzrqye.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2vsazbmht.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gt2ucqkqxst.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gt2nzbyyxyp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gt2isgurwzp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2ncoqlacd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2csdsplld.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2hpdgktwz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2evzqchyx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2czktusks.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2tnknwdfo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gt2pykhlxvo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cucudq.cn/Article/details/gt2miuspgsr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2eynigbxe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gt2nhdrkfoy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2oomatzis.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cashguo.top/Article/details/gt2bdtvxqde.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gt2avmxmjaa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gt2dakvrrqw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2eqvnnzgr.html

A. 基础语法与类型
来源：http://dali.yj202588.top/Article/details/gt2gtpiqffq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dnxmywmm.html

[A01] Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqqyrgum.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gt2knpraquk.html

PHP:  echo "Hello, World!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2biwbxpzj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gt2ghviprww.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gt2qukddidx.html

Java: System.out.println("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2urmwofbg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gt2knvsawrg.html

Ruby: puts "Hello, World!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwjiuooj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gt2bsqhuybm.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gt2iiudrdwe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhoulong.xyz/Article/details/gt2sgxqorih.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqxwoahv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2vdkmzkbh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2hruzsmvr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2drdwimvb.html

Go:   name := "Alex"; age := 20
来源：http://dali.hongshengwenyu.top/Article/details/gt2hliezttj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gt2rewuhexl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gt2hzulrecs.html

[A03] 常量定义
来源：http://dali.tian-w.cn/Article/details/gt2cdotxkrg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gt2onnmxfxg.html

PHP:  const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2gavbnzxv.html

JS:   const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2ncraqcob.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2ucjcpnpg.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2jphqgmsb.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gt2zbdrxrmx.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gt2tqyggupd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2mdsgmrrx.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gt2xecberaz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.redwolf501.top/Article/details/gt2yiambitc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tian-w.cn/Article/details/gt2ygckkksm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrjowobj.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gt2lydjexnw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tanke756.top/Article/details/gt2qevrxsvi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gt2owyiqnsq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxuanxn.top/Article/details/gt2xbaeikaw.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gt2tfckvxpm.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gt2wumrrqwa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnqzz.top/Article/details/gt2izkmpiax.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2cijwwfnn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2pepdhgbx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2wciofvxp.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2mhvnblhw.html

Go:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smklgzxq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuqgolhc.html

C#:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2ymtzfveu.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gt2gnhqmcoo.html

Py:   int("42"); float("3.14")
来源：http://dali.mhx1999.top/Article/details/gt2gdpkimkv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyabuxqo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2jvxnvkbz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xylfe.cn/Article/details/gt2ckwxkhio.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daria6918.cn/Article/details/gt2kqeuniqj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gt2jhgguoxe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gt2lhciflpi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uixvhujk.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2jocteqve.html

Py:   str(42)
来源：http://dali.jqgufenzy.top/Article/details/gt2ibrffoiq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gt2fgqdabaa.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gt2wkaxcexn.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2qaytijpj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigufen.top/Article/details/gt2rowomjne.html

Go:   strconv.Itoa(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2evlnaayo.html

Ruby: 42.to_s
来源：http://dali.vqdsnc.cn/Article/details/gt2qatebjan.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhcxzmlv.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gt2ftyuplmk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2afzcczzi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gt2uwutibbz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gt2pvggfzgg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsooeocc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kelfdncm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2cxchrdtq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gt2urupoyii.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2hpctjjkf.html

[A09] 绝对值与最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2ghtubgcc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2bzalhjea.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2tabjrnwf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2ymvpeqfq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2kqcznptb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgvlbaqs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbebgoeh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jyoumei.cn/Article/details/gt2xpsxvass.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dypjrlpl.html

[A10] 生成随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjnzqgid.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gotoacloud.top/Article/details/gt2nslrzkzf.html

PHP:  random_int(1, 100);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyhmvqfj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gt2hkmnkjzy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gt2yrmvncfe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenzaomai.com/Article/details/gt2pelqjkzg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sufxvd.cn/Article/details/gt2hvpypytu.html

Ruby: rand(1..100)
来源：http://dali.yj202588.top/Article/details/gt2fdfbpmfj.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj202588.top/Article/details/gt2rxtekbbu.html

[A11] 条件表达式（三元）
来源：http://dali.quarkkingdee.top/Article/details/gt2mzluapdz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gt2jjjiwwhy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2rsyoksgm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2afdpqvpb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2doefrveu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2zchdzglr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.smart0.xyz/Article/details/gt2hkvvmwqa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbpjhbxa.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwivdpgj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2bfjyhfyq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cheryme.top/Article/details/gt2wsdcokyf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ydzc1.top/Article/details/gt2udcnqjed.html

JS:   `Hello, ${name}!`
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvrqwgsv.html

TS:   `Hello, ${name}!`
来源：http://dali.sxryk.cn/Article/details/gt2kqgciojy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2bnekqgwp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.0kj1m.cn/Article/details/gt2mwzhinlj.html

Ruby: "Hello, #{name}!"
来源：http://dali.aibaodan.cn/Article/details/gt2qfszkdui.html

C#:   $"Hello, {name}!"
来源：http://dali.bjfxy.top/Article/details/gt2hzoqxxaq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xziqi.cn/Article/details/gt2dswkmnba.html

Py:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2nkikwysv.html

PHP:  "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gt2anvobhqk.html

JS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gt2mlooimbp.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2xhnrdfum.html

Java: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2fskxpkom.html

Go:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2gyyvkjrq.html

Ruby: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2utkljsyh.html

C#:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2cxkezlia.html

[A14] 注释写法
来源：http://dali.jqgfzy.top/Article/details/gt2wbmcxnrj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.svipenyu.cn/Article/details/gt2eqstebov.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gt2rknfciab.html

JS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2tmvhpmjr.html

TS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gt2sesbevhl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ppjwa.cn/Article/details/gt2ykqckxar.html

Go:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gt2qjvoqoyi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zdqjudy.top/Article/details/gt2mdbmfgby.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvjpgvwy.html

[A15] 空值判断与默认值
来源：http://dali.sysykeji.top/Article/details/gt2yycfwvji.html

Py:   value = data or "默认值"
来源：http://dali.cdnleiting.top/Article/details/gt2atkshlhj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2tyypqnds.html

JS:   const value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gt2vtyyfkip.html

TS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gt2mzvsogvt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tianlin.xyz/Article/details/gt2zlqoarac.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cqqwz.cn/Article/details/gt2blpnjtfj.html

Ruby: value = data || "默认值"
来源：http://dali.dashuyun.cn/Article/details/gt2mmiyddvs.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2tfetuoqi.html

[A16] 真假值判断规则
来源：http://dali.jiagoushi.top/Article/details/gt2xsajlbty.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yangfankeji.com/Article/details/gt2gqpvnddf.html


<!-- 参考信息 -->