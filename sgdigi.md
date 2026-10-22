代发 wailian999

[U89] JS：数组去重
来源：http://dali.shzxlz.cn/Article/details/gt2jxwdbflq.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2gljijkno.html

[U90] JS：数字数组排序
来源：http://dali.ydzc1.top/Article/details/gt2nrqduilu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2ayfoxpze.html

[U91] JS：对象键值遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnhvrgax.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gt2kxuonqrn.html

[U92] JS：深拷贝
来源：http://dali.bjfxy.top/Article/details/gt2kcksrfwg.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2srfcvbmq.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gt2gfvwqmlq.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gt2heisnijd.html

[U94] JS：箭头函数
来源：http://dali.cucudq.cn/Article/details/gt2yribucoh.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gt2gkfrcjby.html

[U95] JS：Promise 包装
来源：http://dali.tanke756.top/Article/details/gt2cgycxmzg.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gt2wmnisyje.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gt2maixnccv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2qqfisgrh.html

[U97] JS：并发请求
来源：http://dali.shzxlz.cn/Article/details/gt2uyyikssi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2ogmlvnpd.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2iqpotgut.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gt2ygrgfuie.html

[U99] JS：事件监听
来源：http://dali.nwbrower.top/Article/details/gt2nwbktbwo.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gt2bsflnxje.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gt2eglgvzmj.html

document.querySelector(".item")
来源：http://dali.ehwqpu.com/Article/details/gt2znplylxh.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gt2nnlblexi.html

el.classList.toggle("active")
来源：http://dali.cashguo.top/Article/details/gt2pgptpumn.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjblelqb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.smart0.xyz/Article/details/gt2czwkoffg.html

[U103] JS：定时器
来源：http://dali.yueranfly.top/Article/details/gt2adwbtdug.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gt2ytkuieos.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytpbrjin.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2anxqsrrg.html

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gt2ylmtxlou.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gt2gaydcguy.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2jgomhujn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajwmuxaj.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gt2hxjjtoql.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2ppaefopd.html

[U108] JS：随机整数
来源：http://dali.quarkkingdee.top/Article/details/gt2ezaubtvb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2selulack.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gt2bslcwppi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2yzynuprx.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gt2zsxsoatn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.haohaochexian.top/Article/details/gt2zkirzjvi.html

[U111] JS：对象转 Map
来源：http://dali.yuanzhike.top/Article/details/gt2uimhzoen.html

new Map(Object.entries(obj))
来源：http://dali.fengsongda.top/Article/details/gt2varkaofo.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gt2qtxyxkvj.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2xvexignl.html

[U113] JS：正则替换全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdavbkzb.html

s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2uegjzalx.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigufen.top/Article/details/gt2mzbzgvwm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2zkscrfpn.html

[U115] JS：生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2wpgvubil.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2otijmldu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gt2reedvgkm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gt2mjcqvecg.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gt2cpkgsybz.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gt2mcbinszy.html

[U118] JS：开发服务器
来源：http://dali.andypj.xyz/Article/details/gt2begwzgyl.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gt2ipblgioi.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gt2xfxtexex.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gt2ksvztgwg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gt2gsssdjms.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gt2zltfhlxz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2knuzatnj.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gt2kpjraweg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2hlswotja.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gt2qdhzkors.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2datbrfqe.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gt2ejorecaq.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gt2lnwvhlgc.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gt2svyyhcds.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gt2qvdmhpbn.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xojlmznm.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gt2gomebfck.html

C# ............. 212
来源：http://dali.redwolf501.top/Article/details/gt2bmrslcxz.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gt2zhqwqley.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gt2nyizeuqb.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gt2hevpyqtp.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2nnugtcox.html

Kotlin ......... 15
来源：http://dali.snrcjt.cn/Article/details/gt2dzhujbpm.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gt2ayefzmvu.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gt2owxdxmwg.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oieyqvhp.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gt2cmdyidyq.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2mtvduoof.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lshgwxpo.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gt2aczubdxc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gt2shmvyoyq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gt2nbekolxm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gt2letsjgnk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gt2mvfpougs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sysykeji.top/Article/details/gt2liunfsjr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gt2jgxjczjd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2mvyrbexf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2tnboveky.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gt2irmuqyke.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2cdzcgohi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2msdgfawh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvksforh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2cmzmxurv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gt2vbgwyzzi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gt2vunxtymn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjjnbdic.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2nphiaamm.html

R Bash 专题                             80
来源：http://dali.daxiang520.top/Article/details/gt2fsuwcknv.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcxjtlfr.html

T 其他语言补充                          60
来源：http://dali.cdnleiting.top/Article/details/gt2vcnwthhv.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gt2ojpcqivp.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2aplaqvks.html

合计                                  2106 条
来源：http://dali.yonumen.top/Article/details/gt2defezvuw.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyumssli.html

使用提醒
来源：http://dali.0kj1m.cn/Article/details/gt2gzqomoqj.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2npvjzsqb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shzxlz.cn/Article/details/gt2osovnfhk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gt2uezudljn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenjidiqi.icu/Article/details/gt2icawmfnk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.redwolf501.top/Article/details/gt2vmqrmksd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpmscyie.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gt2tedbybcg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ymmffftq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuanzhike.top/Article/details/gt2xwlnnfzx.html

Common Programming Examples Cheat Book
来源：http://dali.yonumen.top/Article/details/gt2jzjzelnu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceipdjoi.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gt2xpdjjsej.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gzhubu.top/Article/details/gt2hzjbidil.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gt2roolzmmk.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gt2rfosexeu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zdqjudy.top/Article/details/gt2arcxdrjs.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gt2tnfmidwa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oofcihsx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gt2mjwbpakl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwldyxgf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkhvklvm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gt2fzmpgvpq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gt2kbahalzz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.quarkkingdee.top/Article/details/gt2xeljceyd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppldxdkz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258888.top/Article/details/gt2rowhjlni.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.316326.xyz/Article/details/gt2prnwjdlc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fzhhl.top/Article/details/gt2bxkwagio.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenjidiqi.icu/Article/details/gt2gybzfdtq.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gt2mkcwkyai.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.kuanghao11.cn/Article/details/gt2wqcweqiq.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2kbemiojf.html

目  录
来源：http://dali.tanke756.top/Article/details/gt2qptzlbrp.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2tzuroups.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gt2dugpmjem.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2ibglfwzo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gt2awgawwxw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2briisdkb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gt2jgqyghia.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yangfankeji.com/Article/details/gt2oxpzbaqm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqrhkiyw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gt2gqdfnmbl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2ydthlwym.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2hyfyvefp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2mjxiufts.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2zujihhqc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2kyhlxqnq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdabdpds.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gt2fdlqjwbu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2csyghtpo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ybcxt.top/Article/details/gt2oulxtbbr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2erfrpgys.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangdashe.top/Article/details/gt2jhszfflw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2swyakrcz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2kvhtpfht.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nmuxjijp.html

A. 基础语法与类型
来源：http://dali.ehwqpu.com/Article/details/gt2ggszondl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lyigtdty.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gt2lgjeovgq.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2vpvjcklt.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gt2tumtjszb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2yviemtzq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhoulong.xyz/Article/details/gt2ekltnytq.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2titedaeg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gt2ypzwqbjs.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258.top/Article/details/gt2gabizmto.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2gightsfb.html

[A02] 变量声明与赋值
来源：http://dali.ehwqpu.com/Article/details/gt2hdxujzbq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xylfe.cn/Article/details/gt2budbltcp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gt2nkwxeqhf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2myzyttqf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yonumen.top/Article/details/gt2mhsggpyr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2bwutybqz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gt2mmatncig.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gzhubu.top/Article/details/gt2tcjwliil.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2qxbukbop.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gt2elcllzzn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.pycfn.com/Article/details/gt2piksbbuc.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2okwfnapk.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2glacmsge.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2oungzvsp.html

Java: static final double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2upkbynbu.html

Go:   const PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gt2kuqiczoz.html

Ruby: PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gt2zjwoviqb.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2sqadxwpd.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2rqbkceeb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gt2qyzsioxk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.vqdsnc.cn/Article/details/gt2oauekdoc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gt2mxdzugqm.html

TS:   typeof x; x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gt2yytloejz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwefopjw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gt2hswkpbuv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.316326.xyz/Article/details/gt2aekaflot.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gt2enbbzikv.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gt2eiyxytii.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nwbrower.top/Article/details/gt2nlndabli.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2eafyjpmy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2wmbpmfjj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2lqshtwpn.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2xnwowsny.html

Go:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2nendeskd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2ifgxjfhm.html

C#:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2zvsynmlq.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2vymwwhts.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mynkdsjn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gt2pvdnymsq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gt2cximwygx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nwbrower.top/Article/details/gt2zakiaalv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gt2jnvvxcpk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gt2ireritgm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrusgnko.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gt2rbqbrtbz.html

[A07] 数字转字符串
来源：http://dali.jqgfzy.top/Article/details/gt2igicmgld.html

Py:   str(42)
来源：http://dali.vqdsnc.cn/Article/details/gt2addwixuw.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuxming.cn/Article/details/gt2uwnmaffh.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2nrkolino.html

TS:   String(42)
来源：http://dali.guowangkeji.top/Article/details/gt2zggfgngx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258888.top/Article/details/gt2boxgywus.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxinkj.top/Article/details/gt2gvfqiwtu.html

Ruby: 42.to_s
来源：http://dali.xuetiantiany.cn/Article/details/gt2tabowqoz.html

C#:   42.ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2kvjfaenh.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gt2hvefavgq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2zqjtqczs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jqgfzy.top/Article/details/gt2qscfeomh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnnopfry.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlkpzunp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxrigje.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2vsyxfubc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daria6918.cn/Article/details/gt2pnsgrjbp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvfltvyo.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2rcclyvla.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2hwockccq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ejolxpea.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hammf.cn/Article/details/gt2lloyecfo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2lqrezvrf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hotlrpwd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.haohaochexian.top/Article/details/gt2nwckymrp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gt2smajxkhq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2fdorpaop.html

[A10] 生成随机数
来源：http://dali.iojbl.cn/Article/details/gt2oyqqogke.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gt2gvatywgq.html

PHP:  random_int(1, 100);
来源：http://dali.yj20258.top/Article/details/gt2jfpqghkj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gt2okfdaadq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcxngane.html

Java: new Random().nextInt(100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gt2xvrvljiy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gt2lspflkjt.html

Ruby: rand(1..100)
来源：http://dali.meibo888.top/Article/details/gt2ftkmivkv.html

C#:   new Random().Next(1, 101)
来源：http://dali.guowangkeji.top/Article/details/gt2krfwtacx.html

[A11] 条件表达式（三元）
来源：http://dali.hywenlv.cn/Article/details/gt2himvsqvl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.316326.xyz/Article/details/gt2bxcacwpb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2relyirfn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2ylxcaznv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gt2fqdhgmgy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2cpsdpzkt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gt2ppyklnld.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gt2nyaswyns.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjfxajnk.html

[A12] 字符串插值 / 格式化
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmeyotmt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuanzx.com/Article/details/gt2iejcmcvn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gt2wvkexkgk.html

JS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gt2fwqhlxgw.html

TS:   `Hello, ${name}!`
来源：http://dali.zdqjudy.top/Article/details/gt2cexfujde.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.havefunace.top/Article/details/gt2sicqxsyk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdjnoaat.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhoulong.xyz/Article/details/gt2uafefmzf.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gt2okohbayc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gt2wgfyqmzv.html

Py:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2adcvkfsa.html

PHP:  "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gt2hfyhebog.html

JS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2uecfkvzc.html

TS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2cjkrdusi.html

Java: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2cgmywojt.html

Go:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2gtrknnwd.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2hcgtrbfc.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2brqmaixr.html

[A14] 注释写法
来源：http://dali.kuanghao11.cn/Article/details/gt2xbpudird.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yuxming.cn/Article/details/gt2hiklgvch.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2gogzdfak.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvahoeny.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2cgpuaole.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sweek.top/Article/details/gt2pkxhnxmw.html

Go:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clmxhfsp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fengsongda.top/Article/details/gt2rlkfxtfp.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2bquzjgrb.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2vadhveae.html

Py:   value = data or "默认值"
来源：http://dali.yj202588.top/Article/details/gt2pdovwnqd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2mnxleugl.html


<!-- 参考信息 -->