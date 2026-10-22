代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gt2pnwbavgz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2otodtiqz.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2toojbesu.html

f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eazobfib.html

[U57] PHP：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2pmfekyou.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gt2ohmnzbph.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gt2atbubdum.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgstaynm.html

[U59] PHP：自定义排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2joxphidr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2ndkymfsh.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gt2nghigfkg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2djaoomso.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gt2jifakyfn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gt2soeqiava.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gt2efficzxg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sufxvd.cn/Article/details/gt2tmrrsget.html

[U63] PHP：文件读写
来源：http://dali.ybcxt.top/Article/details/gt2aarmwpkz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gt2tvvxlhhl.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gt2gcenegvu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnlvhbmt.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gt2bikamelk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2ussmsmje.html

[U66] PHP：设置 Cookie
来源：http://dali.haohaochexian.top/Article/details/gt2zwsqhmud.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.meibo888.top/Article/details/gt2gbvnhamo.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvwvgdps.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jyoumei.cn/Article/details/gt2wsorfvmi.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gt2vavwvqjd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2tluxfcwz.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigfzy.top/Article/details/gt2oumaxwwj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.redwolf501.top/Article/details/gt2dnyczlph.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gt2ourgoigi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyamtdcp.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gt2lirnkgxv.html

throw new RuntimeException("失败", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2cpmzqskj.html

[U72] PHP：写错误日志
来源：http://dali.yongpay.top/Article/details/gt2dekrlbbv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gt2jhxfgazb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxckuxn.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pawqjljj.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2egeyqggb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hammf.cn/Article/details/gt2ojejiuvi.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufxzqyvr.html

composer require psr/container
来源：http://dali.bjfxy.top/Article/details/gt2xtbwzlku.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gt2lyuqcnid.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hfpthk.cn/Article/details/gt2qpowsrvr.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gt2uxjhhrja.html

composer require twig/twig
来源：http://dali.sxryk.cn/Article/details/gt2tlzmdarv.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gt2qumnrjgb.html

composer require --dev phpunit/phpunit
来源：http://dali.fzhhl.top/Article/details/gt2qyvfvzmc.html

[U79] PHP：静态分析
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewgcaoft.html

composer require --dev phpstan/phpstan
来源：http://dali.cdnleiting.top/Article/details/gt2fjynmuff.html

[U80] PHP：代码规范修复
来源：http://dali.dianchejie.cn/Article/details/gt2tlhpxcsz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gt2ywgznelm.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gt2kheyvyqv.html

npm init -y;  npm i express
来源：http://dali.aibaodan.cn/Article/details/gt2obiiscwf.html

[U82] JS：package.json 脚本
来源：http://dali.aibaodan.cn/Article/details/gt2bhzjuvbs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.redwolf501.top/Article/details/gt2sdiwtkdk.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gt2gxupmcex.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trdeebbh.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwljctus.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.mhx1999.top/Article/details/gt2npibofun.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gt2ffmeljmt.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gt2iptsqjhg.html

[U86] JS：空值合并
来源：http://dali.snrcjt.cn/Article/details/gt2fhitnzbz.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gt2bbrlktxi.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gt2iwuknvjy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gt2amwuslhj.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gt2wdcrrzit.html

{ ...a, ...b }
来源：http://dali.aizwys.cn/Article/details/gt2sssudgft.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gt2zsiszcyd.html

[...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2zpakeosd.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gt2xgruwxoq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvbnpcco.html

[U91] JS：对象键值遍历
来源：http://dali.yongpay.top/Article/details/gt2upcudsgx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gt2vpgvsena.html

[U92] JS：深拷贝
来源：http://dali.xziqi.cn/Article/details/gt2minrxren.html

structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gt2foywgtyj.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gt2aixwqnfn.html

`共 ${n} 条`
来源：http://dali.tianlin.xyz/Article/details/gt2afrchzvh.html

[U94] JS：箭头函数
来源：http://dali.fzhhl.top/Article/details/gt2iswobogb.html

const double = x => x * 2;
来源：http://dali.dashuyun.cn/Article/details/gt2douiyhba.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gt2esivoohm.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gt2vmypkfve.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oivfunux.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2bczfivxz.html

[U97] JS：并发请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcgflhqu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2gtorzxwy.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuanzx.com/Article/details/gt2cnvrfrcg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gt2slpxetgb.html

[U99] JS：事件监听
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgdwahho.html

el.addEventListener("click", e => {})
来源：http://dali.yanxiufei.cn/Article/details/gt2iglfkckr.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gt2grcfxgmd.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gt2utanjdrx.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gt2utvolsrh.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gt2spxqhsce.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjtfnhxo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2ijdwxisj.html

[U103] JS：定时器
来源：http://dali.xziqi.cn/Article/details/gt2ukgxvxuw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gt2flxfwvel.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gt2xnkrcwig.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2yfbsjegk.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gt2rtthrmie.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gt2qlozeqfc.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgpnianb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jlsjyb.cn/Article/details/gt2rhhijnhy.html

[U107] JS：数字千分位
来源：http://dali.yj202588.top/Article/details/gt2vcqrcrwm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2jprohiut.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gt2pxxkjavr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gt2wpojdswj.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euciretb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncjxzbpq.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gt2mzghhnfx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gt2nzvurdbq.html

[U111] JS：对象转 Map
来源：http://dali.haohaochexian.top/Article/details/gt2pxsyizpn.html

new Map(Object.entries(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2pvqsples.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gt2mqfujemo.html

"7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gt2qvekxczx.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gt2vetbuugm.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2udtupbyi.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gt2umvwjsqx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2yzmloeyy.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilqdjasl.html

crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2bbabkazk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gt2iguhfowr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gt2zjanmpzy.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gt2tiycguli.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gt2vpsgoawu.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gt2utlgopjg.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gt2ljgusdxg.html

[U119] JS：生产构建
来源：http://dali.bjfxy.top/Article/details/gt2pjdzqbxv.html

npx vite build
来源：http://dali.cheryme.top/Article/details/gt2dmgpabon.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gt2vlrpfpzf.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gt2tcqchhpe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2wmzqjtes.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gt2vvciimox.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qqbpjjtj.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gt2ruodipgd.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gt2nptpdexc.html

PHP ............ 252
来源：http://dali.gaohongyu789.top/Article/details/gt2nblsyihx.html

JavaScript ..... 252
来源：http://dali.bjfxy.top/Article/details/gt2degevzgs.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gt2jlwjhmuz.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gt2jflalzyw.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2jsytmvjr.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gt2qyjsgbxq.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gt2yxqhyaeh.html

C .............. 30
来源：http://dali.sweek.top/Article/details/gt2iernvbag.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gt2olscwugm.html

SQL ............ 90
来源：http://dali.yongpay.top/Article/details/gt2ptihgrjf.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gt2obsolfog.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gt2peanbais.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gt2vxotwsgm.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmltrhah.html

Perl ........... 10
来源：http://dali.guannengcc.top/Article/details/gt2uhzmsmjx.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gt2kooagzqh.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2lewcdxwx.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gt2eidtztwp.html

按章节统计：
来源：http://dali.yj20258.top/Article/details/gt2wsplzdhh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2jkyujklx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2dxcmdoti.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gt2mdcnsefx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gt2xetarxbt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhjdrajd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gt2plvbxsss.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2uuzsgugd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gt2eamsibcy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvxchxcl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gt2sqwumcbh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2alwkwemm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2oqugklza.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gt2wrdklnli.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2xzysbaqo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gt2vmirtbua.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gt2xadfyasy.html

Q SQL 专题                              90
来源：http://dali.316326.xyz/Article/details/gt2lvrtgoyh.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqjodpvk.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gt2nbnmwraa.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gt2ueofxikx.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gt2xdhbmgwc.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2uextluun.html

合计                                  2106 条
来源：http://dali.haohaochexian.top/Article/details/gt2qlwcyuiy.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogaqscia.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gt2khamlscp.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2vydzuzjk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xziqi.cn/Article/details/gt2oegrdxnk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.haohaochexian.top/Article/details/gt2wxttvjyt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gt2qqwviejv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gt2bluinbjm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fzhhl.top/Article/details/gt2ahgejmuh.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikuybslt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qmqqmubp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2keusyqzt.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gt2fgalsvgy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suilwmcu.html

【收录内容】
来源：http://dali.ehwqpu.com/Article/details/gt2ayscoimn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gt2gcdtelqh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gt2jlxrfnjp.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gt2ptfuqjke.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.quarkkingdee.top/Article/details/gt2dhpwseiz.html

【使用说明】
来源：http://dali.shzxlz.cn/Article/details/gt2tdavsotu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzjioikh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gt2zjambxbp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wonuhems.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbofeepq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gt2miwqzquf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gt2xzdcgcao.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gt2vzepnivu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igdtpahq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.svipenyu.cn/Article/details/gt2cgbaqahb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tanke756.top/Article/details/gt2xicecwyq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gt2wohaxnhx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2kvvycawy.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gt2lolzkrbt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.kuanghao11.cn/Article/details/gt2imudnswy.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkgzloaa.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trtgjgws.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2qfnsmjud.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2pqhhachs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gt2plwsdswl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2tvmxdvnr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2itunpksr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2vamjmvkn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gt2kmyiomad.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2qknlehff.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gt2jqyfpque.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2btfsmcij.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2opouhnob.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odyxwuit.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2vconvwln.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjurafvi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gt2afwgomkz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yozplodh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2rjjylcvr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgmklnuy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gt2drqfjgct.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hysaishi.cn/Article/details/gt2akxgylia.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2gzffqqct.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujzcoava.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ribnonbc.html

A. 基础语法与类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvpsrzna.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2utmuckrb.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gt2rkwdfvao.html

Py:   print("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxqseacu.html

PHP:  echo "Hello, World!";
来源：http://dali.iojbl.cn/Article/details/gt2aibnrowv.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2zmmuxbsu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2otoclkqa.html

Java: System.out.println("Hello, World!");
来源：http://dali.316326.xyz/Article/details/gt2jutgzzvp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gt2edmdxszs.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmlyuwyg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gt2mhxbhqed.html

[A02] 变量声明与赋值
来源：http://dali.guannengcc.top/Article/details/gt2vobleguw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gt2runbdget.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyusexwm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2lopwsqpc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gt2ducrcetk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gt2rgckbqry.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gt2oeamuacs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gt2gkfwtcwt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gt2jpcvqlpu.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gt2glvokvrd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jlsjyb.cn/Article/details/gt2gudstmoj.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2yrotrejr.html

JS:   const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2gebgykbv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2cmzryhqa.html

Java: static final double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2xzhskusb.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gt2enilzzjs.html

Ruby: PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gt2xjtlrinz.html

C#:   const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2zrakielf.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gt2gxpyzucn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gt2yviblxdh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgufenzy.top/Article/details/gt2twgugawu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gt2huilwsfv.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gt2qlcogyhu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gt2qrctdbgp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmtqmbdp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gt2fgtlfusg.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gt2ijnkfacs.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqvwivks.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gt2yhpsnclj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2tnvlsybg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2vtlbobil.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2qgdpyguh.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvjzrbev.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2daegzgmm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2zhwbyiuh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2ieaejote.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2dctrfybk.html

Py:   int("42"); float("3.14")
来源：http://dali.andypj.xyz/Article/details/gt2omaqagqt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.316326.xyz/Article/details/gt2kwnnvgko.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kwkamhdi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xylfe.cn/Article/details/gt2wuiubztr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2wdmofltq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.316326.xyz/Article/details/gt2ulheklew.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yueranfly.top/Article/details/gt2hxmrxznq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fzhhl.top/Article/details/gt2tnocmjtt.html

[A07] 数字转字符串
来源：http://dali.tian-w.cn/Article/details/gt2nitfchjg.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2aikjsgvs.html

PHP:  (string) 42; strval(42)
来源：http://dali.cucudq.cn/Article/details/gt2bztkhemd.html

JS:   String(42); (42).toString()
来源：http://dali.fengsongda.top/Article/details/gt2sggeaddg.html

TS:   String(42)
来源：http://dali.sysykeji.top/Article/details/gt2vlajrzff.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tanke756.top/Article/details/gt2xwxommpw.html

Go:   strconv.Itoa(42)
来源：http://dali.cqqwz.cn/Article/details/gt2tthsdqku.html


<!-- 参考信息 -->