代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gtyigctmft.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gtjtsvnpwh.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gtohpcvsje.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gtnztszive.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtnjfkxwxb.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgceurkw.html

[U52] PHP：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtejhwdyxf.html

$double = fn($x) => $x * 2;
来源：http://dali.sweek.top/Article/details/gtbhseikto.html

[U53] PHP：空合并运算符
来源：http://dali.hywenlv.cn/Article/details/gtlscehcns.html

$v = $a ?? $b ?? "default";
来源：http://dali.hongshengwenyu.top/Article/details/gtfqvhmbdv.html

[U54] PHP：空安全调用
来源：http://dali.shangyingyoupin.top/Article/details/gteclitbke.html

$obj?->method()
来源：http://dali.quarkkingdee.top/Article/details/gtwupqfujr.html

[U55] PHP：match 表达式
来源：http://dali.xinyue.icu/Article/details/gtpaipazns.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gteuxwhhja.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtuceykfgv.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gteraldkmv.html

[U57] PHP：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtjmzzcsaz.html

"值: {$a}"
来源：http://dali.yanxiufei.cn/Article/details/gtulasfijy.html

[U58] PHP：数组三件套
来源：http://dali.yueranfly.top/Article/details/gtybfthlga.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtysyyfnnm.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtcedgkbnl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtantnwzvj.html

[U60] PHP：JSON 编解码
来源：http://dali.yangfankeji.com/Article/details/gtbhyutbyp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtxoayfnfy.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gtnrnljclx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmwsohyv.html

[U62] PHP：日期对象
来源：http://dali.mhx1999.top/Article/details/gtldwdnqzd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtxetlmvzo.html

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gtyzevbnnf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gtkrigenmk.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gttxgwdwkz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gtsaknuhcq.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gtlftwxxxc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtuwxpdshz.html

[U66] PHP：设置 Cookie
来源：http://dali.316326.xyz/Article/details/gtheuqrjki.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgmmtwjs.html

[U67] PHP：处理文件上传
来源：http://dali.nwbrower.top/Article/details/gtslomzazt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtmgkdanqk.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gtblgsnewn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtkidehjbr.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkwnftlb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.aizwys.cn/Article/details/gtzvcfwstm.html

[U70] PHP：PDO 事务
来源：http://dali.jqgfzy.top/Article/details/gtmmqytswf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtyduswexr.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtvdtouahc.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtqeurbpbe.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtasvnejri.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gtlwxtmejo.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvtcmnpq.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtoxlmaftf.html

[U74] PHP：读取环境变量
来源：http://dali.316326.xyz/Article/details/gtwjojvlkd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guowangkeji.top/Article/details/gticpyoayc.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gthqodedtu.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gtqselmoas.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gtidissxfw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.svipenyu.cn/Article/details/gtxryrfroh.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtwahrayrj.html

composer require twig/twig
来源：http://dali.jqgfzy.top/Article/details/gtscnngytl.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtduwcmzet.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gtrdnprwyq.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtwietfiqs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtlyaxarwh.html

[U80] PHP：代码规范修复
来源：http://dali.cashguo.top/Article/details/gtbllwyawc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtjouitrsf.html

[U81] JS：初始化项目
来源：http://dali.sysykeji.top/Article/details/gtlsmtwisz.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gtbslcmumd.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gtunrtqumu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yvedp.cn/Article/details/gtxxhjtxth.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtlljvdzxz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtakfaxbzo.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtffyxclxq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gtpvgaqqkp.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gtgxlzqmpr.html

a?.b?.c
来源：http://dali.iojbl.cn/Article/details/gtpfdlwjob.html

[U86] JS：空值合并
来源：http://dali.gzhubu.top/Article/details/gtfgnxupsh.html

a ?? b
来源：http://dali.redwolf501.top/Article/details/gtgidrcgza.html

[U87] JS：解构默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtypimdnut.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtcpmafbaw.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtledzyzyq.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtnorkhqti.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtttmggoib.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtujqrrubs.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gtnvxovzxu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtpuoufwee.html

[U91] JS：对象键值遍历
来源：http://dali.svipenyu.cn/Article/details/gtwpnfzqyw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtladuqket.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqioqjev.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtikihbvjj.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gtzbxlzyfr.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gtjdmwrzhr.html

[U94] JS：箭头函数
来源：http://dali.yuxming.cn/Article/details/gtuzevzkho.html

const double = x => x * 2;
来源：http://dali.wangdashe.top/Article/details/gtldirmmli.html

[U95] JS：Promise 包装
来源：http://dali.zdqjudy.top/Article/details/gtdqugvqsz.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gtglaxxaem.html

[U96] JS：async/await 与异常
来源：http://dali.jqgfzy.top/Article/details/gtqrahtdxt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkhhlervf.html

[U97] JS：并发请求
来源：http://dali.ydzc1.top/Article/details/gtlqavpvgc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhswtaif.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtpxzvhrvh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gtnnzwdtck.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gttdafufvt.html

el.addEventListener("click", e => {})
来源：http://dali.yj202588.top/Article/details/gtuqfmluvo.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gtsiohcucr.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gtzodicpho.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtmzsusxaj.html

el.classList.toggle("active")
来源：http://dali.zhengqikj.top/Article/details/gthlwewwxs.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gthddxvjcr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gttzxyzlez.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gtwxxnxnqi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gtykcxguvn.html

[U104] JS：防抖
来源：http://dali.fengsongda.top/Article/details/gtqupxpvyn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtynjiwzps.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gtttqvwhkj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvodabgt.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gtuksrkdnj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gtkocnjhck.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtiyfedezi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumqirmxr.html

[U108] JS：随机整数
来源：http://dali.yuanzhike.top/Article/details/gtjmlccajz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtkirfticb.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtwiuvnlbm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtojlpdxis.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gtrodqbrcd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gtxubpphnf.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtvevzkojb.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gttatdtyhd.html

[U112] JS：字符串补位
来源：http://dali.yanxiufei.cn/Article/details/gtmoxowpic.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtyvhpqmtn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gtaykffbnn.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtlflkrzdf.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtjjjpejxa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtrlcbwrlc.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gthvyinkfc.html

crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtkfesjavi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xylfe.cn/Article/details/gtlcnxjqgk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtdcjswslu.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gtebueljua.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gttumamavo.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gtayrokcah.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gtzbcckwky.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtffojvdyt.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gtaenvralw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gtxxrcbumi.html

import.meta.env.VITE_API_URL
来源：http://dali.jianghu66.top/Article/details/gtplutyfth.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtysqckiqi.html

统计汇总
来源：http://dali.gzhubu.top/Article/details/gtefdujnlb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtauolsfkg.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gtinpeyemd.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gthyijmndy.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymuqmrhn.html

JavaScript ..... 252
来源：http://dali.hnxiangtu.top/Article/details/gtdgqjupni.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gtoysbnhwg.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtgaurmwfe.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gttyuswoca.html

Ruby ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtbxkjplqk.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtojbujyzh.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gtvxdqzyzi.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtqibivtbu.html

SQL ............ 90
来源：http://dali.yangfankeji.com/Article/details/gtjyyvocep.html

Bash ........... 80
来源：http://dali.haohaochexian.top/Article/details/gtdxtkdegi.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtoiizolce.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtjwyrxaob.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtfaygohhj.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtxjetvfnl.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gtddabgpsm.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtgtlcgpgw.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gthyyajtyp.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtfkncecuc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtimfmcoyc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtoqwliywm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gthvuxozvq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtnlbwotrz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtwseedhba.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtdjjhzyua.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtjpiymmcx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtemxxdgrv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtlefpjecl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gtvbfsifmp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtdczmvmah.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtrozndhpg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjxruanv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtxailmpkp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hysaishi.cn/Article/details/gtgmbvqtbr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtbzjvxqjm.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gtypyboifb.html

R Bash 专题                             80
来源：http://dali.ydzc1.top/Article/details/gtrlbhokxk.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gtnrrjzdsv.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtbaimcogc.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtuzlhaopr.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtnmgympll.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtjfhadwvo.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtfrhmnxgt.html

使用提醒
来源：http://dali.sxryk.cn/Article/details/gtjspctoss.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtizymkzzb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtntwtksdk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jlsjyb.cn/Article/details/gtqeenevsi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtlzzhapno.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gtlxkbimij.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhongyouzk.top/Article/details/gttvnlgaeg.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtvxkrnwdm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcmshsxed.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtgfphxrkm.html

Common Programming Examples Cheat Book
来源：http://dali.cqqwz.cn/Article/details/gteortzmyw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpuxltdze.html

【收录内容】
来源：http://dali.yj202588.top/Article/details/gtyefxzxng.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cashguo.top/Article/details/gthmwdpwhl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gtqsofiozj.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gtqgdinded.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtbefwzaky.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gttpqarqpc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.birdmap.top/Article/details/gtkmlsygso.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daxiang520.top/Article/details/gtzvvbpdwq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shzxlz.cn/Article/details/gtuuppvakk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gtetqonaez.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gtydulynfb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gtbgxxlmoq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gtjrfxszro.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sufxvd.cn/Article/details/gtvsxmfqvm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gtemjhdxrq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxinkj.top/Article/details/gtvcbqwzwn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gttvkgdkyt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aibaodan.cn/Article/details/gtghrnztjv.html

【文件统计】
来源：http://dali.xuetiantiany.cn/Article/details/gtxmsednxz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhongyouzk.top/Article/details/gtumximcpd.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtvearwlem.html

目  录
来源：http://dali.316326.xyz/Article/details/gtjahxdrig.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtsiyiyxgl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtsnsuiakt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtcrotzsll.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtqysojmcb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtvavhwcmc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gtuodjppdv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdxaerfx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtiuougnws.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtncoqqroq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gteaiatfvh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtguwepxru.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtinedammr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtiaxmaonx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gttibomxqj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtjwvfcipt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gthhzpsgxi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtbvvvdbih.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tanke756.top/Article/details/gtexelwbvi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlrgwfje.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gtvfeivqfn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprtplokl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtmdndmukh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzlmsuafp.html

A. 基础语法与类型
来源：http://dali.yuanzhike.top/Article/details/gtawejphao.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmokzyye.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtsmprwcwv.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtkesrlufb.html

PHP:  echo "Hello, World!";
来源：http://dali.quarkkingdee.top/Article/details/gtbtjkjdsv.html

JS:   console.log("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtqxmbgncj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jyoumei.cn/Article/details/gtyocstuub.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtjwolrzpo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gtycvqxbki.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gtyflrwykx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gtfvdsuowh.html

[A02] 变量声明与赋值
来源：http://dali.chenjidiqi.icu/Article/details/gtdhgajofk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtqudmwkge.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daria6918.cn/Article/details/gtjopkoxxi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ppjwa.cn/Article/details/gthyfdauay.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtrszrnvvu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gtfdupbhzq.html

Go:   name := "Alex"; age := 20
来源：http://dali.hfpthk.cn/Article/details/gtiuwrhifm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ydzc1.top/Article/details/gtwkdinhnr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gtwpysunll.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtjqtfwhnd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tanke756.top/Article/details/gtspwoanur.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtoakambcz.html

JS:   const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtsimsnrvc.html

TS:   const PI: number = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtguksqtqr.html

Java: static final double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzgjvumr.html

Go:   const PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gtdugojvll.html

Ruby: PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gtykgkmwln.html

C#:   const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtdrxfvufr.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtmpjwyxbu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sufxvd.cn/Article/details/gtranvkcjd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.birdmap.top/Article/details/gtidkdtben.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtfpailknv.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivelwboy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.bjfxy.top/Article/details/gtexwlwkmo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yanxiufei.cn/Article/details/gtiihotwap.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pycfn.com/Article/details/gtiikgyykw.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gtfdeadvas.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gtpwxcsahu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtqwzmhztv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtybibgwnf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtabbeqvpf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtmpjasdfr.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtbasfbpip.html

Go:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtbpehypvx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtzsybqkxo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtwvhraxrb.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtuvizxwsq.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtbspyitxl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jianghu66.top/Article/details/gterieowxe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtfybkgsdu.html


<!-- 参考信息 -->