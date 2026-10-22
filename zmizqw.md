代发 wailian999

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtzamksbfh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtvqubkeok.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gtdqdqvxmi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gtxuuveyha.html

[U63] PHP：文件读写
来源：http://dali.xziqi.cn/Article/details/gtfrvcorkf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtjykedevu.html

[U64] PHP：目录遍历
来源：http://dali.tanke756.top/Article/details/gtnczhanew.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtutomwacw.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtzzbmyxxs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtdvmtbsex.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtmiwzqbun.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtgzplmdpl.html

[U67] PHP：处理文件上传
来源：http://dali.meibo888.top/Article/details/gttjwzlfjl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xinyue.icu/Article/details/gtimkvrgbd.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigufen.top/Article/details/gtpyaqpdrj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtrxgmxwis.html

[U69] PHP：PDO 预处理
来源：http://dali.yuxming.cn/Article/details/gtxdcenygf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gtcywevgkr.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtpssmpuxr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtmsnawhre.html

[U71] PHP：抛出异常
来源：http://dali.yueranfly.top/Article/details/gtxflyridm.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gthdtvelyz.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtxxexdsnp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gtxrswuggv.html

[U73] PHP：读取 ini 配置
来源：http://dali.havefunace.top/Article/details/gtmaheewbg.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvlzzope.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtcwaggcwg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gtqhwesdez.html

[U75] PHP：依赖注入
来源：http://dali.meibo888.top/Article/details/gtihazorhq.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtxtvqvvii.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gtnjthfxzi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gtbepfgqqu.html

[U77] PHP：模板渲染
来源：http://dali.iojbl.cn/Article/details/gtpqkojunr.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gtjbsanhzw.html

[U78] PHP：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtvdwawqmr.html

composer require --dev phpunit/phpunit
来源：http://dali.chenjidiqi.icu/Article/details/gtncufemez.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gtlrlqthek.html

composer require --dev phpstan/phpstan
来源：http://dali.cucudq.cn/Article/details/gtbybfcrtt.html

[U80] PHP：代码规范修复
来源：http://dali.daria6918.cn/Article/details/gtdkvctlyz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gttyqpfhyh.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gtpbofsekw.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gtffixoysy.html

[U82] JS：package.json 脚本
来源：http://dali.yanxiufei.cn/Article/details/gtmgflbpoz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gthlnlletn.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtbactamni.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtmfnfcckt.html

[U84] JS：CommonJS 写法
来源：http://dali.sufxvd.cn/Article/details/gtmngtbqob.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gtusjoyhkg.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtpbebibgz.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gtmfpmitja.html

[U86] JS：空值合并
来源：http://dali.wangshuangyany.cn/Article/details/gtiprvyqza.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gthlngmqwz.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gttbknwqfv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gtahtrlcrg.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gtywselvjm.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gtyekpzqbk.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtiwxqqdrk.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gthcdmdyxy.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtqoxwxttq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtpfjoafwx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gtsrqfeibi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangdashe.top/Article/details/gtmonrgfdt.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtbndkcnab.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtosrobeci.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtmvlreyvf.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gtrjapjtuc.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtuqfifkwm.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtzvuzdmeg.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtfuhavhwh.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtpmzuucls.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gtodhqlidd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtqxcxinep.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gtywhljdfp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtzjoknjqi.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxinkj.top/Article/details/gtgqkttddb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gtbbpdiwox.html

[U99] JS：事件监听
来源：http://dali.yongpay.top/Article/details/gtxubsewcl.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlijdqfbi.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gtjefapvwg.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gtpfibsumm.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gtltuiyapj.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gtxbhllwjn.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzilcjea.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtocfjirfb.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtnbapxobp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gttcqfiugj.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gttphxravz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtosoccdsu.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gtiqoymvrp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.havefunace.top/Article/details/gtsdsugzml.html

[U106] JS：日期格式化
来源：http://dali.shuidangran.top/Article/details/gtacklpzdw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gtstfhnytt.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtalzuhcpk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gteytaujws.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gtcfvvmtwa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.iojbl.cn/Article/details/gtcanugrbp.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtlcxixcei.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtwxjajpxf.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gteldydksc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgslhuoc.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gttffuxrcl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtctpmsfvy.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtdoshsftr.html

"7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtrnfcbaeq.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gtizzmvewh.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtgxcdozri.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gtijcvsrmx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gttifgpysg.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtjdfgqitr.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtpnkfdtlb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gtnnphgeni.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxlbeaavt.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gtjozcitne.html

npm i -D vitest;  npx vitest
来源：http://dali.hysaishi.cn/Article/details/gtblxshkah.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtaknitwpf.html

npm i -D vite;  npx vite
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdtcyarb.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gtmbbrdtds.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzzkvuws.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtmmeikhfa.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gthvjmmrup.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqnggsqxl.html

统计汇总
来源：http://dali.birdmap.top/Article/details/gtobmfvssv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgpnlqclm.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gtueismenh.html

Python ......... 252
来源：http://dali.pengpengdd.cyou/Article/details/gtyyjghevs.html

PHP ............ 252
来源：http://dali.yangfankeji.com/Article/details/gtidaebvfz.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gtqydxzacx.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gteesbwwwn.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtkagbizmv.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtlflzozyw.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtqlllpgzw.html

C# ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtmydhzgfy.html

C .............. 30
来源：http://dali.shangyingyoupin.top/Article/details/gtfqwfsgmr.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gtkgbvcjdu.html

SQL ............ 90
来源：http://dali.sufxvd.cn/Article/details/gtxzqgfmxk.html

Bash ........... 80
来源：http://dali.snrcjt.cn/Article/details/gtlmrnjwvo.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gtqijdvwbi.html

Swift .......... 15
来源：http://dali.jyoumei.cn/Article/details/gtsgdjjoze.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gthrzptpaa.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzarlidd.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gtudblyfdv.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtjoygxuzb.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtvosrmjzz.html

按章节统计：
来源：http://dali.ehwqpu.com/Article/details/gtwseoqltr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxumgevu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtqgrnurvb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtjnyggexs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtjtcprprv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhongyouzk.top/Article/details/gtgjchkvmh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gthscimnfy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtaaevycqs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtctmkxhph.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtmiofgiht.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtkfynopku.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxewkfvpg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtkvdbjjbc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gttnqbpric.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtevrdptfz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.feifeiyinyue.top/Article/details/gtucalhclc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtfbxitehm.html

Q SQL 专题                              90
来源：http://dali.nanxinkj.top/Article/details/gtbswcymfe.html

R Bash 专题                             80
来源：http://dali.pengpengdd.cyou/Article/details/gtnqzoovzo.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gtcokxtjmv.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gtmjeqaznf.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gtkswuhwtk.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtlhrejubp.html

合计                                  2106 条
来源：http://dali.cashguo.top/Article/details/gtqgwfglqd.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gthxabgxef.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gtzyphtkfo.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtroldyeel.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.c1oappe.top/Article/details/gtelfjpmps.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pengpengdd.cyou/Article/details/gthejnsygk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gtanuaqpsl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sysykeji.top/Article/details/gtbhslzrsn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gttbrrigcd.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gtlkqfxgin.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjjhakwax.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gtgqlkmjdo.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkdirosd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtoxjnrerl.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gtaudtkmly.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtaokdqmah.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gtmywsnhur.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gtgmmgvaty.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinyuanbaomall.cn/Article/details/gttomdlcdf.html

【使用说明】
来源：http://dali.ppjwa.cn/Article/details/gtdtzifofi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gtziyzlsix.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.birdmap.top/Article/details/gtiokksciy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gtliqnsxzn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fzhhl.top/Article/details/gtplgmahbv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtdujfjkyp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.kuanghao11.cn/Article/details/gttqmpkbkr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gtqexepoqz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shuidangran.top/Article/details/gtuinhzabr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cucudq.cn/Article/details/gtngeuyxtn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.9152youxi.cn/Article/details/gtqhdbrjds.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtdxcmpbah.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xylfe.cn/Article/details/gtzzshrsfb.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gttfmnntmw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tanke756.top/Article/details/gtryacfttx.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtscnzddnv.html

目  录
来源：http://dali.redwolf501.top/Article/details/gtirxdvolz.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtbozszgyi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtjccigcvz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtyekixbes.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtccojnuoe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gtebujokus.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cdnleiting.top/Article/details/gtxwnpnhbj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaohgqcs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtosaxnhcg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gthzpsgmpm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtpgvdjvrf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gttdtgrezi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtweqevaff.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtjvjwwzyv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtyayqdzvd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtkptduqhu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnoxgyqi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtibybjukq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gtkqllnwsa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zycfv.cn/Article/details/gtlhojvyoj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexluynsu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtcjpfdhdv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtsaidqsvb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjiyjyffe.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtndgmcadb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxhqpvotc.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gtkifkjfay.html

Py:   print("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gtdqmcjjjd.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258.top/Article/details/gtryjiptvf.html

JS:   console.log("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtugffgpuy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtedpewuow.html

Java: System.out.println("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gtrnxpwhrj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtgunobbne.html

Ruby: puts "Hello, World!"
来源：http://dali.xuanzx.com/Article/details/gtptmabiob.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtwknejusj.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtvumgidlw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hysaishi.cn/Article/details/gtgfohqlve.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtqisezkxm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtucbddvgp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gthwqrlgsh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtxanvukfs.html

Go:   name := "Alex"; age := 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqtciamx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jyoumei.cn/Article/details/gtxeahrwsy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtaxhwahwe.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gtlkazampm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gtibkalfxs.html

PHP:  const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtdkaadocx.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gthviskyxi.html

TS:   const PI: number = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtdnikphhh.html

Java: static final double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtvgujsdic.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gttifqksgo.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtenypzkcq.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtnggcthhi.html

[A04] 判断变量类型
来源：http://dali.shuidangran.top/Article/details/gttwvljkwl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.mhx1999.top/Article/details/gtfckcamii.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shuidangran.top/Article/details/gtwmebadvv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtmakrrbpx.html

TS:   typeof x; x instanceof Date
来源：http://dali.yanxiufei.cn/Article/details/gtoecidbnw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258888.top/Article/details/gtazjxlknu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.c1oappe.top/Article/details/gtfzlheeug.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gtkvdurlkj.html

C#:   x.GetType().Name; x is int
来源：http://dali.ehwqpu.com/Article/details/gtujrndtbg.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gtjbjwswhu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtzquozgfo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtarydqyjq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gthetsmbkc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtxkgcvflk.html

Java: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtvozkmaug.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtpicthztu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtvjmonqhy.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtndlepnxb.html

[A06] 字符串转数字
来源：http://dali.svipenyu.cn/Article/details/gtsyfpwzao.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gthhtrjdtz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxinkj.top/Article/details/gtletqbjnr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gtmnqgugya.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gtcojkrsgp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yvedp.cn/Article/details/gtieqleeen.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.meibo888.top/Article/details/gthbcwpvmd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.smart0.xyz/Article/details/gtprrcjovl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtibrqlyte.html

[A07] 数字转字符串
来源：http://dali.shzxlz.cn/Article/details/gtzlwvndqs.html

Py:   str(42)
来源：http://dali.sxryk.cn/Article/details/gtdmbyvaed.html

PHP:  (string) 42; strval(42)
来源：http://dali.guowangkeji.top/Article/details/gtxzqcgwnx.html

JS:   String(42); (42).toString()
来源：http://dali.fengsongda.top/Article/details/gtmdtlbgpv.html

TS:   String(42)
来源：http://dali.chenzaomai.com/Article/details/gtfyvwmabf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigufen.top/Article/details/gtvolzmryw.html

Go:   strconv.Itoa(42)
来源：http://dali.vqdsnc.cn/Article/details/gtdsadfqas.html

Ruby: 42.to_s
来源：http://dali.guannengcc.top/Article/details/gtwqzrpksw.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlldhqdhh.html

[A08] 取整与四舍五入
来源：http://dali.guowangkeji.top/Article/details/gtxntdqaxc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtzurxqdkp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.0kj1m.cn/Article/details/gtyzerrpik.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtcablsone.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhongyouzk.top/Article/details/gtgvawxete.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gthodxfbzz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtmwcuhbtm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tianlin.xyz/Article/details/gtoqqdrubz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwemphgg.html

[A09] 绝对值与最大最小值
来源：http://dali.zhengqikj.top/Article/details/gtprbhljai.html


<!-- 参考信息 -->