代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtdkcvumdx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtifgxebik.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gtctwssuun.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtgmznculz.html

[U57] PHP：字符串插值
来源：http://dali.birdmap.top/Article/details/gtyhcdjvij.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gtkijlzxwm.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gtbefiucjj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtsybclwnj.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gtaqtevmed.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtddddvfwp.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtujwwbhfl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtjmkrsigt.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gtfjvwsccv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtigzqiqob.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gttjjhtoxv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigfzy.top/Article/details/gtvkuwerbb.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gtscvpupla.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gtkulqkroo.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtysrrtfef.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shuidangran.top/Article/details/gtfuxfjqnf.html

[U65] PHP：会话
来源：http://dali.jianghu66.top/Article/details/gthkyfpzvt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtxwqmggue.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gtqrybzcjc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gtucqggjtv.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gtfapqncjk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gttbbnsvry.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdouexwn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gtkulyzmwe.html

[U69] PHP：PDO 预处理
来源：http://dali.c1oappe.top/Article/details/gtmidxoyws.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhixingplan.top/Article/details/gtfstnszvi.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtztpxwcda.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtdzbzfins.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtzbvfuyzk.html

throw new RuntimeException("失败", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtkcpcsukf.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gtxiisgrru.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenlongwang.top/Article/details/gtwopwcolq.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gtzjcphrtp.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtjrbunzsv.html

[U74] PHP：读取环境变量
来源：http://dali.yonumen.top/Article/details/gtfnvycbzx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gtlrnyyypz.html

[U75] PHP：依赖注入
来源：http://dali.zhiwuduotai.top/Article/details/gtqoyottzf.html

composer require psr/container
来源：http://dali.jinqigufen.top/Article/details/gthetmzobt.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gteeaegrak.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtwrbpmiai.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gtufsuirtr.html

composer require twig/twig
来源：http://dali.xylfe.cn/Article/details/gtzcczcbtr.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtgoklcqml.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gttuxzytup.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gthlevgqli.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gtdamowhpo.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gtsowterja.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gtfizwhauy.html

[U81] JS：初始化项目
来源：http://dali.zhiwuduotai.top/Article/details/gtmjxwfgmj.html

npm init -y;  npm i express
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxikgkun.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gtdpdcolvm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.haohaochexian.top/Article/details/gtbomuwlmm.html

[U83] JS：ES Module 导入导出
来源：http://dali.jianghu66.top/Article/details/gtnfhqtwgo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtuuxrldsj.html

[U84] JS：CommonJS 写法
来源：http://dali.aibaodan.cn/Article/details/gtlefkusvw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gttkpnmgbg.html

[U85] JS：可选链
来源：http://dali.c1oappe.top/Article/details/gtzhprvswb.html

a?.b?.c
来源：http://dali.birdmap.top/Article/details/gtuldwcpsc.html

[U86] JS：空值合并
来源：http://dali.yuxming.cn/Article/details/gtmqvkptxq.html

a ?? b
来源：http://dali.andypj.xyz/Article/details/gtuevjucxt.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtpppyrfvu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtjthzdtvo.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gtgqsdofrf.html

{ ...a, ...b }
来源：http://dali.chenjidiqi.icu/Article/details/gtbevfikqw.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gtdxwpwmdu.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtpbjfbghj.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gthotxjmfu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgntlromb.html

[U91] JS：对象键值遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpcxpymm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpwjlmmr.html

[U92] JS：深拷贝
来源：http://dali.sysykeji.top/Article/details/gtschzktwp.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtlohzbayt.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gtmevkmolf.html

`共 ${n} 条`
来源：http://dali.iojbl.cn/Article/details/gthficwehh.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtylbzuirc.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gtayhxwgxb.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtzkxfyeap.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gtmafkdbxs.html

[U96] JS：async/await 与异常
来源：http://dali.havefunace.top/Article/details/gtlpjouhvf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gthgkzuwlz.html

[U97] JS：并发请求
来源：http://dali.hysaishi.cn/Article/details/gtvjhbqtjr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtlavlewkm.html

[U98] JS：fetch 带 JSON
来源：http://dali.sysykeji.top/Article/details/gtiumuuhrz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtjppylqdj.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtombazlmg.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gtadcaehfc.html

[U100] JS：DOM 查询
来源：http://dali.snrcjt.cn/Article/details/gtyktgtwko.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvpeutlu.html

[U101] JS：classList 操作
来源：http://dali.jqgfzy.top/Article/details/gtsiwgtdpl.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gtiyiezeva.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gtfsjtgfqq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gteodsextr.html

[U103] JS：定时器
来源：http://dali.sysykeji.top/Article/details/gttxdedxtf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gtokjuhfci.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtdskqhkvh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtljapsicg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtsgshmbqv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gtkxzzaugp.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gthvqnsncp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnshgfkyh.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtguesmbru.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtimcmmspu.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaswgjfg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtwhngplcm.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtfqbzjivl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtjmestvuh.html

[U110] JS：数组分块
来源：http://dali.fzhhl.top/Article/details/gtvdsehudz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuocbcgti.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gtkjemdgxt.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtnhskmyzv.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gtxxqjdnus.html

"7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtxbaokbck.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtmaytcclu.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtkursmiby.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtanlylcuq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gthwfknjpn.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtfsphipox.html

crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtktuknrnx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gtvyqjecan.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gtevrrfpro.html

[U117] JS：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtwscdbmqs.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtjxpgmtph.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gtirmuupaa.html

npm i -D vite;  npx vite
来源：http://dali.nwbrower.top/Article/details/gtlyktwlzd.html

[U119] JS：生产构建
来源：http://dali.nanxuanxn.top/Article/details/gtlacxgcwo.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtoioteevt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfowrpvnq.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gttfowwbnf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtomvspkdz.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtqbxgkzuk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqjgkkogy.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtccnnfpnk.html

Python ......... 252
来源：http://dali.9152youxi.cn/Article/details/gtpgogiumh.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gtwpnoobza.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gtzqhatirx.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gtszysypmq.html

Java ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtvdwfckpf.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtybiikqdo.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtlbhviptl.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtcaftodoy.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gttshncaqm.html

C++ ............ 30
来源：http://dali.hnxiangtu.top/Article/details/gtycuahxml.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtmduashpl.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtmgikiwvo.html

Kotlin ......... 15
来源：http://dali.zhengqikj.top/Article/details/gtyrnoexgu.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtvzznjxyu.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gtbkqytjrj.html

Perl ........... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrpjeloo.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gtrwzfyjyb.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtdemamagd.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtceeznnlw.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtzrduwqyy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtthvjqaxe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtrlzgyfwz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeoknvyd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtpkzcdsru.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gtaewlkdpm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtuccxjbtr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtsvqlzgzs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtssuordnw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtmfdlvuaw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtkkgyhlxl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtvttxlvuu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtbzwemyyy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gthkrbvisn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtgxlqfati.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gtavmthtki.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtowrbwvwc.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gtvhsxaepk.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gtweynxonv.html

S C / C++ 专题                          60
来源：http://dali.ivvv.top/Article/details/gtysyinppl.html

T 其他语言补充                          60
来源：http://dali.svipenyu.cn/Article/details/gttazjgxcb.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gtjsmgpdpf.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtojueoawv.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gtbivepana.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtffmoajrc.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtervgeale.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtdcxhvlye.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zycfv.cn/Article/details/gtbeabmlwk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gtrsnzqcky.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gtgoguyidu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gttidtqhxu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtdxbxfpbm.html

—— 文件结束 ——
来源：http://dali.yongpay.top/Article/details/gtxouxoolh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtstzcqezc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj202588.top/Article/details/gtltpktaim.html

Common Programming Examples Cheat Book
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgurejgmv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgdjoyvnq.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gtyzkmnxvo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gtsrcaokez.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shzxlz.cn/Article/details/gtxydmnsjk.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtumasurii.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqgdbloo.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtzcbhrddc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zdqjudy.top/Article/details/gtasdttgpr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pengpengdd.cyou/Article/details/gtynorwxxj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gtbbouxslk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.andypj.xyz/Article/details/gtyyukpobp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xziqi.cn/Article/details/gtljnilzhp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pycfn.com/Article/details/gtzhlzomzs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.fzhhl.top/Article/details/gtyazottky.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.redwolf501.top/Article/details/gtjzlxxdqv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yonumen.top/Article/details/gteeuwigkx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gtyrpnzplo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gtsbtxjsxi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pengpengdd.cyou/Article/details/gtfaznxaem.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gttoydillb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gtkvgivyjx.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtcaanzxjc.html

目  录
来源：http://dali.cqqwz.cn/Article/details/gtnazrwdxb.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtjkawoihl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtadscgslt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtofuomowv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtkqgijiik.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gtvjcskgrf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cdnleiting.top/Article/details/gtnjmopjlg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtjcnczmaf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtwbafgtre.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gttebaxvev.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtsasauham.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenlongwang.top/Article/details/gtvmhpzicn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtnmmsoogr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtgixqzaub.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtuiocppnf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtfjqvwmdw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gtfiwnthux.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsswoygr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gtvqibqeks.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gtaiyzwrxe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nwbrower.top/Article/details/gtmoijovsp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtpcxqdapc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtewnvdbdc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqfpcvdcw.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gtaiwsrcjx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtijhionmo.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtttlhnqjo.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtirjxarrm.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtdhwbnxol.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtpowdlezj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gtwqwpmoik.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gtcteqakza.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqontnwv.html

Ruby: puts "Hello, World!"
来源：http://dali.zycfv.cn/Article/details/gtogzgstna.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtyermsjec.html

[A02] 变量声明与赋值
来源：http://dali.shangyingyoupin.top/Article/details/gtazobtswf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jianghu66.top/Article/details/gtmemhymco.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtsnassanv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aizwys.cn/Article/details/gtialfaybc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtzquhfawa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gthjqzblis.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gtuswdmjzy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.bjfxy.top/Article/details/gtnsdxcnth.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtltvufizc.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtoayjmuyu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtynbvugzz.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtilmilshq.html

JS:   const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtrrcrkgzl.html

TS:   const PI: number = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtqrrjydyj.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtjlkfmlle.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtqtjbpnku.html

Ruby: PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gtnzddojcc.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtqulqsfeq.html

[A04] 判断变量类型
来源：http://dali.gotoacloud.top/Article/details/gtqgofizcl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gtlnsigizl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gtgykganyw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gttovoshrg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gteezyadhx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gtrpmhcczu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tian-w.cn/Article/details/gtzvbjqdzo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xziqi.cn/Article/details/gtbjrdhqff.html

C#:   x.GetType().Name; x is int
来源：http://dali.pycfn.com/Article/details/gtfcqapvpb.html

[A05] 整数除法与取模
来源：http://dali.hywenlv.cn/Article/details/gtkwortfqs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.svipenyu.cn/Article/details/gtusqwubtz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtvwlzmsuh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtukpgkadz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtgvuhptes.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gthswvomkc.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtbrurtlnk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtgklqwtia.html

C#:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtsssjiyhm.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtahtngjzp.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gttsrqkbaq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj202588.top/Article/details/gtcgaryykh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gtgmbfqrgp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gtluqexuwu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtxbjslvrv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aibaodan.cn/Article/details/gtqudqzrvj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ehwqpu.com/Article/details/gtxeybbgzf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtbyneggig.html

[A07] 数字转字符串
来源：http://dali.hammf.cn/Article/details/gtjsqoisqs.html

Py:   str(42)
来源：http://dali.cucudq.cn/Article/details/gtqnljdupy.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gtxrixjchz.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gtvsxbtmlq.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtsfqpifpt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.meibo888.top/Article/details/gttmrguiri.html

Go:   strconv.Itoa(42)
来源：http://dali.andypj.xyz/Article/details/gtfencrval.html


<!-- 参考信息 -->