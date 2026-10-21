代发 wailian999

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gtfnqxdjil.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtdpcshwdm.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gttlhjhjou.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamirrstp.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gttkypksqz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtxskcbvhi.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtdydbjsba.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenzaomai.com/Article/details/gtyfjwpqjw.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gtneoepclg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gtcohfjljq.html

[U70] PHP：PDO 事务
来源：http://dali.0kj1m.cn/Article/details/gtrygovrzl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gtsnxgeixy.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtookjwwos.html

throw new RuntimeException("失败", 500);
来源：http://dali.gotoacloud.top/Article/details/gthzgldxbw.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gtsjnlypcu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gtmsiltjzb.html

[U73] PHP：读取 ini 配置
来源：http://dali.jyoumei.cn/Article/details/gtiodcnacz.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtwpmkynbw.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnqvvipf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtdzkatsda.html

[U75] PHP：依赖注入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybmayeje.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gtzvenekaj.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gtvbiqroet.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gtaouhlhym.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtkppmxrip.html

composer require twig/twig
来源：http://dali.yuxming.cn/Article/details/gtgmxrbdqu.html

[U78] PHP：单元测试
来源：http://dali.gzhubu.top/Article/details/gtdrhosiiv.html

composer require --dev phpunit/phpunit
来源：http://dali.yanxiufei.cn/Article/details/gtupmugyys.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gtotqojxym.html

composer require --dev phpstan/phpstan
来源：http://dali.wangshuangyany.cn/Article/details/gtkhwfirao.html

[U80] PHP：代码规范修复
来源：http://dali.0kj1m.cn/Article/details/gtqsybmmxo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gttnierdei.html

[U81] JS：初始化项目
来源：http://dali.cucudq.cn/Article/details/gtazmoydfh.html

npm init -y;  npm i express
来源：http://dali.yj20258.top/Article/details/gthdspdsmn.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gtomksnqns.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuanzhike.top/Article/details/gtaixivjxs.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gtlfyzccwu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtqhwfauxc.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gtvtkctswi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tianlin.xyz/Article/details/gtzfmwbpef.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtucngmfrq.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gtgksvwcdg.html

[U86] JS：空值合并
来源：http://dali.shuidangran.top/Article/details/gtibprnnna.html

a ?? b
来源：http://dali.dianchejie.cn/Article/details/gtdymdhlge.html

[U87] JS：解构默认值
来源：http://dali.quarkkingdee.top/Article/details/gtheesyzdl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenjidiqi.icu/Article/details/gtmmtkkvfa.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gttitelcgj.html

{ ...a, ...b }
来源：http://dali.sweek.top/Article/details/gtjvcveoay.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtlzocswfx.html

[...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gthdyntaeg.html

[U90] JS：数字数组排序
来源：http://dali.chenjidiqi.icu/Article/details/gtkasvlzos.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gthgisgubz.html

[U91] JS：对象键值遍历
来源：http://dali.gzhubu.top/Article/details/gtwdfhsxkv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuanzx.com/Article/details/gtelaiytse.html

[U92] JS：深拷贝
来源：http://dali.sweek.top/Article/details/gthwysvuta.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gthwmymsrv.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gtnavxshju.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gtwlemeoqu.html

[U94] JS：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtfpztzkdl.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gtdsaufrgj.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtdwdryknh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlzsbsec.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gtqhygctrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtspgvefbf.html

[U97] JS：并发请求
来源：http://dali.wangshuangyany.cn/Article/details/gtevdwzedt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwapiakx.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclsvnzky.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gttyxworwr.html

[U99] JS：事件监听
来源：http://dali.yj202588.top/Article/details/gtqbvsmssl.html

el.addEventListener("click", e => {})
来源：http://dali.gaohongyu789.top/Article/details/gtyljztgeu.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtprvumuwh.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxhutulj.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gtrthnvtjo.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtwtmyiozx.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gtjluxiaoc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhiwuduotai.top/Article/details/gtokptqymd.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtzaozroac.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtuveghhmp.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gthwykxkmd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtwcgasplm.html

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gthwtiodjm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtpfijmlkr.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtapifoqqs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gtljrzzria.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqbrieaw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtwjrsgb.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gtbpmyrlso.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gtsejvyoki.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gthqxfxkmo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtltppzwji.html

[U110] JS：数组分块
来源：http://dali.jyoumei.cn/Article/details/gtcvbarejl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xziqi.cn/Article/details/gtmqsqvcgf.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtnblwxodj.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtrovszxud.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtdcxbhqhi.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtdralyops.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtgytofrsw.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtomsmgtnm.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gtrlejjlss.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtkctcuiuq.html

[U115] JS：生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtrjevxalr.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtejkxqgoi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shangyingyoupin.top/Article/details/gtjotirxxo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtkyltqhkt.html

[U117] JS：单元测试
来源：http://dali.hysaishi.cn/Article/details/gtbjujxnom.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtrdaxyhim.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gtzujnxunz.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gttnpccjhu.html

[U119] JS：生产构建
来源：http://dali.sufxvd.cn/Article/details/gtdlcrklbo.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gtiazcwvvg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gtbsvycess.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtaihhlmds.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqdaymcju.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtqlxajwur.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsnagkvsr.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gtrlonllzw.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtxvhoahxn.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsqbwvim.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gtyexasvsn.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtoiyffnxn.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtacxclxlb.html

Go ............. 212
来源：http://dali.hammf.cn/Article/details/gtidqopdzg.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gthyepxfgl.html

C# ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtzvcaoklb.html

C .............. 30
来源：http://dali.c1oappe.top/Article/details/gtvbjlijvk.html

C++ ............ 30
来源：http://dali.gaohongyu789.top/Article/details/gtxpwwfunq.html

SQL ............ 90
来源：http://dali.hnqzz.top/Article/details/gtekaztywy.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gtkmbnsoge.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtatgoboyd.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtvubtbdas.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtedliidav.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtmjzawkkg.html

Scala .......... 10
来源：http://dali.yj202588.top/Article/details/gtscufdtek.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtpklwsozf.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gtbhrptnrl.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gtfupkuvxi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtrarhkhhf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gttuvkfyok.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtznphmogd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtepdacnim.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gtolacsknx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtzbiprlit.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtjqvfrqnf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtxjpxgoqu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtgavytdce.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtlqppgtrh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtvvdtutds.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtuuwwcwrl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtwklzcuiz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtaooafmrj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtadjqgapt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtmfeelwxa.html

Q SQL 专题                              90
来源：http://dali.yj202588.top/Article/details/gtvfleahxe.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gtymwhdswh.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmxrvupf.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiojzrfb.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtykvgvdtb.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtdzurkfno.html

合计                                  2106 条
来源：http://dali.birdmap.top/Article/details/gtttvdamjn.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyphcjkob.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gtsjysvirv.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gthzsudceq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gtghkpnznr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ivvv.top/Article/details/gtruhzzpcf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gtrpfnluvg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhengqikj.top/Article/details/gtwwohgucp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jiagoushi.top/Article/details/gtytcaiava.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtyjbkmpgp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrqdimnjv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gthohlemmy.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gtugxpbpom.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwgrinkeg.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gttbsxmghl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtecmoblhd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gtccqumcwd.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gtegjdypru.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxinkj.top/Article/details/gtlmgrzzle.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gtkyknvgpm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.bjfxy.top/Article/details/gtmkxfcjfo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gtasdfjqdh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gtdpzrwraj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hongshengwenyu.top/Article/details/gtylmgyycm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gtbzbtylaq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.havefunace.top/Article/details/gtdxpsiyzt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.redwolf501.top/Article/details/gtoasdsapn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gtoljatddi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtkxczomov.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jiagoushi.top/Article/details/gtzuuwuyle.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gtqvjjjdae.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenzaomai.com/Article/details/gtpwftpxov.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gtvqjwpqmu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtovzeyeej.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtjetwamma.html

目  录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakvhfmpl.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtupuvmbtz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtxqdvvqrl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtyfyztave.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtuhexnevu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtlitukejf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgpyursgk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtjkkhhwzi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtnucajcnq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gtzqcnvdke.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtafflnkzq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gtuqrndvrg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gthvkonray.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtbdiqrotu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtloyfupxq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gtdoyzzpcq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gtvzpmpqqo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtlehsdpyj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.9152youxi.cn/Article/details/gtdjovefvz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnqzz.top/Article/details/gtvqzyiaom.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbmcpvyl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtjatkgzky.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtqdqfmwfz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvnemhgtk.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtblqdogxr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxuokckrf.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gtdkevedxm.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtfkyekozd.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtazmnkv.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtfggorrgu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pengpengdd.cyou/Article/details/gtqqappgwk.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtjobcrkra.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtaomizqcm.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gtofxzqfej.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdshgeelj.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtzikbdjlh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gtysjhxbpz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtxyledvtk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtbddqxxfm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gtfabppeut.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtjwkjmikv.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgipuedc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtrtckwrio.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtxxneopms.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtzbdvgqur.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tanke756.top/Article/details/gtmtugrdsf.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtguzdwhji.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtosmgnjxd.html

TS:   const PI: number = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtmfhjqwdx.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtosyzccnz.html

Go:   const PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gtpdvvmvsc.html

Ruby: PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtynllqwza.html

C#:   const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtyzxwxrgs.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosfvrmzs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtqyawcych.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gtywusxxjo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gtiiyhxxny.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtazsvdqsi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gtsewffvat.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgufenzy.top/Article/details/gtudgxveuo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gtxzncigly.html

C#:   x.GetType().Name; x is int
来源：http://dali.tanke756.top/Article/details/gtukdfxptb.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtolqbsawn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yueranfly.top/Article/details/gtedrdhjjo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtcrooroki.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtgdsdcdii.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtgcrtshta.html

Java: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtpueusqrx.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtedrrokjc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtblethvqh.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtycxihlsa.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtzsolgmhh.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gteoipgktu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuwvsspq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhongyouzk.top/Article/details/gttdqtqjdn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yueranfly.top/Article/details/gtmoufeggr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtrbtblrla.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gthvagpuvg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gzhubu.top/Article/details/gtodfkvvin.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gtheeiykyy.html

[A07] 数字转字符串
来源：http://dali.tianlin.xyz/Article/details/gtuauwrhsx.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gtbzkrnnan.html

PHP:  (string) 42; strval(42)
来源：http://dali.birdmap.top/Article/details/gtqfhabgby.html

JS:   String(42); (42).toString()
来源：http://dali.aibaodan.cn/Article/details/gtqpjitrgp.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gtgmzitzjp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.0kj1m.cn/Article/details/gtbkaydebe.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtwgdhdfaq.html

Ruby: 42.to_s
来源：http://dali.sweek.top/Article/details/gtmcgwdmol.html

C#:   42.ToString()
来源：http://dali.dashuyun.cn/Article/details/gtxcwkjsnh.html

[A08] 取整与四舍五入
来源：http://dali.tanke756.top/Article/details/gtzvjxzysh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtqbymiaeo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnroubprq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtgvghfggm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuanzx.com/Article/details/gtehkcklbf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtjyqiilrn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtuqcqzypk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.andypj.xyz/Article/details/gtaayscyre.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtjokjzwfz.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gtkpgilxow.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzazgsoxa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtcmmfmagh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtokjdhwil.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtwspwjnft.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtitvioona.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigufen.top/Article/details/gtuosnhgkj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.9152youxi.cn/Article/details/gtxhbmbauu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvkpnflz.html


<!-- 参考信息 -->