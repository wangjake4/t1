代发 wailian999

[U61] PHP：正则
来源：http://dali.gaohongyu789.top/Article/details/gt2vuhspjpv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2wdjywpig.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gt2vrwtvwbc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gt2eonjbqpf.html

[U63] PHP：文件读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyhkbqob.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gt2nasbcctf.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2mgzqikvg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnqzz.top/Article/details/gt2zzdpjghd.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gt2rnbnlhuh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2nvaceadj.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gt2uhmpdvfr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shzxlz.cn/Article/details/gt2ydxhyuuj.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gt2pnaysqjc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gt2axutzwdm.html

[U68] PHP：PDO 连接
来源：http://dali.zdqjudy.top/Article/details/gt2utgkakfl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.9152youxi.cn/Article/details/gt2agrqxbqj.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gt2afgzbvpn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjjywuwp.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqjylwga.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gt2xuttlpmh.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2avnueyck.html

throw new RuntimeException("失败", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2rtjuffbx.html

[U72] PHP：写错误日志
来源：http://dali.yangfankeji.com/Article/details/gt2ordtcpdn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yvedp.cn/Article/details/gt2wkujmxcc.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gt2xbexlybc.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gt2nmicqrjd.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2gpmhntue.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgufenzy.top/Article/details/gt2mmlkeusi.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gt2uruqhbsq.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gt2zdmmidxr.html

[U76] PHP：简单路由
来源：http://dali.fengsongda.top/Article/details/gt2ubeqlluc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gt2pnbfwjip.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gt2khcholzo.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gt2rmpozpny.html

[U78] PHP：单元测试
来源：http://dali.meibo888.top/Article/details/gt2swqaovcs.html

composer require --dev phpunit/phpunit
来源：http://dali.ppjwa.cn/Article/details/gt2jkaqplli.html

[U79] PHP：静态分析
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdcmaann.html

composer require --dev phpstan/phpstan
来源：http://dali.hammf.cn/Article/details/gt2henqzzxh.html

[U80] PHP：代码规范修复
来源：http://dali.svipenyu.cn/Article/details/gt2ltjktjyn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.c1oappe.top/Article/details/gt2afkrxlpg.html

[U81] JS：初始化项目
来源：http://dali.sxryk.cn/Article/details/gt2ifqdyswc.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqemvsct.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2melocgtt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gaohongyu789.top/Article/details/gt2shwyiibj.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zihhwjgs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2efvojbpz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qinlnyej.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpymebyf.html

[U85] JS：可选链
来源：http://dali.bjfxy.top/Article/details/gt2hlmxaiai.html

a?.b?.c
来源：http://dali.gotoacloud.top/Article/details/gt2bznzwqey.html

[U86] JS：空值合并
来源：http://dali.xylfe.cn/Article/details/gt2kjffbobq.html

a ?? b
来源：http://dali.havefunace.top/Article/details/gt2iikmvoxp.html

[U87] JS：解构默认值
来源：http://dali.jyoumei.cn/Article/details/gt2fdqndlmh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gt2dblsjdga.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gt2tdxbylme.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gt2zuhxqpbp.html

[U89] JS：数组去重
来源：http://dali.zycfv.cn/Article/details/gt2ronxlhij.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2xmyooywy.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gt2czfcjbsv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gt2mkzjhips.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gt2lgyfgdct.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgufenzy.top/Article/details/gt2vevvvdog.html

[U92] JS：深拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2oaskiuji.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2ddqcscwp.html

[U93] JS：模板字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ksmqxaur.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gt2nahcmjml.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gt2jeiqkupv.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gt2vbjzzjdw.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gt2viidonnr.html

new Promise((resolve, reject) => {})
来源：http://dali.zdqjudy.top/Article/details/gt2syzxfejk.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gt2gqklqoya.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2aefxceno.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gt2jeychcwa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2qywvxvvm.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gt2jdrlffgw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gt2jrgxozis.html

[U99] JS：事件监听
来源：http://dali.hnqzz.top/Article/details/gt2ygqbimdk.html

el.addEventListener("click", e => {})
来源：http://dali.smart0.xyz/Article/details/gt2yulosmnp.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gt2collcxsj.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gt2eiswpaxa.html

[U101] JS：classList 操作
来源：http://dali.daria6918.cn/Article/details/gt2lqsumyii.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gt2cqoybanx.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gt2erzvifxz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gt2mxcyikth.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gt2rkffnwoc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gt2hozjtera.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gt2gzufrtnh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2ubvgwfqr.html

[U105] JS：节流
来源：http://dali.cdnleiting.top/Article/details/gt2wdamdiyb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxrvabzb.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2wkikdcyl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gt2owvkxmac.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2miytojbt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2xziyxbnf.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gt2ldzfipwz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shzxlz.cn/Article/details/gt2qakudqfn.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gt2zfwlarjd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gt2kposxogz.html

[U110] JS：数组分块
来源：http://dali.zhixingplan.top/Article/details/gt2hmxkyjny.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gt2zukwdulq.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gt2qbrvexjn.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gt2rkedwmgy.html

[U112] JS：字符串补位
来源：http://dali.vqdsnc.cn/Article/details/gt2hzevolqk.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gt2fpwxhtbr.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gt2gfkyqxyc.html

s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2mxnitrsa.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gt2bjnijzrq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gt2oajlszjg.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2nezbshwe.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2sydpekpf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gt2kucxbyrq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gt2ynmazdxx.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gt2ufybuhka.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gt2enjficfi.html

[U118] JS：开发服务器
来源：http://dali.xuanzx.com/Article/details/gt2uvdrstay.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rehylald.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhnnkwq.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gt2cnpqbrds.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntykenjr.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gt2qxheewkx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gasymzub.html

统计汇总
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eopdwdej.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2olkpjabb.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gt2tqqjfula.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2clnmvboh.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gt2ebfsbrju.html

JavaScript ..... 252
来源：http://dali.yonumen.top/Article/details/gt2xxmtagqr.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gt2gvdbupuw.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2ilkiwmij.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2yclkzmtp.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gt2lojoibsp.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gt2kupokwse.html

C .............. 30
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozcxtwcj.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gt2qpioduud.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gt2kiavpiyv.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gt2isxflrsq.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkpcdtvm.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2bkmivrci.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gt2rgvznmbb.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvdhuiog.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gt2frdxiuhg.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2fpvymwou.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gt2jmuxnelm.html

按章节统计：
来源：http://dali.pycfn.com/Article/details/gt2ukpnudtd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gt2wbearysx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdehipst.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbdrjxjb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akxbnmcc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gt2ewqzodec.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2iepjsufv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2slxfvtsj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gt2kmoaltro.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2puizicty.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2ivqechux.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2icsurzii.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2uifiqdig.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2qizrpcne.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gt2dsrhzthw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guannengcc.top/Article/details/gt2mrpbnzju.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2kfntirlt.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gt2jhdmnuyx.html

R Bash 专题                             80
来源：http://dali.yonumen.top/Article/details/gt2dkfgobqz.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gt2mlafrheh.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gt2oeqkaqhv.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gt2nzbbqyqf.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2ecnerzbh.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2dczzzapt.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2lvhylfva.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gt2tsfahyhm.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2nfidsctd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gt2ozqqtyev.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gt2xacgyxgw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gt2msnqwgza.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gt2ezwwrxpo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gt2abeffakf.html

—— 文件结束 ——
来源：http://dali.c1oappe.top/Article/details/gt2ljveyfdt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2lwpaypdz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigfzy.top/Article/details/gt2ilthpmxn.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gt2aeayptwt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mvtznmij.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gt2pmmvqxlt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hysaishi.cn/Article/details/gt2xbjsybyc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jiagoushi.top/Article/details/gt2grnobvcf.html

SQL · Bash · C · C++
来源：http://dali.iojbl.cn/Article/details/gt2gcrquzcx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gt2qtgdxdos.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gt2reovqxdk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gt2iuvdssro.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgfzy.top/Article/details/gt2oxwsrmwm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gt2crjgertn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shangyingyoupin.top/Article/details/gt2augqrqoy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oeqgnsjc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gt2sobygeuj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mshklgze.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhixingplan.top/Article/details/gt2irqlbciq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gt2mpkzrklo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gt2oquxayoa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shuidangran.top/Article/details/gt2gdakrobs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhengqikj.top/Article/details/gt2kzauiazb.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gt2pccywkrb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebtbzjzq.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2wolacvss.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gt2qxznygwu.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2jnkbajei.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gt2pizwlhyx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2qdoijkpp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gt2artcfiij.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2pkkbeonh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ydzc1.top/Article/details/gt2ukhbjwww.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2idazxsav.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gt2kjnspihr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gt2hpaqjtjp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2prekkfrm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2althrmmo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2waeafuni.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2vnohyapi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2gxixrzee.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biadzdyg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gt2oqbfjrvu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2vkbciyyh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tanke756.top/Article/details/gt2hvyzxnnw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gt2kvmumdqx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ziymwcbf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzsawwo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2srhxdimc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2afkzxcak.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gt2qcqnbkpv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2aizqzmey.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gt2issgqciw.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gt2akaghxcc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gt2otrccxpp.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gt2foouvtdg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iclpbawr.html

Java: System.out.println("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gt2reioyhpd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gt2bcrwfvej.html

Ruby: puts "Hello, World!"
来源：http://dali.hfpthk.cn/Article/details/gt2abvyfcdl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2lmakgaqd.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gt2ecucmzmk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gt2ejbkzndr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tanke756.top/Article/details/gt2fmcogcpn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2zfebzaiw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gt2scipjoud.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2gfweocko.html

Go:   name := "Alex"; age := 20
来源：http://dali.ppjwa.cn/Article/details/gt2jquzkhqm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gt2zmmfpeuy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2wvdiymai.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2zarzypuw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhoulong.xyz/Article/details/gt2vyuultlb.html

PHP:  const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2isprltkg.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2vvxhlglg.html

TS:   const PI: number = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2evotfxel.html

Java: static final double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2avzdxbes.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gt2heavmzvs.html

Ruby: PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gt2npicrrgk.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2pygcsjnh.html

[A04] 判断变量类型
来源：http://dali.quarkkingdee.top/Article/details/gt2gykmapfq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sysykeji.top/Article/details/gt2syjulpba.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aizwys.cn/Article/details/gt2alybdaag.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gt2qyimhcif.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2krascawx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gt2llzwtdfn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bliynnvk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gt2pabjxotu.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivtwsaxk.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gt2gbpwepjx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.birdmap.top/Article/details/gt2juupqowr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2okepwsiz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2kavmavrj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2bupfukkn.html

Java: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2pvtcbnmt.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2mqczlecw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2ruktjzuh.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2fmqgdqhi.html

[A06] 字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gt2mmbfqtih.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2krbmgyrd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gt2rqbxzyvv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2mwwdqtos.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gt2jqnawfjp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgbsrmaj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gt2rjgiprnx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gt2rhzlnqhg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcxtjyfm.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2xmqmatix.html

Py:   str(42)
来源：http://dali.jianghu66.top/Article/details/gt2lzfukuyk.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhpwuivo.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddujmnxq.html

TS:   String(42)
来源：http://dali.yj202588.top/Article/details/gt2cflaxvel.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jiagoushi.top/Article/details/gt2nlcuokgc.html

Go:   strconv.Itoa(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2lejmpqcd.html

Ruby: 42.to_s
来源：http://dali.ivvv.top/Article/details/gt2bjhyvrnw.html

C#:   42.ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlgysxba.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2lisuoakg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2mgqtzfym.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ybcxt.top/Article/details/gt2lsztxqiv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2bwtsabmy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyhtqdwo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gt2gmhpwdud.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2vpnsinhe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbygsezd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqcpmfuu.html

[A09] 绝对值与最大最小值
来源：http://dali.dashuyun.cn/Article/details/gt2gupizuxe.html


<!-- 参考信息 -->