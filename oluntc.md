代发 wailian999

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gtmgiocbyj.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkreqxxa.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvornkvi.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtwzqkgikq.html

[U53] PHP：空合并运算符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwkrjwjq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gtyptgzhvn.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gtlkmcmvye.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gtrupcjmak.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gtiashspxr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtjtyqptmh.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gtpojbdocv.html

f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttaevguhw.html

[U57] PHP：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtdhqpzysb.html

"值: {$a}"
来源：http://dali.ivvv.top/Article/details/gtqoouzkpj.html

[U58] PHP：数组三件套
来源：http://dali.zhongyouzk.top/Article/details/gtfixemxsv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtdqklbcei.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gttxsiyhlm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtptpzutag.html

[U60] PHP：JSON 编解码
来源：http://dali.shuidangran.top/Article/details/gtaqztxpjt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenlongwang.top/Article/details/gtfdutdtwn.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gtlkgqctuk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtbfutqqqo.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gtylvjjaue.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gtmpgfdwjq.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtnkcvtdkk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigufen.top/Article/details/gtvzyrcswf.html

[U64] PHP：目录遍历
来源：http://dali.zhongyouzk.top/Article/details/gtzjahcson.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqdwvskm.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtkpmmkfqq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gteofmtsgy.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gtdyvcmaym.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gtxmbyxlvd.html

[U67] PHP：处理文件上传
来源：http://dali.hysaishi.cn/Article/details/gtflwhhepe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gttqinfzpi.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtogpqvvow.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hfpthk.cn/Article/details/gtrjntbncq.html

[U69] PHP：PDO 预处理
来源：http://dali.mhx1999.top/Article/details/gtjisncpvj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gtotajsedu.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gtgagrcadv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gtrmiumvzt.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gthxsjsgwj.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gtljqsbkpr.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gtgtwokrjl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gtnpujrbht.html

[U73] PHP：读取 ini 配置
来源：http://dali.gogol.net.cn/Article/details/gtxfsroywv.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtsowlkwka.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtikcerkso.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gtkjvkddbh.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtngscmtcb.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gttsatvuja.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtvjwntrlu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ybcxt.top/Article/details/gtcsrbfsis.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtvmbxwnqa.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtpkuwhebt.html

[U78] PHP：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtkbzumqwk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gtiixnddju.html

[U79] PHP：静态分析
来源：http://dali.zhongyouzk.top/Article/details/gtnjqcouxt.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtmkrndrdg.html

[U80] PHP：代码规范修复
来源：http://dali.snrcjt.cn/Article/details/gtngfjukpq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gtckwjcavd.html

[U81] JS：初始化项目
来源：http://dali.gaohongyu789.top/Article/details/gtninoevgl.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gtlklhedid.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtvsylggzr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fzhhl.top/Article/details/gtcxbscxgi.html

[U83] JS：ES Module 导入导出
来源：http://dali.jlsjyb.cn/Article/details/gtwcasvqvl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtfpzdhbav.html

[U84] JS：CommonJS 写法
来源：http://dali.ydzc1.top/Article/details/gtinrrbryf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.vqdsnc.cn/Article/details/gtidtjxnaa.html

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gtsbbttcdl.html

a?.b?.c
来源：http://dali.xylfe.cn/Article/details/gtghsldfck.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtfntkjnrs.html

a ?? b
来源：http://dali.0kj1m.cn/Article/details/gtulltpsom.html

[U87] JS：解构默认值
来源：http://dali.feifeiyinyue.top/Article/details/gteculderw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvesjucio.html

[U88] JS：对象展开合并
来源：http://dali.shangyingyoupin.top/Article/details/gtavgettpo.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gtdywkvoul.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gteifgkitq.html

[...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtjmzomdwf.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gttfadhyhe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtcecruqij.html

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gtrdvphncf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlukeutt.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtverfnwle.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtdzbjxudk.html

[U93] JS：模板字符串
来源：http://dali.chenlongwang.top/Article/details/gtxjxmhbrl.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gttnvxcavo.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gtintqafci.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtnqmuffba.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtqrxyxgls.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtxhdpjcgf.html

[U96] JS：async/await 与异常
来源：http://dali.kuanghao11.cn/Article/details/gtxktngyto.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtxxyxrofx.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtojwkzsfh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtackgribr.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gtpbkczqir.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gtyilfhwyd.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtygputghw.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gtfcwycrve.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtyzxxebao.html

document.querySelector(".item")
来源：http://dali.jqgfzy.top/Article/details/gtfsigutws.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtuugxxggf.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gteofmslud.html

[U102] JS：本地存储
来源：http://dali.hnqzz.top/Article/details/gtyqrsfgjg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtztcafkgs.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gtfnnoeree.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gtpeymwzpw.html

[U104] JS：防抖
来源：http://dali.shanyushiyangtech.top/Article/details/gtxohekzvh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtwahoguvp.html

[U105] JS：节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbfkujqy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtzamnskpy.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gtfevhedcp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gterginbld.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtfgptgfdm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtjsekzfde.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gtvqlzrbyt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gttepksqkx.html

[U109] JS：数组分组
来源：http://dali.zhixingplan.top/Article/details/gtxgzkzycm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtqjoesylj.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtwpnmwqvb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtpxrcajns.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqkpbjdn.html

new Map(Object.entries(obj))
来源：http://dali.jqgfzy.top/Article/details/gtmgvppfrf.html

[U112] JS：字符串补位
来源：http://dali.xuanzx.com/Article/details/gtnitjxwfb.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtrmuuboqh.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gttcrifyid.html

s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtrhroqock.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtkdctfqlg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtcobdbijk.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtnjspijal.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtcdlmfaqe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gtwntcsfhm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoottyge.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtachgiwkv.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtutrxezxw.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtxqtvoelu.html

npm i -D vite;  npx vite
来源：http://dali.ivvv.top/Article/details/gtfojfbodw.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gtsdodfhon.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtgwqyanwq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gtfarnzzra.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomzuvjun.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttqvquput.html

统计汇总
来源：http://dali.kuanghao11.cn/Article/details/gtxzfiggfp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsqiqfltu.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtqowclxfc.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtjllyqyws.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtrsuafkit.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gtuqhekwhv.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gtodijzbry.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gtwkagmbdh.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gthrdqevyz.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gthqyxuiaz.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtedklbueu.html

C .............. 30
来源：http://dali.sxryk.cn/Article/details/gtlphavhlu.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtflqifmuv.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtjyqouced.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gtdphpdued.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtitrtfltr.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtbccvxrpq.html

Lua ............ 10
来源：http://dali.nanxuanxn.top/Article/details/gtjkumncxn.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gthberkdvb.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gthvdebwpv.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtfmyefofk.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gtnzqwtqxh.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtqbedjwoy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtgwjsvdmm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtvmqlyoia.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtvjgtwgwn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrjbkzms.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuetiantiany.cn/Article/details/gtgxtuqcpa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtjekbmfnc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtzbueyqnp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtbgjfobdt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtrvbzxamr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtjfphzewe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtywtutdua.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtearvkmkh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvrdhhdw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtubstabmy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtjfspuzxs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtqgktnbst.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gtkvmkpyfc.html

R Bash 专题                             80
来源：http://dali.yuanzhike.top/Article/details/gtzckhyzlt.html

S C / C++ 专题                          60
来源：http://dali.cucudq.cn/Article/details/gtaiduromd.html

T 其他语言补充                          60
来源：http://dali.ppjwa.cn/Article/details/gtlzdarfjr.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gtwhfplbss.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gthnslygro.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtubecmjxp.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtmuqbikga.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gtewbdnjsc.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtzaaxkmpv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcimdjcmm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gtuponyuni.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gtxodzsgzu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtxcujscrf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhoulong.xyz/Article/details/gtylnjjlkd.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtfwqcgpbf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkzqbtzrw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmdktlxk.html

Common Programming Examples Cheat Book
来源：http://dali.xinyue.icu/Article/details/gtoapyhldx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcptyykgp.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gtnvwjcsdy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.vqdsnc.cn/Article/details/gtjoiroeqr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtqpiubjci.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gttrskdenb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gtbrvtemob.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtkuecqbma.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.birdmap.top/Article/details/gttiodafek.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gtdrtqofhu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gtkfeybkee.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.0kj1m.cn/Article/details/gtbpbrpwbb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangshuangyany.cn/Article/details/gtizqbiewk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gtgslrkyad.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.redwolf501.top/Article/details/gtwnvlmjxu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shangyingyoupin.top/Article/details/gtrxxpssev.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.svipenyu.cn/Article/details/gtgrkumucp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.birdmap.top/Article/details/gtxyqpakom.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gtxlojxijo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.nwbrower.top/Article/details/gtpzdeosso.html

【文件统计】
来源：http://dali.cdnleiting.top/Article/details/gtgkwswsvd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tianlin.xyz/Article/details/gtztzwjkie.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtletaaswt.html

目  录
来源：http://dali.0kj1m.cn/Article/details/gtdqkzznna.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtjappyzkn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gtxlvzmghd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gteejrjtnj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtspqdhkyx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtbzyxnbdw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xinyue.icu/Article/details/gtgpqyvlmu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkdcmkho.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtmbtobdwl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gtbfhaidql.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgvunvff.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtijlhuksw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfztqojhe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtofwgylax.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtbdryjvsj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gtqzsfekpk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gtmxjqgsyk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtwzjeyaol.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ppjwa.cn/Article/details/gtfffsijaw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gtjrgudrds.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gtevjfztst.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtobhoiodl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtjfqxxbtc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlompkecs.html

A. 基础语法与类型
来源：http://dali.hysaishi.cn/Article/details/gtmymntxoh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtyygljvnm.html

[A01] Hello World
来源：http://dali.c1oappe.top/Article/details/gtmktuvfqd.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtzuvhhvam.html

PHP:  echo "Hello, World!";
来源：http://dali.yvedp.cn/Article/details/gtrlwzphmr.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtlguyyiug.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ppjwa.cn/Article/details/gtpclkugnn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtnmdvswzs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gtfcknmyly.html

Ruby: puts "Hello, World!"
来源：http://dali.sysykeji.top/Article/details/gtnjidaaxd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtrlxfdbwq.html

[A02] 变量声明与赋值
来源：http://dali.jinghuilouyu.cn/Article/details/gtliagpnun.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pycfn.com/Article/details/gtfuaybdtq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtlzcyrjqp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.meibo888.top/Article/details/gtzimoawin.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gtikfwtklr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtwiwknzvf.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gtugigqvht.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gtomxxugqx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtomgxltdb.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gtdcggcpxt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtthqwchkz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtyiwkhwvy.html

JS:   const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtykvutmil.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtdusspzww.html

Java: static final double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtuadktcpp.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtwzwbeqmf.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtukcfpdmy.html

C#:   const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtzuhxpaxp.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gtebzlnveh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.wangshuangyany.cn/Article/details/gtjnmgioka.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.birdmap.top/Article/details/gteuekggfx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtspjgofks.html

TS:   typeof x; x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gtgzrtxqpc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pycfn.com/Article/details/gthaekapbk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtqnefmwbi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hywenlv.cn/Article/details/gtsjjdlubn.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gtxcupcaen.html

[A05] 整数除法与取模
来源：http://dali.mhx1999.top/Article/details/gtbhxanydb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gtsubngcgo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtesjytgef.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtevbqrwuw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtndqhykib.html

Java: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtzbsoynen.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtfnnzrzaj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtrareprvl.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtcqnqauey.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtnbmxcujn.html

Py:   int("42"); float("3.14")
来源：http://dali.fzhhl.top/Article/details/gtadjkjant.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cucudq.cn/Article/details/gthnsqgjjx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gterubuvik.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtrfvbuyti.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtdixvwsru.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hywenlv.cn/Article/details/gtjubntvhg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gtcjwlaplx.html


<!-- 参考信息 -->