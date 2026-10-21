代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gtkbfgzxhd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtsdfyipns.html

[U46] PHP：可空类型
来源：http://dali.zhoulong.xyz/Article/details/gtrojxqmpx.html

?string $name = null
来源：http://dali.yanxiufei.cn/Article/details/gtrzbemrov.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gtyknxawgq.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gtgsirbryo.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtlianzrpg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gtvxhszwlw.html

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gtjsepygnk.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gtherjorbd.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gtfgrrujnv.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthcpvzetj.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgheqzis.html

[$a, $b] = $arr;
来源：http://dali.dianchejie.cn/Article/details/gtcndmtdpl.html

[U52] PHP：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtyrzzgybk.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtvrolwuja.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtjunkkvck.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtvxaltrdw.html

[U54] PHP：空安全调用
来源：http://dali.0kj1m.cn/Article/details/gtkmvauypa.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gtlxwmmcbe.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gtzjavlutp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtehqrkdbg.html

[U56] PHP：命名参数
来源：http://dali.jinqigufen.top/Article/details/gtqjbefrhh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkkwsupwf.html

[U57] PHP：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtrmpqzkfw.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdegymbr.html

[U58] PHP：数组三件套
来源：http://dali.yj20258888.top/Article/details/gtetwhvllm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gtcnbcopzn.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gtkmrieytx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtkdmsilbx.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhbyxljh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtsdmaimzv.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gttjikjzav.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gtbveyycst.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gtrwatbnfe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangdashe.top/Article/details/gtuvhheyww.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gtqzavtgiw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ybcxt.top/Article/details/gtdrmhvrjg.html

[U64] PHP：目录遍历
来源：http://dali.zhengqikj.top/Article/details/gtwumkdhgx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnxiangtu.top/Article/details/gtbulnrsha.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyfoxlgz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtqdnbwuqe.html

[U66] PHP：设置 Cookie
来源：http://dali.316326.xyz/Article/details/gtoukzoevg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtxsmczwbs.html

[U67] PHP：处理文件上传
来源：http://dali.yueranfly.top/Article/details/gtjkdjiwqk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gtncaaqbmt.html

[U68] PHP：PDO 连接
来源：http://dali.chenlongwang.top/Article/details/gtcouthpzu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gtkaxddbig.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebfxktzy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gtvpgdhbel.html

[U70] PHP：PDO 事务
来源：http://dali.jqgufenzy.top/Article/details/gtqzteuvox.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtjcugxxrx.html

[U71] PHP：抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiwquhew.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gtyowvxkcd.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtnqhcmwee.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtlienkqif.html

[U73] PHP：读取 ini 配置
来源：http://dali.daria6918.cn/Article/details/gtfpgumoem.html

parse_ini_file("config.ini", true)
来源：http://dali.pengpengdd.cyou/Article/details/gtwjacrkni.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtjztlnzrd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guannengcc.top/Article/details/gtoxqmedea.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gtsrxpmcec.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtrcrfysmq.html

[U76] PHP：简单路由
来源：http://dali.zhongyouzk.top/Article/details/gtwaeutwyb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cqqwz.cn/Article/details/gtkjacnptf.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtxtfcycqb.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gtiulystwa.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtidbavzfw.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gtpboazqjt.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gtezlyptrz.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gtxqecavil.html

[U80] PHP：代码规范修复
来源：http://dali.tian-w.cn/Article/details/gtgmsicskd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdiczkmc.html

[U81] JS：初始化项目
来源：http://dali.0kj1m.cn/Article/details/gtjyebszbi.html

npm init -y;  npm i express
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadbvuirr.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtrwsfytav.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258888.top/Article/details/gtdlkrjcfo.html

[U83] JS：ES Module 导入导出
来源：http://dali.svipenyu.cn/Article/details/gtmznlkphc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtuyqrvzfs.html

[U84] JS：CommonJS 写法
来源：http://dali.gaohongyu789.top/Article/details/gtgqtmwjdn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gtfwsnxeqv.html

[U85] JS：可选链
来源：http://dali.sysykeji.top/Article/details/gtcosnysoq.html

a?.b?.c
来源：http://dali.wangshuangyany.cn/Article/details/gtphnixosr.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gtuaepvhec.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtstlxrfzj.html

[U87] JS：解构默认值
来源：http://dali.nanxuanxn.top/Article/details/gtrjouxewq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cheryme.top/Article/details/gttqonkkxl.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtppwjesqn.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtbibcikze.html

[U89] JS：数组去重
来源：http://dali.pycfn.com/Article/details/gtthfbyiru.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gttphepcfp.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gtczrmfzhg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtxqwibxal.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gtpvqpnybs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gtymuvuwph.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtmlcadbdv.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtjmtxvzmp.html

[U93] JS：模板字符串
来源：http://dali.zycfv.cn/Article/details/gtbbaendss.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gtwsbnzmnh.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtpiuktwmr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtatrjegtz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtnhasoqho.html

new Promise((resolve, reject) => {})
来源：http://dali.quarkkingdee.top/Article/details/gtwiycesgl.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gtaqcxdlzq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtduesuaib.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gtlkyfbkit.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtftwdvp.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gtsoentowv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gtaopsdpfe.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gtwzgdlwfn.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gtsjgoszui.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gtczoreagl.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gtutgdtjnv.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtkdikbudy.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtxbyiucrx.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxhlqrtx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.svipenyu.cn/Article/details/gtxtgqhepx.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtiphlxthg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258888.top/Article/details/gtikaeivyb.html

[U104] JS：防抖
来源：http://dali.daxiang520.top/Article/details/gtaveqsbwq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtjjtyrzil.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtcgwquhze.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gtxvwojqfx.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gtpznuvgvn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtcbzqpaic.html

[U107] JS：数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtlbgzvzqh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtvmfruxrw.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gtmdskqxfl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnxiangtu.top/Article/details/gtukdndqsu.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtfqzyckjh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtvwjqlfrc.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gtgbhsophc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gtwkjqvpyn.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtyoysmyhk.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrfvddqf.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gthpabnzgh.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtolzazcnt.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtxjccurpo.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtbvsnaqin.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtbqzxmbfh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtdlwvxtzy.html

[U115] JS：生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtjwhfknog.html

crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtwqbywbir.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtmahxsnwv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtshvtupca.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gthhkqpuij.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gtephdkiws.html

[U118] JS：开发服务器
来源：http://dali.dianchejie.cn/Article/details/gtjguthpro.html

npm i -D vite;  npx vite
来源：http://dali.feifeiyinyue.top/Article/details/gtrcbwttmn.html

[U119] JS：生产构建
来源：http://dali.aibaodan.cn/Article/details/gtpbutjpyt.html

npx vite build
来源：http://dali.smart0.xyz/Article/details/gtcuiqapgz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgfzy.top/Article/details/gtnfhxjzxj.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtddvuhady.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtckanziof.html

统计汇总
来源：http://dali.0kj1m.cn/Article/details/gtrvmcwrry.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtujzaplef.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gtuiaiaqve.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtqlaolhok.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gtvsrsaasu.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtczahodsl.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gtcpznzrdo.html

Java ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtlhftyozn.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtknsmqzav.html

Ruby ........... 212
来源：http://dali.iojbl.cn/Article/details/gtzwtuymfk.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtffbdudhu.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtnalwsxhx.html

C++ ............ 30
来源：http://dali.yongpay.top/Article/details/gtxshgsfnw.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtwrxwiaca.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gtscwesqez.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvedgpty.html

Swift .......... 15
来源：http://dali.shzxlz.cn/Article/details/gttvrkwnpb.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtooksyeqy.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gtyrcztysa.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtxupulgme.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtjxrrezto.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gtpuidhxoo.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyckjjzr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtcewxehhm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtyvfdxhiy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtufgiejhx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtwcjquqyu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zdqjudy.top/Article/details/gtshfbdfhw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtqwyxlswb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtrdnsavng.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtggagurfh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtbmtwrwva.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtrjohxipm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtljzeexgn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtliycaocb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtcbculmrk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtesyjnzvo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtjvxbikup.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtyrcssyph.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangtech.top/Article/details/gtraydewke.html

R Bash 专题                             80
来源：http://dali.meibo888.top/Article/details/gtwkhekuam.html

S C / C++ 专题                          60
来源：http://dali.birdmap.top/Article/details/gtupygbwpt.html

T 其他语言补充                          60
来源：http://dali.iojbl.cn/Article/details/gtyjowyphr.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gtqdnmiojg.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtssxqwchz.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtoqpleuwv.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemqvrivu.html

使用提醒
来源：http://dali.yuxming.cn/Article/details/gtxktlrahm.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtxvbielwx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksarbwio.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gtehzmqmvr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtkbrejszg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hywenlv.cn/Article/details/gtvnqpbwcm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtrwvdhjbc.html

—— 文件结束 ——
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeyktnts.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfqgwqqky.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gtptogmvbm.html

Common Programming Examples Cheat Book
来源：http://dali.dianchejie.cn/Article/details/gtmgkprzzx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmrklmaru.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gtgjblpgwh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gtonjtzqnm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cqqwz.cn/Article/details/gtbmtbcnrl.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtcrfudkbc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hysaishi.cn/Article/details/gtmczzqjdm.html

【使用说明】
来源：http://dali.redwolf501.top/Article/details/gtqwyglglv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtyceliobx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnxiangtu.top/Article/details/gtpmjhfuik.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtaauswdig.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gtzfyvadku.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yangfankeji.com/Article/details/gtxfbaleix.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shuidangran.top/Article/details/gtvqrrlpwh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gtueczeesv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sweek.top/Article/details/gtsqlstrpw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gtvotxoody.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gtliysyywz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbnlqwgl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gtxvihoqoy.html

【文件统计】
来源：http://dali.xinyue.icu/Article/details/gtkgsjjsdx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtoiofqsvb.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtsbhlmkiz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gtxsjmxrzc.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtwrfhekss.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtsmqdauoy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtloiwgxvz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtwgjvnjfw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlspmyzia.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gthgpitcdy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtclakawau.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtbmwgtxja.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtrsapepfh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtdajybxfr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtasqsojar.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtlhpbxhrf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnzyfygc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gthiyeapmw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtgdriciry.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gtobbwrpiw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtjdxzuffl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gtqiosmdbl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tanke756.top/Article/details/gtavlgvehp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gzhubu.top/Article/details/gtaxlcviab.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtjjmwpblb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtyxgfdcdj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzjjvscqt.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gteodmkxok.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyrbvfeam.html

[A01] Hello World
来源：http://dali.jianghu66.top/Article/details/gtnchrxdio.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtflxkyybl.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gtkdngogtn.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtgraehymq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gttvmdjsjg.html

Java: System.out.println("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gthbckupbq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gtzdfhbnct.html

Ruby: puts "Hello, World!"
来源：http://dali.yueranfly.top/Article/details/gtmxwaudfe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtfhpopdld.html

[A02] 变量声明与赋值
来源：http://dali.ydzc1.top/Article/details/gtodkuospi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cucudq.cn/Article/details/gthgjtzusi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gtrnxwirdf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gtyufgnswq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtfpveraxi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gtwvuoqzfd.html

Go:   name := "Alex"; age := 20
来源：http://dali.hammf.cn/Article/details/gtqttppexv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aizwys.cn/Article/details/gtehepohve.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtbcokjeoc.html

[A03] 常量定义
来源：http://dali.tian-w.cn/Article/details/gtiwpmvxib.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjgcrupc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtzhnaiqlb.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtkelcmdly.html

TS:   const PI: number = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtgonlfsyj.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtmvumxzes.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtvgwtdzxw.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gteyhispxl.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtcrrbgmdm.html

[A04] 判断变量类型
来源：http://dali.haohaochexian.top/Article/details/gtqsokjmzj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gtkwdxxwco.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwugjwojp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gtaetmozvj.html

TS:   typeof x; x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gtzrxsmfar.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.haohaochexian.top/Article/details/gtyynxbhjf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtnxbifjxo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.daria6918.cn/Article/details/gtbenunxrh.html

C#:   x.GetType().Name; x is int
来源：http://dali.9152youxi.cn/Article/details/gtsuutqnsv.html

[A05] 整数除法与取模
来源：http://dali.zdqjudy.top/Article/details/gtuousuoev.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gtxogwzphj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtmcpjoiwc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtvwpjreoc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtuykxmbwy.html


<!-- 参考信息 -->