代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtrrmlkrsk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gtdpbbwzqa.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gthdcwvjax.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgjranzc.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtvcozfgeo.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtovrsxqlg.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtohtujsxb.html

const double = x => x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtclquppmq.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gtqcrfkcqo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gtolwvmjvy.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmqwynos.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtpcgikyff.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gteldmrjfq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtuamokykp.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtfxrqnomh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtbfnxpkwk.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtzfqpanms.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtendtxrso.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtsawrciwg.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtufihsibg.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gtsiztpxzw.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gtckwfrysm.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtlbaxsopc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gtkbiiozvh.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtftqhcclu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtqaghilng.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtttdoufpz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtazcvdxzr.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gtnzzxgubq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtusgmyndx.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gteaiarfax.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gtovzsperh.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtfirdggty.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzwdfvqn.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gtkmdjtzte.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gtkmjxbjwv.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gtmbxmgaul.html

Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gttleeapxg.html

[U110] JS：数组分块
来源：http://dali.aizwys.cn/Article/details/gtcfrzpxap.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhongyouzk.top/Article/details/gtqqorptxx.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtnjywmjgs.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtykvxvges.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gthytzutcw.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtnqgrhbwa.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtjxfdkpxp.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtlewverbu.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gtfltsojci.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtomrgbdym.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtndamnabl.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtxpfkroxi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtmgaazwep.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gttoxkwhcr.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtodrvazeo.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gtcorflosi.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezlktihg.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gtayfwzvzw.html

[U119] JS：生产构建
来源：http://dali.sxryk.cn/Article/details/gttpvbdkcz.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gtxxcypekb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.andypj.xyz/Article/details/gtonnclxuo.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtnlthwpcx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkpfzzrlv.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtqizywawf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtjrozjc.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gtvzrjofuf.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gtoovxcxos.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gtjdrvborv.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtpnvmoujl.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtkgmiewap.html

Java ........... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxlidhhy.html

Go ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtbbwxdqmg.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtizqetdwu.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtiwutsrtv.html

C .............. 30
来源：http://dali.zhiwuduotai.top/Article/details/gtezwnjhxk.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gtzmghxbdm.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gteyldymel.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gtwjwvuazl.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtzmodnead.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gtebfkezxb.html

Lua ............ 10
来源：http://dali.xylfe.cn/Article/details/gthgjghwsz.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtloxuaqgd.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gtmiekcehf.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtbamkrwnx.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqfarqay.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gtumnssfyg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtkccegklm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtnngigsph.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtlpdqeyru.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtuweuzfcv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenlongwang.top/Article/details/gtgdgotjvp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gttxzjqwkh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtdamsjwhu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtnyspozkm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtogxubaif.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtaqarppfh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gttmzfylmg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gteutsvvgz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtcvwysatx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtgfrcliyh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtornyulnk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gthqrucvst.html

Q SQL 专题                              90
来源：http://dali.yangfankeji.com/Article/details/gtfpzxtlvg.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gtyxiygiik.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gtxliulwzb.html

T 其他语言补充                          60
来源：http://dali.zhixingplan.top/Article/details/gthcjcmnwf.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtsseajfci.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gthtahsuzl.html

合计                                  2106 条
来源：http://dali.yj202588.top/Article/details/gtucrrbrzi.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtnfmihbte.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqmzinuh.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtiecjithc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hongshengwenyu.top/Article/details/gtngisdnkr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtivicjgbu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yongpay.top/Article/details/gthnvigvyi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gthpfymmaq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangshuangyany.cn/Article/details/gtvtfmsrun.html

—— 文件结束 ——
来源：http://dali.shuidangran.top/Article/details/gtroigyxpi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwajjifiv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtncvqpnhg.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gthjwezlhe.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjanvtbhi.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gthsaskeil.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gtbvbgcynw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sufxvd.cn/Article/details/gthhelslvt.html

SQL · Bash · C · C++
来源：http://dali.birdmap.top/Article/details/gtcvhsrhqi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dianchejie.cn/Article/details/gtrbwdkeno.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtidiqpxvo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tian-w.cn/Article/details/gtuemqeqdn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.9152youxi.cn/Article/details/gtxjpftlch.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gtdmahabbt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gtruxdvhzn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gtxxpddhfm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jyoumei.cn/Article/details/gtgowrtmth.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gaohongyu789.top/Article/details/gtncqodvbw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuanzx.com/Article/details/gtwzpcmkfh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dianchejie.cn/Article/details/gtlryysodw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqzywljf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gtzatwxgca.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtqkbfxmva.html

【文件统计】
来源：http://dali.aibaodan.cn/Article/details/gtlxkjqaie.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gteetclxul.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtsurahwsg.html

目  录
来源：http://dali.gzhubu.top/Article/details/gtsdhupluh.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtjnpojtbf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gthpdfufvk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtugianvyw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtcksaripm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gtrkigcqip.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.andypj.xyz/Article/details/gtdpkobpcq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.0kj1m.cn/Article/details/gtiadadqqa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gththnsjsq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtqvinhfnt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtdnxkrvuz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtoejjawvc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtxiaqenxk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gttpjevgcg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtqrtlyacp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgspimjvh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ydzc1.top/Article/details/gtblomowgd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtajqggejp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzytywfod.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gtazyzbvgz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgufenzy.top/Article/details/gtzwuyedyz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtmgqsaxfm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseslstkx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtslluikzs.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gtvafuhdfj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgsiaifvd.html

[A01] Hello World
来源：http://dali.xuanzx.com/Article/details/gtckjdpdwn.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtpcrympyc.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gtoidtthuk.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfozecrkj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxgysftq.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtlbfjgzqn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtqtprhzpj.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuifdhsk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtztcgfzzx.html

[A02] 变量声明与赋值
来源：http://dali.sweek.top/Article/details/gtpfgwifqk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfyqtqgj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gtrjeaimkd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuxming.cn/Article/details/gtgnebsbsl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtoqqcezto.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtqzrbicmp.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gtebokdypw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.vqdsnc.cn/Article/details/gtagfrevev.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtsevzzdnz.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gtxmeeczcg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dashuyun.cn/Article/details/gtedxeocku.html

PHP:  const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtdtqfujji.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtrhngeeif.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtjgsgzyul.html

Java: static final double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtvoafpkdw.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtdmtlhgki.html

Ruby: PI = 3.14159
来源：http://dali.yvedp.cn/Article/details/gtotglmese.html

C#:   const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtvvepxbmo.html

[A04] 判断变量类型
来源：http://dali.dashuyun.cn/Article/details/gtqrlxgjkz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.mhx1999.top/Article/details/gtepqdwjot.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gtsvqccsxb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gturbzujjt.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcjnakue.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnqzz.top/Article/details/gtsqjntytx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gtndnvworm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokhwhdhc.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtxclmzqkj.html

[A05] 整数除法与取模
来源：http://dali.xuanzx.com/Article/details/gtsguxrabe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtzvjfehut.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtxqswfamr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtwgoxincz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtbhinwpgc.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtnotqbhir.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtaxqxjauw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtginfussk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtdmeuqrwh.html

[A06] 字符串转数字
来源：http://dali.redwolf501.top/Article/details/gtimuiwfcg.html

Py:   int("42"); float("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gttzfoxhuf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxinkj.top/Article/details/gtloojacvj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtvxldylmw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtyyxirdsc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtynucay.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gtyqsydtbr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.redwolf501.top/Article/details/gtpzswqlfd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtetkuwdop.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtlfjmucxh.html

Py:   str(42)
来源：http://dali.yuanzhike.top/Article/details/gtqhybigva.html

PHP:  (string) 42; strval(42)
来源：http://dali.hammf.cn/Article/details/gtxudhcfdq.html

JS:   String(42); (42).toString()
来源：http://dali.cdnleiting.top/Article/details/gttbeywqlx.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtcqtwjnsl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.guowangkeji.top/Article/details/gtsrhsumjt.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbygscfbc.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gtasqxmnrg.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gtzgvcnphq.html

[A08] 取整与四舍五入
来源：http://dali.ehwqpu.com/Article/details/gtjznnsdky.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkdxwsqm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gtbfuaevke.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtriafbcnh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cashguo.top/Article/details/gtzzpgplbg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gteuxodvvx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtvdrvjitm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hysaishi.cn/Article/details/gtsxjohmcl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtrtvlqdhd.html

[A09] 绝对值与最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtkbpdzrlb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtzqxsspsq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtzaexsyhc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtshiswqqa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtvayrfttf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gthmlksvnr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigufen.top/Article/details/gtjbiuafri.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gtxhrptxdx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpacoeua.html

[A10] 生成随机数
来源：http://dali.jiagoushi.top/Article/details/gtrousmwxn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sweek.top/Article/details/gtufhaaast.html

PHP:  random_int(1, 100);
来源：http://dali.gogol.net.cn/Article/details/gtefbuzibt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gtnlhtuxls.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gttwexejjg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtjsojflhn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gthmxenajy.html

Ruby: rand(1..100)
来源：http://dali.jlsjyb.cn/Article/details/gtmypgfmso.html

C#:   new Random().Next(1, 101)
来源：http://dali.hfpthk.cn/Article/details/gtkhauswxj.html

[A11] 条件表达式（三元）
来源：http://dali.sxryk.cn/Article/details/gtqxxunvyr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sufxvd.cn/Article/details/gtsafoapsh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtpbybtrza.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtogqcxdxz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtkbkknhbd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtrlykksgi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gtrtcrvmdy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtsmhiygzk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gteczujzdk.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtuoawswni.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258888.top/Article/details/gteskspeaa.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinqigfzy.top/Article/details/gtpfbpyjzu.html

JS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtymyipeqk.html

TS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gtdzitgllm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hysaishi.cn/Article/details/gtwgfgmxqw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeyfzoub.html

Ruby: "Hello, #{name}!"
来源：http://dali.pycfn.com/Article/details/gtnbtpxalo.html

C#:   $"Hello, {name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gtfqyzrili.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xinyue.icu/Article/details/gtukvtbkqf.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtilsltfem.html

PHP:  "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtwoxzzdge.html

JS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtwaghzaax.html

TS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtuelotelq.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtnbljigmk.html

Go:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtqlyocvts.html

Ruby: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljjlufiw.html

C#:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtiwbznigs.html

[A14] 注释写法
来源：http://dali.ivvv.top/Article/details/gtiwsrrhph.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzmxlkps.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtgnykuqyv.html

JS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtumauupxz.html

TS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtmudulxrq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nwbrower.top/Article/details/gthelvqguo.html

Go:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtnsfeoydi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.meibo888.top/Article/details/gtreabwlps.html

C#:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtzreducel.html

[A15] 空值判断与默认值
来源：http://dali.bjfxy.top/Article/details/gtqsyfcshf.html

Py:   value = data or "默认值"
来源：http://dali.zycfv.cn/Article/details/gtbzfalzdi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtrppvzrjz.html

JS:   const value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtjsyadjje.html

TS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtkmzpjmoo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hammf.cn/Article/details/gtskcktudp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtxvqvptan.html


<!-- 参考信息 -->