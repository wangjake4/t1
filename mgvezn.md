代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.yuanzhike.top/Article/details/gthgwwbdqc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gtlqllewci.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gttqzvtuzc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jianghu66.top/Article/details/gtosdytjqk.html

[U71] PHP：抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtkrwvpyzs.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtxrblxwim.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtbmivxhjv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtmvbpgwvt.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gtqovdsmtx.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gtzialskdv.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtpqsjqlyy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtirwymmub.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gtphdlrphw.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gtzaldozzn.html

[U76] PHP：简单路由
来源：http://dali.tanke756.top/Article/details/gtgammcyfi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.c1oappe.top/Article/details/gtgtknrkmf.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtasfpctve.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtpzxwopqt.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gtmbxwrwys.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtcsxxxita.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gtgxtmydvk.html

composer require --dev phpstan/phpstan
来源：http://dali.hnqzz.top/Article/details/gtptjxrruj.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gtrtknimza.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.svipenyu.cn/Article/details/gtylychvgb.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gtmuqirtlx.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gtfbmowaud.html

[U82] JS：package.json 脚本
来源：http://dali.nwbrower.top/Article/details/gtbjznegno.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtcdygwylx.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuetiantiany.cn/Article/details/gtztovehhp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtekvxjlql.html

[U84] JS：CommonJS 写法
来源：http://dali.birdmap.top/Article/details/gtquhlhkvx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtjegnunlv.html

[U85] JS：可选链
来源：http://dali.jianghu66.top/Article/details/gtbborbcrj.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtlasgchrl.html

[U86] JS：空值合并
来源：http://dali.jyoumei.cn/Article/details/gtycjzxbbh.html

a ?? b
来源：http://dali.sweek.top/Article/details/gtynknypgt.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtjblzuxpd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cdnleiting.top/Article/details/gtacbhefym.html

[U88] JS：对象展开合并
来源：http://dali.cqqwz.cn/Article/details/gtimxqsfsr.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gtdiniihtd.html

[U89] JS：数组去重
来源：http://dali.cashguo.top/Article/details/gtsrswyxku.html

[...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtuxikgkxz.html

[U90] JS：数字数组排序
来源：http://dali.havefunace.top/Article/details/gtbdkpeoej.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtrbttdfen.html

[U91] JS：对象键值遍历
来源：http://dali.xziqi.cn/Article/details/gtoprolkkc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtmehpszwa.html

[U92] JS：深拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtxnifbz.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtyvxoosgi.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gtoawipblq.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gtnrkmupjw.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtuidceobw.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtbovltljm.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gtkssgbtfj.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtmqbusrre.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gtovjvxqaj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gthwenvjux.html

[U97] JS：并发请求
来源：http://dali.xuetiantiany.cn/Article/details/gtkfkhacko.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtdxmjzypw.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvigvsgx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfwshxuf.html

[U99] JS：事件监听
来源：http://dali.nwbrower.top/Article/details/gtqoywtfsw.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwykulsit.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gtsgikehzd.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gtqbfednmz.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzmfaelg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gtxacffzao.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhynjwfm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gtdsdndbpb.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gthraucwyj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gtcriacotd.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinfwasin.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtwscckvyx.html

[U105] JS：节流
来源：http://dali.dashuyun.cn/Article/details/gtbscrtvli.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtlzwxlz.html

[U106] JS：日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbklengtg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtiqyrhfva.html

[U107] JS：数字千分位
来源：http://dali.sysykeji.top/Article/details/gtxpxlrbqv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtpxtzslef.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gtjnmrmook.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtcuwmgjyx.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gtuvcdcvee.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoorgqqk.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gtxfnaylkh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gtxunadrgk.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtnpzxnyhp.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtlhslfhcj.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gtpebhzvje.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtubswdoxk.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gtwwwclnum.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gthismohen.html

[U114] JS：JSON 深比较
来源：http://dali.xinyue.icu/Article/details/gtxmkhvmbw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtrmdlxzac.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtoakmjxli.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtkbgiaehl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gtsvvwxfcl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdbknbcqd.html

[U117] JS：单元测试
来源：http://dali.yj20258.top/Article/details/gtmckkqjwx.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtgeewevui.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gtllogzkte.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gtkhknlvfh.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gtvxdrwjhh.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gtcddvnnxb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtfttutocl.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gteokrfndk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfvbifqni.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gtmjgpieni.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtavuyvvrp.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwwceyoe.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gthtutojrv.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtyzoyncyc.html

JavaScript ..... 252
来源：http://dali.mhx1999.top/Article/details/gtehpwebqa.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtnwvytrlh.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtlotjklxa.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtwawqewlw.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtbclsvsnp.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtvxeirfmd.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtnbysclos.html

C++ ............ 30
来源：http://dali.hywenlv.cn/Article/details/gtszrfdysy.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtdenunxti.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gtlhxufmxg.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtudutdcwy.html

Swift .......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtnsmdztqx.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gtoprerkyx.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtrclqeikb.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtyujdaajh.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtpcmeltzu.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtrchqsnsm.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtekkyjbjl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gthejqzetg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gtynafeixw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtppkiwwyb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpogrijub.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtacmpzfot.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtvmblxbon.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtwrfkttbt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtfjtjzwyg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtaixuvgwz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtvxxmjbyp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtixaoudog.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtyylaxkhw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtfrlblugl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtelmgtasx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhengqikj.top/Article/details/gtaroeiejs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtrydebwco.html

Q SQL 专题                              90
来源：http://dali.shangyingyoupin.top/Article/details/gtgfyukkhr.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gtwtarxmdg.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gtgdqubywh.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gtcpjzmimk.html

U 高频实用片段                         120
来源：http://dali.yongpay.top/Article/details/gtikexhrbj.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtwwdosrow.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtxlbfuooe.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtnsbazbnk.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gtotpoaasu.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtmvgradhj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenzaomai.com/Article/details/gtiedyqbll.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gtuiucovgg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtsdsymmeo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhiwuduotai.top/Article/details/gtagobmzio.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daxiang520.top/Article/details/gtchzmfkrl.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gtozlgxume.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtetplkwhh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtmuhniaop.html

Common Programming Examples Cheat Book
来源：http://dali.ehwqpu.com/Article/details/gtnzbhdthb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmbwzcxhx.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gtzcgzlxdg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gtglkzkykc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gtemiubcga.html

SQL · Bash · C · C++
来源：http://dali.xinyue.icu/Article/details/gtwgpbxbas.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gtgplwsiiz.html

【使用说明】
来源：http://dali.dashuyun.cn/Article/details/gtwmawbilg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnxiangtu.top/Article/details/gtatihkgzs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gtgosqqvzb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.c1oappe.top/Article/details/gthyajjfda.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gotoacloud.top/Article/details/gtbsaljmai.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtbwsxretj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aibaodan.cn/Article/details/gtklqtqtdd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.daria6918.cn/Article/details/gtenvfdmcj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangshuangyany.cn/Article/details/gtplqlguku.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gtitzgxovh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxnijypm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gtjyxgwpav.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gtgztuddpo.html

【文件统计】
来源：http://dali.fzhhl.top/Article/details/gtzeaugofg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuanzhike.top/Article/details/gtxwxfqmql.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtspxbzhym.html

目  录
来源：http://dali.jiagoushi.top/Article/details/gtyataqpkd.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtdzqodyxv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gtwewzdizp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtiagyogse.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gtnweshrxe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakhlhthm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hysaishi.cn/Article/details/gtwvyqummj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gtujpkntpx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtimmxmsjk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tanke756.top/Article/details/gtfhoetnfg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gthehtrszi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtckscmmam.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtwjocwxak.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbpbtvjl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gteeninudh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gteahbxdbg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tanke756.top/Article/details/gtoyxcsqqr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gthzmdoccn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gtqvttyinq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.smart0.xyz/Article/details/gtaljdspua.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgfzy.top/Article/details/gtivlkbyjk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gteifxklvl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtxkgdcgvt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtypvtvgab.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gtdwsplqms.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrzvkidos.html

[A01] Hello World
来源：http://dali.dashuyun.cn/Article/details/gtnvblydvp.html

Py:   print("Hello, World!")
来源：http://dali.wangdashe.top/Article/details/gtqzskawlj.html

PHP:  echo "Hello, World!";
来源：http://dali.aibaodan.cn/Article/details/gtfkcwlkwg.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtkyghjffv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gtqhhixtkl.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtkvcgwnyo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtgyvurmzj.html

Ruby: puts "Hello, World!"
来源：http://dali.aibaodan.cn/Article/details/gtexzdmpqq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtnpbvrdhy.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtdiiucxmw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtfrrgliks.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daxiang520.top/Article/details/gtegknqkly.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gteknvzyrt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.iojbl.cn/Article/details/gtxgamqark.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtwcblxzmb.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gttymgctdo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtnwiiklrg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtbwhexqpx.html

[A03] 常量定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsahrnbiu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gtieckukbs.html

PHP:  const PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtvwrfpoqk.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtkhrzbczq.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtyrxqjhcg.html

Java: static final double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gthdtcbxaa.html

Go:   const PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gtinithuuw.html

Ruby: PI = 3.14159
来源：http://dali.meibo888.top/Article/details/gtonamayjm.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtkgmaicrw.html

[A04] 判断变量类型
来源：http://dali.yj202588.top/Article/details/gtbahqscdk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gtjjcctxbd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ehwqpu.com/Article/details/gtvezanikx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gteksvovsl.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtvftzzpor.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitacfuoi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtnklwuiai.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gotoacloud.top/Article/details/gtbzgmnqyd.html

C#:   x.GetType().Name; x is int
来源：http://dali.guannengcc.top/Article/details/gtijiqfgcy.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtodczhuyr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jlsjyb.cn/Article/details/gtortbuszd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtcuvoexlw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtoyqyrpug.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtdmxlllgj.html

Java: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtealiigrn.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtwactsnca.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtgzfcsvmo.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtatzokfne.html

[A06] 字符串转数字
来源：http://dali.ivvv.top/Article/details/gtqavjplxh.html

Py:   int("42"); float("3.14")
来源：http://dali.havefunace.top/Article/details/gtfeazuqhl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacuosskn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtbjllbypu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtsiopyzbb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gtuneizsrp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumwlqtlf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gtmsiwimsw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtfwzpzyho.html

[A07] 数字转字符串
来源：http://dali.dashuyun.cn/Article/details/gttzqhhnea.html

Py:   str(42)
来源：http://dali.tanke756.top/Article/details/gtemtzsnjx.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gteqlspohv.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gthhjodsex.html

TS:   String(42)
来源：http://dali.chenzaomai.com/Article/details/gtaymvgwqk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgfzy.top/Article/details/gtuwhzzdjh.html

Go:   strconv.Itoa(42)
来源：http://dali.ppjwa.cn/Article/details/gtnllholyq.html

Ruby: 42.to_s
来源：http://dali.sweek.top/Article/details/gtaqixafjn.html

C#:   42.ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtagejtnvt.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtyrogctwu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtusioxgxe.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258888.top/Article/details/gtrhfiezbx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtdrjcwoxq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cdnleiting.top/Article/details/gtjibnvezc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtdistiaot.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtgulndqlr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gtbmjohbmq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtsvgqdcwu.html

[A09] 绝对值与最大最小值
来源：http://dali.xuanzx.com/Article/details/gtmzetgfed.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtnpdocsur.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtvanmhdwa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtlaciptwo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtaxtodgxx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtduasrthz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gtlmkxydek.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ydzc1.top/Article/details/gtqzyzcwhc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtwncijyli.html

[A10] 生成随机数
来源：http://dali.zhengqikj.top/Article/details/gtqjblwugb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxinkj.top/Article/details/gtwafrcukp.html

PHP:  random_int(1, 100);
来源：http://dali.9152youxi.cn/Article/details/gtqusdxlri.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtgguyjrqm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtywehbkix.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gtqgoohbow.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hywenlv.cn/Article/details/gtzrewmuap.html

Ruby: rand(1..100)
来源：http://dali.zhongyouzk.top/Article/details/gtnwbiyzdm.html


<!-- 参考信息 -->