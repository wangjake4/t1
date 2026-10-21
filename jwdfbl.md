代发 wailian999

[U63] PHP：文件读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxncftbvc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gttwfowzvw.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gtdsfyjxhj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sxryk.cn/Article/details/gtpxxauyuo.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtnczzbvxe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtbqkaggpq.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gtyeoineti.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gtxzlonyae.html

[U67] PHP：处理文件上传
来源：http://dali.fzhhl.top/Article/details/gtaewowvbv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtlngpnyns.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gtgvjhyrdf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gtsupadxdm.html

[U69] PHP：PDO 预处理
来源：http://dali.yonumen.top/Article/details/gtvbihxdrr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.redwolf501.top/Article/details/gtmrgmqdpk.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gtdyibvzqt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gttitklnxt.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gtvzahdosu.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gttcvrbjgd.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtkeqskauf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtryglgceo.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtawwsquhg.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gtuespjcsj.html

[U74] PHP：读取环境变量
来源：http://dali.yongpay.top/Article/details/gtjtbrstdh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yanxiufei.cn/Article/details/gtmbvjkvpd.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gthilkhzsk.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gtqxfbhela.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gtqwzoprtm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gtwsdrtluo.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtvfxsxcrc.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtwjctrfnb.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtxnepksif.html

composer require --dev phpunit/phpunit
来源：http://dali.jlsjyb.cn/Article/details/gtzuyycyyy.html

[U79] PHP：静态分析
来源：http://dali.chenzaomai.com/Article/details/gtekdvpkqj.html

composer require --dev phpstan/phpstan
来源：http://dali.xuanzx.com/Article/details/gtifsqcyxc.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gtxlrfjjdt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gtuoqhgwud.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtsteuggbk.html

npm init -y;  npm i express
来源：http://dali.yvedp.cn/Article/details/gtzvajuzie.html

[U82] JS：package.json 脚本
来源：http://dali.wangdashe.top/Article/details/gtpnzwdqxv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258.top/Article/details/gtxzslbwov.html

[U83] JS：ES Module 导入导出
来源：http://dali.cashguo.top/Article/details/gtrjcnnymc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtkejeacqk.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gtzdxozbkc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gtbcvrsvly.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gtvzzsumoh.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvfeupct.html

[U86] JS：空值合并
来源：http://dali.ydzc1.top/Article/details/gtqakyybra.html

a ?? b
来源：http://dali.daxiang520.top/Article/details/gtmnmtlqlj.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtmqguujoa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gtrkqdiukt.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtfafdokek.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtvnecvmwt.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gtynyqaeyk.html

[...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtsjehrhxo.html

[U90] JS：数字数组排序
来源：http://dali.jinqigufen.top/Article/details/gtvmeaiknj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtqsvggses.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtkdwskjfp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuetiantiany.cn/Article/details/gtweqcsmnu.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gttvujoxaj.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtlrsfvfkz.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gtnlpyqfad.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gtudedpzsd.html

[U94] JS：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gtpgnaduea.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtmtimicnn.html

[U95] JS：Promise 包装
来源：http://dali.dianchejie.cn/Article/details/gtzkqbabhp.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtoiclowem.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtplecsrym.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtzoqxdnes.html

[U97] JS：并发请求
来源：http://dali.wangdashe.top/Article/details/gtxmxongys.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtzrwlahxi.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtstxzxgir.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gttazgaskh.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtgsnyvzaj.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtwetxqwqo.html

[U100] JS：DOM 查询
来源：http://dali.gaohongyu789.top/Article/details/gtjqsxckeo.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gtuigthjdu.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtutcfibda.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gtmsxexgzu.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtozoxquxr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhongyouzk.top/Article/details/gtylvftxki.html

[U103] JS：定时器
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvjggxzv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gtfgbjrvjj.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtyurrsnkn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtinygznuk.html

[U105] JS：节流
来源：http://dali.bjfxy.top/Article/details/gtoqawzbqu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtxdsabezb.html

[U106] JS：日期格式化
来源：http://dali.yj20258.top/Article/details/gtsezsmfbc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gtsnhxjasu.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gtuwsyfnqe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtdgurkmbc.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gtldbqxeya.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ppjwa.cn/Article/details/gtpieoqadd.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gttlpjemhl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtytsknpml.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gtealrwwed.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gtsoeutvyu.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtnwqxsvee.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtwyhyuuoa.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtuguupbmh.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtnxazszna.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtzbojnzza.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtpgzrmhzs.html

[U114] JS：JSON 深比较
来源：http://dali.yj202588.top/Article/details/gtmglrgstk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtkhopjzwx.html

[U115] JS：生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtmryhdgba.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtjutaqqnw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gtmqtxfhil.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvpwjdwx.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gtseuqnctt.html

npm i -D vitest;  npx vitest
来源：http://dali.sxryk.cn/Article/details/gtrlhfpwla.html

[U118] JS：开发服务器
来源：http://dali.316326.xyz/Article/details/gtitpdqmvw.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtqwmsmnfz.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gtqzyfosoa.html

npx vite build
来源：http://dali.xinyue.icu/Article/details/gtvnojwwnp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gteuqkdzhh.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gtqrbfqvsc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwimbmcqb.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtuxgajhxj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwjaiqeat.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gtvlsknggt.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gtrdhacwfr.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtlaeuiric.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gtajaqhciu.html

TypeScript ..... 212
来源：http://dali.zhongyouzk.top/Article/details/gtsmvuwoky.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gtnovszxjd.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtkymyldve.html

Ruby ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtdlennqnp.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupstjkew.html

C .............. 30
来源：http://dali.guowangkeji.top/Article/details/gtfywjkqns.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gtgvbsplds.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtpjsdgjvq.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtizpyqahn.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gtqvbgdbls.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtganhynfj.html

Lua ............ 10
来源：http://dali.xuanzx.com/Article/details/gtpowzuzvw.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtmzawteqa.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtttoagwta.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtyvgtghcq.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtskpifgfs.html

按章节统计：
来源：http://dali.shanyushiyangtech.top/Article/details/gtecramfez.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtnhvogcme.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtepnubqqn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtlxqztrve.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtllkuwtle.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gtvkihnbdz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtfikjxdjv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtnjhhccbm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zycfv.cn/Article/details/gtigjhbwza.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtwuablekk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gttdnmeytr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtlygdcbgd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtridhwcag.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtwgnspcue.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtbeztcwew.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtikypimxe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtettmgftr.html

Q SQL 专题                              90
来源：http://dali.xuetiantiany.cn/Article/details/gtzavnceaj.html

R Bash 专题                             80
来源：http://dali.birdmap.top/Article/details/gtavevmuok.html

S C / C++ 专题                          60
来源：http://dali.jinqigfzy.top/Article/details/gtjfthsrlo.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtesdgtzdk.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtuhjjydqx.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtwpbtcnxk.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtuwqmquji.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtqkaozajy.html

使用提醒
来源：http://dali.gogol.net.cn/Article/details/gtbjtcciym.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtyuuiumeh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtabamiuud.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gtrvpkfjts.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtsyvvnjya.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtmjvgdwlh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.316326.xyz/Article/details/gtjnbjfwpr.html

—— 文件结束 ——
来源：http://dali.mhx1999.top/Article/details/gtzbijcily.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvljppqmc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gtniffalfq.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gtyrdxtydx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjsucfqxw.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gtcfmsoqjz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gtaaugudgx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gtamhystrc.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gtaogxrrlj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gtrkbuyrtr.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gteziprrea.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gtkcqwvlyd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zdqjudy.top/Article/details/gtfegucpoj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cqqwz.cn/Article/details/gtvnogmmdm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gtsacfczzr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtvltkuhke.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinqigufen.top/Article/details/gtqqplyzna.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvvcvtle.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gttycscewg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gturgfpjwz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sxryk.cn/Article/details/gtcmseufna.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gtsmllyczf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gtapeitzcs.html

【文件统计】
来源：http://dali.birdmap.top/Article/details/gtzpxgqgpc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtnkxhbwwe.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtdrdbousc.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtmvvcdxec.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtezjnteyu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigfzy.top/Article/details/gtvuesgeca.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtfpowlmat.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtrskxydwv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtqkdddhrc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aibaodan.cn/Article/details/gtdrszakso.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtrllooxut.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtfyjttjrw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobmelrrj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtnbffvwor.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtxpaazbwt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtsfvphlgd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtzmjgzydm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtbfjvwbaf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtciamogbd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gtaonprxcc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtcstmorqn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtazqpgtok.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtnorefcom.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtsszeqbwx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtpowhunvh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258.top/Article/details/gtjlvczndn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbzudnuqw.html

A. 基础语法与类型
来源：http://dali.gotoacloud.top/Article/details/gtjctmsork.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgpgiwamb.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtveserlds.html

Py:   print("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvacitcnt.html

PHP:  echo "Hello, World!";
来源：http://dali.cashguo.top/Article/details/gtwcwsdeer.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gthszjrpmx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtqjjrkqkk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbriddzoa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtbdaiofoj.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtrszmrvzy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtcysvtird.html

[A02] 变量声明与赋值
来源：http://dali.c1oappe.top/Article/details/gtkounofqj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtaqkuxjpa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtgczjkipi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtpjwcnxkg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.fengsongda.top/Article/details/gtbgatpsqn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtahdhqieb.html

Go:   name := "Alex"; age := 20
来源：http://dali.xziqi.cn/Article/details/gtlycmfyku.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkwahfrl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gthtquticx.html

[A03] 常量定义
来源：http://dali.zdqjudy.top/Article/details/gtotnhapmy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gtmvibaqgl.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtnpywfnaw.html

JS:   const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtekwpzpam.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtgpezibjg.html

Java: static final double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtgruwomrd.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtbgkozvvh.html

Ruby: PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtpisxowfj.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtzxsdsqob.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtrogogcez.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cucudq.cn/Article/details/gtxpbyqiam.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangdashe.top/Article/details/gtungwtmce.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtdvcgrbih.html

TS:   typeof x; x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtthhfnxfd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtwjtllwje.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gtykzskiof.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.quarkkingdee.top/Article/details/gtywwsqsvv.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gtmnvnmbek.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gtakcevazl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuxming.cn/Article/details/gtsgjhvgtg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtycvjogvw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gttmkqdqso.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gteungnfsl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtunfusmbl.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtfanagtto.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtqwlehemm.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtgklvmzeo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtbgrurcou.html

Py:   int("42"); float("3.14")
来源：http://dali.tanke756.top/Article/details/gtxeerlruv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangdashe.top/Article/details/gtsgclyoft.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtgrtoxbjd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258.top/Article/details/gtiokjgsvh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtdzbygssc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfzrvgwk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ppjwa.cn/Article/details/gtlcsriejw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangdashe.top/Article/details/gtudvozezp.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gtdgaryxes.html

Py:   str(42)
来源：http://dali.birdmap.top/Article/details/gtokaujdvc.html

PHP:  (string) 42; strval(42)
来源：http://dali.dianchejie.cn/Article/details/gteeahnnts.html

JS:   String(42); (42).toString()
来源：http://dali.tianlin.xyz/Article/details/gtmmelzjhv.html

TS:   String(42)
来源：http://dali.jiagoushi.top/Article/details/gtdbypcrka.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtxzdryogr.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtozrpesot.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gtrkfkuulk.html

C#:   42.ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gttluebbhl.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gthbpgcher.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtrwntwtew.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aibaodan.cn/Article/details/gtgreqglgc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwqazarh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gtnxkkrzff.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtqeuwvexo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtypjhpeec.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gtovbcfugo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtxosrhonx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtslvcujus.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiljjwnx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydujynbn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtwyhgllqv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtgfquojum.html


<!-- 参考信息 -->