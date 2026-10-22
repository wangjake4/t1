代发 wailian999

[U63] PHP：文件读写
来源：http://dali.hongshengwenyu.top/Article/details/gtnovnvgum.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gtvtakldot.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtupejzwja.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yongpay.top/Article/details/gtgihptmdv.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gtdpuoqsnw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtgigfnmvy.html

[U66] PHP：设置 Cookie
来源：http://dali.aizwys.cn/Article/details/gtxxvksazf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hammf.cn/Article/details/gtgenmifua.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gtfqzatklv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgufenzy.top/Article/details/gtwfnugign.html

[U68] PHP：PDO 连接
来源：http://dali.316326.xyz/Article/details/gtaduditsx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gtqomfndaz.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gtexxyofre.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenzaomai.com/Article/details/gttovnnaze.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtxjpiujgv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gtwcwrczyz.html

[U71] PHP：抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtulbeaydu.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtssduabmu.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gtelsjhrnw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gtuymrrwvs.html

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gtiwwkfzan.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gtilqxxyeh.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gttqswdnal.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcegzmzb.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtsmsiwqsz.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gtblpreflk.html

[U76] PHP：简单路由
来源：http://dali.sxryk.cn/Article/details/gtlxqqykeq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ydzc1.top/Article/details/gtzrthoybh.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtnnzrsymm.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gtgmltkini.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtzeivfxph.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gtsrsnvxnc.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtwxzsplna.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtwmmbnumx.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtxjujztit.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.haohaochexian.top/Article/details/gtocqdhauu.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtuewcgjye.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gtcbeugqin.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gtwoayhlwv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gtpaqukkhd.html

[U83] JS：ES Module 导入导出
来源：http://dali.jqgfzy.top/Article/details/gtpcepxwhl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtykfsslpl.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtllezsksb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gtsnjidrbu.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadynldqo.html

a?.b?.c
来源：http://dali.redwolf501.top/Article/details/gtzcsmbupq.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gtaqygoqpp.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gtzedrcjzj.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gtnlqznbqs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gtrvouietw.html

[U88] JS：对象展开合并
来源：http://dali.feifeiyinyue.top/Article/details/gtgwlsjspr.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvlqsabf.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gtuxuidxzi.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtjybuxdyl.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtndnqcsva.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtupgyrlql.html

[U91] JS：对象键值遍历
来源：http://dali.quarkkingdee.top/Article/details/gtatjsibeg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinghuilouyu.cn/Article/details/gtccouuazk.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtwbhdippz.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtvixwqaxz.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtnanvtfnv.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtrbqpwzqg.html

[U94] JS：箭头函数
来源：http://dali.daxiang520.top/Article/details/gtvxtskxst.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gtpwtwbzzo.html

[U95] JS：Promise 包装
来源：http://dali.ydzc1.top/Article/details/gtyoxrzdjg.html

new Promise((resolve, reject) => {})
来源：http://dali.ehwqpu.com/Article/details/gtqxcqntzz.html

[U96] JS：async/await 与异常
来源：http://dali.tianlin.xyz/Article/details/gtzfdsnkmb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gthfdnypdo.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodbouzgf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtfouivbnp.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gtceahvoox.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gtsveaolro.html

[U99] JS：事件监听
来源：http://dali.xuanzx.com/Article/details/gtncpkohza.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtosmuokoy.html

[U100] JS：DOM 查询
来源：http://dali.fengsongda.top/Article/details/gtuhpknayr.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtokfasmll.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtiqzqxoiq.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gtwjhggmas.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtpofkatop.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtarmgiipk.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtotuytraj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtutrsazjf.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtksdahdqz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtkstqqoal.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwiqyigd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.bjfxy.top/Article/details/gtfucckzqa.html

[U106] JS：日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtvptqshcc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gtcyslxvnp.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtoqntiftv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtzcinfhrt.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtcigkbaaj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gtdnlphumr.html

[U109] JS：数组分组
来源：http://dali.zhengqikj.top/Article/details/gtpmeokwnd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtbrvrpjto.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtykmdpgno.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj20258.top/Article/details/gtlnsbrisd.html

[U111] JS：对象转 Map
来源：http://dali.daria6918.cn/Article/details/gtzjnuxpkl.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtkufqrgnx.html

[U112] JS：字符串补位
来源：http://dali.jlsjyb.cn/Article/details/gtetftyhiw.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtfzuvioxc.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gtksivuesi.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtyampnldk.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gtjpjqdbjn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtbcpzvtff.html

[U115] JS：生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtjrfpugsp.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniwvkfnh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtvfdsddsg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtszrkrksx.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gtlmbescme.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gtpnkdnpjl.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtalleavex.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gtjouyycks.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtkbmuhajm.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtvvcnakgy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.pengpengdd.cyou/Article/details/gtfxiqgzpr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gtzryifwbv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsucartih.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gtmpeoaelv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpdkxvhri.html

按语言统计（条）：
来源：http://dali.daxiang520.top/Article/details/gtvfplsaxf.html

Python ......... 252
来源：http://dali.kuanghao11.cn/Article/details/gtjlyntadg.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gtqfnxclgj.html

JavaScript ..... 252
来源：http://dali.hfpthk.cn/Article/details/gtrqwkbjez.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtxtynobuc.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gthuvpfnha.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gtphcskbdk.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtccsmwqkd.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtndxhkqtf.html

C .............. 30
来源：http://dali.yj20258888.top/Article/details/gtkeueynvx.html

C++ ............ 30
来源：http://dali.svipenyu.cn/Article/details/gtzmouxtpo.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtdtvothpe.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gtmhxwjzna.html

Kotlin ......... 15
来源：http://dali.cucudq.cn/Article/details/gthdvzxjti.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnehekfk.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gttwatfchc.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gthwajhnxw.html

Scala .......... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtowimxxru.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtxhzxhjzz.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtincdnetc.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtdsmctllg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtspenhrzc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusjibvjr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtrrkatoja.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtkahwcjvy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gtmrzqrdou.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvozxadg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtfhxsnqhc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtkjcgbbso.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtdgbnjapa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtmsgobiks.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtvaqtkrtc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gthepjnwcc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtdlsaqihw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrfcdarp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuetiantiany.cn/Article/details/gtukvyoryi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtxlsypsde.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtlksirxnm.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gtvlfbzwyo.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gttuxvayfo.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gtgscorggo.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gtimlauooe.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtjigjjsuu.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gtjwjkhycx.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtevwfnbgp.html

使用提醒
来源：http://dali.hongshengwenyu.top/Article/details/gtlqkrxqwv.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtyfdqvgzy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gtcpncbkjs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtnlauoyve.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gtetsbnqxw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangshuangyany.cn/Article/details/gthargplsy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xinyue.icu/Article/details/gtnwkrgzjm.html

—— 文件结束 ——
来源：http://dali.yanxiufei.cn/Article/details/gtemjywlda.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtenkwwbtz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgufenzy.top/Article/details/gtojuvfgmu.html

Common Programming Examples Cheat Book
来源：http://dali.xinyue.icu/Article/details/gtfkdxszlb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnlruuzpl.html

【收录内容】
来源：http://dali.ydzc1.top/Article/details/gtpjcyfijc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gtnbintylt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gtgcwhepfh.html

SQL · Bash · C · C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzhhnlkp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj202588.top/Article/details/gttxhevvjz.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gtxbpljeca.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gtzbpnnszu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gtbhotvasx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gtbnmovaab.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gtkdkczbbp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gtolhzsuec.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gtmxysxeat.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtkciocpxy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gtlqcmekke.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yongpay.top/Article/details/gtfvtayfbd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nwbrower.top/Article/details/gtnguxjfwu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gtdfsohixp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gogol.net.cn/Article/details/gthtmcvchu.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gtjsmmjpld.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.smart0.xyz/Article/details/gtekqqwals.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtfughwuta.html

目  录
来源：http://dali.shuidangran.top/Article/details/gtctptokoa.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtbzuuhusq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtgkbedulq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtorhuyyib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgdnriyav.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gtpwuharhw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gteivrzlnp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtjmjtisum.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtaosoohxz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtjiwsfaid.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gthgrpmwov.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtfwqdubsw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtqugmarnu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtdzdzzlvf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtxproinzp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtiympbzva.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dianchejie.cn/Article/details/gtoydghdiu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtxfaznfgk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gtpkkdqhjy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xinyue.icu/Article/details/gtixfwewna.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gtarptryjg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtnvnsvocs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gterbsillr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqehltcrb.html

A. 基础语法与类型
来源：http://dali.guowangkeji.top/Article/details/gtsivribyb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpcjafhiu.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gtmtipined.html

Py:   print("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gthrfdmyza.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gtfhdarexp.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtvyxlizca.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daria6918.cn/Article/details/gtwzflixqd.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtixkcveoh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtheqhyinl.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gtrzoiwlse.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtkghpulve.html

[A02] 变量声明与赋值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaiwrvzk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hywenlv.cn/Article/details/gtoxixyjio.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtnfelvoka.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtbxsdrjqa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gtamgnztif.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtyvpenbny.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gtvgukjwjq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gtaiwkiwts.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtfowfbdde.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtzuyfliil.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guannengcc.top/Article/details/gtigzlqpxu.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtwuauvpqh.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtovxtneno.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtxjkvajlf.html

Java: static final double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtzihglwhi.html

Go:   const PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtutevgh.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtgfuguttq.html

C#:   const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecubaogc.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gtnkgxjgbu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daria6918.cn/Article/details/gtonuwidwd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daria6918.cn/Article/details/gtchgkytmi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gtbokulkvi.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtqahiltfh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeamswwa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.redwolf501.top/Article/details/gtugghyddn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnqzz.top/Article/details/gtqbgnyqhi.html

C#:   x.GetType().Name; x is int
来源：http://dali.guowangkeji.top/Article/details/gtlixucdzm.html

[A05] 整数除法与取模
来源：http://dali.chenjidiqi.icu/Article/details/gtftjhguwk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gtuwsgbdho.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtphkutdue.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtlmffhqjz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtgfkdtuql.html

Java: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtteqmpcoq.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gterdnlzrs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtmlgxkzju.html

C#:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtcvzzyuct.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiyhgklz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtkwxoysrt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pycfn.com/Article/details/gtrhelzsal.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gttlhjreyi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtwnjsezhw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtcylzbfai.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cashguo.top/Article/details/gtcprkpfgz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dashuyun.cn/Article/details/gtlvuapndp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtgohitzpd.html

[A07] 数字转字符串
来源：http://dali.sysykeji.top/Article/details/gtkqougkzz.html

Py:   str(42)
来源：http://dali.tanke756.top/Article/details/gtpdqnputu.html

PHP:  (string) 42; strval(42)
来源：http://dali.jiagoushi.top/Article/details/gtbftexsml.html

JS:   String(42); (42).toString()
来源：http://dali.nwbrower.top/Article/details/gtjfgxiqed.html

TS:   String(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyjpdczw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fengsongda.top/Article/details/gtfitnqatc.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gtpamjexsz.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtklhpmlqd.html

C#:   42.ToString()
来源：http://dali.316326.xyz/Article/details/gtilxberyg.html

[A08] 取整与四舍五入
来源：http://dali.sxryk.cn/Article/details/gttnzhsgxx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtavbwjssd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxuanxn.top/Article/details/gtslgyiqal.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtcukzgdct.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shzxlz.cn/Article/details/gttafanjgz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtfcilsdks.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtpallcfot.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gtroqavyrc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtokzlhgws.html

[A09] 绝对值与最大最小值
来源：http://dali.shuidangran.top/Article/details/gtdjdydgbo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtnfucchmf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtyegqcprm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxrnrywok.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtcbvojrbs.html


<!-- 参考信息 -->