代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.guowangkeji.top/Article/details/gt2uuzyqxmc.html

throw new RuntimeException("失败", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2kyvnpbbk.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnrylkrx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gt2kyzvkcbl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gt2rnchsrkv.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gicpudgm.html

[U74] PHP：读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2mjysvvow.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tian-w.cn/Article/details/gt2ulvcnpgs.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcgnfkjj.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gt2wrmongsj.html

[U76] PHP：简单路由
来源：http://dali.tian-w.cn/Article/details/gt2tysuvhnu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gt2pckazzms.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gt2oxgruieb.html

composer require twig/twig
来源：http://dali.cashguo.top/Article/details/gt2hpifipdk.html

[U78] PHP：单元测试
来源：http://dali.0kj1m.cn/Article/details/gt2oovguzmo.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gt2lvhgoryv.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gt2rkhbwhbh.html

composer require --dev phpstan/phpstan
来源：http://dali.yuanzhike.top/Article/details/gt2mdajfcfz.html

[U80] PHP：代码规范修复
来源：http://dali.xziqi.cn/Article/details/gt2jwmimqbg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gt2mgcoeepl.html

[U81] JS：初始化项目
来源：http://dali.svipenyu.cn/Article/details/gt2cviqszok.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uumwhlkn.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gt2vimqpars.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zycfv.cn/Article/details/gt2ufkfwvvy.html

[U83] JS：ES Module 导入导出
来源：http://dali.jlsjyb.cn/Article/details/gt2fdedfgyg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2ryvfvium.html

[U84] JS：CommonJS 写法
来源：http://dali.hnqzz.top/Article/details/gt2hxjoaxog.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.vqdsnc.cn/Article/details/gt2ckzrclsk.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gt2zxrdqvcr.html

a?.b?.c
来源：http://dali.yuanzhike.top/Article/details/gt2wjyjdfby.html

[U86] JS：空值合并
来源：http://dali.xinyue.icu/Article/details/gt2tgovmqfm.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gt2kygsitqn.html

[U87] JS：解构默认值
来源：http://dali.hywenlv.cn/Article/details/gt2hsxsmxac.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tian-w.cn/Article/details/gt2oqrbxqjr.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gt2tjhsggar.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gt2waztgnsr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uydonzwi.html

[...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2cetbfgpv.html

[U90] JS：数字数组排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvcxmmmq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2vvacfuzy.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2zqdqzyri.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gt2fyzcesnk.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gt2jzyvldrg.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gt2pmascihb.html

[U93] JS：模板字符串
来源：http://dali.snrcjt.cn/Article/details/gt2zhndkily.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbpgmnkv.html

[U94] JS：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2fyhwpzut.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gt2qgpdpwtj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtrqbob.html

new Promise((resolve, reject) => {})
来源：http://dali.dashuyun.cn/Article/details/gt2gldikgcf.html

[U96] JS：async/await 与异常
来源：http://dali.yangfankeji.com/Article/details/gt2mgyvpyif.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2cwtcuqqo.html

[U97] JS：并发请求
来源：http://dali.xuanzx.com/Article/details/gt2riokjmxc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2ddpkyjtf.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2rwuwjoof.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gt2eeqdjtqo.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gt2yvkcmlpe.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odtlpsns.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gt2eiaqdani.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gt2gejzoxze.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gt2cqztjrwl.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gt2mnjydnql.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2hjsenycn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gt2jmebriry.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2gphdzhis.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gt2myxbbqyc.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gt2skvhcyaf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2qveixuew.html

[U105] JS：节流
来源：http://dali.zhongyouzk.top/Article/details/gt2bhfndtkl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gt2tqtuvxgv.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2osnhhxkr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gt2jmzvszsb.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2wamadbfd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2hzzjbnhy.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gt2jopxwlur.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.andypj.xyz/Article/details/gt2fhxdreui.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gt2vtukyjar.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gt2mabsroza.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2mvfyqvcb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhoulong.xyz/Article/details/gt2yqqzuwia.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2htlxgqkn.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2blicvxib.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gt2buptalcy.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2hndkwokh.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gt2ukbgbiiz.html

s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2nodfjist.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gt2oavrtzsz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2gfehozar.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2owsjksyk.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2hjwdrkwt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gt2syzldxta.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gt2xngduzji.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llwobmpg.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gt2yrviavgv.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gt2jwhdqihl.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gt2qypnlolb.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gt2qnxxneda.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gt2qxzhqumu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gt2cbgxchxk.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqwthxfu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2dxrrdcqx.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gt2lbcjfoxv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbfvxllu.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gt2bigzniku.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gt2zrmoukci.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkntdato.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gt2qhjdejkz.html

TypeScript ..... 212
来源：http://dali.zdqjudy.top/Article/details/gt2sdcggabf.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2fvlbwyie.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2yppmfqys.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2wjrpyvrx.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gt2nwvalhzx.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gt2czsagclf.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gt2enwwwwnc.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gt2tjugaqvi.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gt2omkfewkt.html

Kotlin ......... 15
来源：http://dali.yj20258888.top/Article/details/gt2hzrcwjjl.html

Swift .......... 15
来源：http://dali.c1oappe.top/Article/details/gt2fzjdvelu.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gt2kbplyulf.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2hjapsciq.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gt2sqnetfxa.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2rihkukgo.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2ltakvvam.html

按章节统计：
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukwjbmik.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ybcxt.top/Article/details/gt2sgnkyqyc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2nnzulava.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gt2cvdpkyan.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gt2lqysjzju.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gt2kskywmgd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2uybymrva.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2swfghvft.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gt2yesgzmzy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2cskdlmdb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyffisbg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2vgikvwpx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2zuyctwjy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqzkqjcq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gt2dzgtcicb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvedzntw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2keyfzhqx.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gt2pfklxdqe.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gt2mjuqxybi.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gt2lwvrpdcg.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gt2rjpzjqgp.html

U 高频实用片段                         120
来源：http://dali.cucudq.cn/Article/details/gt2zrjqezlp.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2tzbdcpoy.html

合计                                  2106 条
来源：http://dali.yj20258.top/Article/details/gt2flrzvntf.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2yfmnxbho.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gt2npuiwthz.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gt2brktbegs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xinyue.icu/Article/details/gt2ntgmqqyp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gt2efkrmpns.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzbdtniz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gt2mfbxlyvj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shuidangran.top/Article/details/gt2nvizqwez.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gt2titfukgx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fymjjuxn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gt2yyuxouxc.html

Common Programming Examples Cheat Book
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyimwymy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2rowlvjij.html

【收录内容】
来源：http://dali.redwolf501.top/Article/details/gt2vzmhkcdb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yangfankeji.com/Article/details/gt2hpcqenpl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gt2pytxhbtx.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqpvkcbw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gt2czenklih.html

【使用说明】
来源：http://dali.hammf.cn/Article/details/gt2xjvcmphd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.haohaochexian.top/Article/details/gt2yreaabnx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shzxlz.cn/Article/details/gt2yfdibcef.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnqzz.top/Article/details/gt2voggvtek.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.kuanghao11.cn/Article/details/gt2tqobjdms.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gzhubu.top/Article/details/gt2luuyowjc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gt2vjojkrkg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigfzy.top/Article/details/gt2fsfdfzhe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnxiangtu.top/Article/details/gt2fpmipzsm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fzhhl.top/Article/details/gt2pqtpcpoq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gt2wvussfyi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hywenlv.cn/Article/details/gt2rluibsps.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gotoacloud.top/Article/details/gt2nmaqbbsp.html

【文件统计】
来源：http://dali.sysykeji.top/Article/details/gt2igbjuheq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.iojbl.cn/Article/details/gt2svqftubr.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2tmkdruuy.html

目  录
来源：http://dali.yvedp.cn/Article/details/gt2rjrypxrp.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2kfdgaoyx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2spiiwqwx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2xstcgsvv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gt2tdkjfaea.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcwugxss.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2lngnhcbb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gt2ezviqcjr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2rgbfwxbc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guhoyqjl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2psxwevyg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhihxrjy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ectjzjgi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2vpiaxwub.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2ctzjxbxb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gt2dykhwitf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnjuftvh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2pervjvtf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gzhubu.top/Article/details/gt2mpfygsux.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2wxalyiyi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2zskmwshe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2zjowhktp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2nxidtjcw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2xftunbwj.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gt2kbljdfvs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xtkruews.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwvalvwy.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gt2cywocagz.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gt2rhrjnxed.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gt2efbbsoos.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nwbrower.top/Article/details/gt2wzjkbeoe.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gt2aqlbwwze.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gt2wsvgexes.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gt2lndbyhvu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gt2aablfuwy.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gt2dizqjmms.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gt2uvdnkuhl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2tlsqyzpk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdpgsgji.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckifbxjf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gt2favxerbe.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gt2uwcnmgqq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gt2aqicxtpd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2bvyfudds.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gt2sokhyjad.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcjwaofn.html

PHP:  const PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpgvwqog.html

JS:   const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2vptpsidr.html

TS:   const PI: number = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2wfyzprjb.html

Java: static final double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vedtphit.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gt2ludwbzbc.html

Ruby: PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gt2mmdeiafw.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2felmdexi.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gt2svwrsyva.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gt2eyqbpjcs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.haohaochexian.top/Article/details/gt2hygvixsf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gt2egbmwnih.html

TS:   typeof x; x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gt2hffdmqte.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sysykeji.top/Article/details/gt2cvdxqmsc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.kuanghao11.cn/Article/details/gt2pjgwwdqk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lfkcapjp.html

C#:   x.GetType().Name; x is int
来源：http://dali.jyoumei.cn/Article/details/gt2qhvijban.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gt2ziruwghn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.kuanghao11.cn/Article/details/gt2ssoeuwof.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnbovhth.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2nteotygm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2bbixwptc.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2vfcwgaqy.html

Go:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2yznuopfi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2vmufuchf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2anyihjjs.html

[A06] 字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2nyistgmv.html

Py:   int("42"); float("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccujvjaf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gt2darlwvcf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2txftlgfa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yvedp.cn/Article/details/gt2swuvkpzs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.smart0.xyz/Article/details/gt2irknzxiq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhuzyblh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gt2tphjplwd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.bjfxy.top/Article/details/gt2dgmznhrx.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rhgdpful.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gt2xzlezggz.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gt2wtyxfdeu.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gt2szvwuotd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmyyefo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tanke756.top/Article/details/gt2qzijjful.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gt2zuigjgfi.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gt2yfoeonro.html

C#:   42.ToString()
来源：http://dali.snrcjt.cn/Article/details/gt2wwiitlpp.html

[A08] 取整与四舍五入
来源：http://dali.svipenyu.cn/Article/details/gt2mjptuqvw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2ayauljxf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.havefunace.top/Article/details/gt2ebfaqhkv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gt2eyjgyybc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jyoumei.cn/Article/details/gt2wuhpmrih.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gt2fdumkmnt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2pffimvkt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dashuyun.cn/Article/details/gt2ydugppyy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2zgjnptqn.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2impbddky.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2yisojqgb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2ttujydak.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndhrmxv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2nvohvvzo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjjzmlwb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gogol.net.cn/Article/details/gt2iskumkyk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jqgfzy.top/Article/details/gt2mkkgfzgp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2fzvbgjwa.html

[A10] 生成随机数
来源：http://dali.nwbrower.top/Article/details/gt2waanpjpe.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhoulong.xyz/Article/details/gt2wsvwypzu.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyqhtxpu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgdsnmos.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gt2bzzsiwbe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.9152youxi.cn/Article/details/gt2pdheiaik.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gt2cxuhlhdv.html

Ruby: rand(1..100)
来源：http://dali.jiagoushi.top/Article/details/gt2iiimjazu.html

C#:   new Random().Next(1, 101)
来源：http://dali.nanxinkj.top/Article/details/gt2guzmbhwz.html

[A11] 条件表达式（三元）
来源：http://dali.yongpay.top/Article/details/gt2sdzsftbn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2tqylxcze.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gt2ovhsldhu.html


<!-- 参考信息 -->