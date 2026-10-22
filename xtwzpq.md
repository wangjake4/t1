代发 wailian999

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gt2initvbje.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gt2snzyhcoi.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gt2tixlpwfn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cdnleiting.top/Article/details/gt2opnsfjwm.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gt2qdjjudbb.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gt2swqihdzm.html

[U82] JS：package.json 脚本
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fcyvyimv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcgwrcvk.html

[U83] JS：ES Module 导入导出
来源：http://dali.shuidangran.top/Article/details/gt2ggyqkkkg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2razosimf.html

[U84] JS：CommonJS 写法
来源：http://dali.wangdashe.top/Article/details/gt2ggphsoue.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyraleoh.html

[U85] JS：可选链
来源：http://dali.tian-w.cn/Article/details/gt2jvbfodop.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayyurvhv.html

[U86] JS：空值合并
来源：http://dali.yueranfly.top/Article/details/gt2yktmfbnp.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2bxvgqmsj.html

[U87] JS：解构默认值
来源：http://dali.iojbl.cn/Article/details/gt2dmavgucy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gt2pxzhmyvb.html

[U88] JS：对象展开合并
来源：http://dali.jlsjyb.cn/Article/details/gt2zpllgrwf.html

{ ...a, ...b }
来源：http://dali.gogol.net.cn/Article/details/gt2axtomsaj.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gt2xplltzno.html

[...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2zeveeilo.html

[U90] JS：数字数组排序
来源：http://dali.gaohongyu789.top/Article/details/gt2kstehkix.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2glfwazth.html

[U91] JS：对象键值遍历
来源：http://dali.nanxinkj.top/Article/details/gt2jmekslqb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gt2jvkjnxpt.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gt2qamwuasy.html

structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdjldcpz.html

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gt2fiwsoxtj.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gt2xkknuklq.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gt2yxakpgze.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gt2mezdncju.html

[U95] JS：Promise 包装
来源：http://dali.hnqzz.top/Article/details/gt2smfnevuc.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhbpwtvy.html

[U96] JS：async/await 与异常
来源：http://dali.yangfankeji.com/Article/details/gt2zwsfulth.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2rkhvxyua.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gt2hdxrfjdv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gt2uinpvodj.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbjgyqtc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gt2obotsukp.html

[U99] JS：事件监听
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvutdtoh.html

el.addEventListener("click", e => {})
来源：http://dali.c1oappe.top/Article/details/gt2ovgndhcf.html

[U100] JS：DOM 查询
来源：http://dali.jiagoushi.top/Article/details/gt2rubcsdnm.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gt2aezuwntq.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gt2mxzadjwv.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gt2blygyffo.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gt2szmxuiya.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gt2ispwgxfj.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gt2senumaqp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gt2gwmnnvoh.html

[U104] JS：防抖
来源：http://dali.jianghu66.top/Article/details/gt2oczcnlco.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2doofjsnt.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gt2xpadwhiw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gt2ahvzumfx.html

[U106] JS：日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyyrrelm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gt2tircxrdh.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gt2koyqxakr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2srvqlpiq.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gt2jalqtjlj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.andypj.xyz/Article/details/gt2lqkvdhrh.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gt2iplqngpe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2rjsiivss.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jheugnnc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gt2zudnhyky.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gt2xdceufss.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gt2vvggezru.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gt2txmxmfbt.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2qkyswaom.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gt2rtochqpw.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2lbjztfbd.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2uijjextu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2ywhnvhti.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzteiyao.html

crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2nnlgpkel.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sxryk.cn/Article/details/gt2fjvepzsl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gt2ydqyzluh.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncdlnnrr.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gt2vcraapxk.html

[U118] JS：开发服务器
来源：http://dali.zdqjudy.top/Article/details/gt2amxdhhiu.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gt2deqdnqkm.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gt2zolcjeot.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gt2ssdiusdb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dashuyun.cn/Article/details/gt2tplcdcqu.html

import.meta.env.VITE_API_URL
来源：http://dali.andypj.xyz/Article/details/gt2joreahcx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2iyrxepsy.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gt2tylcfzup.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2jkuaajiq.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gt2eomformd.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gt2lfppjurv.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gt2jbctxggt.html

JavaScript ..... 252
来源：http://dali.cashguo.top/Article/details/gt2tkofdmep.html

TypeScript ..... 212
来源：http://dali.hammf.cn/Article/details/gt2vkqaebnz.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gt2vabkksgb.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gt2tgwersvl.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2aoncvpek.html

C# ............. 212
来源：http://dali.daria6918.cn/Article/details/gt2wmibruwg.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gt2sztccomi.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gt2zdgqxhpi.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2cedcqujn.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwpnsogo.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gt2evfrwnce.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gt2susrurde.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gt2cdncqnfy.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gt2ekvealsr.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2mcwtzjpa.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjzchbvj.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juutjuut.html

按章节统计：
来源：http://dali.shzxlz.cn/Article/details/gt2riatxrms.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2oneuxpyy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gt2ktimkexz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gt2fqopypdi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gt2ujrnryvr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gt2couikqdd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2qiypebso.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2awcsrbpd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gt2hmzpntcf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2mhyqgtwh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gt2dyfemhno.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2cuisegut.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2fudkrjxh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2loisyytf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gt2ducuejsa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gt2kvfazloh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2eryffkeu.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gt2vpckspnp.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gt2lzscxmlc.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2pmtmncwi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rprliveu.html

U 高频实用片段                         120
来源：http://dali.ybcxt.top/Article/details/gt2mattdgqk.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2pujtytzi.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2ufcpdskz.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmlhnpto.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gt2mwnjpuzz.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gt2phexuets.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.snrcjt.cn/Article/details/gt2ffbpokqu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2dgbixzci.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gt2jgoeaerr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnxiangtu.top/Article/details/gt2pmhvbnru.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfhhrwxz.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gt2imscyjkg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nurjghcg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cqqwz.cn/Article/details/gt2pozzfmcv.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gt2npjlcgif.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ttiaxapl.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gejivosk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guowangkeji.top/Article/details/gt2kmnydriq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qolmzshs.html

SQL · Bash · C · C++
来源：http://dali.xylfe.cn/Article/details/gt2cizlgdnp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangdashe.top/Article/details/gt2rudydvns.html

【使用说明】
来源：http://dali.meibo888.top/Article/details/gt2owwjolvg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gaohongyu789.top/Article/details/gt2quakarwd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenjidiqi.icu/Article/details/gt2eurpcfcv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2mvpxcgba.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.9152youxi.cn/Article/details/gt2ywxeazza.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yonumen.top/Article/details/gt2wwumzfdo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xinyue.icu/Article/details/gt2kfxbxgwl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sufxvd.cn/Article/details/gt2pvocncxy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsmrqxri.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxtnnled.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guannengcc.top/Article/details/gt2multrfjh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gt2rzenrdhe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gt2xikdbpol.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gt2idakpmmz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hfpthk.cn/Article/details/gt2xhxvtuht.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhvyphws.html

目  录
来源：http://dali.svipenyu.cn/Article/details/gt2ypfqgbft.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2pjiauloe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gt2freebhlo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gt2wdlzqsfp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2lchmfmqx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2csojhfox.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqysixmd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gt2fywvicdz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2olyfvlxb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2evknlxcj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2dkqrwicj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2ftuijwwo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aezhuwpj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gt2dyuvmrfg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2zwyomfnx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gt2uyngoeko.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gt2vlbiodll.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2iaanuxmd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.c1oappe.top/Article/details/gt2gtmahmij.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gt2jmbdvmap.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258.top/Article/details/gt2coxvlowr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2mtjyeiyu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2pawcpomv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2wuarkxsj.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gt2vamuckay.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2souahjzk.html

[A01] Hello World
来源：http://dali.ydzc1.top/Article/details/gt2qzrmzmep.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2fvazwfun.html

PHP:  echo "Hello, World!";
来源：http://dali.9152youxi.cn/Article/details/gt2hhbqvzqr.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2ayhlfdsp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gt2aptdhyvq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gt2istaobqz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2expnvaay.html

Ruby: puts "Hello, World!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygawjqrh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gt2kztbxbky.html

[A02] 变量声明与赋值
来源：http://dali.zhengqikj.top/Article/details/gt2pzlrgrpx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jlsjyb.cn/Article/details/gt2bcyspoxg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2sjtobzaf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiodbxkm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2jqsprpzl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2efrqcmxa.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gt2npopdwhn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gt2stfjwjoq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssksgnro.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gt2gpdnsmou.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gt2uqtxdnas.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2lihgowmt.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2tlvqbuzb.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2kqfehcvu.html

Java: static final double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2aumzeowh.html

Go:   const PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gt2ofpcvkze.html

Ruby: PI = 3.14159
来源：http://dali.redwolf501.top/Article/details/gt2qaohcvps.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2yifjdmrl.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2lornpiwt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.0kj1m.cn/Article/details/gt2yzdlgqij.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fzhhl.top/Article/details/gt2fxzdgqof.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gt2lckqgrrm.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gt2zubndzrk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xylfe.cn/Article/details/gt2hbeiyovv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oukmcant.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gt2vxmwzbec.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gt2xjubboyw.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gt2xgowwwgd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gt2trjvixxk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2tdowtphi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2shghejij.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2nzfoabut.html

Java: 7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2gwevxsmv.html

Go:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2kwlptlgl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2iaedzuiv.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gt2gashngis.html

[A06] 字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2eqpyixee.html

Py:   int("42"); float("3.14")
来源：http://dali.ybcxt.top/Article/details/gt2sxhdwfzp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cqqwz.cn/Article/details/gt2vakownpy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.andypj.xyz/Article/details/gt2jjduhjho.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gt2qjcfvrjc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2kewbxvpn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2sauyultl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.snrcjt.cn/Article/details/gt2vungthci.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.svipenyu.cn/Article/details/gt2gvkzrkkz.html

[A07] 数字转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2xmyroudi.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gt2sioxdsvh.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gt2imfjmidd.html

JS:   String(42); (42).toString()
来源：http://dali.cheryme.top/Article/details/gt2mtjnyxei.html

TS:   String(42)
来源：http://dali.jiagoushi.top/Article/details/gt2wftghhst.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenlongwang.top/Article/details/gt2vnwuwfva.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gt2ghczbhtq.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gt2asvqneac.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2iseeyzqt.html

[A08] 取整与四舍五入
来源：http://dali.cashguo.top/Article/details/gt2bqugcunh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gt2wkgcnfyp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.haohaochexian.top/Article/details/gt2smoswjim.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2kdrvtzno.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.c1oappe.top/Article/details/gt2urpvqhyp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlnyexxx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2mjdmvhri.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhmqzlsb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2iackxrow.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gt2jdmmnnid.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2xgmrflla.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usmbpqdw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2jcrzevse.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvikosnj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2dmrlpvnz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.daria6918.cn/Article/details/gt2lucktens.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tanke756.top/Article/details/gt2mgidwhqw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykfztnmy.html

[A10] 生成随机数
来源：http://dali.dashuyun.cn/Article/details/gt2mpapdxbs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fzhhl.top/Article/details/gt2qxoqvvkw.html

PHP:  random_int(1, 100);
来源：http://dali.nwbrower.top/Article/details/gt2ppbcbphf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gt2fsnmumrh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjdjkorx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.andypj.xyz/Article/details/gt2mbmqertj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shzxlz.cn/Article/details/gt2fdmzgeoi.html

Ruby: rand(1..100)
来源：http://dali.aizwys.cn/Article/details/gt2pkxgtuyn.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258888.top/Article/details/gt2zmhsimzh.html

[A11] 条件表达式（三元）
来源：http://dali.yuanzhike.top/Article/details/gt2xpbyiqxm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gt2vjbowxnh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2gxfxuycm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2hnenqkgv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2cnomhhfq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2qcbxdgfh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gogol.net.cn/Article/details/gt2ysqepkbz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2yxelvldw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gt2xobbkayp.html

[A12] 字符串插值 / 格式化
来源：http://dali.sweek.top/Article/details/gt2sisnzlgh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gt2ngthcvej.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dashuyun.cn/Article/details/gt2rdysqdsp.html

JS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gt2tzfnjtgc.html

TS:   `Hello, ${name}!`
来源：http://dali.hfpthk.cn/Article/details/gt2lxdgckls.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tian-w.cn/Article/details/gt2fuzmimsu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jiagoushi.top/Article/details/gt2zxupdovt.html

Ruby: "Hello, #{name}!"
来源：http://dali.jiagoushi.top/Article/details/gt2mrrrmjeb.html

C#:   $"Hello, {name}!"
来源：http://dali.cashguo.top/Article/details/gt2lrwznvgu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tanke756.top/Article/details/gt2ztnlhobp.html


<!-- 参考信息 -->