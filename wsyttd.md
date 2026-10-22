代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigfzy.top/Article/details/gtivgemcho.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gtnnmigcgy.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gtafqbjeeg.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gttexswtqv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gtixecmfcu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pycfn.com/Article/details/gtwmlsjakh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxuanxn.top/Article/details/gtjslfmpgo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtovcocxcu.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gtdnwneibx.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gtzrsxiwcm.html

[U44] PHP：开启严格类型
来源：http://dali.nanxuanxn.top/Article/details/gthzwmaloz.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtlhdqdhqk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtfpxwumqa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtajeloyha.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtzbspqwwr.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gtzzxjojdk.html

[U47] PHP：联合类型
来源：http://dali.daxiang520.top/Article/details/gtkdlyxxei.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gtvzahjlbt.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gtmicjfuid.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtbjrabxbr.html

[U49] PHP：只读属性
来源：http://dali.andypj.xyz/Article/details/gtvetiqbaa.html

public readonly string $name
来源：http://dali.xylfe.cn/Article/details/gtprpspywx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gtlpzekgjc.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrutmfcn.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gtdauryglz.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gtftnexmnh.html

[U52] PHP：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtyzvgsgbi.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtilqxozec.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gtmaocfbyu.html

$v = $a ?? $b ?? "default";
来源：http://dali.daria6918.cn/Article/details/gtcqhgzzpj.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtznfjaxbb.html

$obj?->method()
来源：http://dali.jlsjyb.cn/Article/details/gthhgdwuce.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtyxxrwckz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbqoghcy.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnehpccxu.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtvogcldlw.html

[U57] PHP：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gttzjnjvsm.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtekwbtkpc.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtxtypkqus.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shzxlz.cn/Article/details/gtsvhucocl.html

[U59] PHP：自定义排序
来源：http://dali.hammf.cn/Article/details/gtlhfebvyz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtlkwfgaro.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtygexvyty.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gthblbjfdl.html

[U61] PHP：正则
来源：http://dali.redwolf501.top/Article/details/gtvdjsfsdw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gthqrwhgdk.html

[U62] PHP：日期对象
来源：http://dali.cheryme.top/Article/details/gtltjkldve.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gttbuvswjk.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gtumvzypjm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtgzsrvfhg.html

[U64] PHP：目录遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgyhvhbz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gtdyrvcdbh.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gtbplfusoi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtecexkblw.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gtvjqpcvwg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nwbrower.top/Article/details/gtbcepruoc.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtzubsxtoe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtaxncvptn.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gtnfceqswx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.quarkkingdee.top/Article/details/gtgrqupxtq.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gtcqbpexde.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.birdmap.top/Article/details/gtkwslywfl.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gtuzlkywak.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhongyouzk.top/Article/details/gtqqwikotj.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gtanxonhqa.html

throw new RuntimeException("失败", 500);
来源：http://dali.gotoacloud.top/Article/details/gttmnkytvl.html

[U72] PHP：写错误日志
来源：http://dali.redwolf501.top/Article/details/gtqvnueysm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yonumen.top/Article/details/gtoggwpybh.html

[U73] PHP：读取 ini 配置
来源：http://dali.gotoacloud.top/Article/details/gtpcdmuxmp.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtzgceeuse.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gttacjjpyi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtmewuwrkx.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gtsmnvaysh.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gtnqnbwoqm.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtmeaccpuj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gtmwdzpemz.html

[U77] PHP：模板渲染
来源：http://dali.aizwys.cn/Article/details/gtrzvubhig.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gtjfedbqqg.html

[U78] PHP：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtrufoltwq.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gtrkpyjbez.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtsyytjxyk.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjhimftt.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gtpypgqbzv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtpcftfjat.html

[U81] JS：初始化项目
来源：http://dali.andypj.xyz/Article/details/gtwuufcxka.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gttsmbkxjk.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gtodjfbzni.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sweek.top/Article/details/gtwrhygssh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gteslrpdtw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtecwexffe.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258.top/Article/details/gtdmizcnlb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnqzz.top/Article/details/gtajpjhnxo.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtjghgpnnu.html

a?.b?.c
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhqvbhgy.html

[U86] JS：空值合并
来源：http://dali.cqqwz.cn/Article/details/gttosxpbff.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtzhzwsvrd.html

[U87] JS：解构默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtodkgllyu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sufxvd.cn/Article/details/gtcburfvaf.html

[U88] JS：对象展开合并
来源：http://dali.daria6918.cn/Article/details/gtlgxcjbyg.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gtiqmpptav.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gtqnerjvcs.html

[...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtoyyadotx.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtarcpimgd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtacuzmpkt.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gtbfisgjbd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cdnleiting.top/Article/details/gtzppfdihb.html

[U92] JS：深拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtlcsmdtho.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtlfunmozv.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtkiufkuna.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gtedfnuumn.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtqeuqfrek.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtrpaejtav.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtuwtmhbju.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtfbwktojw.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gtmuyzipok.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrvarlwfx.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtrifgtbef.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtmohhykla.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gttwjdecbp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpecersz.html

[U99] JS：事件监听
来源：http://dali.xylfe.cn/Article/details/gtruenkhbs.html

el.addEventListener("click", e => {})
来源：http://dali.ybcxt.top/Article/details/gtjxeuueqm.html

[U100] JS：DOM 查询
来源：http://dali.yangfankeji.com/Article/details/gtaidiplnv.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtjhrhjdcl.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtklmofsyp.html

el.classList.toggle("active")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspjbyrvv.html

[U102] JS：本地存储
来源：http://dali.smart0.xyz/Article/details/gtjzvcytoi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gtzevgokph.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtxhlrmhdv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwqahfyp.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtiwmladxo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtnrujdmoy.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtxjjsyobo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gtqwzbmzma.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gtnckssxvf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gtskvsqzov.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gtvoygsgux.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtzpsfavkf.html

[U108] JS：随机整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqxicnkh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuanzx.com/Article/details/gtwduxctme.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gthemirvtf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtncytnqzn.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gtkbbwunuv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gtmuhgzgat.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gtqoaueewc.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gttwrvipuq.html

[U112] JS：字符串补位
来源：http://dali.wangdashe.top/Article/details/gtjrzyfphp.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtisznslqm.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtefrlzkdk.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtptwqcknz.html

[U114] JS：JSON 深比较
来源：http://dali.mhx1999.top/Article/details/gtgajnpyqy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtcgxjyhbz.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtystjjtbi.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtkmxgbykj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gtbdpewqhl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gtdpizxcnr.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtgbabxqon.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtdkiqxehl.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtfngwzwfh.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtqkgxicbk.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gttkxhcsip.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxrlcjjp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gtmhoumtfu.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gtbiizrolm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpdxpsoql.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfynyhya.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtluinfqkj.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtfcazqtzk.html

Python ......... 252
来源：http://dali.pengpengdd.cyou/Article/details/gtwzlvpitp.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gtqyvumuuo.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gtsqnxvqet.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gtcgrzcqtd.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtoucdmgpx.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtcoqbrkvx.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gtsnlzbbrm.html

C# ............. 212
来源：http://dali.xuanzx.com/Article/details/gtzljvgoht.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gtzkxprfje.html

C++ ............ 30
来源：http://dali.nanxuanxn.top/Article/details/gtfofxpflo.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gtuqydilym.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gtpgzulnje.html

Kotlin ......... 15
来源：http://dali.jyoumei.cn/Article/details/gtlkzttpmp.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gtkheozcmz.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gtznjllikp.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtzxzeaqoh.html

Scala .......... 10
来源：http://dali.tanke756.top/Article/details/gticefpjku.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtbkilbkso.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gtknjkgffw.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gtxjfvfotw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gthkkwxosp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtezoacdwe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtnqgjxttm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitpqzohf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gticletkyp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtiweoyoya.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxydetydg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtvygakgzz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gthgmhwsvh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtwbhnoosk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsqiuubz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtzsisivfl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtfaumfiyf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtcocetaqv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gtcipupzxu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtkqcbtfwx.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gtjfzsvdqf.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gtkisqpngi.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gthgxplycz.html

T 其他语言补充                          60
来源：http://dali.cdnleiting.top/Article/details/gtmqbmsbua.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtmfvgjwzw.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtvttoqeus.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gtphytbsgz.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtlvcjfvuq.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gtljmtcqch.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtkkhunhoc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gtnkjlpert.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xinyue.icu/Article/details/gtmclhbpsb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtzcjrsivq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gtfathjxnj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenjidiqi.icu/Article/details/gtwuqgvbic.html

—— 文件结束 ——
来源：http://dali.bjfxy.top/Article/details/gtffjzucah.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrfgxmezh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xinyue.icu/Article/details/gtjmuhateu.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gtmnfnefas.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaehpsfkk.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gtgrmojsrr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenzaomai.com/Article/details/gtommflogd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtppxpmbnv.html

SQL · Bash · C · C++
来源：http://dali.9152youxi.cn/Article/details/gtqdssmfrc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gtebnnifpm.html

【使用说明】
来源：http://dali.cashguo.top/Article/details/gtvoumfamv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gtrrieqkok.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gtsbcbneqe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yangfankeji.com/Article/details/gtpviatehp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gtynfjrabu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gtgcxyofup.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gtfxukndhb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhixingplan.top/Article/details/gtkxnokdil.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gtgbaoroko.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuetiantiany.cn/Article/details/gtcfcdcymn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtzppjjjny.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gtdbdudnvs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gtptkomzzn.html

【文件统计】
来源：http://dali.sxryk.cn/Article/details/gtytckgjmk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gzhubu.top/Article/details/gtkqcnrrrw.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtomsgtjsd.html

目  录
来源：http://dali.mhx1999.top/Article/details/gtadgswvhh.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyksmbhzz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guannengcc.top/Article/details/gtmcdlwoic.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtjcditerx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtiofhtwvu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gtpdnxwahy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.svipenyu.cn/Article/details/gtemngxitq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtqkhmlcsn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtttfgjwha.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtsgxxcnoa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoasfrzxu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gthleaslhq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtoqkswyfo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtqmkrhjlf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtmiblzmui.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtvrclrrfr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gtayrmazgd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtfwmmtask.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtfbsriywj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gtrxxsgnqh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkquitrin.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtoxrfwpis.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtflgysgsy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfvxzufja.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtineugqkz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwegymnlm.html

[A01] Hello World
来源：http://dali.sufxvd.cn/Article/details/gtblmsqkld.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtztxxumrq.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gtghymffqa.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtkeoaqunx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuxming.cn/Article/details/gtsfonvabd.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtjxstwinw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtpdlhvnke.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gtxfzyqtvm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtgzsbjrhx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gtbxysmuti.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gtmdzrpqcf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrconzzrw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuanzx.com/Article/details/gtniwukfdh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtulifqagb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtvfsgotfa.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtipnlmngh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegqoqsvh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtonfjoman.html

[A03] 常量定义
来源：http://dali.wangdashe.top/Article/details/gtihbcjxhc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtkdouuhid.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtfeypahgf.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtwrrdzegw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtajpatlzn.html

Java: static final double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtvqdzbclg.html

Go:   const PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtvvlzzhxb.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtvryrbbya.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtdhsfuwau.html

[A04] 判断变量类型
来源：http://dali.0kj1m.cn/Article/details/gtoizelvuy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gtshajneno.html


<!-- 参考信息 -->