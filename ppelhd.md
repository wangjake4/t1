代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtdjsoinsn.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gtmabcklby.html

[U44] PHP：开启严格类型
来源：http://dali.hnqzz.top/Article/details/gtnuobmnhv.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtwqcshsrc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gtdqpttpcw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtboqoxybh.html

[U46] PHP：可空类型
来源：http://dali.sufxvd.cn/Article/details/gtrtgjtnzx.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtiumjiszx.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gtdsetvjdk.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gtrjqytkgl.html

[U48] PHP：纯枚举
来源：http://dali.daria6918.cn/Article/details/gtrlqfatlf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.haohaochexian.top/Article/details/gtzcpmstaw.html

[U49] PHP：只读属性
来源：http://dali.gogol.net.cn/Article/details/gtpdpshfqk.html

public readonly string $name
来源：http://dali.cqqwz.cn/Article/details/gtsoonhgly.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtdlpiaukm.html

public function __construct(private int $id) {}
来源：http://dali.hfpthk.cn/Article/details/gtoszixisa.html

[U51] PHP：数组解构
来源：http://dali.xuetiantiany.cn/Article/details/gtzgmmzgzh.html

[$a, $b] = $arr;
来源：http://dali.jyoumei.cn/Article/details/gtwxjhalfb.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtxpugpgbc.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gtwymsmbhd.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gtabvqywbb.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gtibsbfgso.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabkbkqhb.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gttcqthxww.html

[U55] PHP：match 表达式
来源：http://dali.shuidangran.top/Article/details/gtfzlceugo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttauztbjl.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gtoidldgby.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtqmvmfijs.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtrjivrnae.html

"值: {$a}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwylctet.html

[U58] PHP：数组三件套
来源：http://dali.daria6918.cn/Article/details/gtstssesvx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gtpbonmktx.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gtznymfajo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtdyqpaiyo.html

[U60] PHP：JSON 编解码
来源：http://dali.yonumen.top/Article/details/gtcpihkted.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtewavdcly.html

[U61] PHP：正则
来源：http://dali.kuanghao11.cn/Article/details/gttsbvyuyp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gthsxmuzxf.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gtwdmautsr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gtplgsnfph.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gtkemzycnk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtubliprzd.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gttrvgauyl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtheeyvasr.html

[U65] PHP：会话
来源：http://dali.wangdashe.top/Article/details/gtkyaoutdo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtaumoqimq.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gtkllnxntl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtzuqfuwpa.html

[U67] PHP：处理文件上传
来源：http://dali.pycfn.com/Article/details/gtxmcujwct.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gttnrhhuca.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gtejpnhqgb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangshuangyany.cn/Article/details/gtghmevfzh.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gtcjsytatb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtcohjqrcn.html

[U70] PHP：PDO 事务
来源：http://dali.wangdashe.top/Article/details/gtytexthdq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.vqdsnc.cn/Article/details/gtggqhwrtr.html

[U71] PHP：抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtclnhzwps.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapovyjoq.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtwmykeedg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtziprgewy.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtuawtoejh.html

parse_ini_file("config.ini", true)
来源：http://dali.wangshuangyany.cn/Article/details/gtimvpzqrt.html

[U74] PHP：读取环境变量
来源：http://dali.nanxinkj.top/Article/details/gttgoftxhk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gttzzkkafu.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gtsxjuqusj.html

composer require psr/container
来源：http://dali.ivvv.top/Article/details/gtwtpfwvzt.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gtodnmbpac.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.svipenyu.cn/Article/details/gtgjerqgyt.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gtzialoczx.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gtgnpphaya.html

[U78] PHP：单元测试
来源：http://dali.316326.xyz/Article/details/gtwcziillx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhiwuduotai.top/Article/details/gtgfossrzr.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gtaqlphsxb.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtocfdaerp.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gthtxnerdz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtbfhuhuxq.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gtygytubzz.html

npm init -y;  npm i express
来源：http://dali.sysykeji.top/Article/details/gtgrftusme.html

[U82] JS：package.json 脚本
来源：http://dali.jianghu66.top/Article/details/gtdbakduhh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtqffnwoti.html

[U83] JS：ES Module 导入导出
来源：http://dali.jyoumei.cn/Article/details/gtkqopgklk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtqeyxeqzl.html

[U84] JS：CommonJS 写法
来源：http://dali.hnxiangtu.top/Article/details/gtzvaioxzo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hysaishi.cn/Article/details/gtnoofujng.html

[U85] JS：可选链
来源：http://dali.0kj1m.cn/Article/details/gtzsjlaquw.html

a?.b?.c
来源：http://dali.pengpengdd.cyou/Article/details/gthtpjisdz.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gtstobprwq.html

a ?? b
来源：http://dali.xuanzx.com/Article/details/gtxvpsehla.html

[U87] JS：解构默认值
来源：http://dali.cqqwz.cn/Article/details/gtfofaojux.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangshuangyany.cn/Article/details/gtifwqxalg.html

[U88] JS：对象展开合并
来源：http://dali.sweek.top/Article/details/gtmffajqkz.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gtzmkdbhya.html

[U89] JS：数组去重
来源：http://dali.yj202588.top/Article/details/gtgqzlpfwu.html

[...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtegmhopbc.html

[U90] JS：数字数组排序
来源：http://dali.xylfe.cn/Article/details/gtrgsemthl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtwmilnkbr.html

[U91] JS：对象键值遍历
来源：http://dali.cucudq.cn/Article/details/gtdqdtricp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gtumdjshtv.html

[U92] JS：深拷贝
来源：http://dali.wangdashe.top/Article/details/gtdrlintdr.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gteofsuibq.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gtqvdwltaa.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gtfkjcrszl.html

[U94] JS：箭头函数
来源：http://dali.316326.xyz/Article/details/gtwhovjnxj.html

const double = x => x * 2;
来源：http://dali.zycfv.cn/Article/details/gtqxjnyrqt.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtdkllzmvy.html

new Promise((resolve, reject) => {})
来源：http://dali.jianghu66.top/Article/details/gtjnhtyvrr.html

[U96] JS：async/await 与异常
来源：http://dali.sysykeji.top/Article/details/gtqyzyaetj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtkheritap.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqzwnjea.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtgoeplprp.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gtamfxpwsk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtpehklvet.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gtmlarlmlb.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gttgnoifah.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gtlhvaofgn.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gtcdkudeae.html

[U101] JS：classList 操作
来源：http://dali.daria6918.cn/Article/details/gtikqaerai.html

el.classList.toggle("active")
来源：http://dali.yangfankeji.com/Article/details/gtfjzgvpnw.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gtyvldfyls.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gtozdfppbn.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gtvzmkhhwu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtkckjbgoe.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnsuduew.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtubqsuska.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gtmhuvrvtd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtgyelwezw.html

[U106] JS：日期格式化
来源：http://dali.aizwys.cn/Article/details/gtbbsorxkd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gtljjkltlt.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtzpsgjrtk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtxudlosji.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtzdkjhcgn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtlgnyztll.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gtrqinzqtm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gthtkanydh.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtvcghpxlb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gtqypnggzq.html

[U111] JS：对象转 Map
来源：http://dali.haohaochexian.top/Article/details/gtvkwwsitn.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtffeomapw.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtzuvkqkqi.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtcjtpvddw.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gtpbtypktt.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtnlvinves.html

[U114] JS：JSON 深比较
来源：http://dali.yuxming.cn/Article/details/gtglqqzuyt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtsbneyseb.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtuxfmmjvy.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtabmarmfa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gtviaespgx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.c1oappe.top/Article/details/gttzyzzxyg.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gtwceqbsht.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtoztvzcqd.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gtlbqixlxl.html

npm i -D vite;  npx vite
来源：http://dali.jinqigfzy.top/Article/details/gtogdtgkrh.html

[U119] JS：生产构建
来源：http://dali.shuidangran.top/Article/details/gtpozhhoyn.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gtzopaartb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkabmpfmv.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtqzmgvptv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzryouzbu.html

统计汇总
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzwmfkbh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzjkensyr.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtdrzphsta.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtchoftlbr.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtjjhizfzu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtjjoprkaj.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtbhjaktup.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gtcsxaahou.html

Go ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtkojecrks.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gtpuryapyo.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gtjdujhmpz.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gtyujhbgtn.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gtuegnbtwm.html

SQL ............ 90
来源：http://dali.meibo888.top/Article/details/gtnccnyrgq.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gtccpzrqvp.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwwyxowq.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtainoubyw.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gtxaocihxf.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gtnfrdnoyl.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtghcnfcpu.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtrampomgd.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gtmpnqweiv.html

按章节统计：
来源：http://dali.yueranfly.top/Article/details/gtwdhqwdif.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtfxqzowfa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtknsqkhph.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtnooswluj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtflwuasfe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gtgpjcfmin.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtqhlfhzhv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtkjobbraq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gtpzqctxae.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gttylmngmr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtwrzokwyk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtmrukiloy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtrbgzuvpa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtgpsumgpa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtstvlturq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.snrcjt.cn/Article/details/gtdykexlpj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmrldhos.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gtimarvttb.html

R Bash 专题                             80
来源：http://dali.gogol.net.cn/Article/details/gttewjfsxd.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gtljdmhcqt.html

T 其他语言补充                          60
来源：http://dali.birdmap.top/Article/details/gtkshshpru.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekwpwvqc.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtivacvfke.html

合计                                  2106 条
来源：http://dali.ppjwa.cn/Article/details/gtxpqqejxk.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtuwzwthbo.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gtbpvqpdsl.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtiataakqy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gthcmgzdbd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gtvfkfhgch.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gtqjfoknlt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtpdrcjwue.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yvedp.cn/Article/details/gtbjnjedxu.html

—— 文件结束 ——
来源：http://dali.zhiwuduotai.top/Article/details/gtdqusegma.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpwvebtlc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtmqeohvqj.html

Common Programming Examples Cheat Book
来源：http://dali.tianlin.xyz/Article/details/gtvfghlqpf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbyyjqrab.html

【收录内容】
来源：http://dali.sxryk.cn/Article/details/gtjlsuoxxz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gtabymfogt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gttzlovlpm.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplktwmiw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gttyuhszci.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtkpvseips.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gtydaozmcf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gtpdbmmolc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gtmljhfkxa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gthhyyeaam.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtqaeughko.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gtrgngfzbi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gtrbnhtcgm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gogol.net.cn/Article/details/gtijaqnixx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.quarkkingdee.top/Article/details/gtbpmkteej.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtrwewkhdc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gtcosrvdew.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtphdsyres.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gtngltjhrw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gteqdytwsg.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtsblvsgbe.html

目  录
来源：http://dali.iojbl.cn/Article/details/gtgiawcnwc.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtrnxyswki.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtwgozcfau.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtmwrrvlvr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtmhwxjapu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gtwsnmeigw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtthledrmm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cashguo.top/Article/details/gtgawzsbfw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gtjzvxemog.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtwtffzvdq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtlracnzva.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtnqtlktoo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtizmmlcpk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtycdpdzod.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtgoeyqnyw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtvmghkdzm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ivvv.top/Article/details/gtijtbhgax.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtuluxwilt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gtbjyogzro.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ybcxt.top/Article/details/gtnuzcqeui.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangdashe.top/Article/details/gthrttgzje.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtyfycmbav.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnohveul.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkjyveatu.html

A. 基础语法与类型
来源：http://dali.sufxvd.cn/Article/details/gtxizkfhxu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbfwmbvth.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtbxyfuizl.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtcvnbydxl.html

PHP:  echo "Hello, World!";
来源：http://dali.tanke756.top/Article/details/gtrurnmzgi.html

JS:   console.log("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtzlyriqao.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.haohaochexian.top/Article/details/gtpzfllguf.html

Java: System.out.println("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtimromnts.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtockoqjlp.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gtvokqgqvq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtnrcoyxou.html

[A02] 变量声明与赋值
来源：http://dali.shzxlz.cn/Article/details/gtpfyvvexp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hfpthk.cn/Article/details/gtafquqnwx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtdhndmfos.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gttpqrdeiy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtwjsomkqn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtolndkcvb.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gtvbtukgai.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yonumen.top/Article/details/gtqplrabve.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtdqnnigcw.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gtjahmuoxg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtyumukocc.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gttqepwbsd.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtjkdzwium.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtmwoohbkx.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtxxxzztze.html

Go:   const PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtkwwgymxu.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtlfbeenri.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtbkwkeljz.html

[A04] 判断变量类型
来源：http://dali.hfpthk.cn/Article/details/gtcujaqaws.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gtjgoqcffj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guannengcc.top/Article/details/gtuqbricmk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtgwvqdnso.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtvmgtoora.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gtbwuzhavo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ehwqpu.com/Article/details/gtcoagdwws.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cheryme.top/Article/details/gttxqpxhya.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangdashe.top/Article/details/gtcvufxhuq.html

[A05] 整数除法与取模
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnsjylvm.html


<!-- 参考信息 -->