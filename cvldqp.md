代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.xziqi.cn/Article/details/gtgxfflbig.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hfpthk.cn/Article/details/gtmmfjyiss.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gtmhunjvss.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gtybtaqyax.html

[U71] PHP：抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtrllvjxsw.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtnljarupq.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtpxbdswxp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gtxjzqtzpm.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkcvjela.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtczqhvofp.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtiwkzkyzm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtqnwiwiix.html

[U75] PHP：依赖注入
来源：http://dali.hnqzz.top/Article/details/gtlruojxjk.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtvammbytu.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gtojwkanyv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtdqhmcwmg.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtcxikesxq.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gtiowxdalj.html

[U78] PHP：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtynwmslxp.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtoqmfbudv.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gtuyuzwkms.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtbaxikskr.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gterqzyndq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gteomckrpv.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgtmykxw.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gtaisoabrp.html

[U82] JS：package.json 脚本
来源：http://dali.iojbl.cn/Article/details/gtacnnzaaj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhengqikj.top/Article/details/gtygmkejrf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtnewwqzhn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtgpfaccmt.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gthnwptlsz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gtuirhgzda.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gtsxmiwnhd.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gtxujtdruw.html

[U86] JS：空值合并
来源：http://dali.yuanzhike.top/Article/details/gtrueeovbp.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gthsmhimar.html

[U87] JS：解构默认值
来源：http://dali.9152youxi.cn/Article/details/gtgumrijyt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhoulong.xyz/Article/details/gtzgeudeph.html

[U88] JS：对象展开合并
来源：http://dali.fengsongda.top/Article/details/gtqgxiapqy.html

{ ...a, ...b }
来源：http://dali.haohaochexian.top/Article/details/gtjheqoppj.html

[U89] JS：数组去重
来源：http://dali.pycfn.com/Article/details/gtthutvhbh.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtbkzqcsro.html

[U90] JS：数字数组排序
来源：http://dali.ybcxt.top/Article/details/gtxinnvqfm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtjoprzgrc.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gtsnffpwyg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yonumen.top/Article/details/gtquwfcqhu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtvciutcvm.html

structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnumcpswj.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gtquxcatrv.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gtnwifbcpr.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtrdbymuxg.html

const double = x => x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmuukmvb.html

[U95] JS：Promise 包装
来源：http://dali.vqdsnc.cn/Article/details/gtkzdyfpni.html

new Promise((resolve, reject) => {})
来源：http://dali.gzhubu.top/Article/details/gthuiqmkuu.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gtboyjxkja.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gttwcbtwmo.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gtdewtyvmb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtepalczox.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenlongwang.top/Article/details/gtdawrftyd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtejvnhaby.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gtasbqtvlo.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtaayeyalf.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtlootdk.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gtdhtmncvp.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gtrwzpixod.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gtgqpvfeii.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtupfgvexp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangshuangyany.cn/Article/details/gtddovtchc.html

[U103] JS：定时器
来源：http://dali.kuanghao11.cn/Article/details/gtoyrvrqtu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shangyingyoupin.top/Article/details/gtyqihksek.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gtnzqhabsr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtrthgfjpo.html

[U105] JS：节流
来源：http://dali.yuxming.cn/Article/details/gtqjyeudpq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gtzipmkkxp.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtkgoprjle.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.9152youxi.cn/Article/details/gtydnvkhim.html

[U107] JS：数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtzfmspzlp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtdvechoyg.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gtjlvosqzv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gtumuyxgil.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtlieaigsh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkkwxxcs.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gteddeetvo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtsxihztxy.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtynewjeju.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gtlezpqwpw.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtuxhmleaf.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtodjwsrqy.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtanqxjkoz.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtkasymhgy.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gtiuredfhb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtmfkayeev.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gterieiymo.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtfgciybhc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtmuicvuto.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gtlnevomow.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtuakwrbyx.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gtzajjwwif.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gtvrjioggl.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtfsretqve.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtjdyzxbbe.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtxzsesfil.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gtmpyzozpb.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gttrkljudi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsvstoblp.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gtqvtwkeiv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlcgognni.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtnbaidgmt.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gtfhedqslb.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gttuhdgoro.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gtagpsobpi.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gtxvaegzhb.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gtedsimifo.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtihggquae.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtsdbmodso.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gtqiqcudqe.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gtehqduabl.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtrnjwekzx.html

SQL ............ 90
来源：http://dali.xziqi.cn/Article/details/gtqdkfekxw.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gtkkvfmttw.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gtdohcnjbm.html

Swift .......... 15
来源：http://dali.gzhubu.top/Article/details/gtrurwesxz.html

Lua ............ 10
来源：http://dali.feifeiyinyue.top/Article/details/gtogifwcru.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gtbfwtxliw.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtjzzhmyjb.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtlpfohlmx.html

合计 ........... 2106 条
来源：http://dali.shzxlz.cn/Article/details/gtwgkkvzyd.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxpqchek.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gtxzrhckqe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtdmmcjipa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtidgqyogb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtpvqobfrs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gttfphbntj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtomyfyhlh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtgwzvzwco.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtqhjcwefd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtsnctqrwg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtfmqttyqc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gttpoznceo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtragrddxa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtdyokjvhu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtaejegwrv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtmgxchfbw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtopybttld.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gtfcculfor.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gtiexgewsy.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzaiizga.html

T 其他语言补充                          60
来源：http://dali.tanke756.top/Article/details/gtqnpqfznf.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gtikahnuoo.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtxmfqahiv.html

合计                                  2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtpmpsmnmd.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtuprjpyzp.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gtieqdpqyb.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtiazqdzjk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shangyingyoupin.top/Article/details/gtwbdgkgnj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.quarkkingdee.top/Article/details/gtegqzvpqz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hysaishi.cn/Article/details/gtyyztuust.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gturaqvabp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtozcesede.html

—— 文件结束 ——
来源：http://dali.xziqi.cn/Article/details/gtygytfnuu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtltxwwzap.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gtlbcvkfvr.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gteqaxcqxq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpmueozip.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwkaoamx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cdnleiting.top/Article/details/gtudseqssl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtssfnhsus.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtkzewsqzi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtlqojjhda.html

【使用说明】
来源：http://dali.c1oappe.top/Article/details/gtwtrgttfu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guowangkeji.top/Article/details/gtrgvcqovg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gtbkzoiglc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gtlswadwzm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gtowlgvtrr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtismiijqu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangdashe.top/Article/details/gtdqnoatyq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yongpay.top/Article/details/gtyjzgbtpp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtcrdygnus.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gotoacloud.top/Article/details/gtrypfrtyu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zdqjudy.top/Article/details/gttxykivhj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gtxewcfcly.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.andypj.xyz/Article/details/gtyxxrgjrz.html

【文件统计】
来源：http://dali.guowangkeji.top/Article/details/gtwzwxsjwg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hysaishi.cn/Article/details/gtubxfmuyr.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtfnzbqmqk.html

目  录
来源：http://dali.yuanzhike.top/Article/details/gtngbpgjeh.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtxbcbgwlf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtlmamgvqx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtfirjpbom.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtckdjfjzf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gteglmxdpr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yonumen.top/Article/details/gtaxqpcevt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gtdpgtojzv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gtyswixwxu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtqtrapalg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtjxhqqqdn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtwqmbatxx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtbdkycgtx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtwiexumqa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtfiqfruuq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gtivufrptt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hywenlv.cn/Article/details/gtjqpawspf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtekwmpbso.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guannengcc.top/Article/details/gtsuxujvzr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtijrhzmvz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gthhicjzah.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtffuownjo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtatkqhrkw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthkoemsdb.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gtyqowmzjv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjotjgqk.html

[A01] Hello World
来源：http://dali.zdqjudy.top/Article/details/gtrjcmzgwf.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtliqmjyzj.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gtsaqlllwj.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtvyhlnpsj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gtoclemkiw.html

Java: System.out.println("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gthmylftpk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtuilhcnnn.html

Ruby: puts "Hello, World!"
来源：http://dali.pengpengdd.cyou/Article/details/gtvxuxhcok.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtplrfaisz.html

[A02] 变量声明与赋值
来源：http://dali.meibo888.top/Article/details/gtvgxdrstv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gtcdghqnwk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cucudq.cn/Article/details/gtrgmmiygk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuxming.cn/Article/details/gtxsrbiigb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtxqeduvry.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtlsgowtjg.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtytefuocl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gtydmrhqff.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gtqouhdolx.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gttsrekont.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.feifeiyinyue.top/Article/details/gtlsdchakj.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtthbdqneb.html

JS:   const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtixgdafqe.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnvhqifw.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtutqbhduu.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gtpvzjixsm.html

Ruby: PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtayjkhwre.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtzjvwhdfw.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdquanru.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gtwessmgwz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zycfv.cn/Article/details/gtjpinuwqj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtsefzcmgw.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzbsxbgd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cashguo.top/Article/details/gtbdpdwycg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfkdcotr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jiagoushi.top/Article/details/gtiqfedcuz.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gtwewquqxh.html

[A05] 整数除法与取模
来源：http://dali.0kj1m.cn/Article/details/gtzvwmmhuz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gtuszzsqvs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtwyfdmljd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtmqryupkn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtaycvuhxs.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtfemkokeb.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtfrdmlzdr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtgoscmmtn.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtckqnpvxe.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtyyrpgsze.html

Py:   int("42"); float("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtnvgnszsb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258888.top/Article/details/gtmizgahhx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafjtrcal.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gtmyukgjno.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtifdrfswv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yongpay.top/Article/details/gtpmasulgp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.svipenyu.cn/Article/details/gtdyvkqkmd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtzpnttowx.html

[A07] 数字转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtqpcgxott.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gtlqfluknq.html

PHP:  (string) 42; strval(42)
来源：http://dali.tanke756.top/Article/details/gtdcmjcwmu.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gtuvwexjkr.html

TS:   String(42)
来源：http://dali.zhixingplan.top/Article/details/gthoebatow.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxuanxn.top/Article/details/gtndzjvube.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gtlvmcwwpd.html

Ruby: 42.to_s
来源：http://dali.zhengqikj.top/Article/details/gtnfssybde.html

C#:   42.ToString()
来源：http://dali.sysykeji.top/Article/details/gtivkldfai.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gtlafxcijo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gttakqzomc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gtfvphdnbh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtqyhrhkia.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gtrgailhgs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtalahtjdd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtpfbpfdln.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tanke756.top/Article/details/gtoxfonayu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtflmiaclt.html

[A09] 绝对值与最大最小值
来源：http://dali.xylfe.cn/Article/details/gtrfnjlfiy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobgatwij.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwkgptkkj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtuqthdwni.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtrktkehuw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gtbnmvafdy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tanke756.top/Article/details/gtyavpasjv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.guannengcc.top/Article/details/gtodegcsrp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtcgadjojf.html

[A10] 生成随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxmftbsp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.andypj.xyz/Article/details/gtvpvyhstq.html

PHP:  random_int(1, 100);
来源：http://dali.yuanzhike.top/Article/details/gtslpfvtyg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtppgergdg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gtjwpshbxf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqmjgwud.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yvedp.cn/Article/details/gtuxlaqkvc.html

Ruby: rand(1..100)
来源：http://dali.zhixingplan.top/Article/details/gtklakyexe.html


<!-- 参考信息 -->