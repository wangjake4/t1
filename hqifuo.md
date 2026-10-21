代发 wailian999

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtnzpajixi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ehwqpu.com/Article/details/gtssugpucv.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gtvlkbwwdd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yonumen.top/Article/details/gtgedveubv.html

[U65] PHP：会话
来源：http://dali.xinyue.icu/Article/details/gtmypyaxdk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gtpdxbfagr.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gtdmrayaec.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtfyftyqjh.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigufen.top/Article/details/gtoaxkqvee.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtvjvqznfb.html

[U68] PHP：PDO 连接
来源：http://dali.yj202588.top/Article/details/gtrjvybjpf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shzxlz.cn/Article/details/gtdzkxabrz.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtjegwzybl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gtfcdrivyn.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtsjsgigoh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtzwmgrywh.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gttjrelxvc.html

throw new RuntimeException("失败", 500);
来源：http://dali.sxryk.cn/Article/details/gtrxzcoglk.html

[U72] PHP：写错误日志
来源：http://dali.jinqigfzy.top/Article/details/gthblzobeq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtezfubavd.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gtnwmiqgja.html

parse_ini_file("config.ini", true)
来源：http://dali.ppjwa.cn/Article/details/gtpuhfyhch.html

[U74] PHP：读取环境变量
来源：http://dali.meibo888.top/Article/details/gtwdmawbpy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.9152youxi.cn/Article/details/gtvdxxnutm.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gtffetczhv.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtnedehffb.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gtwdzugdvs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gtmfizjmrs.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gtdujixwbj.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gtmhupnzsg.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gtafvhmzsx.html

composer require --dev phpunit/phpunit
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkijunhya.html

[U79] PHP：静态分析
来源：http://dali.shzxlz.cn/Article/details/gtigpxjmwl.html

composer require --dev phpstan/phpstan
来源：http://dali.daria6918.cn/Article/details/gtiawskzak.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtaonqskuk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gtaruxuvwj.html

[U81] JS：初始化项目
来源：http://dali.svipenyu.cn/Article/details/gtaojnqoai.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gtkpuhszto.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gtmvqwnzdf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sufxvd.cn/Article/details/gtrxrmxkad.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gtshancsjf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtezhwlhku.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gttdhqdrvx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hfpthk.cn/Article/details/gtsclzzoar.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gtyjezaeeg.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gtyaqrenth.html

[U86] JS：空值合并
来源：http://dali.yueranfly.top/Article/details/gttfintdli.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gtusvfryuj.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gtbnstosha.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cqqwz.cn/Article/details/gtmgmmkfql.html

[U88] JS：对象展开合并
来源：http://dali.jinqigufen.top/Article/details/gtsbfapobv.html

{ ...a, ...b }
来源：http://dali.iojbl.cn/Article/details/gtangzqmzg.html

[U89] JS：数组去重
来源：http://dali.ehwqpu.com/Article/details/gtywhiesxg.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtfcgxkqmo.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtkyyordqq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtippmrxsd.html

[U91] JS：对象键值遍历
来源：http://dali.zhixingplan.top/Article/details/gtuxbaqxpu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gtllbpeaio.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtcealhvja.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvjjpjrku.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtbwwutihg.html

`共 ${n} 条`
来源：http://dali.vqdsnc.cn/Article/details/gtzdwcofxw.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtfmqttvag.html

const double = x => x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxsikthk.html

[U95] JS：Promise 包装
来源：http://dali.fengsongda.top/Article/details/gtjhfxaqyw.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gtihfroyeo.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gtedupabek.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtlbxhogmo.html

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gtenuccyga.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtbbanmuto.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gtwbidftcs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gtjhwuqxwl.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gtbathnjvg.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtdqonbnii.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gttsvrftkz.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfgonegj.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtzdmykuwk.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gtosttatxc.html

[U102] JS：本地存储
来源：http://dali.quarkkingdee.top/Article/details/gtseqzoirm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gtycukwuyr.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtrqxvbxev.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gtsakgzjhu.html

[U104] JS：防抖
来源：http://dali.yangfankeji.com/Article/details/gtspmuqppn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtoympjwde.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gtsplrcmdc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gtdweautjf.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtpxkkedvw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqcinsra.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gtibddrpon.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtcvsfzuww.html

[U108] JS：随机整数
来源：http://dali.bjfxy.top/Article/details/gtpsdatyks.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gteyivmvqs.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gttsneotnm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtcbwwuxfs.html

[U110] JS：数组分块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxjwdldq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtyejrtwbj.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtzfyuhncj.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gteilsfqvo.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gtdyimqlnl.html

"7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtpyzloksc.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gtqfullklc.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtjsgwpgqv.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gthsaaabtf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtywjooaqy.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtaunmmxgo.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtfrluhmxf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtvzwjfsaw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgczkjjzp.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtxwnltdrw.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gtqqjorbbj.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtyygcnzir.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gtmdgvozxh.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gtayntzryq.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtgpoudsah.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gtrnxqxojz.html

import.meta.env.VITE_API_URL
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorxtnmjt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzcpemmsc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtaujepnoy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdzvyuhjz.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtjsrheefl.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtjiiikyxx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gtxrluofzb.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gttuobmnnp.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gttedmckhc.html

Java ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtqmvyzayf.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gtemanifbg.html

Ruby ........... 212
来源：http://dali.cashguo.top/Article/details/gtsgoonvvu.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtenxagpjt.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtydggmjlc.html

C++ ............ 30
来源：http://dali.guannengcc.top/Article/details/gtoodzcdqa.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtqphosnfu.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gthkxoxbyi.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtczewxypt.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtjjmovfnn.html

Lua ............ 10
来源：http://dali.hysaishi.cn/Article/details/gtayxjlrcx.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtuedryzxw.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmdehjdh.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtqudmfaer.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gtnwamfwor.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gtyxbpiwqg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gtesafchmx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtwhhbvvee.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtuduszsmd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtsodcqcme.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gtdokpsnkj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbepcflj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtxwafjmjl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtqrcrylal.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtxpuzsjqw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtrvxobmhy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtxxnjswgo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtyghlzmcd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtsfqmeyiz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtmhwsflpq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jyoumei.cn/Article/details/gtxmrbrrjt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtbzptbsib.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtpipybzto.html

R Bash 专题                             80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskahwwas.html

S C / C++ 专题                          60
来源：http://dali.c1oappe.top/Article/details/gtxwgctowm.html

T 其他语言补充                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqifqgcq.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gtawwevhvs.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtsyicchfv.html

合计                                  2106 条
来源：http://dali.gogol.net.cn/Article/details/gthjqfgmnf.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtyynkbhoj.html

使用提醒
来源：http://dali.zhongyouzk.top/Article/details/gtelsdctgm.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtsgxvyadr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gtordphzrf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gtvjrbgyqz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gaohongyu789.top/Article/details/gtzayjoyrj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jyoumei.cn/Article/details/gtokhcwigb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gttfghdcki.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gttbrwbxge.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtujseobqt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ydzc1.top/Article/details/gtygligdgz.html

Common Programming Examples Cheat Book
来源：http://dali.hammf.cn/Article/details/gtxrrxvvqi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteyahhrkb.html

【收录内容】
来源：http://dali.xinyue.icu/Article/details/gtgzegmrea.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gotoacloud.top/Article/details/gtgiuqbdco.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gtzeeryefo.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvxzoqea.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhixingplan.top/Article/details/gtknrmzpmc.html

【使用说明】
来源：http://dali.jianghu66.top/Article/details/gttxrdfzfc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtrxprxifb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvuopavz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gtgdafaoqo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnqzz.top/Article/details/gtccmmtbya.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhengqikj.top/Article/details/gtccbroudo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gtueijkora.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtizxuxcln.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pengpengdd.cyou/Article/details/gtcjgrvkfq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guannengcc.top/Article/details/gteqxobqaj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigfzy.top/Article/details/gtcfsrikwk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gtwmwfrgrg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gogol.net.cn/Article/details/gtgzwgdrvm.html

【文件统计】
来源：http://dali.jinqigufen.top/Article/details/gtbirlwgjc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgufenzy.top/Article/details/gthqkudfqc.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtmnexcxgp.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gtihkraezn.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtvhbuusjf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtzcpjzjxw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtfzoyussc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gttxewychf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtzdrkgrxf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.kuanghao11.cn/Article/details/gtiesdzcjs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtidjahlva.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtjogocqbt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtxzbaibpc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtjvwgtgky.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwemwtnu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtvfqzqxqw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtzhmobufs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtgngfynru.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtfptxsdoj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtfcjwkwqk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtdqlaqcgi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gtbbqameyd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtutjjypbd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gogol.net.cn/Article/details/gtabxzrtzt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtqggpipfi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtaxvmzhza.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfonpzpa.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gtsqndsmdy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtwkblgwyp.html

[A01] Hello World
来源：http://dali.bjfxy.top/Article/details/gtreiuvjic.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gtjnvmefzy.html

PHP:  echo "Hello, World!";
来源：http://dali.svipenyu.cn/Article/details/gtyltvodnz.html

JS:   console.log("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtdnastqtw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gtwvtnobkd.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtosudaqha.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtyohcjgse.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtnmifltst.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtvbronnea.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtrwwahrsx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtqlntvdxq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtnleipjry.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.havefunace.top/Article/details/gtvbqnbreb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gtombwghew.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtzavwhfch.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtsfqwyxuk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhedzunv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtcperzwoa.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtcsdzmzmd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gtviupuvwe.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtthvulvzj.html

JS:   const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtsiiwnjzd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtsvrudtyy.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtznosfwdv.html

Go:   const PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtpitykzqg.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gteoyiwyuz.html

C#:   const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtfihafsux.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gtixamwgar.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xziqi.cn/Article/details/gtifvfibzx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.andypj.xyz/Article/details/gtkrrdbxiv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gtaxwzsopf.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gtsxqkqxfh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guowangkeji.top/Article/details/gtjwkstvsw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gtgfafefga.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxuanxn.top/Article/details/gtieklxdsm.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258.top/Article/details/gtrukptcpq.html

[A05] 整数除法与取模
来源：http://dali.ydzc1.top/Article/details/gtqgiqtaly.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.9152youxi.cn/Article/details/gtyjlpwfeb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtdggnxeek.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtunxqvkou.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtpipveish.html

Java: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtajkvjedo.html

Go:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtvfoprfyr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtmtdzxpwk.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtqfspioyb.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtqnbbvjlk.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258.top/Article/details/gtiwplcmgo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jiagoushi.top/Article/details/gttcwemval.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gtqzoqcvlf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtzmqwulff.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guannengcc.top/Article/details/gtxahtrjsz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhongyouzk.top/Article/details/gtssomhmwr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuetiantiany.cn/Article/details/gtjspehcms.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daxiang520.top/Article/details/gtvkqxculx.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gtrjqbvvss.html

Py:   str(42)
来源：http://dali.fzhhl.top/Article/details/gtpqwjkure.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gtxpywvdrh.html

JS:   String(42); (42).toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsselith.html

TS:   String(42)
来源：http://dali.xinyue.icu/Article/details/gtbmuvwikk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ppjwa.cn/Article/details/gtojslhcyb.html

Go:   strconv.Itoa(42)
来源：http://dali.jianghu66.top/Article/details/gtwptzwtxq.html

Ruby: 42.to_s
来源：http://dali.cdnleiting.top/Article/details/gtyjvwxkqv.html

C#:   42.ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtkgzguujt.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gtdrkiwxhs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtiymstnwq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gtzqyjvvrm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtmvjeuhjk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gtotiljtlu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtkbtibigp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtyxnjbphm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hfpthk.cn/Article/details/gtvytcgxld.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnnvckce.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtxalwarpo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtddlmmldy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtmejrtqdc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtbwpobcux.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtcvtcmhfu.html


<!-- 参考信息 -->