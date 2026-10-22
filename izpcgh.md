代发 wailian999

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gtqhwwjylm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.bjfxy.top/Article/details/gtorpofilb.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gtxdqajswc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gtipzivhws.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtmraxdzeu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtzrmvvwaw.html

[U66] PHP：设置 Cookie
来源：http://dali.tianlin.xyz/Article/details/gtogtlcrih.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtsyrmwnte.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gthsbotdgx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.svipenyu.cn/Article/details/gtjxtujbqh.html

[U68] PHP：PDO 连接
来源：http://dali.redwolf501.top/Article/details/gtebqjsilu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjylfgth.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258888.top/Article/details/gtypzwwsmy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gtssisoxpv.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtiwgzzyvn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.snrcjt.cn/Article/details/gtifvenucf.html

[U71] PHP：抛出异常
来源：http://dali.hysaishi.cn/Article/details/gthmduttyv.html

throw new RuntimeException("失败", 500);
来源：http://dali.dashuyun.cn/Article/details/gtxblepmbe.html

[U72] PHP：写错误日志
来源：http://dali.tian-w.cn/Article/details/gtfbflwjuv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gtzpsotbae.html

[U73] PHP：读取 ini 配置
来源：http://dali.shuidangran.top/Article/details/gtivfkfecd.html

parse_ini_file("config.ini", true)
来源：http://dali.hnxiangtu.top/Article/details/gtpcnuxkce.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtycpncgqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hywenlv.cn/Article/details/gtltowmeny.html

[U75] PHP：依赖注入
来源：http://dali.xziqi.cn/Article/details/gteupybhlm.html

composer require psr/container
来源：http://dali.tian-w.cn/Article/details/gtsfboyywi.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gtaftcdxkc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gtqmgahvuk.html

[U77] PHP：模板渲染
来源：http://dali.zhixingplan.top/Article/details/gtqugrnqwd.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gteuzpszvt.html

[U78] PHP：单元测试
来源：http://dali.hysaishi.cn/Article/details/gtqvbflxus.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gtzsitldia.html

[U79] PHP：静态分析
来源：http://dali.yonumen.top/Article/details/gtcpfnlscy.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gttyroxbei.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtgrapgfre.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuxivmqr.html

[U81] JS：初始化项目
来源：http://dali.xuanzx.com/Article/details/gtlzsestns.html

npm init -y;  npm i express
来源：http://dali.hfpthk.cn/Article/details/gtvvjhozqg.html

[U82] JS：package.json 脚本
来源：http://dali.sysykeji.top/Article/details/gtxtanypkd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gtxjllgtir.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhiwuduotai.top/Article/details/gtubnyjfar.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtzwlqibcw.html

[U84] JS：CommonJS 写法
来源：http://dali.iojbl.cn/Article/details/gtyrhgiyqk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gtvnohuomz.html

[U85] JS：可选链
来源：http://dali.ivvv.top/Article/details/gtzzbvgren.html

a?.b?.c
来源：http://dali.yanxiufei.cn/Article/details/gtoydztbju.html

[U86] JS：空值合并
来源：http://dali.fzhhl.top/Article/details/gtppqdwwyq.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtxhznoxzs.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtguburvll.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtbnsrsfxy.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gtftusivyg.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gthiroibvq.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gtodeonedt.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtqesephxa.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtsbcfwqxo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtmwdiasqd.html

[U91] JS：对象键值遍历
来源：http://dali.chenzaomai.com/Article/details/gtadsbsvpi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gtxwbvxmuw.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtzdywohll.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtngdnskaw.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujdpnxya.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtvuzmvwut.html

[U94] JS：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtjdrkkqnb.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwsyyvqn.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisxafcxi.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtixmorznn.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtnwctyyzh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtfkhrzsia.html

[U97] JS：并发请求
来源：http://dali.ivvv.top/Article/details/gtnuayylpr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gthjhjotfx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtoxyafncb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxuanxn.top/Article/details/gtvhylggkm.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gtrqoxuvxd.html

el.addEventListener("click", e => {})
来源：http://dali.yonumen.top/Article/details/gtsoktarwn.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gtmqvcpaow.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gteqjzwanw.html

[U101] JS：classList 操作
来源：http://dali.hongshengwenyu.top/Article/details/gtmldqogcm.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gttshybvgi.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gtjyaispjl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gthxnsmxbq.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtspijaywg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gtdsdoibig.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gtwvmfdjpj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtvzunafhs.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtfpztdpns.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gtbljccovk.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtxwpzmgsq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sweek.top/Article/details/gtpcxckvtu.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtzhjptsot.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltrkafhi.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtfnicyjrr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gtuyzdtfjs.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gtptnmysqh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtqiuxscsb.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gtqbrpbxnh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtvbswaiac.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtfmmzazcw.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gtjjfrwpcw.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gtefrwmmhv.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtzsjkgdsv.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gtebrjyeaz.html

s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssohlktu.html

[U114] JS：JSON 深比较
来源：http://dali.redwolf501.top/Article/details/gtcfeobvkl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtmprlqmlt.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtjfvcdazs.html

crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtwczroeoc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gtwyjzslpd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsrhscrx.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gtwgnmpgsx.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gtrnuycipe.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtzowxtpdb.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gtezfpfuiw.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtzhfxptog.html

npx vite build
来源：http://dali.jinqigfzy.top/Article/details/gthanqvatv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtksqolhnr.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtuvcyucxr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdctxdyvt.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gtlyxypgkc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjmyhpopl.html

按语言统计（条）：
来源：http://dali.9152youxi.cn/Article/details/gtxilkgfwa.html

Python ......... 252
来源：http://dali.nanxinkj.top/Article/details/gttcghflrx.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gtyrmdbyqg.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gthrgrueiz.html

TypeScript ..... 212
来源：http://dali.dashuyun.cn/Article/details/gttisihqps.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtghlmvfvl.html

Go ............. 212
来源：http://dali.shzxlz.cn/Article/details/gtwgtxwyba.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gtzawrixib.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gttxxockkd.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtqramtnyd.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gtzlnundmh.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtsavszusn.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtwxwntbrp.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gtfqmjjjdz.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gthfdodtkk.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtnfakcrtx.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gtjrlorqnt.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gteoayxqkk.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtsmvsiupn.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtgkbhqvty.html

按章节统计：
来源：http://dali.tanke756.top/Article/details/gtarcedphx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtnrhigvgn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvmfmvld.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtaugifvqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gtfseghvsc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtidnwxebi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gttgbapyze.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtbxncdvln.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtscjolexw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtyysqrqov.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtawxeznon.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtahoqkocg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtlnselnuf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtdoskyvpv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtbzdgvcmw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtueofpqnq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtjroxhpef.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gtmcydizxc.html

R Bash 专题                             80
来源：http://dali.ppjwa.cn/Article/details/gtmjkistuz.html

S C / C++ 专题                          60
来源：http://dali.pycfn.com/Article/details/gteqysfpdj.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gtvvmntojf.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gtqnkssckq.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtpvvtogtk.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gthkgznwkn.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gttrlmtolq.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gtsgutziut.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtjjkliefy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gtnxxorxmt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gtsvvpshqo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtgshsrlbh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzzsovss.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtxeyerrjn.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwczpueuz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzppltzhg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hfpthk.cn/Article/details/gtykkslrhe.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gtmfdwperr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtonubxrmr.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gtmisldfth.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtrhylrrjd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gttqniiiyt.html

SQL · Bash · C · C++
来源：http://dali.guannengcc.top/Article/details/gtriknuayl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yueranfly.top/Article/details/gtknkkdmbs.html

【使用说明】
来源：http://dali.yuanzhike.top/Article/details/gtdtkljpxm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtfnkwtxui.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sxryk.cn/Article/details/gtmtqpvuhw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtjjfkkzrh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gtniiywlac.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.bjfxy.top/Article/details/gtljsdhhop.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yuxming.cn/Article/details/gtgwgvahlm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtjcyzyzwc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ehwqpu.com/Article/details/gtuctfkvnk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gtenvewylk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.9152youxi.cn/Article/details/gtqydurujt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gtgbkckjvp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gtvntdnatf.html

【文件统计】
来源：http://dali.zhixingplan.top/Article/details/gtszocunyl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxuanxn.top/Article/details/gtmcrogkqu.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtpphveptx.html

目  录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwqxbtqm.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtqjrzglcd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gtlmphbflv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gttsncldrq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtzjccxxwt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtqicwwxyb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtdswpiqdt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtkxxgscgu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtrglachhp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtcfcyeagp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtobmzrrjj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtmbzercwe.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxoeaqvy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtflsfnikf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtdunjmzpp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.kuanghao11.cn/Article/details/gtucbzwcsc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cdnleiting.top/Article/details/gtosadxvmw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtudojiekl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gtgjqsnshe.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gtwlothxpp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.snrcjt.cn/Article/details/gtczzdhuio.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtygtuzkua.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtrzckhomv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjnikoota.html

A. 基础语法与类型
来源：http://dali.316326.xyz/Article/details/gttwcqakvo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiydwvwos.html

[A01] Hello World
来源：http://dali.gogol.net.cn/Article/details/gtqiysrzhk.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtlffgmevq.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gtqyftfuob.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtecphutox.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjrzinop.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtdurivbxm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtavrfbnyi.html

Ruby: puts "Hello, World!"
来源：http://dali.yongpay.top/Article/details/gtxfyeevyo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtgafavkzd.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtbjcrukzn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gtmqbyhjzo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtqyglxlwa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtjtvfdmfr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtqyrhsvjj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtyihmeucr.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gtpbxcghqi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuetiantiany.cn/Article/details/gtghcbtunk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtaxwiyznb.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gtgklmmsxx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gtmgfmohst.html

PHP:  const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtyglssovu.html

JS:   const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gthsawdyyz.html

TS:   const PI: number = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gthbpejkdi.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtsakwword.html

Go:   const PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtuzqdddya.html

Ruby: PI = 3.14159
来源：http://dali.tanke756.top/Article/details/gtemleuaxa.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtcqqxhxch.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gthfbpfggf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gtthhkshee.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hammf.cn/Article/details/gtosgufqod.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtchiybfyt.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtieihgwef.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtgpkmzilr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.mhx1999.top/Article/details/gthinodskm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yangfankeji.com/Article/details/gtoitfhkqp.html

C#:   x.GetType().Name; x is int
来源：http://dali.meibo888.top/Article/details/gtjzuvnmhv.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gthuxtqmze.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxuanxn.top/Article/details/gtizrvxebg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtomvgdtio.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtydtruilu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtwoxdapde.html

Java: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtuxsghhmk.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gttnotgpfz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gttrwbsymu.html

C#:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtnnvtpmen.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtfokamvym.html

Py:   int("42"); float("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtxljegyek.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.svipenyu.cn/Article/details/gttlddmwxe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gthcsvefkk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ydzc1.top/Article/details/gtqbxxhgsd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gtxkcejnyj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuxming.cn/Article/details/gtitjnftgj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gtdlatkjnj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtazrfbilh.html

[A07] 数字转字符串
来源：http://dali.hysaishi.cn/Article/details/gtlzzqvqxt.html

Py:   str(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticigtief.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gteadljprp.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gtmryscvtu.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtvfpmtzpp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jyoumei.cn/Article/details/gtnfhrnecv.html

Go:   strconv.Itoa(42)
来源：http://dali.snrcjt.cn/Article/details/gtwhrpowjo.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gtjyourtrr.html

C#:   42.ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtppcbxuev.html

[A08] 取整与四舍五入
来源：http://dali.svipenyu.cn/Article/details/gtiricwcjg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtspvkbltd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.vqdsnc.cn/Article/details/gtenwspbad.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtdffajkwe.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtunandnya.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtdjqsdbkl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtpkxmboib.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.andypj.xyz/Article/details/gtdgpjwrud.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtzxfenkaq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtklhghztg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtblfnerwi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtiacnllju.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtiwamznmr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtebgizbfg.html


<!-- 参考信息 -->