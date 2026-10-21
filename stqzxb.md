代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtciuurpax.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtsjqtfzvr.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gttndxtmpd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtlfdutiar.html

[U59] PHP：自定义排序
来源：http://dali.hfpthk.cn/Article/details/gtrjijldmk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtcygrdupb.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtnqwsmctc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gtbbahrzbh.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gtahmdcsox.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtxksivhxu.html

[U62] PHP：日期对象
来源：http://dali.haohaochexian.top/Article/details/gtovjqjnbc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangdashe.top/Article/details/gtfjlzsehb.html

[U63] PHP：文件读写
来源：http://dali.xylfe.cn/Article/details/gtladdkypu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtedmktmfh.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gtyvssdqie.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgadsqfl.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtqknjleeb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gtidrybfbg.html

[U66] PHP：设置 Cookie
来源：http://dali.meibo888.top/Article/details/gtdaanectw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gtjqibbmyu.html

[U67] PHP：处理文件上传
来源：http://dali.iojbl.cn/Article/details/gtulsyjofq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtddaigajc.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtfpyjaoau.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxinkj.top/Article/details/gtbekqmcvn.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gtwgovamhc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.smart0.xyz/Article/details/gtwfevbayg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gtdmgcxjln.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tianlin.xyz/Article/details/gtukhhfieh.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtddvddhgk.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtkhuponeo.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtuymhebey.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhongyouzk.top/Article/details/gtaowcndqx.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenzaomai.com/Article/details/gtnsxwfmuo.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtqogoipem.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gtvycyhvxg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtwzdvsyjt.html

[U75] PHP：依赖注入
来源：http://dali.zhengqikj.top/Article/details/gtcigdeggo.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gtohyjqqdw.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gtzgdpzxgg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hongshengwenyu.top/Article/details/gtklrpkkjz.html

[U77] PHP：模板渲染
来源：http://dali.cashguo.top/Article/details/gtqwgltmnp.html

composer require twig/twig
来源：http://dali.hongshengwenyu.top/Article/details/gtkpxmcliz.html

[U78] PHP：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdlelmrb.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gtvvzbipgb.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gtpzekzgvw.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gtoazremnm.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtulhjtbvk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtvzyfjpef.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtwbjkpizy.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gtxidcriao.html

[U82] JS：package.json 脚本
来源：http://dali.chenzaomai.com/Article/details/gtenawazko.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gtyocrluxy.html

[U83] JS：ES Module 导入导出
来源：http://dali.ybcxt.top/Article/details/gtqtffghdh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtrhexvogo.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gtlbwgvcqa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.0kj1m.cn/Article/details/gttayltvgt.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtolwwiukw.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gtmjnzfbjp.html

[U86] JS：空值合并
来源：http://dali.jlsjyb.cn/Article/details/gtxfxdpqvf.html

a ?? b
来源：http://dali.guannengcc.top/Article/details/gtiuagyomx.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gtoocjelum.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcdozliw.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gtxzfndxwn.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gtgeokgdxx.html

[U89] JS：数组去重
来源：http://dali.xylfe.cn/Article/details/gtuknxpcyg.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtcxdtzkzb.html

[U90] JS：数字数组排序
来源：http://dali.andypj.xyz/Article/details/gtkcvjfulq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtohrtjoow.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtzdifzowd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gtqkqeieyh.html

[U92] JS：深拷贝
来源：http://dali.birdmap.top/Article/details/gtovauuyxa.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtevcfmsxm.html

[U93] JS：模板字符串
来源：http://dali.9152youxi.cn/Article/details/gtamlcjbaf.html

`共 ${n} 条`
来源：http://dali.yangfankeji.com/Article/details/gtgpphwdcf.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjaqrepg.html

const double = x => x * 2;
来源：http://dali.yuanzhike.top/Article/details/gtnqjgkhrg.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtbqscnkyw.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtrvstdegs.html

[U96] JS：async/await 与异常
来源：http://dali.mhx1999.top/Article/details/gtlkyhzjkl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlrlpmodo.html

[U97] JS：并发请求
来源：http://dali.svipenyu.cn/Article/details/gtsfzqcioc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtkycaqvvh.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgfzy.top/Article/details/gticlkabol.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gtryqfxlwv.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gttzbjvtyu.html

el.addEventListener("click", e => {})
来源：http://dali.iojbl.cn/Article/details/gtvckigtos.html

[U100] JS：DOM 查询
来源：http://dali.xuetiantiany.cn/Article/details/gtsuequgqg.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gtnotomdrs.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gtjwuqtazv.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gtldewlhlm.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gtzkbucmmn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gtrlufhsfi.html

[U103] JS：定时器
来源：http://dali.cashguo.top/Article/details/gthocdwbzn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavowjqcb.html

[U104] JS：防抖
来源：http://dali.jinqigfzy.top/Article/details/gtmcdjrhxl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtgbltvluh.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gtnlftzojl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtkpammkes.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gtsjywhyxm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.bjfxy.top/Article/details/gtqfyqccbt.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gtcrdfknix.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjawqhtoo.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gtzumppnih.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gthqkehbht.html

[U109] JS：数组分组
来源：http://dali.xylfe.cn/Article/details/gtrkbcprtl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtxwbtwfpi.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtnewtxvbz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gthepxtgnw.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gttvuevajf.html

new Map(Object.entries(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtmgqczbfb.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gtgtlmeazu.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtjjbqdjpp.html

[U113] JS：正则替换全部
来源：http://dali.zhongyouzk.top/Article/details/gtmizdljaj.html

s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtkazjehut.html

[U114] JS：JSON 深比较
来源：http://dali.wangshuangyany.cn/Article/details/gtpbktjbcv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtyotmbrwp.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtzwkjgrjv.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtonrzldrt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtoxrtydgv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtbzeseuch.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gteswnapkn.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtzbaxdsfr.html

[U118] JS：开发服务器
来源：http://dali.hammf.cn/Article/details/gtmtdqzpjt.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gtydpkclmf.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtmspxqkvz.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtlacmhows.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shangyingyoupin.top/Article/details/gtqbzjjlob.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gtwwplqcwe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtityehmlq.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtvnvxykwv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtspblhyds.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gtyhrkoptd.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gtkwndxgiz.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gtsocldtxp.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gtqosifhni.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gtzzihfwgz.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtbyjryknj.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtxsfrygsx.html

Ruby ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtbtsiptvq.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtuzwboqpn.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtfaksbiwz.html

C++ ............ 30
来源：http://dali.xuetiantiany.cn/Article/details/gtmckiabyw.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gtxrqntjec.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gtvtqqpssg.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtbwwzewku.html

Swift .......... 15
来源：http://dali.sysykeji.top/Article/details/gtmbqlcrry.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gttedgylsh.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gtskiupcqn.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gtwylzwznu.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtgnzshman.html

合计 ........... 2106 条
来源：http://dali.sufxvd.cn/Article/details/gtvmzxtxlo.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gtjhkjcgng.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtzlmwtszq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtjbnlefzq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtqguvlgyn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtwsylskrp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gotoacloud.top/Article/details/gtkxxxggju.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtbwwfceqq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtgojbwwzb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtadeqfugw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtxwvngyjy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtdzdlheib.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtonmiwvwb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtoxkekxhn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gteblnxxrs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtmeqpcfmg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gotoacloud.top/Article/details/gtakqezyvz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gthcpltswd.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtzigyamcx.html

R Bash 专题                             80
来源：http://dali.yongpay.top/Article/details/gtbqgfnxnu.html

S C / C++ 专题                          60
来源：http://dali.smart0.xyz/Article/details/gtdfipjsud.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtspxibyqj.html

U 高频实用片段                         120
来源：http://dali.gzhubu.top/Article/details/gtcfyaivmt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtoukjoyhc.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gtxgazgifi.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopvtieiq.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtnhoomwmd.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtowiybfcm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gtqxotmkqe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gtgbojdiqu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gtzxnsomdo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yueranfly.top/Article/details/gtsjvmgqaj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gtwplqwonc.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtkpyvuejo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaufmopae.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258.top/Article/details/gthctrukkz.html

Common Programming Examples Cheat Book
来源：http://dali.xuanzx.com/Article/details/gtdoqxehgw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtejbzjhdo.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gtlzpbskdh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobhbupyz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gtoikfbwqd.html

SQL · Bash · C · C++
来源：http://dali.andypj.xyz/Article/details/gtxxgevuaz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gteblvzhwq.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gtyhmgysjy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gtafhaxqrs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gtttldsqwm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gtbmsqmohv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gtetrjakxc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gtuwvvqotp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gtybihhstn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocqwogsy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gtyokzrjmf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dianchejie.cn/Article/details/gtmmhxrogr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangdashe.top/Article/details/gtbgcspwfk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gtspmbwepv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhengqikj.top/Article/details/gtuwxzuvne.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtrhqofffu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yvedp.cn/Article/details/gtipdehtvv.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtgxdsgcnr.html

目  录
来源：http://dali.c1oappe.top/Article/details/gtyywzqlrf.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtssnqysfw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtvfzuarge.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gtqappdglq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtwghlibue.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtetcjzotq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yvedp.cn/Article/details/gtryulrzat.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtmlogsvzt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtvccuxmoc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtlohafqzl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtxkgxaozi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtcvxjixjx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtjtezauwg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtdswxxdkh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbchkjus.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtcawkjzvv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.c1oappe.top/Article/details/gttlqhqntz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtnnckarxy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtvawzurtz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtinueqbxr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dashuyun.cn/Article/details/gtdbgiksno.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtjsozqrru.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtzscqypfh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuwawhkzy.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gtcffqwuqg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxikunvcs.html

[A01] Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtwuaqnbcq.html

Py:   print("Hello, World!")
来源：http://dali.hfpthk.cn/Article/details/gtqlvxdypq.html

PHP:  echo "Hello, World!";
来源：http://dali.yueranfly.top/Article/details/gttomymmsa.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhglgrrv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xylfe.cn/Article/details/gtnmkqoqfq.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtjstawlab.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hfpthk.cn/Article/details/gtzsikfhzv.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gtmifvjpww.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtwmzujmcu.html

[A02] 变量声明与赋值
来源：http://dali.bjfxy.top/Article/details/gtdqtdyjrr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.meibo888.top/Article/details/gtmtirqlzc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.fengsongda.top/Article/details/gtczjbgyxk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtpqxfjttk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.redwolf501.top/Article/details/gtnsnqowkp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gthvvxdlxv.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gtzxsjjskj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tian-w.cn/Article/details/gtwuodkutq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gthwnxmpmu.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gtktrnsszr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jiagoushi.top/Article/details/gtkcuwalzn.html

PHP:  const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadmdsnno.html

JS:   const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtamvaxhmi.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtvdabnhim.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtcqhjaorq.html

Go:   const PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gtldabrpow.html

Ruby: PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gttjdpnybw.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtnngkxywx.html

[A04] 判断变量类型
来源：http://dali.redwolf501.top/Article/details/gtrrqsxqud.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigufen.top/Article/details/gtgixddyyz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gtiarimgmv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gtvnqihcfr.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtyupctjsx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jiagoushi.top/Article/details/gtjeuiyrvg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.kuanghao11.cn/Article/details/gtcmweabzu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pengpengdd.cyou/Article/details/gthgjigncq.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gtmvwgiqpd.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gtpzvxaqoz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.pengpengdd.cyou/Article/details/gthmgaqabu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtxhzueccc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gthrbjtqas.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtdisrdpel.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtgkrorzmh.html

Go:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gttiutmbul.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtocllahpm.html

C#:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtgnfotfbl.html

[A06] 字符串转数字
来源：http://dali.316326.xyz/Article/details/gtezhkjegg.html

Py:   int("42"); float("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtrnnssuur.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sufxvd.cn/Article/details/gttzprbyuc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yvedp.cn/Article/details/gttpecjiih.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtimvdvpin.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangdashe.top/Article/details/gtbakxtnmx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ppjwa.cn/Article/details/gtqcsqhpgk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gtztkmtkzj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ydzc1.top/Article/details/gtcnblbanj.html

[A07] 数字转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtuwaaznhi.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gtokvaetaj.html

PHP:  (string) 42; strval(42)
来源：http://dali.jyoumei.cn/Article/details/gtofnnmtgr.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gtnbeyebuq.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gtpsnfvxxg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.snrcjt.cn/Article/details/gtmcuzcbhj.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gtjchmcwtf.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gtibjicpax.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtqqxkgmtj.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcbhgobv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtymfueoly.html


<!-- 参考信息 -->