代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.9152youxi.cn/Article/details/gtbfebenja.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gtxfszxtzm.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhijezhk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gtlcewefun.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtazhnqtnp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtdxuhakmw.html

[U46] PHP：可空类型
来源：http://dali.jqgufenzy.top/Article/details/gtjpzqyzox.html

?string $name = null
来源：http://dali.svipenyu.cn/Article/details/gtjbvgecbf.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglzipoop.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtggcsfzuf.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gtesinnuah.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gtbngwhiln.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gtmigqkuhv.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gttfsuguzg.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gtcswbeghe.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqclqkkdj.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gtmjfgvwbm.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gtselboqac.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtwigxkjza.html

$double = fn($x) => $x * 2;
来源：http://dali.tian-w.cn/Article/details/gtxsrydrvt.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gtsklfeapm.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtxdcvtkie.html

[U54] PHP：空安全调用
来源：http://dali.haohaochexian.top/Article/details/gtnkeqxdcs.html

$obj?->method()
来源：http://dali.haohaochexian.top/Article/details/gtavbjaycn.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtsjdsivik.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtrzlvvrhi.html

[U56] PHP：命名参数
来源：http://dali.yj202588.top/Article/details/gtqhiuyusb.html

f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtygkshbpx.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtqhgdyrlz.html

"值: {$a}"
来源：http://dali.birdmap.top/Article/details/gttkyowtrm.html

[U58] PHP：数组三件套
来源：http://dali.tian-w.cn/Article/details/gtajvrwuiv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gtchntlpws.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gtvqklkbqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtckzhrzsf.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gtpgdxfofl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gtrohpzjuo.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gtqapvjvrc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gteyuknrdc.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtvtpfikks.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gtqjqzneqs.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gtsqzadpty.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gtvulgcspa.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtxtwaxxtf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtzoknvllg.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtzuiedcjn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtpczclkut.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gtvrmxuznk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pycfn.com/Article/details/gthwmpmvtk.html

[U67] PHP：处理文件上传
来源：http://dali.zhongyouzk.top/Article/details/gthulcnjct.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtvuenugto.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtsjtvgvpu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gtspuyyqrc.html

[U69] PHP：PDO 预处理
来源：http://dali.svipenyu.cn/Article/details/gtdjuefzdp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gtqbyzpvks.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258.top/Article/details/gtnxisxnqc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gthgqtluhk.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gtugxfdyfg.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gtjpdzulup.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtscniyzeu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnqzz.top/Article/details/gtczjquvsb.html

[U73] PHP：读取 ini 配置
来源：http://dali.cashguo.top/Article/details/gtiedowffa.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gtxjohtfys.html

[U74] PHP：读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtzciiaoxv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gtuajnaiac.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gtophhlesz.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtmvcarixz.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gtusehvzfn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtbncgpezn.html

[U77] PHP：模板渲染
来源：http://dali.yanxiufei.cn/Article/details/gtbiiufnlz.html

composer require twig/twig
来源：http://dali.kuanghao11.cn/Article/details/gteccrynik.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtcccbxyqf.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gtyjmrkwzt.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtyeeypdrc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtwqbtaygs.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtppfwrnwj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtacqrtufq.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtbutuidqk.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gtgvcxxmfx.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtdygjjhrc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gthymrkhcg.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuanzx.com/Article/details/gtemobhmqz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtgrlurxya.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gtdazyxeop.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gogol.net.cn/Article/details/gtihoqfhlp.html

[U85] JS：可选链
来源：http://dali.c1oappe.top/Article/details/gtqbjdlgox.html

a?.b?.c
来源：http://dali.sysykeji.top/Article/details/gtupjkqqzk.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtyktoyngj.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtqehwsvhk.html

[U87] JS：解构默认值
来源：http://dali.yanxiufei.cn/Article/details/gtmxuupegu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tian-w.cn/Article/details/gtsxszlnzf.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtadxbsbat.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtoyimkvkv.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gtymujafmu.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtaoubcote.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gtrdfxaxip.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtbuyyrphl.html

[U91] JS：对象键值遍历
来源：http://dali.gaohongyu789.top/Article/details/gtbgvqjany.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gtosasrtef.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gtqvquegfw.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqhladgth.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gtxbxvwlic.html

`共 ${n} 条`
来源：http://dali.jiagoushi.top/Article/details/gtrwlyqgqx.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtcljzmlfz.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gttnjwvjsy.html

[U95] JS：Promise 包装
来源：http://dali.kuanghao11.cn/Article/details/gtfkwkpgnx.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtnbpucmva.html

[U96] JS：async/await 与异常
来源：http://dali.wangshuangyany.cn/Article/details/gtuiklinyz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtlazrdxdm.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gtfmxktrrt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtgwgwdrgp.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtsbztcmzb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aibaodan.cn/Article/details/gtaqzoojoz.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gtooqatjbo.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gtuhhxliln.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtuxuxbtdo.html

document.querySelector(".item")
来源：http://dali.andypj.xyz/Article/details/gtrpaiqejc.html

[U101] JS：classList 操作
来源：http://dali.aibaodan.cn/Article/details/gtsoksnpdo.html

el.classList.toggle("active")
来源：http://dali.havefunace.top/Article/details/gtpiakshba.html

[U102] JS：本地存储
来源：http://dali.dianchejie.cn/Article/details/gtysxnbbvj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gtqfqzptwn.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtscwwyarh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtjudatqen.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtudiejbqi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtsvwcdxkj.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtfnqnrnpj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gtvtxzbwvh.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtkiqogqze.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtbhaidgsf.html

[U107] JS：数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtkbmcljhi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtzexxnqkc.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gtuffjtdbj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cucudq.cn/Article/details/gtqtcvllry.html

[U109] JS：数组分组
来源：http://dali.xuetiantiany.cn/Article/details/gtwypwemhb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaflmeqvv.html

[U110] JS：数组分块
来源：http://dali.fzhhl.top/Article/details/gtdurdeden.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtfbilkuhp.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gtlalrvqjc.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtaidyimrx.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gtnoamsppx.html

"7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtsoslqfwx.html

[U113] JS：正则替换全部
来源：http://dali.jianghu66.top/Article/details/gtnpyaymre.html

s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtglprukez.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gtzfvymqkw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtsbfsyhbx.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtfihegbqr.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtxrhyohae.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gtletrtqnk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gtbzqjntqt.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtceslxjpo.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gtlsowvfhm.html

[U118] JS：开发服务器
来源：http://dali.jyoumei.cn/Article/details/gtytkirdny.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gtnpjcpqme.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcuqxpin.html

npx vite build
来源：http://dali.xuanzx.com/Article/details/gtsumplizk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gttzpsbhxn.html

import.meta.env.VITE_API_URL
来源：http://dali.hnxiangtu.top/Article/details/gtpckbuxps.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvwwdyepc.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gtcldyxkfo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvkqyvuci.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gtqhmxzgrr.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gtemgkiefu.html

PHP ............ 252
来源：http://dali.meibo888.top/Article/details/gtkgigzuke.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzonntlx.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtcbkafzpd.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtvyrrgasx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtxatqnxoi.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtlipvaqyi.html

C# ............. 212
来源：http://dali.gzhubu.top/Article/details/gtxhqsyxnr.html

C .............. 30
来源：http://dali.xziqi.cn/Article/details/gtpggrmwop.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gtufgwjlmj.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtgrbyeimr.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gtpllptfal.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtpjnszulv.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtlytiwbmk.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gtjomsjzqp.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtcnpdfzbi.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gtkdbkpdkg.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtllbmkoyo.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gtfitzqpxl.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtqirgphgd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtnpnodakk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtiywdjbpn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtqmrqmymv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtfuxffzir.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gtlgbsaylf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtcjhacuvf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtpschjoao.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtuvnrtypx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtrnzllhnu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtjpaecmya.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtxtpfzwqe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtkeoqeoqk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtfyhnctkk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtntxsgqpg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtxjuoxqvc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtcbjbjhse.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gtmyryqkyk.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gtmccnorsn.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gtdcogusmw.html

T 其他语言补充                          60
来源：http://dali.shuidangran.top/Article/details/gtssrpskqf.html

U 高频实用片段                         120
来源：http://dali.gzhubu.top/Article/details/gtxyejyvuz.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtmdhqadns.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gtxtmmitgf.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtdrhvtnmb.html

使用提醒
来源：http://dali.sweek.top/Article/details/gtssysfene.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtcfioyacj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtckxpmgkq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtrrasolmh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.havefunace.top/Article/details/gtpemkmdck.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yangfankeji.com/Article/details/gtscqjyanq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gthwpqjjla.html

—— 文件结束 ——
来源：http://dali.jinghuilouyu.cn/Article/details/gtztqbrobd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrbqvtivo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gtadotqrft.html

Common Programming Examples Cheat Book
来源：http://dali.sxryk.cn/Article/details/gteqwdravm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthbpidjbe.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gtqywkiiuk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.feifeiyinyue.top/Article/details/gtanowxwik.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gtgobewouj.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gtcxmziyli.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gtqkwvuatm.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gtuhzxgxsm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jianghu66.top/Article/details/gtpiglxicn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuanzhike.top/Article/details/gtiewlkpkf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gtorkuioiw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gtqoyyqhzc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guannengcc.top/Article/details/gtuuqptenj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cheryme.top/Article/details/gtkezwpxkd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gtbtuzgbzf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtfkzoiwdp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtllgqqkid.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.fzhhl.top/Article/details/gtllkbwysm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sweek.top/Article/details/gteadupnaz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtyqkghjlc.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gtatqzuocj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.bjfxy.top/Article/details/gttntlfmsk.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtopfjxnmy.html

目  录
来源：http://dali.daxiang520.top/Article/details/gtmhwtsirh.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtimyhnuhj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtvfmjvdol.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtrbmjofir.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtjgxuquxh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gterxxbjfx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aibaodan.cn/Article/details/gtqkbnhthk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtdxwcuswb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtpcgiauqj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gteicuwljy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtjhsijmuu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtiqizutql.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtshstdauh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtidspkpae.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtrdhfviff.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtttztccsn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtriyqycoe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtsrmqtomw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.haohaochexian.top/Article/details/gtbosdysia.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtopyfyacr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sweek.top/Article/details/gttdrsxgxk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtetqlaezm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtmkqupjnj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwlmzsbqr.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gtwlbvtzyx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcpdretfj.html

[A01] Hello World
来源：http://dali.haohaochexian.top/Article/details/gtewymtnzn.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtkgebashe.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gtfpagnbet.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtkhqzvl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.meibo888.top/Article/details/gtcqivejhq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtmmldzcxs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtzpzogktf.html

Ruby: puts "Hello, World!"
来源：http://dali.gotoacloud.top/Article/details/gttjaiziuv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtaywnyyoi.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gtausehgtw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtrjvmsxik.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtlcssuyrq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtpbiiixnl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gtsuewpvzu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiywqkfsn.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gtskxoaxml.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gtbdzpdqss.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gtsmccovao.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtemuudjbn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.0kj1m.cn/Article/details/gtnsiuxydi.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsadkqwcr.html

JS:   const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtxzunzpyw.html

TS:   const PI: number = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtwsdovokm.html

Java: static final double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnngryiib.html

Go:   const PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtltgawuhj.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gtadczcgul.html

C#:   const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtaqeimazo.html

[A04] 判断变量类型
来源：http://dali.havefunace.top/Article/details/gtvrtqclul.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigufen.top/Article/details/gtljcgraai.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aizwys.cn/Article/details/gtllqexjkc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gtnmchctef.html

TS:   typeof x; x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gtzcvjeyri.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtvnvchygd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gtyhlbgoff.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gtcsxfpbej.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangtech.top/Article/details/gtguhaulws.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gtsyitmasp.html


<!-- 参考信息 -->