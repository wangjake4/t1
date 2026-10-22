代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gt2ygigmxlv.html

composer require twig/twig
来源：http://dali.cqqwz.cn/Article/details/gt2ylwyzyqx.html

[U78] PHP：单元测试
来源：http://dali.kuanghao11.cn/Article/details/gt2ipmvfllb.html

composer require --dev phpunit/phpunit
来源：http://dali.hnxiangtu.top/Article/details/gt2wvqajizu.html

[U79] PHP：静态分析
来源：http://dali.xuanzx.com/Article/details/gt2kvkpumux.html

composer require --dev phpstan/phpstan
来源：http://dali.cashguo.top/Article/details/gt2oforgvcz.html

[U80] PHP：代码规范修复
来源：http://dali.gogol.net.cn/Article/details/gt2lqchmyeu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gt2blxhgzmu.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2vlrvawas.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gt2egvmvhvq.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gt2nomvrdzt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangdashe.top/Article/details/gt2lnkooxry.html

[U83] JS：ES Module 导入导出
来源：http://dali.shangyingyoupin.top/Article/details/gt2syoquokh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztwspyat.html

[U84] JS：CommonJS 写法
来源：http://dali.iojbl.cn/Article/details/gt2gpemxojx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gt2msoqytbl.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gt2fktkpsjm.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gt2uhvnohjz.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gt2wwrlancc.html

a ?? b
来源：http://dali.gogol.net.cn/Article/details/gt2ghngkops.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gt2kltqqokq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gt2lxjchhqy.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gt2qgmtbtgb.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gt2hqunjwjz.html

[U89] JS：数组去重
来源：http://dali.sysykeji.top/Article/details/gt2tvzrbgtm.html

[...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2ygkwwyxt.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gt2vddwsupf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2swsqidit.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gt2krcnjykx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gt2suqehnmm.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2hfqnrltg.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2vkyxsfxi.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gt2jkvhqqtp.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhfjmrog.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2rbqcjmmr.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gt2bfhueqqm.html

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gt2mctjduyn.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gt2enytrfxk.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gt2eckyxzil.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2blkdvqav.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gt2qlcrwdjr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgydmfro.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2ivhlchow.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cdnleiting.top/Article/details/gt2mvcgyzqj.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gt2yvmdwrpn.html

el.addEventListener("click", e => {})
来源：http://dali.chenzaomai.com/Article/details/gt2sbzshxvy.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpbvgstz.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gt2ncwslint.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2esjuhazk.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gt2prhxiqny.html

[U102] JS：本地存储
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmsupgbw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gt2lkwhozfm.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gt2quipbxtd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nixzfxvt.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gt2rbmxckaa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2fklxjpuj.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gt2bznqpfje.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyntiauw.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtfxecyt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gt2exhpedal.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2lxkprlbb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2fqapjbre.html

[U108] JS：随机整数
来源：http://dali.daxiang520.top/Article/details/gt2mezqwicu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gt2fosvltfz.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irojotep.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gt2suvpmiwr.html

[U110] JS：数组分块
来源：http://dali.smart0.xyz/Article/details/gt2umryqebt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gt2xuybttew.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gt2iwfzdfqz.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gt2wzheiwxk.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gt2rfdodnhk.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gt2qfkxsato.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gt2javbmfnu.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2vlvuhzkq.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gt2pojrltey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2yeuhhcwq.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2eewskejx.html

crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2gvsbplvo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gt2tvuwndcp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gt2cwcghmtd.html

[U117] JS：单元测试
来源：http://dali.guowangkeji.top/Article/details/gt2iodkfiyj.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2pmgamyxc.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gt2wypiqdrp.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdqeezsz.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gt2tejrlisc.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gt2uwpchhgw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj202588.top/Article/details/gt2csfimgil.html

import.meta.env.VITE_API_URL
来源：http://dali.dashuyun.cn/Article/details/gt2gvpsiqpb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ephoulhb.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gt2qfqnzpvj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nkuunrbi.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gt2georhvep.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2rjknhhwe.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gt2sjiagvos.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gt2otctvbxh.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gt2qudegrss.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gt2aikcpamc.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gt2kacbzrqj.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gt2uqriqlxe.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gt2lcbhiwss.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gt2rcppejqz.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2vksgthht.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gt2iobdgftw.html

Bash ........... 80
来源：http://dali.snrcjt.cn/Article/details/gt2srrlhqvx.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gt2lrddofku.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gt2tchjvqfd.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2iailfvfu.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gt2jixxjkld.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gt2hyustcpz.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgzgvwlb.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gt2ehuyyvff.html

按章节统计：
来源：http://dali.haohaochexian.top/Article/details/gt2qspbmjlu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.kuanghao11.cn/Article/details/gt2lawirugs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhzlwvcy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gt2dnryqwun.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqkavogn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.snrcjt.cn/Article/details/gt2bxxxiouc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gt2eoexqlai.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gt2ndtkbahk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpsdarkq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2yqczzbqm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gt2agneendr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2kpjizhsx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2ivjmqcsi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2xilnivgz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gt2nvcotbdk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gt2uplrdyzi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gt2vzwoaaqz.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gt2iyrhemmj.html

R Bash 专题                             80
来源：http://dali.zycfv.cn/Article/details/gt2pdhuybvg.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gt2oeqgjcyz.html

T 其他语言补充                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2wrvytgnc.html

U 高频实用片段                         120
来源：http://dali.tianlin.xyz/Article/details/gt2bkyctyxb.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2invvcchv.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gt2ogsizvkb.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2uzodoatq.html

使用提醒
来源：http://dali.c1oappe.top/Article/details/gt2ahybmnil.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2ipvkiiuf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehcletbx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gt2iuuoxaiv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gt2qbcmgggm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gt2bmoxnwtz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gt2auqrigvj.html

—— 文件结束 ——
来源：http://dali.vqdsnc.cn/Article/details/gt2dagoupyh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2amaurjbn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gaohongyu789.top/Article/details/gt2efikolic.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gt2gddrbdeu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2kilfcdeb.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gt2mrdulktn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gt2blhjfukg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gt2yzzfczll.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gt2rtkrwgtv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gt2wkgsxwmu.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gt2wdwzryle.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gt2iemxwtsh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gt2ryittnoj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shuidangran.top/Article/details/gt2zbesqlzx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhixingplan.top/Article/details/gt2ogyzejpl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sufxvd.cn/Article/details/gt2uymrheuo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvyojrq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.bjfxy.top/Article/details/gt2qrfnaxdv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnxiangtu.top/Article/details/gt2rpefpapc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gt2sdowhsjg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2itevdlfq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgufenzy.top/Article/details/gt2jmeswwdu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gt2fwyrqdle.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gt2tekerjrg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sufxvd.cn/Article/details/gt2yleoqelq.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2glrskccl.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gt2vzfpixio.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2rtszuaap.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hddeohuh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gt2cjhoqjks.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gt2spvkcyme.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2dwlhbrmp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gt2qytdlqtg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gt2zxzpjpay.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gt2wkforguq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2znepfueb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2ffnvmlod.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gt2vxfvlpel.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2nojvfvgh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2ulygwxon.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqeqbdib.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gt2fhioxkbc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.andypj.xyz/Article/details/gt2wilyrvpu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gt2zgnadoxt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hywenlv.cn/Article/details/gt2pbygtgld.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258.top/Article/details/gt2uusmoxvq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.redwolf501.top/Article/details/gt2bwxpkcho.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gt2ryfvcykg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbtkglrk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2vkokpsdz.html

A. 基础语法与类型
来源：http://dali.cqqwz.cn/Article/details/gt2kitrxxoi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzbafmrs.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gt2hbjtqjau.html

Py:   print("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gt2mgdyjgmj.html

PHP:  echo "Hello, World!";
来源：http://dali.jianghu66.top/Article/details/gt2tvvjskzq.html

JS:   console.log("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gt2inkwgnrd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gt2txqdairu.html

Java: System.out.println("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gt2cgnkkjtf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2yjvbyfuq.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gt2aymkgppp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2egsjonvh.html

[A02] 变量声明与赋值
来源：http://dali.hywenlv.cn/Article/details/gt2zjrihjwe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.svipenyu.cn/Article/details/gt2xnuvxzhu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2petgovko.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2ncafhijs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fzhhl.top/Article/details/gt2eynkycpj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gt2rvbnbjhl.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gt2nfgiuwgg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangdashe.top/Article/details/gt2lqbpnyoc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2cstetddw.html

[A03] 常量定义
来源：http://dali.yj202588.top/Article/details/gt2eejbbtlz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.9152youxi.cn/Article/details/gt2pzcszjps.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2uiztfbzk.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pusuamzf.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2jshuyyfl.html

Java: static final double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2iqrslamj.html

Go:   const PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gt2jfofihvn.html

Ruby: PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmgngocy.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2dkcbprjc.html

[A04] 判断变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2pwazursr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gt2wndaoamg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gt2klffcjfz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2edogfure.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gt2ddxohbls.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gt2haolpwll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekwlkgbt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hammf.cn/Article/details/gt2qwelxvdg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gt2aknpikpe.html

[A05] 整数除法与取模
来源：http://dali.jqgufenzy.top/Article/details/gt2ogeqwjoc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnxiangtu.top/Article/details/gt2nnieyhse.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2mxvubkym.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2avspcbvz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2snmtzfez.html

Java: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdrvumro.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2ylqwyqco.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2edrzzlmb.html

C#:   7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2rxlcydkc.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gt2ytvikuza.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gt2pgtwmhlx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gt2attsxito.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.havefunace.top/Article/details/gt2kxbtnsli.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gt2yeeddnpr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daxiang520.top/Article/details/gt2azedvacp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gt2ycijzsdu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gt2jepyavvk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljkwipvv.html

[A07] 数字转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2mcbftgkx.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwyqfkh.html

PHP:  (string) 42; strval(42)
来源：http://dali.hysaishi.cn/Article/details/gt2yrgdmvmh.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gt2hvjyrthx.html

TS:   String(42)
来源：http://dali.nanxinkj.top/Article/details/gt2gjyxffrg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.c1oappe.top/Article/details/gt2rsjougaz.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gt2abrchrdt.html

Ruby: 42.to_s
来源：http://dali.guowangkeji.top/Article/details/gt2riujotfq.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gt2ymcruqcq.html

[A08] 取整与四舍五入
来源：http://dali.sysykeji.top/Article/details/gt2kynmfbsp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2rmvgokbz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.kuanghao11.cn/Article/details/gt2wjqoqkae.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gt2zrsepzet.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izpuvhsb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2xxhbbspi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpajolrs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gt2uinvqnoy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2ifluhrwd.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2hsuszyco.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2srwdyeom.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2ffdsnpuj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2yqciedan.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2aabvlrea.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ilxfvgqu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjtudtag.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.daria6918.cn/Article/details/gt2fhoifkhm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2aaeoolhd.html

[A10] 生成随机数
来源：http://dali.sufxvd.cn/Article/details/gt2eamqrehn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptdfrlaj.html

PHP:  random_int(1, 100);
来源：http://dali.ybcxt.top/Article/details/gt2brtaaalh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gt2ajvgocaf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2izsjsome.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2bunckzxm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dashuyun.cn/Article/details/gt2zmtbskwz.html

Ruby: rand(1..100)
来源：http://dali.chenzaomai.com/Article/details/gt2bggdhkon.html

C#:   new Random().Next(1, 101)
来源：http://dali.xziqi.cn/Article/details/gt2kkmqgnbq.html

[A11] 条件表达式（三元）
来源：http://dali.yueranfly.top/Article/details/gt2vqsetade.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.meibo888.top/Article/details/gt2miqpgijx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gt2eagopjzq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gt2kumcijrz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybrxecpl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gt2bvvdwyfb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigfzy.top/Article/details/gt2bgxumocf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2mrhirhup.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2zhzohaui.html

[A12] 字符串插值 / 格式化
来源：http://dali.jiagoushi.top/Article/details/gt2nkokzriq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxinkj.top/Article/details/gt2nidnwvzy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xylfe.cn/Article/details/gt2jnsmzhcc.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exuyqeel.html

TS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gt2qwhgocfw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daxiang520.top/Article/details/gt2fmsntcve.html


<!-- 参考信息 -->