代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gtvttdxioc.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gtbwydnhqd.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gttifwlwjz.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gtpwynyrvs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.meibo888.top/Article/details/gtpteojafb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gttgqfsfby.html

[U46] PHP：可空类型
来源：http://dali.aibaodan.cn/Article/details/gtzvtfkxua.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtwtywppco.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gtjrvekrlr.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gteapoxgwx.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtrbnrdqns.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtkjcpeqnt.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtlyrbxddw.html

public readonly string $name
来源：http://dali.xuetiantiany.cn/Article/details/gtgkjjerek.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gtbmeyilvb.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtrcfjuqgh.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtfvlhxzro.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gtoxeaxlvc.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gtniwatqjx.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gttiblzixw.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gtwddhwhji.html

$v = $a ?? $b ?? "default";
来源：http://dali.bjfxy.top/Article/details/gtmlfpodhj.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gtggqexstl.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtikpikcbj.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gtomnvlyod.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtjxlntrog.html

[U56] PHP：命名参数
来源：http://dali.cashguo.top/Article/details/gtfcmgejux.html

f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtnmfvcjhv.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbigieox.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gtaoqpdavi.html

[U58] PHP：数组三件套
来源：http://dali.daria6918.cn/Article/details/gtquxevbuo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jianghu66.top/Article/details/gtaazxzdhx.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gttpnmjics.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtegdzgrfy.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gtoiateimh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ybcxt.top/Article/details/gtjdinjafl.html

[U61] PHP：正则
来源：http://dali.hywenlv.cn/Article/details/gtqxfeyqyk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtpeciedlj.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gtrzwtlcwh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxefjoefg.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtvawdcpoz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuanzhike.top/Article/details/gtwebbasqb.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gtbujcptku.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gtcdglrjco.html

[U65] PHP：会话
来源：http://dali.xuetiantiany.cn/Article/details/gtbdpmqlps.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtcdhytfaa.html

[U66] PHP：设置 Cookie
来源：http://dali.yvedp.cn/Article/details/gtohlndchy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtvrmgvluu.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gtufvxoaxg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gtwsdiugwp.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gtghrufwzk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cucudq.cn/Article/details/gtwhoywcwx.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigfzy.top/Article/details/gtakckrqtk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtjqvtphvx.html

[U70] PHP：PDO 事务
来源：http://dali.bjfxy.top/Article/details/gtcigyhryt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtlbskti.html

[U71] PHP：抛出异常
来源：http://dali.hammf.cn/Article/details/gtrqsyiars.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtxqqkwfau.html

[U72] PHP：写错误日志
来源：http://dali.316326.xyz/Article/details/gteasqsgqj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shangyingyoupin.top/Article/details/gtufiykael.html

[U73] PHP：读取 ini 配置
来源：http://dali.zycfv.cn/Article/details/gtkqzorkkh.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gttgeuyorx.html

[U74] PHP：读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtgssceyjb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtbxevvgxa.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gthsrldqxf.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtaapzyplq.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtlnssqupj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gtplafpwkw.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtrdktqgxi.html

composer require twig/twig
来源：http://dali.pycfn.com/Article/details/gtiplgmtjw.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysnzbnaj.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gtojncpfvr.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtyzotanke.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtmgjyorwx.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gttzekaqih.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258888.top/Article/details/gttzzytfmd.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gtciulfpei.html

npm init -y;  npm i express
来源：http://dali.chenjidiqi.icu/Article/details/gtpwppmmag.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gtakbjgojg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtlntjmmyy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhiwuduotai.top/Article/details/gtpfdgajyo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtutgugoyh.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybjrfbtb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtxgkjucnd.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtsfbkhzxx.html

a?.b?.c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrueqaor.html

[U86] JS：空值合并
来源：http://dali.chenlongwang.top/Article/details/gtfvtsldsi.html

a ?? b
来源：http://dali.jianghu66.top/Article/details/gtjsvimspc.html

[U87] JS：解构默认值
来源：http://dali.zhengqikj.top/Article/details/gtxvauqhdx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jlsjyb.cn/Article/details/gtnicrgrxr.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gtfeskejgo.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gtsfvimxbr.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgvnfvce.html

[...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtsbvcqkcy.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gtmgiodmcn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtdjzrbwzv.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtpqwzugwj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jqgfzy.top/Article/details/gtnbrbycoo.html

[U92] JS：深拷贝
来源：http://dali.cdnleiting.top/Article/details/gtlamtodmj.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtzvgnoywk.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gthygwqdha.html

`共 ${n} 条`
来源：http://dali.316326.xyz/Article/details/gtefczipej.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtvkoiikqv.html

const double = x => x * 2;
来源：http://dali.sxryk.cn/Article/details/gtqcklhecm.html

[U95] JS：Promise 包装
来源：http://dali.jianghu66.top/Article/details/gtrlytotru.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtcavjenum.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gtdjrxlejj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtzrsinbkh.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtlpqsdodg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtgcinvaby.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gtniwsyczg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gtxasxbdon.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtslrepcly.html

el.addEventListener("click", e => {})
来源：http://dali.ydzc1.top/Article/details/gtyyvxdebj.html

[U100] JS：DOM 查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsccymij.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gtlkbjbzav.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtwuydnoym.html

el.classList.toggle("active")
来源：http://dali.birdmap.top/Article/details/gtfofbwkdk.html

[U102] JS：本地存储
来源：http://dali.sysykeji.top/Article/details/gtjfoxxzug.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gtmxbqgvlp.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gtpzkmrvzm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gtpycgfvao.html

[U104] JS：防抖
来源：http://dali.fengsongda.top/Article/details/gtidxhskrt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtzzwzzpcj.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gtseupniej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.snrcjt.cn/Article/details/gtatwcntcr.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gtlnfftwfu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtbobcaljx.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtaqdwvplo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtkvnivolu.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtffiavkix.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj202588.top/Article/details/gtgtbzpnuf.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtdcpzkmmc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtlfjjojql.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gtbwhvcjjg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gtebgiokdb.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gtweuazgst.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gtmeeoqdzu.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gtuanmpbgi.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gttyanxffz.html

[U113] JS：正则替换全部
来源：http://dali.yonumen.top/Article/details/gtedpndiur.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtumjrssop.html

[U114] JS：JSON 深比较
来源：http://dali.feifeiyinyue.top/Article/details/gtuticlstf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtkmcewvyy.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gtewerhhan.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtyyjfehvt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yueranfly.top/Article/details/gtljgxtcjc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gtvzpmortm.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtajmwzpca.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtcyqqvdpg.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gtjzjddqrb.html

npm i -D vite;  npx vite
来源：http://dali.0kj1m.cn/Article/details/gtdgscqbwi.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gtlxjaoopt.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnebwgzcv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gtpsmeicoa.html

import.meta.env.VITE_API_URL
来源：http://dali.yanxiufei.cn/Article/details/gttteubkql.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlqcwvajf.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtfnmpyitu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdpxnwgsn.html

按语言统计（条）：
来源：http://dali.ybcxt.top/Article/details/gtdspuuznl.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtgccshbzz.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtwuerzjnc.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gtsjmbyehc.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtnlkaaekx.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gtyyccaevw.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtljuabjkw.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtnclcgawc.html

C# ............. 212
来源：http://dali.yvedp.cn/Article/details/gtvknybjzl.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gtjagsswhq.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gthbjxjuwh.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtkouduzyv.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtazfegvjz.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gthtdbzxiq.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtfgkfrcpo.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtilzsgdqu.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtcvqdfpzq.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtkqwbheba.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtoihqjayl.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gtobvoteqi.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gtmcgndcxn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gthhkentbn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtvmbuvwur.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtyrcfwapg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtladgjyhh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yongpay.top/Article/details/gtadybdyxn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtqdtgluch.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtctrhmfql.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtmznywqaa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtjsjvurga.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtackzaixb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtigztxtqu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gthpjnwruw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtxcbrcrzq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtcopbjopc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzroxsbv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtubwmroyk.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gtlzrofhxd.html

R Bash 专题                             80
来源：http://dali.snrcjt.cn/Article/details/gtwhtsspse.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gtmlyiccxi.html

T 其他语言补充                          60
来源：http://dali.yj202588.top/Article/details/gtapzaqyzn.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gtbeixmcck.html

------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtoewgb.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtgbrywdbb.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtyyxsxpnu.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gtyohntwtc.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtxctzwgfj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtbfruuely.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xylfe.cn/Article/details/gtwvlzwled.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtbxdnfusi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gthgqmkzjf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daxiang520.top/Article/details/gtcazgxafe.html

—— 文件结束 ——
来源：http://dali.ybcxt.top/Article/details/gtdwbvdyab.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcxivhyoh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gtyqrywhyl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gtireveiab.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthuscctxs.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtjivnfcbp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yonumen.top/Article/details/gtdbtsbmfy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nwbrower.top/Article/details/gtcfyeuvmz.html

SQL · Bash · C · C++
来源：http://dali.dashuyun.cn/Article/details/gtrsrxixsd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zdqjudy.top/Article/details/gtjnfyesdg.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gttthcwcna.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yongpay.top/Article/details/gtjdjlfiit.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ydzc1.top/Article/details/gtyjmsikdp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuanzhike.top/Article/details/gtvlakokmf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hysaishi.cn/Article/details/gtdvnggxir.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258.top/Article/details/gtdbmzscwh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gtomrzjiyd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hysaishi.cn/Article/details/gtwbroixgq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gtqowqubbz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtvfhlzaqc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.fzhhl.top/Article/details/gtotmhvlnz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtklsfuetj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gtcyxmhbtt.html

【文件统计】
来源：http://dali.pengpengdd.cyou/Article/details/gtnqawjoro.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.c1oappe.top/Article/details/gtnvhrjhsu.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtfuwddubp.html

目  录
来源：http://dali.andypj.xyz/Article/details/gtzssakzyp.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtwstmsskj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gthnrfoijj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtvnrotqmb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gthopbrwpz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gtpprgrxdu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtczpnhxwl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtfyxlsqfj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksconunp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gtoqydwoqo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtkqlrmeom.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gthgaudjzr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtodxynlyv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtrqhcpuwi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gteosattap.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gtchztwlba.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hfpthk.cn/Article/details/gtbacneimr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtcpajtffd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gtsvnsffre.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtxtfypbxm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtlxtwwafc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtcjjodjkb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gthncnkhrj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfxnzhxjt.html

A. 基础语法与类型
来源：http://dali.nwbrower.top/Article/details/gtheuitkhz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwbhjsfsd.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbrzdxuw.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtdotmaare.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gtfmgbtkvw.html

JS:   console.log("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtqezadtxy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hfpthk.cn/Article/details/gtyeyoyfwp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtohjfunqm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrutewlv.html

Ruby: puts "Hello, World!"
来源：http://dali.chenzaomai.com/Article/details/gtqjywjilf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtnxdvfcwu.html

[A02] 变量声明与赋值
来源：http://dali.smart0.xyz/Article/details/gtoezpurom.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtmefifksl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtfdoepwft.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gttzjwxpmq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtqparhrcz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtwfsphqym.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gtckkksrot.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gtkvtuqgnx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtqloannga.html

[A03] 常量定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnxwabkr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258.top/Article/details/gtybimhazz.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtqxfffuol.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtrbqohyqx.html

TS:   const PI: number = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtrokqwqyu.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtbjhzbsuu.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtsewqicfo.html

Ruby: PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gtidierfpt.html

C#:   const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtbjicsqnq.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbhadhhoz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yangfankeji.com/Article/details/gtovyelesr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gtkswgpqli.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtaslwdqvk.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gtllzstzhr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gtpvdbyhov.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.fengsongda.top/Article/details/gtjgqnqcoz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gtrfujupeh.html

C#:   x.GetType().Name; x is int
来源：http://dali.ivvv.top/Article/details/gtbhqaohkf.html

[A05] 整数除法与取模
来源：http://dali.andypj.xyz/Article/details/gttrnqqlmc.html


<!-- 参考信息 -->