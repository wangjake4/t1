代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtkbyaeswp.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtqhaasngy.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gtkjejjnry.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gtdlucnpby.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj202588.top/Article/details/gtbtlgvezf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtdmbbpscu.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gtspdtealf.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gtexxunqyg.html

[U47] PHP：联合类型
来源：http://dali.vqdsnc.cn/Article/details/gtmfxnaizl.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtkfsyiqsd.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtdiovamta.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrufqlzw.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtfuxsiitm.html

public readonly string $name
来源：http://dali.fengsongda.top/Article/details/gtrdypmjzy.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gttavkgbmr.html

public function __construct(private int $id) {}
来源：http://dali.tanke756.top/Article/details/gtefcqrreq.html

[U51] PHP：数组解构
来源：http://dali.snrcjt.cn/Article/details/gtruywdfyx.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gtmudrulav.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtcqcxweyr.html

$double = fn($x) => $x * 2;
来源：http://dali.meibo888.top/Article/details/gtbgxrnlrt.html

[U53] PHP：空合并运算符
来源：http://dali.daria6918.cn/Article/details/gttcxoheey.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gthewfqkol.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtskrrynnt.html

$obj?->method()
来源：http://dali.xuetiantiany.cn/Article/details/gtrroxoefw.html

[U55] PHP：match 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtymhstjdg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtjktkdmtm.html

[U56] PHP：命名参数
来源：http://dali.meibo888.top/Article/details/gtmdnveump.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtfokzbntt.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtnyldvaji.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gtszeetslm.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtyesvkvat.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtjsjvpqvn.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtqpssryhg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtjzumemkh.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhvrhtei.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhengqikj.top/Article/details/gtsnxghlya.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtvbkaudbe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtilsxlwfq.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gtshacvqfk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gtssjidecu.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gttorpwgta.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.birdmap.top/Article/details/gtaudsybkm.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gtsrqcsasg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xylfe.cn/Article/details/gtghpexekb.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtsagjmotp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtwgpofiks.html

[U66] PHP：设置 Cookie
来源：http://dali.yvedp.cn/Article/details/gtiwdjuopa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtwjbicgoi.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gtvcnhlxvk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gtadznynwd.html

[U68] PHP：PDO 连接
来源：http://dali.redwolf501.top/Article/details/gtgvqdeuba.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gtooefeswp.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gtdfyedpxo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtpielwlmx.html

[U70] PHP：PDO 事务
来源：http://dali.ybcxt.top/Article/details/gtjehytzpm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gtlecnxfud.html

[U71] PHP：抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtacqkuwwy.html

throw new RuntimeException("失败", 500);
来源：http://dali.hywenlv.cn/Article/details/gtcddywqgc.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtzddewyze.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gtmlktsfiw.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtffggtywj.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gtslaxeelm.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtlcyrlsdq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gtzsjrbvbq.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtpuzkmmul.html

composer require psr/container
来源：http://dali.aibaodan.cn/Article/details/gtcvkhjmnz.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gtiozlyqii.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.meibo888.top/Article/details/gtlpngxvmr.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gtehnutnxx.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtbkqzaalt.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gtatkodoyq.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtuarwhaxy.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gtldbkogwh.html

composer require --dev phpstan/phpstan
来源：http://dali.yanxiufei.cn/Article/details/gtbcptyqas.html

[U80] PHP：代码规范修复
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvinplepi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtresglqeq.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtyrzubaje.html

npm init -y;  npm i express
来源：http://dali.hysaishi.cn/Article/details/gtykynhjvr.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258888.top/Article/details/gtujkpztea.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyfmplxl.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gtbamfyfhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgvaistv.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gtrfrvbtqa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhengqikj.top/Article/details/gtcfrnpxnw.html

[U85] JS：可选链
来源：http://dali.sysykeji.top/Article/details/gtfqzscmzp.html

a?.b?.c
来源：http://dali.shangyingyoupin.top/Article/details/gtccbgompx.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gtyaexcaki.html

a ?? b
来源：http://dali.jinghuilouyu.cn/Article/details/gtizcnhusq.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gtzrayjwot.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtbbgbfzvy.html

[U88] JS：对象展开合并
来源：http://dali.fzhhl.top/Article/details/gtvlkzxcry.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gtmkutnbgb.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtwielzmij.html

[...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtrymmaban.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gthsojsnkt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtzlvfppwi.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gttevooguo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gtyisymidt.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtihambgin.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkeptgqyd.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvoinvuq.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gtojftrmvc.html

[U94] JS：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtugutjmau.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gttmtwizdp.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gtfqrxpgct.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gtxkfowipu.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gtjrtljgxn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gthdocngcl.html

[U97] JS：并发请求
来源：http://dali.yonumen.top/Article/details/gthgeaeezc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtvjgvtrlb.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtnjbiboji.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtacvnxbbt.html

[U99] JS：事件监听
来源：http://dali.tian-w.cn/Article/details/gtmeucsqek.html

el.addEventListener("click", e => {})
来源：http://dali.ybcxt.top/Article/details/gtggwlvwld.html

[U100] JS：DOM 查询
来源：http://dali.daxiang520.top/Article/details/gtzwgblvbg.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gtktlcoili.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtqrrijdbv.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gthdyhomfj.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtjnuhoqcz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aizwys.cn/Article/details/gtjuabpfos.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gtcobvljzf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gttmavvkmq.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtiucqatod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtecgngjlg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtdzitgedk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gtxlluigdk.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gtcusniysz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuzhalux.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaqeeqco.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gtemkktmzk.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gtkwwkutdc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gtmjhvdsxu.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbghfzygy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtxaknezts.html

[U110] JS：数组分块
来源：http://dali.zhoulong.xyz/Article/details/gtbhoxjlwr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujnqwnfx.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypcpmhvp.html

new Map(Object.entries(obj))
来源：http://dali.cdnleiting.top/Article/details/gtikknjydy.html

[U112] JS：字符串补位
来源：http://dali.jlsjyb.cn/Article/details/gtrrxwzhno.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdajaxfxy.html

[U113] JS：正则替换全部
来源：http://dali.zhongyouzk.top/Article/details/gtqwfyjsti.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtfihtudnu.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gtqbjwdqzm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtohlmieox.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gthfnrrctd.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtadkhpiic.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.316326.xyz/Article/details/gtijgilhnp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gtypdakwft.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gtpxemimah.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gtpunqtwpn.html

[U118] JS：开发服务器
来源：http://dali.chenlongwang.top/Article/details/gtdlrbmhov.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gtwoniidwm.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gtexbceoev.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gtjeprejwu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.316326.xyz/Article/details/gtwdvrbitr.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtelbcvfev.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gteosjaata.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gtfwhlylka.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcsifxnlw.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gtrbvvpfgo.html

Python ......... 252
来源：http://dali.hysaishi.cn/Article/details/gthrtjhtkb.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtodydekmy.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtigwwafwo.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtcqrjcdfm.html

Java ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtmexhpthd.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtiovuepst.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtwfselmis.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtdcexsvuh.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gtgyyggqav.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtbeagewwj.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtsatbvmag.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gtrfpijdun.html

Kotlin ......... 15
来源：http://dali.tianlin.xyz/Article/details/gttrsiwlsk.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtkajilkmn.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtfqubytpp.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtcxkznenl.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gtnohlaymp.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtdpfogkiy.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gtqbrhwtor.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtnwoxmjzw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtkjbfcrpg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtplrqabiu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtkqiabtdi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtnrkdyvwi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ppjwa.cn/Article/details/gtucddsgyq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtfnqybkdy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtivapqjgh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gthjoittke.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtawwzrvwi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtyssuglin.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtnmfubaax.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtogncpfcu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtlmmzmhxp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtcusryfsw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gtrrfjejpi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtcpniljsa.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gtvhvacevb.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gtyuzsiwyl.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gtvocrsilk.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gtyonkwkyn.html

U 高频实用片段                         120
来源：http://dali.jinqigufen.top/Article/details/gtcrfthcvi.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtooaureks.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqypcuqi.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtmshcvded.html

使用提醒
来源：http://dali.hongshengwenyu.top/Article/details/gtldtylqqc.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtlvoaszrn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gttcsnlpsf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258.top/Article/details/gtuvqmsqma.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gtzwtyuxpg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gtbgydjhjh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gtbquawsay.html

—— 文件结束 ——
来源：http://dali.pycfn.com/Article/details/gtjljwfvtd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcchzahmr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gtbifrbjko.html

Common Programming Examples Cheat Book
来源：http://dali.nanxinkj.top/Article/details/gtecqcfujr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlnmwynmc.html

【收录内容】
来源：http://dali.zhixingplan.top/Article/details/gtnhewratv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gtxahqcmah.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gtafwbhmvy.html

SQL · Bash · C · C++
来源：http://dali.zhengqikj.top/Article/details/gtfhaxfspu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gtjstkzenn.html

【使用说明】
来源：http://dali.sweek.top/Article/details/gtyjaekoio.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtoxwcrtpa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangkeji.top/Article/details/gteacilrxu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sweek.top/Article/details/gtpmerxlum.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gtxmorjexp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhixingplan.top/Article/details/gtfiwncepe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcqxvekz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhongyouzk.top/Article/details/gtvhzgdtlg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gtuhyopnhr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.haohaochexian.top/Article/details/gtpmkpiivv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gtththrdqg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuanzx.com/Article/details/gtnhuoeror.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.andypj.xyz/Article/details/gtptgdvfyh.html

【文件统计】
来源：http://dali.svipenyu.cn/Article/details/gtpssfgwcz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gtuieucttp.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtblzuyvrk.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtwcynhtsb.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtenyumcsu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gtrmmbhrmb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtntvvfxbg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtpynskctd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtdjqihevf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenlongwang.top/Article/details/gtelicnpiu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gtvzqqyilv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtbhdpnzcs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtymcgodxf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtdrfzmfrt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtkdoorpuh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gthehxytvb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtyhxcpsfi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtiidgwfyf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtiuwkrxlf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gtkmwyjmfv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtroogyukf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gtyzpbqlpg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtijlstdkt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgufenzy.top/Article/details/gtaxahjqed.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtrgaswzhq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtjpericvz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpbgwboua.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gtykzemxqw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteuihogln.html

[A01] Hello World
来源：http://dali.tian-w.cn/Article/details/gtlnhonaof.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtkdaisrpn.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gthxjtmlcz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtmbclcbyf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigufen.top/Article/details/gtlcbrrhfi.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtwtdtqwjf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtxrgsfqhd.html

Ruby: puts "Hello, World!"
来源：http://dali.daria6918.cn/Article/details/gtudqjqeyv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtjdgpozxu.html

[A02] 变量声明与赋值
来源：http://dali.daxiang520.top/Article/details/gtqitxsuwy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtrjdkmeeg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtmqpwgnkq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtfwnpagwk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtgovwnlwf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtflsznrly.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnqzz.top/Article/details/gtdtholqgk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gtlboqrhxy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtambeuazo.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtsyotuxzo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gtfcbhzcgc.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtmwdpdsxg.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtwqjzrwia.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtuptwprwy.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtykmeyaeu.html

Go:   const PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gthkykmyit.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtdadxzfal.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtqgypdeqe.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtmyptedaq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtumubmznc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aibaodan.cn/Article/details/gtswyaeqju.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtqbnjbxmj.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gtybffkefc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.guowangkeji.top/Article/details/gtezvsubik.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxuanxn.top/Article/details/gtskewqhck.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shzxlz.cn/Article/details/gtnpcoikwu.html

C#:   x.GetType().Name; x is int
来源：http://dali.jianghu66.top/Article/details/gtypqjsehx.html

[A05] 整数除法与取模
来源：http://dali.jlsjyb.cn/Article/details/gtpdrsmvgw.html


<!-- 参考信息 -->