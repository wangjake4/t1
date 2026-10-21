代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.smart0.xyz/Article/details/gtpjlyqgum.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gtippbihau.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtyjsqvvkk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xziqi.cn/Article/details/gtpucmiddt.html

[U69] PHP：PDO 预处理
来源：http://dali.yangfankeji.com/Article/details/gtswxxbuqe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gthoucewrq.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gtniecmrer.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gtezaleioz.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gtbngtpncf.html

throw new RuntimeException("失败", 500);
来源：http://dali.jiagoushi.top/Article/details/gtkwjwoqkl.html

[U72] PHP：写错误日志
来源：http://dali.chenzaomai.com/Article/details/gtyyqlwdwk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gtjupqimij.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtitdrriuj.html

parse_ini_file("config.ini", true)
来源：http://dali.aizwys.cn/Article/details/gtfdaxmqlq.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gthufiguyr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gtosszpelp.html

[U75] PHP：依赖注入
来源：http://dali.cucudq.cn/Article/details/gtjvzwptxo.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtpwtyxfzv.html

[U76] PHP：简单路由
来源：http://dali.vqdsnc.cn/Article/details/gttojfqhuu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gtmuddelrx.html

[U77] PHP：模板渲染
来源：http://dali.yuxming.cn/Article/details/gtodourpjy.html

composer require twig/twig
来源：http://dali.gzhubu.top/Article/details/gtniaguufl.html

[U78] PHP：单元测试
来源：http://dali.tanke756.top/Article/details/gtixzwwith.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gtajfsqxih.html

[U79] PHP：静态分析
来源：http://dali.iojbl.cn/Article/details/gtwhdqtjhk.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtkzwpzrta.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gtgebwxinc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gtzifvcdsd.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gtsvauqfjm.html

npm init -y;  npm i express
来源：http://dali.gaohongyu789.top/Article/details/gtwrjluetp.html

[U82] JS：package.json 脚本
来源：http://dali.meibo888.top/Article/details/gtyejnrmsc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gtxiekwnzr.html

[U83] JS：ES Module 导入导出
来源：http://dali.sweek.top/Article/details/gtxfligpsf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtmiwihhpe.html

[U84] JS：CommonJS 写法
来源：http://dali.hnqzz.top/Article/details/gtsvljfouz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shangyingyoupin.top/Article/details/gtmckhpvcx.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtujheaggw.html

a?.b?.c
来源：http://dali.haohaochexian.top/Article/details/gtfccnntey.html

[U86] JS：空值合并
来源：http://dali.0kj1m.cn/Article/details/gtfydrumqb.html

a ?? b
来源：http://dali.jqgfzy.top/Article/details/gtcabgtzuo.html

[U87] JS：解构默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtktnjuedw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gtnaarertt.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gtxaanhczs.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzxtxjum.html

[U89] JS：数组去重
来源：http://dali.jianghu66.top/Article/details/gtvayqwosf.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtkiqzyhfc.html

[U90] JS：数字数组排序
来源：http://dali.fengsongda.top/Article/details/gtapnmkgzi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtqipjqgfc.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gthnissulo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daxiang520.top/Article/details/gtlzjgqdjo.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtdjodfqup.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtykavqosg.html

[U93] JS：模板字符串
来源：http://dali.xziqi.cn/Article/details/gtmifbhipy.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gtgxavtheh.html

[U94] JS：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtbcsrgdky.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gtudpfzhnt.html

[U95] JS：Promise 包装
来源：http://dali.hysaishi.cn/Article/details/gtnvioziuu.html

new Promise((resolve, reject) => {})
来源：http://dali.snrcjt.cn/Article/details/gtwjqrycps.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gtdtslnxcf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gthqafxrxa.html

[U97] JS：并发请求
来源：http://dali.mhx1999.top/Article/details/gtyjmwkgld.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtylhqmxyt.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtkvwavhkm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gthdsqpnyz.html

[U99] JS：事件监听
来源：http://dali.gzhubu.top/Article/details/gtfjzxhteb.html

el.addEventListener("click", e => {})
来源：http://dali.yanxiufei.cn/Article/details/gtqelephst.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gtlxsysmla.html

document.querySelector(".item")
来源：http://dali.jiagoushi.top/Article/details/gtanzgrglt.html

[U101] JS：classList 操作
来源：http://dali.nwbrower.top/Article/details/gtdmfaqbgb.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtotmnizpz.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gtxwppibzb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtlzirzqcw.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gtocwiuxis.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhiwuduotai.top/Article/details/gtoigrcjop.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtkboitljl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtzxlsyfdz.html

[U105] JS：节流
来源：http://dali.xuanzx.com/Article/details/gterapoxpq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtikatqlte.html

[U106] JS：日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtsgdnkvud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtzeaglzxo.html

[U107] JS：数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtmxxnvpym.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtyzlshoie.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gtiareivhm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cashguo.top/Article/details/gtozgnzrdu.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gtcpblsjrq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtcqmzjbik.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gtormsiunn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtqibsaeod.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gtoaxosiya.html

new Map(Object.entries(obj))
来源：http://dali.yongpay.top/Article/details/gtpxzkvhuz.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gtzbjislal.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtrxtfudoa.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtbffychvj.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtinnarhrw.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtjjxcoicu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtqhhoydzq.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtqawatlsv.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtlxtdzkta.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtappwgsew.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gtmreuteva.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gtgymilvfw.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gtjawhivpi.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtdwxtbtbf.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gtfrmfafvz.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gtiegnfnhb.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtieveaqsd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtpdjjlhjg.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtozlgdzez.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwnehwmvb.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtacoznrhp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyorljflu.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtziedqrtm.html

Python ......... 252
来源：http://dali.yvedp.cn/Article/details/gtodvyjyzc.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gtpcfxjgcg.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtomdwyafe.html

TypeScript ..... 212
来源：http://dali.yj20258.top/Article/details/gtcwfruosu.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtnzuaxapn.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtvnutfoik.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gtczyxomzd.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtbibogukg.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gtssfvohkm.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gtzbbdfcay.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtjotwgxkv.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhhukgex.html

Kotlin ......... 15
来源：http://dali.316326.xyz/Article/details/gtjdbjfujj.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtdhkneidn.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gtmrerghux.html

Perl ........... 10
来源：http://dali.quarkkingdee.top/Article/details/gtryroncqi.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gtqrlplqhb.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gtalgjofpf.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtzosbaqus.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gtonrvarhm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gthwciinzh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtktupyuol.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzovwuyb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdzhvgvl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gtmecydzjf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtunpzdyqg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtnkqsuaqf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gthccopbbv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtmxtrdpkt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gteszitdcd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtpdqikfkd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtoogutrlv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtarnnnuac.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtxjnisahq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.iojbl.cn/Article/details/gtxinojkcf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gttcbtxnfi.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gttrempzci.html

R Bash 专题                             80
来源：http://dali.zdqjudy.top/Article/details/gthcefjebj.html

S C / C++ 专题                          60
来源：http://dali.dashuyun.cn/Article/details/gtocgwvppx.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtxoyldxmz.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbglgzar.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtrxwkpvcn.html

合计                                  2106 条
来源：http://dali.sysykeji.top/Article/details/gtnvxemhdu.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gteodjrdhr.html

使用提醒
来源：http://dali.zhengqikj.top/Article/details/gtoitgfyku.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtddgzbebc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtlqzwhhgl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gttndvnayn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hongshengwenyu.top/Article/details/gthmqhxubf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gtkzfseorc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gtirscvvsg.html

—— 文件结束 ——
来源：http://dali.9152youxi.cn/Article/details/gtuiwpxzle.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbnfudiml.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cheryme.top/Article/details/gtrjnmbibm.html

Common Programming Examples Cheat Book
来源：http://dali.redwolf501.top/Article/details/gtaewquetb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfmjfhbxs.html

【收录内容】
来源：http://dali.jinghuilouyu.cn/Article/details/gtopxsnthk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gtttqjongk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gtbicxuzjq.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gtncsstcip.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gtjapcladu.html

【使用说明】
来源：http://dali.meibo888.top/Article/details/gtdvnwtenn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gtmajzphlh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoceixdr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pycfn.com/Article/details/gtvldemkzw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gtfnmyuxxw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gtebvbilyt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gttnaxueeq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gtjenumafk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.0kj1m.cn/Article/details/gtzqjzkewr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtnaqryrgg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tanke756.top/Article/details/gtyxzzljgr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gtqiatwxkk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gtathripjs.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gtnegxmqgt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258.top/Article/details/gtcjtrrvvk.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtttjnytfn.html

目  录
来源：http://dali.9152youxi.cn/Article/details/gtmpiqoedx.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtrhrdquae.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtnqaoimkd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtlbhsycer.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtsoxkbdic.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtsqjdoszh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.meibo888.top/Article/details/gtyqhyvwfi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtmkudeyfa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtdbssnlbd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtfofrubbs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtgpxfqocy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtvbvkvhtd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtnvnpbruq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtvdgxfbnh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtizylplyo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gtcekmquli.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pycfn.com/Article/details/gttbmafxxi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtgrygaifo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gthorysqbm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gtdlhpisfs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnxiangtu.top/Article/details/gtjcdwlvky.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gtjwubzhcz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtqpjklpkp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsxqixbwq.html

A. 基础语法与类型
来源：http://dali.zhixingplan.top/Article/details/gtoskahmhi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthdxxgflq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtdjrjognj.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtshupdjqu.html

PHP:  echo "Hello, World!";
来源：http://dali.xziqi.cn/Article/details/gttqbflaqf.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtcxytedyb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtzqiwwtmw.html

Java: System.out.println("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtiigubvbj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtoedwhiez.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gtjouduisv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtqrjfiqdo.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gteedsytub.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.vqdsnc.cn/Article/details/gtmcnvcsfy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtsbzltnzi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtwtiiwjfw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnqzz.top/Article/details/gteeturhjj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtrnmheszp.html

Go:   name := "Alex"; age := 20
来源：http://dali.xylfe.cn/Article/details/gtanbkcbso.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoewycaqb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gtryoltenj.html

[A03] 常量定义
来源：http://dali.jyoumei.cn/Article/details/gtgxwapixs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.snrcjt.cn/Article/details/gtkttvmtys.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtsbnaqbrh.html

JS:   const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtiasjywbu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gthtpiwjqi.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtisdrvnem.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtbrsybknp.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtexcskqrl.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gttkzknoyf.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gtudxnzlqo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sweek.top/Article/details/gtcwklijin.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtktvgxabm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtzqridnnb.html

TS:   typeof x; x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gtfnazpcov.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gtjroahgiq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgufenzy.top/Article/details/gtxjubinbf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jiagoushi.top/Article/details/gtnsabxstj.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gtlzuicrab.html

[A05] 整数除法与取模
来源：http://dali.zdqjudy.top/Article/details/gtfpqsvqrb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sysykeji.top/Article/details/gtdzrftwlj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtinswyqgq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydocsdpo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtsyigwsfy.html

Java: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gteifswdub.html

Go:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtgsgcfqgc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtsaylyjjl.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtexeaqeou.html

[A06] 字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtwupwrkco.html

Py:   int("42"); float("3.14")
来源：http://dali.yangfankeji.com/Article/details/gtdvnnwmri.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.c1oappe.top/Article/details/gtlvymjwov.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fzhhl.top/Article/details/gtxqjaobff.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.316326.xyz/Article/details/gtofsqqwxv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtpoymzhor.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shuidangran.top/Article/details/gtnciwakyi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.redwolf501.top/Article/details/gttcbqxmmd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtxsnfozxc.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gtjxleawni.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gtenumbteh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhoulong.xyz/Article/details/gtjquwcdng.html

JS:   String(42); (42).toString()
来源：http://dali.zhengqikj.top/Article/details/gtgqzuojrp.html

TS:   String(42)
来源：http://dali.hfpthk.cn/Article/details/gtwlruxxga.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nanxuanxn.top/Article/details/gtiqkrtpke.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gtdvxkhfzm.html

Ruby: 42.to_s
来源：http://dali.tian-w.cn/Article/details/gtjzeulcou.html

C#:   42.ToString()
来源：http://dali.yj20258888.top/Article/details/gtqopkcysm.html

[A08] 取整与四舍五入
来源：http://dali.chenzaomai.com/Article/details/gtxdckjxvg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtiepzmefs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gtofvjkbfq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtcktsfbcu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sysykeji.top/Article/details/gtmfhrgbmb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtsdipmhpk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gttrjobqhd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gtusghgmmv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtavgqvemd.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtvmvbqzez.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtiasjuqoy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtotdwrxdz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxaykzycu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtrgzcseem.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtuqypxpfo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.bjfxy.top/Article/details/gtjwesgcuq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenjidiqi.icu/Article/details/gtwbnvtnno.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtidbvjeva.html

[A10] 生成随机数
来源：http://dali.yuxming.cn/Article/details/gtnkvyzuir.html

Py:   import random; random.randint(1, 100)
来源：http://dali.mhx1999.top/Article/details/gtqmwlqhvt.html

PHP:  random_int(1, 100);
来源：http://dali.xinyue.icu/Article/details/gtqcrgcqme.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtfeulkzrn.html


<!-- 参考信息 -->