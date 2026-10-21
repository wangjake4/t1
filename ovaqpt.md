代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtvxvpwmnb.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtduglepmp.html

[U40] Py：打印到标准错误
来源：http://dali.iojbl.cn/Article/details/gtfgjzvpjn.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjokrijdb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuxming.cn/Article/details/gtkpleeyto.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daria6918.cn/Article/details/gtrsdmoiya.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gtjzotykfd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gtbwlqtvdw.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gtjjtutfyg.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gtgpjsldsq.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeguwrja.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtffpktblk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xinyue.icu/Article/details/gtgsubcbqk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtyidcivis.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gtqtkhecrj.html

?string $name = null
来源：http://dali.fzhhl.top/Article/details/gthdzglfte.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtfahoqjxp.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtlohokjsa.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gthcfgthcf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtfrjgfuxe.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gthblzrgvn.html

public readonly string $name
来源：http://dali.vqdsnc.cn/Article/details/gtiofqhqdp.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtcqtegarj.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gtkeugwsoy.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gtqbasykwf.html

[$a, $b] = $arr;
来源：http://dali.cashguo.top/Article/details/gtosadbrif.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gttymtqprd.html

$double = fn($x) => $x * 2;
来源：http://dali.ybcxt.top/Article/details/gtvzowzrwy.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gtmzgicfxc.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtarovuvag.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gtburzdqbt.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gtovxlkmvv.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtjzefkgkk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gtlxalafyu.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtnhedaccw.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtjvbvhzjv.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtjgutdxgw.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtoacvpsnk.html

[U58] PHP：数组三件套
来源：http://dali.hywenlv.cn/Article/details/gtnqxkvpsz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cashguo.top/Article/details/gtmontlpql.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtrebrwfms.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtpaboidot.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtbfwbisdk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtuhrlqvjr.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gtxaagpqhk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtnwkbvbqv.html

[U62] PHP：日期对象
来源：http://dali.hysaishi.cn/Article/details/gtkpujicuz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gtkwbvhqvx.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtlenztajf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcnofoyd.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gtqczhkwnd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.mhx1999.top/Article/details/gtkpnqjnbk.html

[U65] PHP：会话
来源：http://dali.bjfxy.top/Article/details/gtlvsqmieh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtmbathvfi.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gtnnkiypnz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hysaishi.cn/Article/details/gtdbguqroe.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtpajjsjpn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.0kj1m.cn/Article/details/gtvlfiehje.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gtkmrxxnbe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gtyxbhjexv.html

[U69] PHP：PDO 预处理
来源：http://dali.bjfxy.top/Article/details/gtyufbzmxb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gtpwxjoirg.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gtvjseplyp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sufxvd.cn/Article/details/gtrccdbtrv.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtspsdzqjs.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gtqmfmylqi.html

[U72] PHP：写错误日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomrdfwhp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gtmrpmkpjz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhixingplan.top/Article/details/gtofmvacrt.html

parse_ini_file("config.ini", true)
来源：http://dali.guannengcc.top/Article/details/gtxxyxogga.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdknndgqf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhongyouzk.top/Article/details/gtcgifnozu.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtafscvulu.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtmfhystxg.html

[U76] PHP：简单路由
来源：http://dali.sweek.top/Article/details/gtpgjlbhrr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtlnqqohtg.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtodatffkn.html

composer require twig/twig
来源：http://dali.hysaishi.cn/Article/details/gtomsfcrhj.html

[U78] PHP：单元测试
来源：http://dali.hammf.cn/Article/details/gtwqvzpukn.html

composer require --dev phpunit/phpunit
来源：http://dali.aibaodan.cn/Article/details/gtnpoqxcsi.html

[U79] PHP：静态分析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlltzjayy.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtbjqxbglt.html

[U80] PHP：代码规范修复
来源：http://dali.zhoulong.xyz/Article/details/gtlzpvhxja.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtvczxdfpp.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtvctawkrz.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gtnusrvkrd.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtwbjnwidp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gotoacloud.top/Article/details/gtmeqjqshm.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gtvekxubly.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtlbrbavjc.html

[U84] JS：CommonJS 写法
来源：http://dali.quarkkingdee.top/Article/details/gticjgrndi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtluqsdnud.html

[U85] JS：可选链
来源：http://dali.yuxming.cn/Article/details/gtccfkdazz.html

a?.b?.c
来源：http://dali.feifeiyinyue.top/Article/details/gtcoxjgbdy.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gtnbvauker.html

a ?? b
来源：http://dali.svipenyu.cn/Article/details/gtkmjbldca.html

[U87] JS：解构默认值
来源：http://dali.aibaodan.cn/Article/details/gteiykzxrs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfhmvllu.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gtyiouoipg.html

{ ...a, ...b }
来源：http://dali.tanke756.top/Article/details/gtjrhzbjfh.html

[U89] JS：数组去重
来源：http://dali.zycfv.cn/Article/details/gtpomjltxn.html

[...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtjecxhjmu.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtnosaujzd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtrisayvjl.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnsqjbyd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbflfslhf.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gthfgtebng.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtkdnlkmnq.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtuwkpntui.html

`共 ${n} 条`
来源：http://dali.hongshengwenyu.top/Article/details/gtvnihyrfq.html

[U94] JS：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthprhvbap.html

const double = x => x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtubybjjep.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhnlbiif.html

new Promise((resolve, reject) => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxjzlrrj.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gtprjlncag.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtolifbcjs.html

[U97] JS：并发请求
来源：http://dali.yvedp.cn/Article/details/gtzekhsung.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtfjvriwxd.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gtjsqjeeac.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gtmtmxehmw.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gttmohljck.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtidqdcvef.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtsnhxznpz.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gtzwdqzert.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhsdfnbw.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gtgohboihw.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gtnywwnpkx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtwkvpushx.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gtcoorivqr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtkdhoubfs.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtzqjhlqqz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtbagpnexw.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gtvemwoizz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gtznunkhps.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtcymasjno.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtjnosaoik.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gtfahdqezc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.iojbl.cn/Article/details/gtbghmccnr.html

[U108] JS：随机整数
来源：http://dali.hysaishi.cn/Article/details/gtciojkupg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtypnrxglk.html

[U109] JS：数组分组
来源：http://dali.yj20258888.top/Article/details/gtmtilfknw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmppfcgsa.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtzmrordxx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tanke756.top/Article/details/gtuumtrprf.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gtiovysgqm.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gtstyyalqm.html

[U112] JS：字符串补位
来源：http://dali.wangshuangyany.cn/Article/details/gteeahuzaw.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtedubniaw.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtvkjvnnhz.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtfvyaofqq.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtahuahnwt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtwbjpxvog.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtplynbvxk.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtghkvkkhr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gtzgsqcfln.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yvedp.cn/Article/details/gtputkgrkl.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gthhzjfwmt.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtcescszhc.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gtdzqehduu.html

npm i -D vite;  npx vite
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnejiiqtd.html

[U119] JS：生产构建
来源：http://dali.sxryk.cn/Article/details/gtxmuttpxg.html

npx vite build
来源：http://dali.chenlongwang.top/Article/details/gttmddqgvm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hysaishi.cn/Article/details/gtuputxhwg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gtcpydtglp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvlfndwil.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gtnhaxuvcp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdwrenzkh.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gtvxlyzlxn.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtdgphlxvi.html

PHP ............ 252
来源：http://dali.jiagoushi.top/Article/details/gttgvpfush.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzkycfyx.html

TypeScript ..... 212
来源：http://dali.gotoacloud.top/Article/details/gtdfcnwsiy.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtbviufpcv.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtxaktprpo.html

Ruby ........... 212
来源：http://dali.c1oappe.top/Article/details/gtewogsdbv.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtoahcwtpc.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gtlhovujvz.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gtvwqgucml.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxsjxywh.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gtcygvpugi.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtexacoleh.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtcglewjmi.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gtmprrwunu.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtzcvbzlnj.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gtjjfaronc.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gthvcpfdhp.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbymfwme.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gtnardfjdy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtxxwromhq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtaxznudwp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtoypflduh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtiadurpre.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjarlxvxc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtjogpkgas.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtnvmmdnly.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtfwkvvlkt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtbluwgkip.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnasdpyu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhasmrbq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtjethylxc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtgdamnrid.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtqgjqsisf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtvrmbindx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtikmkyply.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gtfauwivtn.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gtelddlyut.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtyujdsccy.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gtuungmkxe.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gttcjsbfka.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtfuvmzgsk.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gtlckegiib.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtdyrzeakk.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltaygicu.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtyrphyjey.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtjreyspfe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gtdclppxlc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gtyydrezea.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dashuyun.cn/Article/details/gtatvefdax.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenlongwang.top/Article/details/gtdpxeftdb.html

—— 文件结束 ——
来源：http://dali.smart0.xyz/Article/details/gtojnfzgaj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtjeeadygb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegetxcrk.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtyfiqpaqg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmeznbhgg.html

【收录内容】
来源：http://dali.svipenyu.cn/Article/details/gtohhjksem.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtqhbibmeh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtrttovhxv.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtvfbexcxa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhengqikj.top/Article/details/gtlrsddrbo.html

【使用说明】
来源：http://dali.chenzaomai.com/Article/details/gtgxsmynln.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hammf.cn/Article/details/gtagdungsa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gttthijphx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gtxmwglcdp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtvjyccitk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shzxlz.cn/Article/details/gtgxgxtttb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hywenlv.cn/Article/details/gtanznireq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cashguo.top/Article/details/gtkogcyxlr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gtvddxbvbc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtssrfwugz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gttqkjthqu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhiwuduotai.top/Article/details/gtorfyflfk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.316326.xyz/Article/details/gtrajnzayn.html

【文件统计】
来源：http://dali.sufxvd.cn/Article/details/gtlnfnbtvn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ybcxt.top/Article/details/gtfxqgzsov.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtxgwvxihg.html

目  录
来源：http://dali.nwbrower.top/Article/details/gtbjqnedqr.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtotkivlpo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gtimfuvbkx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gtxspulnhw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtpxaoocxo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtcfitjngt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gtmpetivrq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sweek.top/Article/details/gtykxjxjwz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtumjjnexf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtdhbfscbd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtwnpiptqp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtkrguvbls.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtwadmanho.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtmwdtxqzp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gteryzjxmm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gtzwqvpqcf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gthlejnwqp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtopnuwdqa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pycfn.com/Article/details/gttyweuxto.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gtxhtwpvcd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gtaqzwevto.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtxlcmfzwj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtazobcqdu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjbyzldoh.html

A. 基础语法与类型
来源：http://dali.yuxming.cn/Article/details/gtfwxvnlgp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfdckwtw.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtgdazmiyh.html

Py:   print("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtpocglgis.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gtfbxydpsd.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtgqqmzdtf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtnpgjistw.html

Java: System.out.println("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtodknkzbt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmizailj.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gttbpovhja.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtymidkzei.html

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gtfrknlpql.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtautljynk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnqzz.top/Article/details/gtqhmxudfl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fzhhl.top/Article/details/gtdrydhccw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtlxpnpntf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtsksvslfw.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtqpajmfia.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cucudq.cn/Article/details/gteotbgijc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtjybjurri.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gthwogkhfh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gtmzrttojd.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvtmpgrc.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtuqmvjqjf.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtqdrjqoll.html

Java: static final double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtducbbdcn.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsslixzys.html

Ruby: PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gtelmhouvn.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblzqosql.html

[A04] 判断变量类型
来源：http://dali.daxiang520.top/Article/details/gtwvwqcfns.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gtrtlcxfwq.html


<!-- 参考信息 -->