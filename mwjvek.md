代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtbgftqcwq.html

throw new RuntimeException("失败", 500);
来源：http://dali.iojbl.cn/Article/details/gtqmbwtyhl.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gtrcwuabwr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gtxjhiwmkl.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gtowtvwcvn.html

parse_ini_file("config.ini", true)
来源：http://dali.aizwys.cn/Article/details/gtumzogtdn.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtoahhonhb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gtibywbscd.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtygoqijed.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gtzhppjrxj.html

[U76] PHP：简单路由
来源：http://dali.hywenlv.cn/Article/details/gtgjektsqg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gtxfngmixb.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtufthvujc.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gtovlydzpr.html

[U78] PHP：单元测试
来源：http://dali.hammf.cn/Article/details/gthavgpuit.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gtigfrgkys.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gttrzawuei.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtorppzfss.html

[U80] PHP：代码规范修复
来源：http://dali.jinqigfzy.top/Article/details/gtunlcgull.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daria6918.cn/Article/details/gtfkmnfbvp.html

[U81] JS：初始化项目
来源：http://dali.yvedp.cn/Article/details/gtsmnjctoj.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gtmtfaeojf.html

[U82] JS：package.json 脚本
来源：http://dali.hfpthk.cn/Article/details/gtyldqcuao.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gtdxruwbsv.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtozwzuekr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tanke756.top/Article/details/gtnjlwsuzx.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gtkeujxzey.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gtpnjaodwd.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtsgqsqjvy.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtkywpkqvx.html

[U86] JS：空值合并
来源：http://dali.wangshuangyany.cn/Article/details/gtdvqoyahc.html

a ?? b
来源：http://dali.svipenyu.cn/Article/details/gtprfnwypv.html

[U87] JS：解构默认值
来源：http://dali.iojbl.cn/Article/details/gtkrbcabzs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tianlin.xyz/Article/details/gtcruseteu.html

[U88] JS：对象展开合并
来源：http://dali.aizwys.cn/Article/details/gtafyhienr.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gtboussccs.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gtygqnskph.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlspgzqs.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gtvpfxrpkc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtlriafmio.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gttlcboifu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtdzqlbqna.html

[U92] JS：深拷贝
来源：http://dali.cheryme.top/Article/details/gtkgupocrj.html

structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtiexoprif.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gtrzozwikr.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gtnwwxxtdo.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtnxbupeoc.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtrfrzzeob.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gthzvwbdwb.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtauwrndkp.html

[U96] JS：async/await 与异常
来源：http://dali.tanke756.top/Article/details/gtvktjcpxn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtcilsddcb.html

[U97] JS：并发请求
来源：http://dali.zycfv.cn/Article/details/gthhjogiqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtfoncfchu.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuxming.cn/Article/details/gtesprgdwq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafggvsfm.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gtmapuclps.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtfohciulp.html

[U100] JS：DOM 查询
来源：http://dali.hysaishi.cn/Article/details/gthrcrdral.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtotpedori.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gtsxnsytjm.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtilnkzqrq.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtxbvjvckb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteumrdnck.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqesktgzi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuvhiqxe.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gtkfqdxwys.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtechrtcjt.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gtdykhngya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtwtgowexw.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gttwfcpqse.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtufgsumug.html

[U107] JS：数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtambbrgsl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtzufzdtfc.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtonyitr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gtqjvgvvqg.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtwozjfjeb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtuofhqmdb.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gtzugnlgdh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gtnxngkpzm.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtlipjryer.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gtyjdvrvmp.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtpgzpmojo.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtqjwkjrmy.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtfaxssrib.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtgbqkrctm.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtmotidqws.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtuewiuwaz.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtyfwumtgr.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtoizuzrjl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gthsbcemay.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgarupeh.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtqcgrtcga.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gttdvxvaqu.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gtwyvktbde.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtirhquojl.html

[U119] JS：生产构建
来源：http://dali.sxryk.cn/Article/details/gtzgrfmuwa.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gtsorztrsb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hysaishi.cn/Article/details/gthkmvfyeg.html

import.meta.env.VITE_API_URL
来源：http://dali.316326.xyz/Article/details/gtialcxcur.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvthxbsih.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gtdjxzggfy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtulkpzmev.html

按语言统计（条）：
来源：http://dali.ydzc1.top/Article/details/gtynucetki.html

Python ......... 252
来源：http://dali.fzhhl.top/Article/details/gtplnartoj.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtemunkknc.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gtjpubqvak.html

TypeScript ..... 212
来源：http://dali.nanxinkj.top/Article/details/gtfijjtwgg.html

Java ........... 212
来源：http://dali.cdnleiting.top/Article/details/gttkizezap.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gtafhopdou.html

Ruby ........... 212
来源：http://dali.sxryk.cn/Article/details/gttduzzwzs.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gtmlhvtxod.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtvczyyrrm.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtnivhejfr.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gtnqwrxhwt.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gtsmgbfqer.html

Kotlin ......... 15
来源：http://dali.aizwys.cn/Article/details/gttovkizfi.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtmjplabxh.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gterbdvqhx.html

Perl ........... 10
来源：http://dali.cdnleiting.top/Article/details/gtoxlqbunl.html

Scala .......... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtzlwglfny.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtqwmkzlcn.html

合计 ........... 2106 条
来源：http://dali.jinqigufen.top/Article/details/gttglcpvdf.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtwrmxargp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtbxfcalgk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtffdatckf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtjihvlyxj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtzzwwawdg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.chenlongwang.top/Article/details/gtaylcgefg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtiraphgib.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtdjupfqyz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtecaqckpk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gttkkdeden.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtwbcnqezi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtoibgcyou.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtpvhwfxum.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtccekmwxg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gttiqplneo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hfpthk.cn/Article/details/gtnthwwmxs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtvielfein.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gtqkopcqoq.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gthgwagrlp.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtccaqsohw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gtyerpweqk.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gtbuizhzed.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtnuojxxfp.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtxlueleqw.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtjqgkarzi.html

使用提醒
来源：http://dali.aizwys.cn/Article/details/gtuzflrtwh.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gttwiapsdy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gtyiepnbil.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fzhhl.top/Article/details/gtdauyxeop.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtbaofhyoc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jianghu66.top/Article/details/gtopsthgph.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gthgrudxuq.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gtdkhczcvw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpxarwwdr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gtldwxkvkp.html

Common Programming Examples Cheat Book
来源：http://dali.yuxming.cn/Article/details/gtwklsfhqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyzdqrbfb.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gtsryohnom.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gtubfufner.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gtrqvfeqph.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gtwfacdbhk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gtvqlujpfv.html

【使用说明】
来源：http://dali.hywenlv.cn/Article/details/gthbhpmszi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dianchejie.cn/Article/details/gtohzqxnjg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gtpcpdcwgp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlipycjta.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gtedqklmwe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtreqwtcyj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nwbrower.top/Article/details/gtagdmzkck.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gtpowvnxzs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gtlktmwkck.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ehwqpu.com/Article/details/gtdmoitbfy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtcbbxfylr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gtmzqpspqo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gtmxoaqfpi.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gtknvkyeym.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.haohaochexian.top/Article/details/gtmlxdtdjr.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtyiwayveg.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtndxwyzpu.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtbobnikrr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmncjvydn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtxhareouk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtnixhrzwc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gtuxnwxtgf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gtwqrzpdpw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtbdorcdxj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gthylxnijv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtzpmbnhxr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtiuhwlupq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtkpadqzvm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtflritpux.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtqwdtzncw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtmikqvq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtrstwvxmg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zycfv.cn/Article/details/gtaftbtvum.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtaenimdbb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daxiang520.top/Article/details/gtzufdgnwt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ivvv.top/Article/details/gtcjknoutc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtvxrxohyc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtlckktlcm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtzowqkqoj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkvddglgt.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtwrhpuhzq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrjytifmi.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtbcbzygkd.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtcnjwxldh.html

PHP:  echo "Hello, World!";
来源：http://dali.feifeiyinyue.top/Article/details/gtluoqvfbz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtrprjikvq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gtukvevvly.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtdgefozch.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtqcdtbomq.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtaxixcetk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgessyll.html

[A02] 变量声明与赋值
来源：http://dali.guowangkeji.top/Article/details/gthvplhfut.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhongyouzk.top/Article/details/gtoarlerqu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtalzyeqgb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zycfv.cn/Article/details/gtlkhdijwd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gtpvfkbnzy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtahwkrdie.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gtjllhhemk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gtadvangpn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtjigdciup.html

[A03] 常量定义
来源：http://dali.meibo888.top/Article/details/gthkmjesjn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhixingplan.top/Article/details/gtpyiyqula.html

PHP:  const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gteqadyeni.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtxfoncgon.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtkyerercf.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtvjtasslf.html

Go:   const PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gthanjcxkb.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtuewdiznk.html

C#:   const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtoaypfjag.html

[A04] 判断变量类型
来源：http://dali.yuxming.cn/Article/details/gtgrbqnxnd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gthhcpygoj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gtcpczkpmz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gtglvybtoy.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqfsiraq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.havefunace.top/Article/details/gtkozmdnwi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gtwomkkxpe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtnmzhieeu.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gtowyfcpun.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gtttliglyx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fzhhl.top/Article/details/gtlugvhqlm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtubnwrleb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtbdskllme.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gthipsudta.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtkropdlbj.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtangqetpd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtywseiadm.html

C#:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtgyjdjgfv.html

[A06] 字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtqenfbsqe.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtxajztvwc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gttbwotmjt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtmhavytlr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtuykhvnaa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtixkcfpls.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gteebjvhqr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cucudq.cn/Article/details/gtfanozjin.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtdhjcwifa.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gtwevpdlyl.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gtkjziqjhr.html

PHP:  (string) 42; strval(42)
来源：http://dali.aizwys.cn/Article/details/gtfsthzvgv.html

JS:   String(42); (42).toString()
来源：http://dali.ehwqpu.com/Article/details/gtrelujelt.html

TS:   String(42)
来源：http://dali.gzhubu.top/Article/details/gtdawngonf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.mhx1999.top/Article/details/gtoklktbyu.html

Go:   strconv.Itoa(42)
来源：http://dali.sweek.top/Article/details/gtudrrzfnj.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoubngsf.html

C#:   42.ToString()
来源：http://dali.hysaishi.cn/Article/details/gtmyzemrlm.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gtrjivbieq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtbeqfphtj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258.top/Article/details/gtrsadvubt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtuoufwrgh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuanzx.com/Article/details/gtemuzevyw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtyhhwwfkk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtrzgivgui.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigufen.top/Article/details/gtsqddbfoz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpegbgrqi.html

[A09] 绝对值与最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtgbbdfucl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtyivzikkd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtpfrpglrm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtdurcshet.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtuzukkajj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtnejbnopn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cucudq.cn/Article/details/gtqdchpjlr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gtfnfvhkwg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtksitjpwm.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gtrtrihuwk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.vqdsnc.cn/Article/details/gtbqtbhzlo.html

PHP:  random_int(1, 100);
来源：http://dali.daria6918.cn/Article/details/gtucwacqnv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtchdjtwgr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtbqstgvip.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cashguo.top/Article/details/gtgbuugkpo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgfzy.top/Article/details/gtifvwmgfi.html

Ruby: rand(1..100)
来源：http://dali.zhongyouzk.top/Article/details/gtcejjqvhc.html

C#:   new Random().Next(1, 101)
来源：http://dali.shangyingyoupin.top/Article/details/gtvaxnzrlk.html

[A11] 条件表达式（三元）
来源：http://dali.0kj1m.cn/Article/details/gtnphymkia.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.haohaochexian.top/Article/details/gtdkvtibtj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtohrgxlbq.html


<!-- 参考信息 -->