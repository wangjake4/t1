代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtopklqdtr.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gtqxifkucv.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gtccbbfcdg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gzhubu.top/Article/details/gtvwbclukt.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtoirwliyw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtibxzcsak.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangtech.top/Article/details/gteptrsmoq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guowangkeji.top/Article/details/gtbqtdjkjn.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gtkxwdaehz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtsohhjjhr.html

[U62] PHP：日期对象
来源：http://dali.daria6918.cn/Article/details/gtnxxlkrdf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrqgnypw.html

[U63] PHP：文件读写
来源：http://dali.hywenlv.cn/Article/details/gtfxlfrnmx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gthkwzxodo.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gtkbredojd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gtmrctzzjl.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gtzjcytzvh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gtijsmoquw.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtbnjcqjph.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtxonocrwe.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gtfdjqjiee.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gtmjakyaju.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gtikiaylvf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gtsbcezput.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gtyakoqqgt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shangyingyoupin.top/Article/details/gtqwonfeoj.html

[U70] PHP：PDO 事务
来源：http://dali.quarkkingdee.top/Article/details/gtkuzvtkgv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gtvhktyumo.html

[U71] PHP：抛出异常
来源：http://dali.jianghu66.top/Article/details/gtokzhrzhd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtkbqehghd.html

[U72] PHP：写错误日志
来源：http://dali.tianlin.xyz/Article/details/gteizltmxd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtxffhlhsl.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gtnjacvvfg.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtfsrlyzzb.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtcnvmygdo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gtcokhbggi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gtfpaljkie.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgypfbqi.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gtirwmqopx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gtjdoorpwc.html

[U77] PHP：模板渲染
来源：http://dali.sysykeji.top/Article/details/gtnzjmjxox.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gtwxuohxps.html

[U78] PHP：单元测试
来源：http://dali.316326.xyz/Article/details/gtjrymdbxj.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gtawnbwxbh.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gtauhvithf.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gtnollwosb.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gtkhvzzoab.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtkknkwqnj.html

[U81] JS：初始化项目
来源：http://dali.feifeiyinyue.top/Article/details/gtawttwkou.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtedcrgpcn.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gtppscbsst.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gthhlfvyxt.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangshuangyany.cn/Article/details/gtpoaonyrb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtimqchmuu.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gtuhupwjqm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenzaomai.com/Article/details/gtyjyoyegs.html

[U85] JS：可选链
来源：http://dali.sufxvd.cn/Article/details/gtzqhfdsjr.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gtrproipry.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmricdmy.html

a ?? b
来源：http://dali.shuidangran.top/Article/details/gtlkaausks.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gtgjghozzq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtihqauqwz.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gtawdpnmdj.html

{ ...a, ...b }
来源：http://dali.daria6918.cn/Article/details/gtfsvfeekg.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gtagbfisox.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtfhljaqsl.html

[U90] JS：数字数组排序
来源：http://dali.cdnleiting.top/Article/details/gtgiikvblc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtcxrjucue.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtyoorzdll.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtgqxnlopn.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gtokpzpxpj.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtcyiabiro.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gtyeaxccbq.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gtrqkjjtzg.html

[U94] JS：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwqudqgh.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gtefngxijx.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrtowgkg.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gtytrqlxmz.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gtrqblytpj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtwnccyfgf.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gtofjwpiqz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtjejtbemn.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtlvlhdpnu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gtbnxgllbh.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtdwxtigdl.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gtotqhqzcx.html

[U100] JS：DOM 查询
来源：http://dali.haohaochexian.top/Article/details/gtfcxvuqgc.html

document.querySelector(".item")
来源：http://dali.jinqigufen.top/Article/details/gtzgqfzpsm.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtkweiwvgo.html

el.classList.toggle("active")
来源：http://dali.tianlin.xyz/Article/details/gtbabywdhg.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtboqookwv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gthmthahvr.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gtibhtvzmi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guowangkeji.top/Article/details/gtymbkmydg.html

[U104] JS：防抖
来源：http://dali.tian-w.cn/Article/details/gtmsxqeifk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtqfkollyl.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gteradencr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gtxbrntygb.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxoaionq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gtchoheygn.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtoohxyrnd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtgrhrnedu.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtitcedtzw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gtkukaqxgw.html

[U109] JS：数组分组
来源：http://dali.gogol.net.cn/Article/details/gtvlwftgyw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtcunsqnpt.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gtearbnvpi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gteejyobbh.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtrgcdlzqw.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gtgetcpfum.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gtyfchgrvt.html

"7".padStart(3, "0")
来源：http://dali.pycfn.com/Article/details/gtuiajkmyq.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtqwthbwte.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtzgfcabln.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjedqzuy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtytrxwntr.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtnyeumpir.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtawxmztvr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigufen.top/Article/details/gtbgftaetx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtcahvxjmx.html

[U117] JS：单元测试
来源：http://dali.316326.xyz/Article/details/gtkchfltdm.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtgpvoimnx.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gttbfcgwtr.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtabrtawws.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gtjldssaht.html

npx vite build
来源：http://dali.sxryk.cn/Article/details/gtjqpqnfnw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gtnpjfghmm.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtxknhhope.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtopqdrvgi.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtaknuiryp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtteephrhb.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gttlfstbmv.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gtmqjkiszu.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gtbvpwndqu.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtqejawmpq.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtsxyoryls.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtgdaqgtqg.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtqsveytxj.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gtlijwytld.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtptsndeib.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gtsodbayxc.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtjagjaezz.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gtidgckvmj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gtuqqwtimv.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtklkysvzf.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gtvsyylqxe.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtbyvbpbbw.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gtqtdtfzql.html

Scala .......... 10
来源：http://dali.zhongyouzk.top/Article/details/gtshfcolzl.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtwajbeyrk.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gtfdaneqhu.html

按章节统计：
来源：http://dali.daxiang520.top/Article/details/gtklisxjcu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtezetvgmx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtynyqhhjy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtcujvbxmg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtpftenlxc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gtfzbyblre.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtvqmrgvfk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtlvhugfuo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtuolsffpn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtwwaioqcx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtzkbzhhwb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxpunmhc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtgrdxmtjq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtbyitwlki.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtawhacenk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuetiantiany.cn/Article/details/gtcggahhsr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gttxbarvgc.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtigexyzzr.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gtejqyxhsz.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtwmqnwnyw.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gtogypkvnp.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gtimvdlnic.html

------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtspggmqku.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gtdlwoyiqs.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtgznzxump.html

使用提醒
来源：http://dali.316326.xyz/Article/details/gtapkgytwj.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtpwlkkeks.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gttaqaoghs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gtriddhift.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.bjfxy.top/Article/details/gtnkaamtkq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtujocwsle.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gttbkqigru.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gtxmojlyqx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmgfwopiw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxowtzyeh.html

Common Programming Examples Cheat Book
来源：http://dali.c1oappe.top/Article/details/gtzzfufand.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvycbmgml.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gtzfpzrrjs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gtfvsfqwqx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gtugesrpbb.html

SQL · Bash · C · C++
来源：http://dali.9152youxi.cn/Article/details/gtkasmvbpq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenlongwang.top/Article/details/gtldkoikut.html

【使用说明】
来源：http://dali.wangshuangyany.cn/Article/details/gtctmkhkdc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtvdtmbvoa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cdnleiting.top/Article/details/gtvtdpsbua.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.feifeiyinyue.top/Article/details/gthhithksp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gtdltnbkjy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ydzc1.top/Article/details/gtclvhpblo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gtdalrtjfa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gtaxfaiztv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yueranfly.top/Article/details/gtcgiksoym.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.9152youxi.cn/Article/details/gtozcbnnwm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gtelhtzbgy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtbijoqcvs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gtuqkjejpb.html

【文件统计】
来源：http://dali.zhengqikj.top/Article/details/gtlkudthaz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gtpncnlwif.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtnncldgbf.html

目  录
来源：http://dali.sweek.top/Article/details/gtetwzeukq.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtxgwkledd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gtuqztpkfc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtqvuwkpuw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavvruhes.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtrscqcier.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gtacorwasd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqxpvevjg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtfbauvqlz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtvnjjbqfr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtnullqies.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtdhujfmuj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtfzjzrojb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtvqowphak.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtdqrydzjc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtctvosjaj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gtilwneaia.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtxpynfgad.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.birdmap.top/Article/details/gtqivrijmd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gtualqgqlc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtbjbjldqn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtbjlxvdos.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtwalozalu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwxiugbk.html

A. 基础语法与类型
来源：http://dali.zhiwuduotai.top/Article/details/gtazygdgat.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtupwytciz.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gtgtclhojv.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtzfufafft.html

PHP:  echo "Hello, World!";
来源：http://dali.gotoacloud.top/Article/details/gtwrwgausv.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrmeoevq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guannengcc.top/Article/details/gtbsmdaqks.html

Java: System.out.println("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtbcgfhbft.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtzedssgej.html

Ruby: puts "Hello, World!"
来源：http://dali.birdmap.top/Article/details/gtfmiddipw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzqaahwg.html

[A02] 变量声明与赋值
来源：http://dali.daria6918.cn/Article/details/gtlzxwyqrx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gttfdxngiu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtbymsbgcj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtidnmqxoe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtgzsjllke.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtkmxzyyqc.html

Go:   name := "Alex"; age := 20
来源：http://dali.andypj.xyz/Article/details/gtoeibljlu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gtqaqzqizt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gtjnbaohah.html

[A03] 常量定义
来源：http://dali.chenjidiqi.icu/Article/details/gtetddcmph.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gtwpolruix.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gthjjqilsv.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtiygwnfqx.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtxyxnjcvn.html

Java: static final double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtvgkkylbe.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtiejubgvi.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtgadleref.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtlvmdjage.html

[A04] 判断变量类型
来源：http://dali.dashuyun.cn/Article/details/gtffhmocxk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gtjxkdfmvu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gtaazygldz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtxziwlmpk.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtwvqvnlme.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gtjpwrztaq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenjidiqi.icu/Article/details/gtktxukoay.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gtgrcijyvz.html

C#:   x.GetType().Name; x is int
来源：http://dali.svipenyu.cn/Article/details/gtaqswnlne.html

[A05] 整数除法与取模
来源：http://dali.cqqwz.cn/Article/details/gtgqhdlabl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pycfn.com/Article/details/gtjvlgrypo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtamfhkstp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtuhnknrsj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqibljqj.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtwnhczeqj.html

Go:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtfxyjbecz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gteutpgjvk.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtgxwtmqun.html

[A06] 字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtbkwgwvcf.html

Py:   int("42"); float("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtcuyptyyz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gtdykorgzn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtjkpuhyqu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gaohongyu789.top/Article/details/gtmblvfsol.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtseaelvuc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiezymfob.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gaohongyu789.top/Article/details/gtesxiwrqo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj202588.top/Article/details/gtobzhejdh.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltkrjywi.html

Py:   str(42)
来源：http://dali.tianlin.xyz/Article/details/gtdsdubycq.html

PHP:  (string) 42; strval(42)
来源：http://dali.shzxlz.cn/Article/details/gttvljlbcx.html

JS:   String(42); (42).toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtuknkjpjl.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gtofoaypwe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.iojbl.cn/Article/details/gtbirjdbqi.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gtkkfxbdoa.html

Ruby: 42.to_s
来源：http://dali.wangshuangyany.cn/Article/details/gtwtcllfaq.html

C#:   42.ToString()
来源：http://dali.jinqigufen.top/Article/details/gtwhrzrxeh.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gtetgesalv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtmgizgbdf.html


<!-- 参考信息 -->