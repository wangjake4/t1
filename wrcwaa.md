代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gt2ptntemmj.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gt2hsxnkdls.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcrwthvu.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gt2sesleeot.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fccbfrsy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2miuvdwir.html

[U46] PHP：可空类型
来源：http://dali.jianghu66.top/Article/details/gt2huesqymp.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gt2tndzcjci.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gt2foublxfw.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gt2rkcbmueu.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gt2ltysguip.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gt2bvvodnyl.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gt2mctloitj.html

public readonly string $name
来源：http://dali.daxiang520.top/Article/details/gt2xdimvvrg.html

[U50] PHP：构造器属性提升
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndnvpjgw.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gt2tzgmtlzp.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gt2aavbhzce.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gt2waulwydx.html

[U52] PHP：箭头函数
来源：http://dali.yj20258888.top/Article/details/gt2huoaznyo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daqcjujp.html

[U53] PHP：空合并运算符
来源：http://dali.birdmap.top/Article/details/gt2tnxkqptb.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gt2bnsepmhj.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxryyynh.html

$obj?->method()
来源：http://dali.aizwys.cn/Article/details/gt2tovjxuwn.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gt2htpqmbjd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gt2jlsehifd.html

[U56] PHP：命名参数
来源：http://dali.guowangkeji.top/Article/details/gt2xusvlgxh.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2tqabgeao.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2txkycfpn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzxzgcp.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gt2cimynoao.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2hlskdxxj.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gt2wtmuxrdr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2fwczpepd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gt2olrultab.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gt2ognhzczn.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gt2ifiqawet.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2mdvnygfp.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gt2afodjrkk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cqqwz.cn/Article/details/gt2fmwvohga.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gt2qiywzywy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuanzhike.top/Article/details/gt2zbdqndbu.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gt2jiezuhck.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gt2qocybpnq.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddybkhpv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2dbcvfkwf.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gt2olpqtwwl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gt2irmbenwo.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gt2gsmnittk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymrxiknw.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gt2ykzflvfm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyaowsyt.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gt2xamtuveb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gt2sdofzaim.html

[U70] PHP：PDO 事务
来源：http://dali.redwolf501.top/Article/details/gt2cljnblou.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwurlfbs.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2wpnqtgey.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gt2unomghqi.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gt2tvmxiwrb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gt2gshsvzby.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gt2dinwkjdy.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gt2cwypfixm.html

[U74] PHP：读取环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2pceujnnw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gt2jefatvva.html

[U75] PHP：依赖注入
来源：http://dali.yj20258888.top/Article/details/gt2ellwscrd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcehzdl.html

[U76] PHP：简单路由
来源：http://dali.shangyingyoupin.top/Article/details/gt2olsfoppb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztgqfzud.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gt2lmekoeaa.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gt2jzqdrizf.html

[U78] PHP：单元测试
来源：http://dali.cqqwz.cn/Article/details/gt2refdzdhq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gt2lkhswvyv.html

[U79] PHP：静态分析
来源：http://dali.meibo888.top/Article/details/gt2bbwzkfdp.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gt2wfpkduax.html

[U80] PHP：代码规范修复
来源：http://dali.cucudq.cn/Article/details/gt2waoedcsf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gt2wkqmfuxy.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2evtakved.html

npm init -y;  npm i express
来源：http://dali.tian-w.cn/Article/details/gt2gdrwpziz.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gt2tjqqsqfq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhengqikj.top/Article/details/gt2uefipfiu.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gt2hqbgibpp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2nvtqnkuv.html

[U84] JS：CommonJS 写法
来源：http://dali.ehwqpu.com/Article/details/gt2ywgoykmb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rogkagii.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gt2coubsxht.html

a?.b?.c
来源：http://dali.chenlongwang.top/Article/details/gt2hwlryeqv.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwrhnmkb.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gt2donsiwhx.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2nmquavvc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gzhubu.top/Article/details/gt2hpixbfzp.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gt2dgdfyuxw.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gt2cpxldrqb.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gt2jmyllnao.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2kctpksla.html

[U90] JS：数字数组排序
来源：http://dali.xylfe.cn/Article/details/gt2ofqymdyl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2nytkvqyr.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gt2wurcnbme.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gt2dkhschdq.html

[U92] JS：深拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2lenjsdss.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2rkgageig.html

[U93] JS：模板字符串
来源：http://dali.cdnleiting.top/Article/details/gt2lunchxvh.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gt2xzsfydlb.html

[U94] JS：箭头函数
来源：http://dali.ybcxt.top/Article/details/gt2kljvwtdu.html

const double = x => x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gt2girondgv.html

[U95] JS：Promise 包装
来源：http://dali.yj202588.top/Article/details/gt2ldnraffo.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gt2zxijzubz.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gt2ykranldi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2zdekncoj.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2jnrghtxi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2xohnxbvy.html

[U98] JS：fetch 带 JSON
来源：http://dali.birdmap.top/Article/details/gt2insliaas.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gogol.net.cn/Article/details/gt2eitkmhup.html

[U99] JS：事件监听
来源：http://dali.svipenyu.cn/Article/details/gt2fncvewvk.html

el.addEventListener("click", e => {})
来源：http://dali.sufxvd.cn/Article/details/gt2ewmgdggq.html

[U100] JS：DOM 查询
来源：http://dali.zhengqikj.top/Article/details/gt2xzwdofhz.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flhbrbdv.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gt2opfigmjh.html

el.classList.toggle("active")
来源：http://dali.cashguo.top/Article/details/gt2nephxokb.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gt2dtlqihah.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gt2uelzbnwo.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gt2armogslk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gt2znypnpdh.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gt2egmxiopj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2petwjcvd.html

[U105] JS：节流
来源：http://dali.xuanzx.com/Article/details/gt2vdiuhdgz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gt2weraeygh.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2fetlypus.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gt2fwxqvspm.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxpipiex.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2vtdzkbpq.html

[U108] JS：随机整数
来源：http://dali.jinqigfzy.top/Article/details/gt2ciyrnhsz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xunjmcfo.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gt2jinnhond.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2oujfxrpt.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gt2qnndsism.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gt2vwnwguwt.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gt2samtyjqv.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gt2skrvjmaa.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gt2nlmlcuxw.html

"7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2mmydsevd.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gt2putkdvdz.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2lwrayvax.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gt2iuubugxx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2ajbzvuvz.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gt2unrrtrox.html

crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfsnxmic.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenlongwang.top/Article/details/gt2owselbzy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gt2daujimix.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gt2xjbkumfr.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gt2ydxwkefw.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gt2qmbgqnia.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gt2pfbwecfv.html

[U119] JS：生产构建
来源：http://dali.daxiang520.top/Article/details/gt2zhhziobq.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gt2hganwqok.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.316326.xyz/Article/details/gt2skmriqcv.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gt2oneoxlje.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wiveykdi.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gt2cbizsygo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jyxnagwt.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gt2rhwvkjoj.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gt2pwhgjzbv.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gt2pljqxquw.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gt2hyuiverq.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gt2shseogpj.html

Java ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2feletfbl.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gt2fwniggeo.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gt2mawhshcu.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gt2ucpmwbee.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gt2prfzsmld.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gt2jlekxhgg.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gt2pmdftchr.html

Bash ........... 80
来源：http://dali.snrcjt.cn/Article/details/gt2iojirxno.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gt2zmprxiyq.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gt2vwcmxamo.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gt2llvhcxsu.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gt2mqnrehee.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gt2banbbfpa.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2xwdhufqn.html

合计 ........... 2106 条
来源：http://dali.yueranfly.top/Article/details/gt2gtanewry.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gt2pakfydzm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwmpvwni.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2lfhfommv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2wtiypqjk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2oytaxvce.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gt2exdckffs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gt2mvgmjhuh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpvkweqk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gt2ylnuglzp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2nfdirqxr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gt2ptkzzvgy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2vablfoma.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2mddoabxf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2tnjuttzm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gt2prkpdyex.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fzhhl.top/Article/details/gt2yawcaali.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2wfyzjpue.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gt2ckayattd.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gt2istfyyrm.html

S C / C++ 专题                          60
来源：http://dali.yueranfly.top/Article/details/gt2yihbpuou.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gt2vcpzikcy.html

U 高频实用片段                         120
来源：http://dali.snrcjt.cn/Article/details/gt2pdusixjj.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2bvztibpo.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gt2cszfbajb.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2fzllovkg.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvsvjufe.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2ofawnple.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gt2fsddmppw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gt2frbbxmqf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gt2vyhobtle.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gt2qyrfonvt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gt2wazynrxf.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgpyqjfg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lhrvtqvi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gogol.net.cn/Article/details/gt2ykleflup.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gt2sfptwdad.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zvvqjveh.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmognzlb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gt2eftzbrqc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj202588.top/Article/details/gt2bumfsjrq.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gt2icehxouv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuanzhike.top/Article/details/gt2jjyfakiw.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gt2cyjsfwwn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdzxxhty.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gt2vrzyjzvd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tianlin.xyz/Article/details/gt2cipewicz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenjidiqi.icu/Article/details/gt2edhteigr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sxryk.cn/Article/details/gt2zyrlldef.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tianlin.xyz/Article/details/gt2ebckbtau.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gt2uxjowmyf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.mhx1999.top/Article/details/gt2puylsdil.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gt2hngtxozr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yuxming.cn/Article/details/gt2wfcflifr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gt2zbzuexcr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.316326.xyz/Article/details/gt2ccmrxued.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gt2gvhmcrdb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gt2djkrljos.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2wuwytxsi.html

目  录
来源：http://dali.havefunace.top/Article/details/gt2pvryxcce.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2jspmyuuh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gt2evrrrptq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2jlmvienx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcigdny.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gt2kugliwep.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.bjfxy.top/Article/details/gt2rdmrwccz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2cynxnjwi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2ruhanjzj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2ugbgvots.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtbnooa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gt2opcehulj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eewtkhgy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ylkejtge.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2bpdpbwms.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gt2rbvezmtc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gt2babptdiw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2odpzxqtg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ppjwa.cn/Article/details/gt2xjopbcnk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuanzhike.top/Article/details/gt2odnzkkdd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.andypj.xyz/Article/details/gt2ubcouyoh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gt2geuabtne.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gt2gneczvxw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2abzeggch.html

A. 基础语法与类型
来源：http://dali.hywenlv.cn/Article/details/gt2ckbrdyhb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zvjxibku.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gt2exzfuisv.html

Py:   print("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gt2kpiyczvy.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzglsma.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2ynozfhau.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gt2xfdimcor.html

Java: System.out.println("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gt2ixmgksfm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2tmzrpqjy.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gt2qfvgmtrq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2ybeldgsh.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fiokighw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj202588.top/Article/details/gt2umuurkxp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2xqezdeqx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuinnhao.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2cmukvavt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2gjuxvbni.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gt2dhjobtbs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gt2byyydreh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjulyzsr.html

[A03] 常量定义
来源：http://dali.smart0.xyz/Article/details/gt2avktkext.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258.top/Article/details/gt2zehudygj.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2fvkyhksh.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2eknjubtw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfqyjvep.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmwbqlng.html

Go:   const PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwvdfrho.html

Ruby: PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gt2bowpijtk.html

C#:   const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2vxrkevth.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2nqtfjpzu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gaohongyu789.top/Article/details/gt2ogjvdyax.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gt2ugumeger.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gt2ldusoibr.html

TS:   typeof x; x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2lvdeqxdp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2auzhnvop.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gt2voivvquk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gt2zfqkajxb.html

C#:   x.GetType().Name; x is int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irmydiub.html

[A05] 整数除法与取模
来源：http://dali.jyoumei.cn/Article/details/gt2iyrzioas.html


<!-- 参考信息 -->