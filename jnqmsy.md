代发 wailian999

[U61] PHP：正则
来源：http://dali.gaohongyu789.top/Article/details/gtaegeuwde.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtudmnwaqf.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gtgnrxqsje.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gtsexkdsbq.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gtyxsufbjb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtsdwnlizc.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gtvdrdynjf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtvxhmxqxt.html

[U65] PHP：会话
来源：http://dali.xziqi.cn/Article/details/gtnelqlzjk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtnczkdrlr.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gtxuuvgkrz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gtihxiagal.html

[U67] PHP：处理文件上传
来源：http://dali.shangyingyoupin.top/Article/details/gtsizsgudt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tanke756.top/Article/details/gtbnogcmqw.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gtfneazadc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtawqtvemk.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtlweoxmwr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gtxdtxsvav.html

[U70] PHP：PDO 事务
来源：http://dali.fzhhl.top/Article/details/gtuejibuyj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gtodqbzcrk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtyxwxreqb.html

throw new RuntimeException("失败", 500);
来源：http://dali.hywenlv.cn/Article/details/gtformxpkg.html

[U72] PHP：写错误日志
来源：http://dali.yj20258888.top/Article/details/gtxvtvvnhg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtryaileit.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtqzisorpq.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtljdcpcpq.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtonhtynfe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gtmmvhyjpe.html

[U75] PHP：依赖注入
来源：http://dali.jqgufenzy.top/Article/details/gtssppbisw.html

composer require psr/container
来源：http://dali.cheryme.top/Article/details/gttuwnkdfu.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gtkdbnlcla.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovwodlvj.html

[U77] PHP：模板渲染
来源：http://dali.hnxiangtu.top/Article/details/gtndduzhzy.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gtiorpidsv.html

[U78] PHP：单元测试
来源：http://dali.sysykeji.top/Article/details/gtqsfxecjq.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gtezwnloik.html

[U79] PHP：静态分析
来源：http://dali.cheryme.top/Article/details/gtnfiunowd.html

composer require --dev phpstan/phpstan
来源：http://dali.yj202588.top/Article/details/gtrklfdciu.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gtaeftusyz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gzhubu.top/Article/details/gtfcmznqmz.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gterqwxhly.html

npm init -y;  npm i express
来源：http://dali.hysaishi.cn/Article/details/gttqnvjrvg.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtvrjctzyd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gtgniffwij.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnxiangtu.top/Article/details/gtyemmusft.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtakxnzpeo.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtzhlmfwaq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.andypj.xyz/Article/details/gtiaxnwndy.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gtlqabjxsg.html

a?.b?.c
来源：http://dali.mhx1999.top/Article/details/gtcnwbpmif.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gttrocqeas.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtnwcqewjb.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gtupvtxutw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.snrcjt.cn/Article/details/gtkpijurcc.html

[U88] JS：对象展开合并
来源：http://dali.zhongyouzk.top/Article/details/gtvlyodjvt.html

{ ...a, ...b }
来源：http://dali.nwbrower.top/Article/details/gttokmwdab.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gtlkwinilh.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyqrllzr.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gtkcsvidif.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtucoekokr.html

[U91] JS：对象键值遍历
来源：http://dali.316326.xyz/Article/details/gtmnyorqfy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtqninekks.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gtzshjyixm.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtfinekucb.html

[U93] JS：模板字符串
来源：http://dali.cashguo.top/Article/details/gthrfrerxc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gtskfpwhlf.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtzrkubcso.html

const double = x => x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtldxtwgyp.html

[U95] JS：Promise 包装
来源：http://dali.redwolf501.top/Article/details/gtmqfjjtwe.html

new Promise((resolve, reject) => {})
来源：http://dali.guowangkeji.top/Article/details/gttvgprsai.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gtnsibrwya.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtgcbxcsnq.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gtibpesdqd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtfcxofkbr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gtnfnzbyqd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ppjwa.cn/Article/details/gtzrwicjor.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtgqxxubgn.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gtknquuzmy.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gtvyckvmqu.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtiwhlsako.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtbeuyzcrr.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtaovwuaty.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gthqqrmnrp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yongpay.top/Article/details/gtkphaxgtz.html

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqkliegc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gtinydhvhx.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gtxinbsgdu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtbxuecylb.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gtxanrrdzp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.mhx1999.top/Article/details/gtgxyoksrf.html

[U106] JS：日期格式化
来源：http://dali.yongpay.top/Article/details/gthhxmnsvw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtmtvlkwsf.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtjkpwhfjq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtmtzyjaxg.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtuxbexebg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gtjkjpvonm.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtjzrylxvq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtlexofluc.html

[U110] JS：数组分块
来源：http://dali.cashguo.top/Article/details/gtwrimryhh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yongpay.top/Article/details/gtswlzvnkx.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtvuuwycbe.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtiutouilj.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gthyyyxefu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtrmhayful.html

[U113] JS：正则替换全部
来源：http://dali.0kj1m.cn/Article/details/gtivyaalpp.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtlyjxsjds.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtgrzfhxur.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gttjnnhdxt.html

[U115] JS：生成 UUID
来源：http://dali.yj20258.top/Article/details/gtogxofbeo.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtwkbkgkgw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtmzmvcefd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbgefeubn.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtxhygxgpd.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtskgpqlqn.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gthvfjwnsg.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtzxksnobs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gttmlrycox.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gtowyhjjtk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtqbyxqaet.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtdebgczjk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwgaqvtgu.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gtkxdlqgev.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijkvzzak.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gtwbflhdiu.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gtzbkjdljj.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gtgeoqigvz.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gthavjszlz.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtcwllodee.html

Java ........... 212
来源：http://dali.xziqi.cn/Article/details/gtmcalalcw.html

Go ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtqcsnyvtp.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtebbeifoq.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtbmxgwaac.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gtbjvunuhd.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtorbazrwy.html

SQL ............ 90
来源：http://dali.zhengqikj.top/Article/details/gtcojporeg.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gtbrjdnnej.html

Kotlin ......... 15
来源：http://dali.svipenyu.cn/Article/details/gtwfxndrje.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtrciwmyvm.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtmilrluhx.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gtizsooepv.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtzhtycujh.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtnizsweub.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtawjukexk.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gtqdlperyg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtmtndcayo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtjthhersy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtkgwjkwgf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtnmesetmz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtimgntyxq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gturwzvohn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtalapbely.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtynfauwur.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtmjnpcfws.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtgzzufvjg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gthqzkjolv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtstybnjtz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtniczjnia.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtyikuasbs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtmbbtwkqi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtfhbhqnsv.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gtzjxmvwfo.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gtqdpddknc.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtltlazqgw.html

T 其他语言补充                          60
来源：http://dali.yj20258.top/Article/details/gttojuuuhd.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gtsvhbsuzb.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtemxoddol.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gteyedxizm.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwiauoao.html

使用提醒
来源：http://dali.jqgufenzy.top/Article/details/gtkfyixgbr.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtyjcefhrk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daria6918.cn/Article/details/gtcsmqtvxw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gtcdgsmscu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtdnenqhgw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtrqhzyzmp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gtdpjfioyt.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gtqnhgrsuo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkaafcemt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gtwrtsqcwn.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gtiwxshgzr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gteveuixsa.html

【收录内容】
来源：http://dali.daria6918.cn/Article/details/gtqeyceoih.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtqoolxawq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwavpctc.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gtbznznven.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gtzcmrrhwn.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gtsshflerm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cucudq.cn/Article/details/gtxxwhxtda.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpplsprfp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fengsongda.top/Article/details/gtwbsinjhv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.pengpengdd.cyou/Article/details/gtrifnnrtu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtbzfvivpg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gtewwgviwc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtstyobjco.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gtntjysryr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dashuyun.cn/Article/details/gtlkacxucw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gtxndkkrvw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuxming.cn/Article/details/gtsjogqeit.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shzxlz.cn/Article/details/gtvsbmcvak.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gtyfbxmjyg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hfpthk.cn/Article/details/gtcinqygis.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsylkebmd.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gtmzthacwt.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtlucjqadb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gththxdgfb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhskcasz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtylhrzuhi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gtubqrpkfv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tian-w.cn/Article/details/gtmpodmieb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gteholbmdf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gttckukycg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtazqswgrq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtsfkvxzkz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtctolncyl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtvowcekvy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtsfnvrbss.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxngigup.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtxjgxktva.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zycfv.cn/Article/details/gtofhfrlrl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtnkwcstto.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gtwjgykian.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtgqchzkvx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xinyue.icu/Article/details/gtpgctycbi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtusermdwn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtgkckhkiw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtwkplbruv.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gtipaqnjzf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtacysaoga.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gtrghtyhov.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkafbeqgi.html

PHP:  echo "Hello, World!";
来源：http://dali.ppjwa.cn/Article/details/gtxrckqiqu.html

JS:   console.log("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtsrgisdit.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.bjfxy.top/Article/details/gtfwfrtfwq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtpuqbboas.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtjofdswth.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gtpiwjjdvn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gttrgmrpoo.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtgxuftitu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.redwolf501.top/Article/details/gtgqtucexc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtmujzzzap.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtzwouilxo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gtudcfbsgr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtmjihznci.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gtyckuqibs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gtkqhycldm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtwpznznux.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtnasggepz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtiidprrgu.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtfjqzsbyw.html

JS:   const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtpsqufazy.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtadstqbgn.html

Java: static final double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtmvphwyow.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtbhabjkik.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gttifsrbms.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtprlryhaw.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gtwfczeves.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.mhx1999.top/Article/details/gtchydugps.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gthcjwjmsu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtqvohtssp.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtwjetpxin.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtmzhlyadu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.birdmap.top/Article/details/gtdijaiwnv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiordyoz.html

C#:   x.GetType().Name; x is int
来源：http://dali.gzhubu.top/Article/details/gtetepsbai.html

[A05] 整数除法与取模
来源：http://dali.nanxinkj.top/Article/details/gtknbompre.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gtlzvwjelx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtbllaynwl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtvkrtnoyx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtmrxrblhe.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtetkxzbun.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtjywqukhf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtusfbmdle.html

C#:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gteqpfmhcv.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtmpbcbyyu.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258.top/Article/details/gtsmftpqzh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gtouwptzji.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtaqxxzytq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtbfapfwdn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gtrcpcjhnc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258888.top/Article/details/gtupadqvfp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hammf.cn/Article/details/gtpcpvewoa.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtpgueujrx.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gtghspofoj.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gtwgxlvneh.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258.top/Article/details/gttlvalpqs.html

JS:   String(42); (42).toString()
来源：http://dali.ydzc1.top/Article/details/gtxmimdfey.html

TS:   String(42)
来源：http://dali.yvedp.cn/Article/details/gtlgshgnkt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwqccuxr.html

Go:   strconv.Itoa(42)
来源：http://dali.ydzc1.top/Article/details/gtomazutkf.html

Ruby: 42.to_s
来源：http://dali.aibaodan.cn/Article/details/gtfmuqdktk.html

C#:   42.ToString()
来源：http://dali.jqgfzy.top/Article/details/gtmpxcvlhb.html

[A08] 取整与四舍五入
来源：http://dali.jinqigufen.top/Article/details/gttovpvbsr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtqwzhsljd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnxiangtu.top/Article/details/gtjcaogiyq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtktysmbsr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ppjwa.cn/Article/details/gtwtdvbtvt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtgoyqetgl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtnhrsgclt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hammf.cn/Article/details/gtdfyprlsm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtkwbvrkry.html

[A09] 绝对值与最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtlsbgqbmx.html


<!-- 参考信息 -->