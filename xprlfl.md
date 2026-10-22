代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtnlcwarvz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuqjkiwc.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtwljpirwr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gthzlsqavc.html

[U65] PHP：会话
来源：http://dali.wangdashe.top/Article/details/gtwbdcicnu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrwuqwlb.html

[U66] PHP：设置 Cookie
来源：http://dali.havefunace.top/Article/details/gtxodnasud.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhzdegkc.html

[U67] PHP：处理文件上传
来源：http://dali.wangshuangyany.cn/Article/details/gtzznhhysh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gtjenikiuk.html

[U68] PHP：PDO 连接
来源：http://dali.iojbl.cn/Article/details/gtvdwvhptd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxuanxn.top/Article/details/gttfohsklo.html

[U69] PHP：PDO 预处理
来源：http://dali.xylfe.cn/Article/details/gttsopczgs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgqkhgrq.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdeygpuy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gtlcyozbbp.html

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gtsehzdzvr.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gtvshvtvyw.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtifbrzgks.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gtyhjlumxu.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gtcizuuoim.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gttzjdtryq.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtjbfaeadu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gtjzrmzkxd.html

[U75] PHP：依赖注入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvomeqqg.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gtacdrttyi.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gttmtayjoh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgfzy.top/Article/details/gtslvhjxsr.html

[U77] PHP：模板渲染
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtzitkvq.html

composer require twig/twig
来源：http://dali.aibaodan.cn/Article/details/gtbefiqynt.html

[U78] PHP：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtspbginpj.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gthtqxgnjl.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtbrsbxdii.html

composer require --dev phpstan/phpstan
来源：http://dali.yuanzhike.top/Article/details/gtyatylibt.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzygwdfwa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtssneoozu.html

[U81] JS：初始化项目
来源：http://dali.yueranfly.top/Article/details/gtdyeeegxn.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gtsfdnkibe.html

[U82] JS：package.json 脚本
来源：http://dali.cheryme.top/Article/details/gtolkhlxly.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gtvqfqpmjk.html

[U83] JS：ES Module 导入导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbutcwhu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtyjeyjnvd.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gttdzvssbj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gtvhstsfqp.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gtlivisatd.html

a?.b?.c
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpadlezm.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gtuhylwfnj.html

a ?? b
来源：http://dali.svipenyu.cn/Article/details/gtvjolxlko.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gtkckkodld.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dashuyun.cn/Article/details/gtnifeeqmv.html

[U88] JS：对象展开合并
来源：http://dali.andypj.xyz/Article/details/gtgdrqngoe.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtlxueqdmx.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gtsaeapfhe.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gttkwbabyk.html

[U90] JS：数字数组排序
来源：http://dali.andypj.xyz/Article/details/gttrwwzfqa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gthdvnvdow.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtkfmxsopb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gtovhxcyxy.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gtfstkpbte.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtqlttryxz.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gtqhufpprf.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtnckjnxch.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gthvdsfbtr.html

const double = x => x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtmmlwnxjh.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gtwomasquy.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gtiwclaiqj.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gtibqpapyo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtxunnwsmq.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtvgjdsqfr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtksuvlofs.html

[U98] JS：fetch 带 JSON
来源：http://dali.redwolf501.top/Article/details/gtyhffjuhy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gteuyugdcl.html

[U99] JS：事件监听
来源：http://dali.jinqigufen.top/Article/details/gtqkwnxqin.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalvlwfxw.html

[U100] JS：DOM 查询
来源：http://dali.kuanghao11.cn/Article/details/gtsveubvte.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gtmbzrtjjr.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gtkavtafbn.html

el.classList.toggle("active")
来源：http://dali.pengpengdd.cyou/Article/details/gtrdujngld.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gtgnrmhwmn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gthgnwmlze.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gtibktqfoq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtxziloqzb.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrdoswzm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtlwmwrmtv.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtoealdupr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtpwwrhrcj.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtcpgwqpht.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cdnleiting.top/Article/details/gtezosvtvd.html

[U107] JS：数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtxtligzgp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtrojniqes.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtjgjnxrfd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gtaoxooyjc.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gtddchfklk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtvyghluen.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gteksrxipo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtojxdtbdv.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gtzyojzxlf.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gttmmytnwk.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtgaychnta.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtuadbnuua.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gtrgnvslpw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtdfykamqt.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gtfhqrktxs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtmvkbwexg.html

[U115] JS：生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtqzwvaavc.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtxzjjaxxy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gtarrjnqrw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gtjoswajhr.html

[U117] JS：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtmlytgjzd.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtrzsiuuaq.html

[U118] JS：开发服务器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqbhgllj.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtzverwfvb.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gtxoueynvi.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtmwghuvsx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gtdhghgpgj.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gtfzwiiplf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvatzrjrx.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gtulcyahri.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudlaatqj.html

按语言统计（条）：
来源：http://dali.ivvv.top/Article/details/gtaixhotty.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnrxqmpp.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvhslyri.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gtdtbmuyoc.html

TypeScript ..... 212
来源：http://dali.fengsongda.top/Article/details/gtjaunctlp.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtbmvcvmln.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtjizvcleq.html

Ruby ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtdilaftme.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtjuxppqmh.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtcyzthkqp.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gtcjfbteau.html

SQL ............ 90
来源：http://dali.xziqi.cn/Article/details/gttautzmff.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazbwitzr.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gtdwqbcaag.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gtcchmoatg.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbywyreml.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtutkfhslm.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtfzdztaqj.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtpifiizvq.html

合计 ........... 2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtyqvyrdir.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gtsftdkbei.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gtgmrhwcas.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtalyzkywh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtwnvfitlf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gtwuhfllwu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ivvv.top/Article/details/gtoizzanca.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gttnkveqbo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpfeyrmr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtlewdhtrv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtsemyxhsh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtxbyoishv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtpxteaxox.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtwzzhdwhb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtynmeqbdd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtffowwddp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsstnota.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gttvcgwlku.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtsglgrjfb.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtkgusckjx.html

S C / C++ 专题                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevmpknuz.html

T 其他语言补充                          60
来源：http://dali.yongpay.top/Article/details/gtocmokrms.html

U 高频实用片段                         120
来源：http://dali.bjfxy.top/Article/details/gtaaavjcox.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtpayiisle.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gthobllejo.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtiwrwpdri.html

使用提醒
来源：http://dali.jinqigufen.top/Article/details/gtcrczplig.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtpzmmxiwi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gthlhefvhe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gtjpqzsnjj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gtyepedkdq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gtocirpgtb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sweek.top/Article/details/gtpzzksuux.html

—— 文件结束 ——
来源：http://dali.dianchejie.cn/Article/details/gtnoaswauc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsbkpisuo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hammf.cn/Article/details/gtmeksfwrt.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gtvvnjjstb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtylwklpze.html

【收录内容】
来源：http://dali.cqqwz.cn/Article/details/gtasrrkurx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gttykhnruf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.316326.xyz/Article/details/gtbnnqpnoj.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtuqfoyhnn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hammf.cn/Article/details/gtnatmzpcr.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gthtyjqvfx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtrkmmvvsk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhongyouzk.top/Article/details/gtfrwlvznq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zdqjudy.top/Article/details/gtvcmogkzt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hywenlv.cn/Article/details/gtcqjogktu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yonumen.top/Article/details/gtvdgfdexq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dashuyun.cn/Article/details/gtjehrypge.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gtwjturajx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtqbelmtxp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.bjfxy.top/Article/details/gtpftbxifo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhengqikj.top/Article/details/gtuiaxyzpz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtxkfcxbnr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gtprskbppk.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gtjnibtoni.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdriegzom.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtibrqexkl.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtargtutro.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtuzdgmzuo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gtafsooqpj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtwwtqemzw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtsyzjhgfk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gtxdgarqul.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.bjfxy.top/Article/details/gtefzbqwhy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtsgityvao.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtilpwwpfm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtuflsjifz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtkshlwmnq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtupmtrqel.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtiyxcwahd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtnionmfxf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtgijvnwfe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtabuwccth.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xinyue.icu/Article/details/gtdoustbbj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtcklzsrkc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gtdxlzdmvn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtklpmypyj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gtbsqkgfpg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtqmwutznd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtzzuxsmvz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvrgwdqgs.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gtliklaxjx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfpwkpxdw.html

[A01] Hello World
来源：http://dali.yvedp.cn/Article/details/gtxtmhlvlk.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtbhaxwckl.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gtkkxoejot.html

JS:   console.log("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnwnofdq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gtgrfelqyk.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtjsotaaws.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtbbgkgmlg.html

Ruby: puts "Hello, World!"
来源：http://dali.havefunace.top/Article/details/gthmohciew.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtfbbufnsw.html

[A02] 变量声明与赋值
来源：http://dali.meibo888.top/Article/details/gtwzfvrvay.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gtzzwojqlk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtjvaixgyl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhcrcgln.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gtgnourasg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtuoinfasj.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigufen.top/Article/details/gtpplvwkrh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gtdcbuxipv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtbnsofofh.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gtrxcrzhil.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xziqi.cn/Article/details/gtbtqrxpef.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtzfkhduhk.html

JS:   const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gttoiftaes.html

TS:   const PI: number = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtpddvsevz.html

Java: static final double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gttrrerdug.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtuuwcxjgy.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtaqhfzrnj.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtvckivpjt.html

[A04] 判断变量类型
来源：http://dali.jqgfzy.top/Article/details/gtspvxiurf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gtxcckiywc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hammf.cn/Article/details/gtfqjtesgj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtbuhhzodg.html

TS:   typeof x; x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtvleymdsu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gotoacloud.top/Article/details/gtowxugugu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.snrcjt.cn/Article/details/gtfvpztotu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtpbltjjuk.html

C#:   x.GetType().Name; x is int
来源：http://dali.xziqi.cn/Article/details/gtiktoecgz.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gtilhpeewv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gtvotfxkkk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtduqnpvdc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.316326.xyz/Article/details/gtotdeeisw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtziyslpcf.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtomoefnys.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtsvanztjx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtqqctnbod.html

C#:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtvbcuoomh.html

[A06] 字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtnktsculk.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtaxugolrw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj20258.top/Article/details/gtvqkgdctw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtolifxemt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gtoucnvdfp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.fengsongda.top/Article/details/gttrolhnvg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgfzy.top/Article/details/gtqhvzduyt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gtfrvtomie.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gtrulbflqd.html

[A07] 数字转字符串
来源：http://dali.jiagoushi.top/Article/details/gtbbwkcecb.html

Py:   str(42)
来源：http://dali.shzxlz.cn/Article/details/gthlfqnuzq.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuanzhike.top/Article/details/gtlwcylwmm.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjceptdv.html

TS:   String(42)
来源：http://dali.cheryme.top/Article/details/gtzakfdrnx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtxnsetgyn.html

Go:   strconv.Itoa(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtktcngopx.html

Ruby: 42.to_s
来源：http://dali.mhx1999.top/Article/details/gtqqdywegh.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gtdfwshtry.html

[A08] 取整与四舍五入
来源：http://dali.yuxming.cn/Article/details/gtjfnpgrzq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gtrfgpwimv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gtpjftfosz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtbcvjwnjo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gtyudtuinf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtvsvahwtn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtucnxekid.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhongyouzk.top/Article/details/gtcpakwrjl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtakaujkrh.html

[A09] 绝对值与最大最小值
来源：http://dali.tian-w.cn/Article/details/gtjqpmftht.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj202588.top/Article/details/gtknbsifbg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtqyrmdbjs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtwdutrfqj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtlxrhyocs.html


<!-- 参考信息 -->