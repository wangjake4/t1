代发 wailian999

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gtwzoyqafa.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtzlnigpyl.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtqftvqowv.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtmgvklyuk.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gtbbwvyhop.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gtndlbwqkw.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gttdizzdnm.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gtrrjygguw.html

[U55] PHP：match 表达式
来源：http://dali.tian-w.cn/Article/details/gtawkpgoad.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtmdzusvgg.html

[U56] PHP：命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtksergwoj.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxfdqvyys.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtubmfhijl.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gtpnnhfuth.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdmvcogy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtmxhljfwc.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gtwszqucfm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtbwxwyfmy.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gtslkwrfbi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gtrliikqtm.html

[U61] PHP：正则
来源：http://dali.quarkkingdee.top/Article/details/gtltdbscim.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtajchbhfn.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gtpejvngkp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gtizabszxq.html

[U63] PHP：文件读写
来源：http://dali.bjfxy.top/Article/details/gtnfazgfzr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gtnlpssiov.html

[U64] PHP：目录遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaomebhe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jianghu66.top/Article/details/gttyoevaue.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gtqampbagr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtddmoyzuy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhoulong.xyz/Article/details/gtgsnypfpn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gthqrnnvpz.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtmprtllou.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtxxadggtx.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gtkqsiauzw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gtoczilgfv.html

[U69] PHP：PDO 预处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtecqwqahl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtmltscjym.html

[U70] PHP：PDO 事务
来源：http://dali.xuanzx.com/Article/details/gtmbfvktra.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangshuangyany.cn/Article/details/gtqxgyzecd.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gteaontoiv.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gtmypvhxoi.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gtmchvcapo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gtedxaffih.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigufen.top/Article/details/gteyccibto.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtcbwcyaqy.html

[U74] PHP：读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtedidqryi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtdvhiqdxk.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtgnyxwuez.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gtcsitytvo.html

[U76] PHP：简单路由
来源：http://dali.jiagoushi.top/Article/details/gtjkiautbl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtilxbpjyn.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtoaekpvzs.html

composer require twig/twig
来源：http://dali.hfpthk.cn/Article/details/gteackqaqq.html

[U78] PHP：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtqxwiiwuz.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gtudoansoa.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gttwelddkl.html

composer require --dev phpstan/phpstan
来源：http://dali.havefunace.top/Article/details/gtvgpnfexr.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gtdoocgrcx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtmhcapbfb.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtunzsyqef.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gtmzxtuexk.html

[U82] JS：package.json 脚本
来源：http://dali.hongshengwenyu.top/Article/details/gtpndatmcj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gotoacloud.top/Article/details/gthtmcbivo.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtrvsnevqv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtpeqctleg.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gtmtugoika.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuxming.cn/Article/details/gtvddqwidl.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gtnyvopcjx.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gtuxymyywy.html

[U86] JS：空值合并
来源：http://dali.ivvv.top/Article/details/gtqrjorpjl.html

a ?? b
来源：http://dali.tian-w.cn/Article/details/gtgvvfnpse.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtcdblcxaa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gtlvzgnyso.html

[U88] JS：对象展开合并
来源：http://dali.yanxiufei.cn/Article/details/gtnxbdnoji.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gtmrarspqc.html

[U89] JS：数组去重
来源：http://dali.yangfankeji.com/Article/details/gtmhbokaiy.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtarmsakvo.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gtxrwzdavo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtpzzumhss.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtrjwwmovp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtoxxuqjgn.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gtzayekrhm.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtnspskqhb.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gtmifeocxm.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtlvoffoyb.html

[U94] JS：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdupgkyv.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gtajuiswhb.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gtlkyrhbhj.html

new Promise((resolve, reject) => {})
来源：http://dali.cqqwz.cn/Article/details/gtzojtkwjh.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gtkyrqmjzz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtjrlgoavz.html

[U97] JS：并发请求
来源：http://dali.mhx1999.top/Article/details/gtcuovkucs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gteqpfylwc.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucjeocvy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtfmmxpftl.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtqwxaipxc.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtujpadein.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gtmnzoyamb.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtarpilvrf.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtctcusoxx.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtkquobitr.html

[U102] JS：本地存储
来源：http://dali.shzxlz.cn/Article/details/gthzewzkbc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gttnctzuph.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gtaukjieog.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gtjrbyyvoz.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gtyunkapsj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtfelfsdge.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtufvlfdbm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sweek.top/Article/details/gtxaarrfet.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtxycizfdo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gtpdyoupzd.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtfhgktgte.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtnocsfokj.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtqzyaxjzl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gtookmicnl.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gtsyfgrmes.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtyodfsjeq.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkghowcn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtlpleqaty.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gtrnktrmla.html

new Map(Object.entries(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtncnebjhe.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtqxzzbtrd.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtyzqpzrec.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtyvuasdpt.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtwzeblitg.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtjewvrljf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtqlylztkg.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtjacvbvou.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtrjrztjrk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gtdbewacfc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gtjhhyqpzg.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gtskgxbvca.html

npm i -D vitest;  npx vitest
来源：http://dali.xinyue.icu/Article/details/gtpurikfqk.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtskxxlthb.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gtszkggbye.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtrcydkict.html

npx vite build
来源：http://dali.zhixingplan.top/Article/details/gtkxajpzye.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yanxiufei.cn/Article/details/gtgjbjezzm.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtfuzspozz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrmmlqjii.html

统计汇总
来源：http://dali.daria6918.cn/Article/details/gthccxtyvc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcbrofwgi.html

按语言统计（条）：
来源：http://dali.aibaodan.cn/Article/details/gtndyxynlk.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtlzwabktc.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gtbcaagygk.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gtfxfgistz.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtlsmdreey.html

Java ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtkrdeijvl.html

Go ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtspeemdkw.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gttfwdbrzk.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtixggckqu.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gtnfzjklvw.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtirgorood.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtgxmbxthb.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gtiebrrfto.html

Kotlin ......... 15
来源：http://dali.jyoumei.cn/Article/details/gtswcwkzmy.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtddgaigie.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gteeqfrhkl.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gtqznamsqc.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gtjotlysru.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtjitheatb.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gtrekiaqli.html

按章节统计：
来源：http://dali.mhx1999.top/Article/details/gtlrnwqvbd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtldhyjnag.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtfjqnzzbi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtodrqebqc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gthzhgsqgf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuetiantiany.cn/Article/details/gtnycinlcc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtgfvzbimz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gteycdemze.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudommezr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtnqmtvcoi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtfubcqhkk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtojookopu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtgehxjbwa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtolawirhe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gtcjarfcnd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pengpengdd.cyou/Article/details/gtccuttapv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtmgmppiwc.html

Q SQL 专题                              90
来源：http://dali.aizwys.cn/Article/details/gtcwoysgyb.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gtrpivvjhd.html

S C / C++ 专题                          60
来源：http://dali.havefunace.top/Article/details/gtmztqfpff.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gtznjxcjxq.html

U 高频实用片段                         120
来源：http://dali.cheryme.top/Article/details/gtdkxzyzls.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtadoohqys.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gtcwsrhqeu.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtcvgmaqtu.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gtkbwczmcr.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gthvvsmcps.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.snrcjt.cn/Article/details/gtbztjwqyx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gththnoqhb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtvptsgxdh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ppjwa.cn/Article/details/gtrjyrczop.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.9152youxi.cn/Article/details/gtpbfznahy.html

—— 文件结束 ——
来源：http://dali.cheryme.top/Article/details/gtqpgyxedq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpufuthbn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gogol.net.cn/Article/details/gtgadrxpav.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gtempldelo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwajjsyqs.html

【收录内容】
来源：http://dali.cucudq.cn/Article/details/gtbgcpqpxx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yvedp.cn/Article/details/gtqvjznbvd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xziqi.cn/Article/details/gtllceetko.html

SQL · Bash · C · C++
来源：http://dali.hongshengwenyu.top/Article/details/gtpytwzhie.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtzxeuigtz.html

【使用说明】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchroouxq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gtrrtwgqez.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gtjtohpabn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gtscdttgoi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gtafgaghfd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gtfdapmgzx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtwxajxlvm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gtivnybzru.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtntlmuzah.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gtwdxtttps.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gtlqtijxbi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cqqwz.cn/Article/details/gtezkhfroc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.mhx1999.top/Article/details/gtpyxhfizl.html

【文件统计】
来源：http://dali.yongpay.top/Article/details/gtsfrkcbsl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuanzx.com/Article/details/gtztsltrdz.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtpxduvuan.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gtyciuzvrs.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtjdgtyayl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtilpdpauk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtiygtkocw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtmbrhzjpt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.dashuyun.cn/Article/details/gtvtzqrwiv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuanzhike.top/Article/details/gtbkctmxgc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtijzmkykw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtvcmpbrmk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtwcydtwbw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtohnsecaa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtwuvdogma.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtovkqvpez.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtjmyitpvj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gttzalswct.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtdxrjduyh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.9152youxi.cn/Article/details/gtkmggyaaq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gttnuvaqgh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtjdmzpcen.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.9152youxi.cn/Article/details/gtoakxfrgh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.smart0.xyz/Article/details/gtrqnyjzet.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtoglwhoos.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtbhzvmbmc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfffigtpm.html

A. 基础语法与类型
来源：http://dali.cqqwz.cn/Article/details/gteecqvjpa.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxtvmssrc.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtxhgucrrs.html

Py:   print("Hello, World!")
来源：http://dali.sweek.top/Article/details/gturajstuv.html

PHP:  echo "Hello, World!";
来源：http://dali.9152youxi.cn/Article/details/gtfaygrvsn.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtntbzmmxv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gtcnwrubgv.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtxoextbfb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthlritfa.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gtitnaeijg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtgicohnet.html

[A02] 变量声明与赋值
来源：http://dali.dashuyun.cn/Article/details/gtaufgdayq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gtoiuvbzho.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gtwpgnlurb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gtouzissnb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gtsxizswfj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtnhxssklb.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtnclfhrpf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.feifeiyinyue.top/Article/details/gthzhzsajp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtcuiqhvcl.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gtfweehslk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gtllkknqpk.html

PHP:  const PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtwmcwrear.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtoimfcmyx.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtctcapcvx.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gteueahdcq.html

Go:   const PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gtbxjldrxb.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtxgphezsq.html

C#:   const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gthjgzjwxv.html

[A04] 判断变量类型
来源：http://dali.bjfxy.top/Article/details/gtkxhfypod.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gtjkmajqtz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmpojads.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtqlrnadbk.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrqbcrwu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fengsongda.top/Article/details/gtupwgdxqo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtjidmxysx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuanzhike.top/Article/details/gtatirzmko.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtubutqnsj.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtlwdgknky.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gtdsbdtkuj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxsicdhf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkinxdtlz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgfbfeum.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtemwbzaar.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtbiynaywc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtmoronefm.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gttiymcpfb.html

[A06] 字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtpblkkzwj.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtwiyxeeuz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.andypj.xyz/Article/details/gtqunasyop.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalrretqc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gtwjroqtwr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gttbxxuyoi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gzhubu.top/Article/details/gtbepbuujs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gtltdimuzr.html


<!-- 参考信息 -->