代发 wailian999

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gt2ffofqjls.html

a?.b?.c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzmhvzgu.html

[U86] JS：空值合并
来源：http://dali.gzhubu.top/Article/details/gt2qhqjzccw.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gt2ignufiiz.html

[U87] JS：解构默认值
来源：http://dali.daxiang520.top/Article/details/gt2ioubgesr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gogol.net.cn/Article/details/gt2hhrcljwj.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2gfbdbbkc.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gt2qwoybdob.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gt2gprzcdal.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2yxonceap.html

[U90] JS：数字数组排序
来源：http://dali.fengsongda.top/Article/details/gt2yxcdkfpw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xekicjlp.html

[U91] JS：对象键值遍历
来源：http://dali.zhengqikj.top/Article/details/gt2bwfperxx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gt2qfjznflg.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gt2uszxdgan.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2fulpzrdk.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ddrfahsb.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gt2cahhlkrt.html

[U94] JS：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkpmfdpe.html

const double = x => x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gt2rogbrmvy.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gt2yhkxlemu.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gt2nmabxmzw.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2dlwzbcjs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2rkmisoti.html

[U97] JS：并发请求
来源：http://dali.fengsongda.top/Article/details/gt2kosxdyij.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2youuljbx.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2yxejtocl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2kkbfwmhf.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gt2auduveha.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gt2qwsoiquz.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gt2cswpncur.html

document.querySelector(".item")
来源：http://dali.yueranfly.top/Article/details/gt2thzlrbat.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gt2mmwidpkd.html

el.classList.toggle("active")
来源：http://dali.cashguo.top/Article/details/gt2ltzveaie.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fllpuntz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gt2ugnzqpjd.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raieyovb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gt2wuwfnxyk.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gt2yuvuqaef.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2lypcudjv.html

[U105] JS：节流
来源：http://dali.0kj1m.cn/Article/details/gt2tdzxcmvi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpurcenr.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gt2bwctqefh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehotwcee.html

[U107] JS：数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2qymybftz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2ujdwallz.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gt2vjesdaoj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gotoacloud.top/Article/details/gt2jmhaixoy.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gt2xangytha.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gt2eukoevwh.html

[U110] JS：数组分块
来源：http://dali.xuanzx.com/Article/details/gt2fmkqfxhd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfvwpatw.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2axktzvzt.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2lhasjtxf.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gt2jcjgtbvl.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2bvdtwrkx.html

[U113] JS：正则替换全部
来源：http://dali.xinyue.icu/Article/details/gt2jyfhfakr.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2vujpohik.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2visaeryr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2yjaenrus.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gt2djsgukpu.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2anotsfqx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhtbrygv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2uwqbibrl.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2dhawglkk.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emzjadih.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gt2ugrxxkim.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gt2nilkjvhq.html

[U119] JS：生产构建
来源：http://dali.sweek.top/Article/details/gt2ytwasama.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gt2vvtifudd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sxryk.cn/Article/details/gt2svlysyrk.html

import.meta.env.VITE_API_URL
来源：http://dali.chenzaomai.com/Article/details/gt2pfdmjwck.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bpbovspv.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gt2eiumwfes.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ndsdeccc.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gt2tvcgzjnw.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pnafnfvm.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhojqees.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gt2zbzakclx.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gt2xwgulcvi.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2niybbkxh.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqubqvkr.html

Ruby ........... 212
来源：http://dali.hnqzz.top/Article/details/gt2gdqvuzvs.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gt2olvcsukl.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebwblwwa.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbpwmvjg.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gt2jqnebalz.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gt2heyozntp.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wewmplfd.html

Swift .......... 15
来源：http://dali.jlsjyb.cn/Article/details/gt2efzxnfrj.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gt2reknphir.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibzvjhbd.html

Scala .......... 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkprihyo.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulbxdqjv.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2agcuefai.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gt2taxmyjao.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.haohaochexian.top/Article/details/gt2vkjdhuqx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqkyfrxw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2nvvtsuax.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gt2rusdpkci.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gt2invsvqir.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gt2zzgbdsnk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2nzwqennd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2qtirgklw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2qpodshub.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gt2qyhrqjhl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skvdlmdo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzpekubn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2fjsxfgwh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2onponrtq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dashuyun.cn/Article/details/gt2psdirisn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2qlnvajyz.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gt2smqsrpdu.html

R Bash 专题                             80
来源：http://dali.yj20258888.top/Article/details/gt2ultdrygf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2leqcluox.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gt2fpgnokcb.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gt2slisvbxy.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2thcmkqob.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gt2zubnaqsq.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2zlpuwilw.html

使用提醒
来源：http://dali.9152youxi.cn/Article/details/gt2boxkadvw.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2oedecdlc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gt2rpbtqlwv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kocdgskf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ydzc1.top/Article/details/gt2drkcdqby.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gt2rtlkgkvs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gt2fhlfqvgm.html

—— 文件结束 ——
来源：http://dali.yvedp.cn/Article/details/gt2odmxwlxb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nmyahewf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sysykeji.top/Article/details/gt2publqfzk.html

Common Programming Examples Cheat Book
来源：http://dali.hywenlv.cn/Article/details/gt2neryuzzv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2joiukmre.html

【收录内容】
来源：http://dali.hongshengwenyu.top/Article/details/gt2btmbpvfa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwpujmhw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2teyygmjl.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gt2kvhstczx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xinyue.icu/Article/details/gt2xeaecsxj.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gt2mqdtqmkr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gt2chvddkzw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gt2bgimbtgd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jianghu66.top/Article/details/gt2dydbybnb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gt2enxytyyp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgfzy.top/Article/details/gt2tkggsyjl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gt2jnmxynva.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuanzx.com/Article/details/gt2fphqaadn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2voxmqvhm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gt2ffycivxd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuanzhike.top/Article/details/gt2ucytmdww.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gt2qdlkekva.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jianghu66.top/Article/details/gt2xnvvqxxz.html

【文件统计】
来源：http://dali.ybcxt.top/Article/details/gt2fjjphfld.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gt2nbhcmitn.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2laovfrcc.html

目  录
来源：http://dali.jlsjyb.cn/Article/details/gt2hrzzxyxz.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2vlcjptuh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2aetkuwni.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gt2weuynidc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2gngrspir.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjwmkvai.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cucudq.cn/Article/details/gt2kjdcbdbr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gt2pqvpfvao.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2zdxunnxj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gt2wkjsmwdf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2mefpdaob.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gt2tozszahw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2cyuklakt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2mjywkggj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2tgxbhxem.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gt2esczusse.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ekkcfifz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2tuntwhfe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gt2bjqinzrt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlzcrdvt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epqxqrhu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqlczmku.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gt2foarcyvp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xpzxupek.html

A. 基础语法与类型
来源：http://dali.yonumen.top/Article/details/gt2mqryzbom.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kuhtjyxk.html

[A01] Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2odhimgch.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2vnuwwcqk.html

PHP:  echo "Hello, World!";
来源：http://dali.hysaishi.cn/Article/details/gt2qccmfish.html

JS:   console.log("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gt2ufiwrtzc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gt2esfldeam.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gt2xgrybrqa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gt2pgnfiblj.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iawxkank.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gt2svxnihds.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gt2gqpzffva.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gt2qpwaxyns.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2sfijophy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fzhhl.top/Article/details/gt2xsptqpjj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2tpmjlsdu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2tohgmydx.html

Go:   name := "Alex"; age := 20
来源：http://dali.daria6918.cn/Article/details/gt2ohxsylwa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gt2kjoxljds.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2tkephidc.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gt2qtneydso.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yvedp.cn/Article/details/gt2ujlwpobc.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2bxsmtvib.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2sjmtvrlf.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlgojhql.html

Java: static final double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2eiovhelo.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2ytpmgvlw.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gt2symthxwj.html

C#:   const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2fgsbctpc.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2dslppbce.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gt2exenejtd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gt2aexcazso.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj202588.top/Article/details/gt2wixampwa.html

TS:   typeof x; x instanceof Date
来源：http://dali.dashuyun.cn/Article/details/gt2yfrqemsk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gt2rjwgoohc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gt2qnonvcxt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smoqxdll.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gt2dwnglrhx.html

[A05] 整数除法与取模
来源：http://dali.hnxiangtu.top/Article/details/gt2vnhhldol.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gt2efsgjdmq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gt2dbjqodey.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2cwvfygqq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2fubtbabv.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2jrxugvrn.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyxfqcny.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2mptzkfnt.html

C#:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2mxxkzjod.html

[A06] 字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozurvrrp.html

Py:   int("42"); float("3.14")
来源：http://dali.mhx1999.top/Article/details/gt2xjhyrmwm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gt2jrwfhqrh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuxming.cn/Article/details/gt2dazmfzmo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cucudq.cn/Article/details/gt2byprwufc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cdnleiting.top/Article/details/gt2urwqrndt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zycfv.cn/Article/details/gt2roqslemw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tanke756.top/Article/details/gt2dtmkmlgf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cqqwz.cn/Article/details/gt2xdcpajix.html

[A07] 数字转字符串
来源：http://dali.ydzc1.top/Article/details/gt2dqzwvaeo.html

Py:   str(42)
来源：http://dali.mhx1999.top/Article/details/gt2zmhmvqer.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gt2ffukwrre.html

JS:   String(42); (42).toString()
来源：http://dali.fzhhl.top/Article/details/gt2phmmnlfn.html

TS:   String(42)
来源：http://dali.xziqi.cn/Article/details/gt2lbzuqrln.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gzhubu.top/Article/details/gt2olfzarna.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2idifavew.html

Ruby: 42.to_s
来源：http://dali.zdqjudy.top/Article/details/gt2arfsqzih.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvheuyx.html

[A08] 取整与四舍五入
来源：http://dali.sysykeji.top/Article/details/gt2erghyaor.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gt2drfncoag.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guowangkeji.top/Article/details/gt2ebucqxkd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2gttbwffm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jyoumei.cn/Article/details/gt2wzpzohtn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2ixoslekq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2hchwwphh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gt2jfoowxni.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2lfjaqgyi.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gt2ujxsufys.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2yabpncoj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxftazmf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwkxfkd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2lvzorlsi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2hgppgxsj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.snrcjt.cn/Article/details/gt2udywrgmg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljqrkabu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ludpbijq.html

[A10] 生成随机数
来源：http://dali.haohaochexian.top/Article/details/gt2rrajoyhf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gt2xxzalwkj.html

PHP:  random_int(1, 100);
来源：http://dali.zhongyouzk.top/Article/details/gt2klkxxguj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.iojbl.cn/Article/details/gt2bqwbbtds.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2oxslayye.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xylfe.cn/Article/details/gt2meavjhqg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yongpay.top/Article/details/gt2cgpryolp.html

Ruby: rand(1..100)
来源：http://dali.cheryme.top/Article/details/gt2epvfqqju.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gt2gzxbkhgj.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnibtebc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenzaomai.com/Article/details/gt2ughgjicl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2odkikrzz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2ppbkaluh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2rvdcjylr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2kpyatbgq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ivvv.top/Article/details/gt2laxmpjph.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2cyuoubya.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gt2tgbncyjq.html

[A12] 字符串插值 / 格式化
来源：http://dali.ppjwa.cn/Article/details/gt2vehxqcqf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gaohongyu789.top/Article/details/gt2fbxamgej.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.9152youxi.cn/Article/details/gt2jscvjplw.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uskeojob.html

TS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gt2wvxaddji.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gt2jyzfoqug.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gzhubu.top/Article/details/gt2hrcrhgck.html

Ruby: "Hello, #{name}!"
来源：http://dali.snrcjt.cn/Article/details/gt2ylodrecp.html

C#:   $"Hello, {name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qccdtgtc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xajmrjiv.html

Py:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mooobizm.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oznbbplf.html

JS:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2eprrvcjk.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2wfdeeopc.html

Java: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzussitk.html

Go:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2vfmammnp.html

Ruby: "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpvyenae.html

C#:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2idzottjy.html

[A14] 注释写法
来源：http://dali.tian-w.cn/Article/details/gt2bonlnvuo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgoqjjcd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gt2lpecryui.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2csoctxjx.html


<!-- 参考信息 -->