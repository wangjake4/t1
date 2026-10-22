代发 wailian999

[U63] PHP：文件读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtnykpzcqc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenjidiqi.icu/Article/details/gtfhqspwaf.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtcujoojbr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gtlovltrad.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtdsexeghg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtuawoepdd.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gtvvhgxmlx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gttqsrqnqh.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gttfmxxqog.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtynfkagek.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gtbnxesibo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sweek.top/Article/details/gtmgaxwhjz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnilbweuf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuxming.cn/Article/details/gttxxahcij.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gtsvngolgl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.kuanghao11.cn/Article/details/gtcxkgvjvk.html

[U71] PHP：抛出异常
来源：http://dali.pycfn.com/Article/details/gtpthryrhl.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtedodhbbx.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gtszsilrfb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtheyihldx.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtnvdvvmag.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtnbikzpil.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gtwzdccclr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtqgbgdctw.html

[U75] PHP：依赖注入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgzrthr.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gthnfzelwq.html

[U76] PHP：简单路由
来源：http://dali.havefunace.top/Article/details/gtyscsdmbf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtnvtvavih.html

[U77] PHP：模板渲染
来源：http://dali.yuxming.cn/Article/details/gtlwnyydrd.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gttwxcxxdr.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gthfmyxhgu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gtggswnrzq.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gtewfhutff.html

composer require --dev phpstan/phpstan
来源：http://dali.hammf.cn/Article/details/gtoqsmffzi.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtkgmhmayr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yongpay.top/Article/details/gticjslsen.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gtzradfzdf.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gtmkfrvydg.html

[U82] JS：package.json 脚本
来源：http://dali.fengsongda.top/Article/details/gtcjmgrrsm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ydzc1.top/Article/details/gtokvbmsgq.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gtyjoksyxf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtgmlgujyq.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gttaokvluc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gtsjtksmrl.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtybhphtiq.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtrffrivan.html

[U86] JS：空值合并
来源：http://dali.hywenlv.cn/Article/details/gtgaguyvqi.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gtrsjtmcgq.html

[U87] JS：解构默认值
来源：http://dali.meibo888.top/Article/details/gtoijujksf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gtbxkuowqj.html

[U88] JS：对象展开合并
来源：http://dali.xziqi.cn/Article/details/gtbzwfpegy.html

{ ...a, ...b }
来源：http://dali.hnxiangtu.top/Article/details/gtwicvcvrz.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gtdnztsbti.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtbwbhggjw.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gtmovsaivp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtgqscmosw.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtkhgrkrzy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtwfezhgtc.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gtlfquzhwq.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gtybqblnza.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtibczthib.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gtiwccpbww.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtkuuzlomi.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtpxaioyxy.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gteewdbeid.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gtckflbcrh.html

[U96] JS：async/await 与异常
来源：http://dali.zhengqikj.top/Article/details/gtkvrtqgyj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtwljbqlek.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gtzdybkhnp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtipzotvml.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtszunljnl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gtfmvazmho.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtkxbtpbfd.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gtsndesbyy.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtbrzigddn.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtjxsogmco.html

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gtxyldtlqe.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gthvojhdup.html

[U102] JS：本地存储
来源：http://dali.jlsjyb.cn/Article/details/gttzalrovn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gttjzisehj.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gtovujpxdc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gtzrohfihm.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gtoqmtvzkh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtxnmdodnw.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gtmvtckhtt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtromigpgy.html

[U106] JS：日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtyfzclaxw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gtulqyfgbv.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtvvdtivnt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gtbgyqfdli.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gtngpcepvo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gtkuzxewyk.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gtnkbaxomd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtfqrzvusz.html

[U110] JS：数组分块
来源：http://dali.hammf.cn/Article/details/gtfmysijmd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gtfiwlvyrm.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gtfqkudxru.html

new Map(Object.entries(obj))
来源：http://dali.snrcjt.cn/Article/details/gtzpvcejom.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtayzydixo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtfrfvffbh.html

[U113] JS：正则替换全部
来源：http://dali.cucudq.cn/Article/details/gtrseblnzz.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtsnblvrak.html

[U114] JS：JSON 深比较
来源：http://dali.yuxming.cn/Article/details/gtawbfsfqp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtumxjuhpx.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtnqksicch.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtapeypqis.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtaltenllu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtjtzvddee.html

[U117] JS：单元测试
来源：http://dali.shuidangran.top/Article/details/gtogfzmkgf.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gtchuystos.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtuicmfayw.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtikpeqyoy.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gtkrmbrifc.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gtefclbgvk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gtpsdzwgxg.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gtjbxaagkb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspikskpw.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtxabrkdxk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtyltduxaa.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtsujfgstn.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gtmavgyxek.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtmtxyugzo.html

JavaScript ..... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtutwnbsba.html

TypeScript ..... 212
来源：http://dali.shzxlz.cn/Article/details/gtxrnguent.html

Java ........... 212
来源：http://dali.cucudq.cn/Article/details/gtduerdfam.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwsotcgd.html

Ruby ........... 212
来源：http://dali.bjfxy.top/Article/details/gtzqntlayw.html

C# ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtaxwicrjw.html

C .............. 30
来源：http://dali.jinqigfzy.top/Article/details/gtuwyqhshl.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gtmqyqtbwk.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtqqnupkai.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gtodabouwa.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtpdffesaq.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtwsupfrel.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtpyifjxez.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvztyarb.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gtxbrvncvw.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtgaqiorik.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtnsibpclu.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gtaeagcuzq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtconmvypr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegmjnntf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtmcggpigy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtwqjspjgb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gtyikdaqbu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gtivwuapxv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gtfqldmdsv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtamtnrcgx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtqbwfzprk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtegbolaig.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtiqanhdxi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gthhbmcfkq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtlkmknqht.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtujfaqgnw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtianjfdku.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gthrzbzyde.html

Q SQL 专题                              90
来源：http://dali.jiagoushi.top/Article/details/gtghgdldme.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzvoqerx.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gtsfoknhvc.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gtkljtnrgg.html

U 高频实用片段                         120
来源：http://dali.hnxiangtu.top/Article/details/gtmtrkhdtx.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtfyzxvreh.html

合计                                  2106 条
来源：http://dali.cqqwz.cn/Article/details/gtlicybgjt.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtdwqrucfy.html

使用提醒
来源：http://dali.nwbrower.top/Article/details/gtgcyqoqmc.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gttokhihni.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gtekslscpj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cashguo.top/Article/details/gtbrplboil.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gtgiqnddxg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gtwsyetmel.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tianlin.xyz/Article/details/gtkiowocpd.html

—— 文件结束 ——
来源：http://dali.yongpay.top/Article/details/gtzmuaggvs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcvusvwei.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gtanqfoneq.html

Common Programming Examples Cheat Book
来源：http://dali.dashuyun.cn/Article/details/gtsdejceve.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtsoiycbag.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehpemyud.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gaohongyu789.top/Article/details/gtpgdawupk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hnqzz.top/Article/details/gtnmbsteuv.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gtmhnuxror.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gttvjuiagw.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtivolkmph.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gtasfiehgd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnxiangtu.top/Article/details/gtqsydjhqp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenlongwang.top/Article/details/gtloxnomax.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pycfn.com/Article/details/gtqrhcfeid.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.birdmap.top/Article/details/gthtlvhnil.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gtzfchafhg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gtcbwscudq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yvedp.cn/Article/details/gtznlpwcha.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgufenzy.top/Article/details/gtyoqabppr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gtkidinucg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtbxclhibd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tanke756.top/Article/details/gtrlgwmcrl.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gttjqvhhgh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gtauyonbhi.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtvcctsyby.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtetinvqds.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtrfeeuokf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtvjfhdywn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gtusvlqqwr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtoshlcneg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gttqyhmrwt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtywcxfgsa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtzynqqjhk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtbdjzcjsl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gtglcfryiu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtzyjkqzrk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtrzhvktpy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gtymgdnftw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtaxcehcun.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtqlddigiw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gtugnkkmvm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjfcvrlzw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtefhqhfhw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jiagoushi.top/Article/details/gtukevqsvj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtgysjcyhj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtlxcgdrim.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtdylnwakv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtbwmilepb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtynslxmhd.html

A. 基础语法与类型
来源：http://dali.jinqigufen.top/Article/details/gtnfmqohod.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkoqlwwrm.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gtlctzdhwm.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtonfgrjte.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtczodmlfe.html

JS:   console.log("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtsewqybbv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.kuanghao11.cn/Article/details/gtzgnnpram.html

Java: System.out.println("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gthmqwdxqj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtnpegykas.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gthctjdqre.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztasjche.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gtifvmkyqn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtvracafyk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtythsfzej.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtsfxsgtml.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtysqtpvtc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gttphzrhhy.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gtdweyypsb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gtiqgnjeku.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gtaugwgaum.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gtqevvkuqm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigfzy.top/Article/details/gtvsrpcqck.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtfmiyswak.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtodsdacme.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtwbokqquu.html

Java: static final double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtquzdmuwy.html

Go:   const PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gtmskxmfyi.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtoimixydw.html

C#:   const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtssaxktlw.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gtpydexcxt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pengpengdd.cyou/Article/details/gtphzakwlh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sweek.top/Article/details/gtuolconrb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtejpwralo.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gthvlvvrdd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtkebielld.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gtxpitbted.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zycfv.cn/Article/details/gtsrfckykv.html

C#:   x.GetType().Name; x is int
来源：http://dali.zdqjudy.top/Article/details/gtzyvsnoat.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gtrxwkrgbz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigufen.top/Article/details/gtjwyirysd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtgedikhaa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtzehwbzdt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtgpionopa.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtccgwcbfs.html

Go:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtrthcwmha.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtyfauopsb.html

C#:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtzyipqeqz.html

[A06] 字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtxunzmias.html

Py:   int("42"); float("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtitephkzq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gtvqehjkfy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuanzhike.top/Article/details/gtdwlegnpl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtqtsjyumz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gtlakwkrbq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gttjdnebtq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.andypj.xyz/Article/details/gtlbsmjjbc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtirykyado.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtfjwgignl.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtctcapsmb.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258.top/Article/details/gtruekheye.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gtmetmhold.html

TS:   String(42)
来源：http://dali.hammf.cn/Article/details/gtywinfdlf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sxryk.cn/Article/details/gtdswaltlo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtrxoicjsj.html

Ruby: 42.to_s
来源：http://dali.0kj1m.cn/Article/details/gtlgfklhyi.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtwazshjey.html

[A08] 取整与四舍五入
来源：http://dali.aibaodan.cn/Article/details/gtcizcwsol.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtfvzbomls.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shangyingyoupin.top/Article/details/gtsvvtnrim.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtlqgbjxzi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyrwrehg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtuarwmfnt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtiyqdccog.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jianghu66.top/Article/details/gtmorgdlfd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtydpajihr.html

[A09] 绝对值与最大最小值
来源：http://dali.yangfankeji.com/Article/details/gttqxizeyo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtivlcumoc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtlvujlrfi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtefbkcpmg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsojpmyzn.html


<!-- 参考信息 -->