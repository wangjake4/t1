代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gtclawmkaw.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gtbaywjkht.html

[U44] PHP：开启严格类型
来源：http://dali.hammf.cn/Article/details/gtrcjypeun.html

declare(strict_types=1);
来源：http://dali.xziqi.cn/Article/details/gtlinyavvk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sxryk.cn/Article/details/gttbrpxchq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gthtirywic.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gtxwytuzro.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gthzmfqyyx.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gtrgasmvsc.html

int|string $id
来源：http://dali.sweek.top/Article/details/gtookasekb.html

[U48] PHP：纯枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtmfemwjek.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gtlfovhjac.html

[U49] PHP：只读属性
来源：http://dali.nanxinkj.top/Article/details/gtkmhjgjkg.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gtuuvtbrcc.html

[U50] PHP：构造器属性提升
来源：http://dali.tianlin.xyz/Article/details/gtttqjiwzr.html

public function __construct(private int $id) {}
来源：http://dali.pycfn.com/Article/details/gtjjiezzoh.html

[U51] PHP：数组解构
来源：http://dali.fengsongda.top/Article/details/gtdvihezjs.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gtoagfbtqf.html

[U52] PHP：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtagbdygal.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258.top/Article/details/gtqopcmwbg.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtictdoazk.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtanqldjrm.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtcydaruhm.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gtkozwdwfy.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidvpitrl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gturwntgio.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtpciuplyg.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtwqzgbhgs.html

[U57] PHP：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtdebdivrq.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gtjurkzayu.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gtgsaillxy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtxahitjnr.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gtdfqzqlge.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtqbzqmqgr.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtyvdnkdsb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtyanbanll.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gtzrikrwfq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrfrqhrct.html

[U62] PHP：日期对象
来源：http://dali.gaohongyu789.top/Article/details/gtdrcjxpxb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gtfcerqotx.html

[U63] PHP：文件读写
来源：http://dali.jianghu66.top/Article/details/gtzmjmhurw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gtbtakentu.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtcmmckazz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtrbgahynk.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gtyriazjbk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gttdotksuj.html

[U66] PHP：设置 Cookie
来源：http://dali.hnqzz.top/Article/details/gtistwagpy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.bjfxy.top/Article/details/gtqhqtsnha.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gtwsqdthnh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gthfwclhuc.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtwcnrqely.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yangfankeji.com/Article/details/gthjxmnnfe.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gtdhtcwmeq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sysykeji.top/Article/details/gtjklegusj.html

[U70] PHP：PDO 事务
来源：http://dali.hnxiangtu.top/Article/details/gttgwpwzvi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gteyeybsql.html

[U71] PHP：抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtsosvbakp.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiwohwfb.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gtjtfjnsqp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyavthaeq.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtbopmtiow.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gtsmgjpvev.html

[U74] PHP：读取环境变量
来源：http://dali.shuidangran.top/Article/details/gteyrevlci.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuanzhike.top/Article/details/gtdqogsoms.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gtrtcwklor.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtriznhyvl.html

[U76] PHP：简单路由
来源：http://dali.jinqigfzy.top/Article/details/gtptblpske.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gtlyjigzfr.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtwsjumyfp.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gtjktowqfl.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtlejfzxts.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtxxhbdkhr.html

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gthwcxzoii.html

composer require --dev phpstan/phpstan
来源：http://dali.tanke756.top/Article/details/gtnmqiydjj.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtixxwmhrq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtjselqefg.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtsotonoch.html

npm init -y;  npm i express
来源：http://dali.iojbl.cn/Article/details/gtsxhsqkge.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbhjnfas.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtvfanytyb.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxuanxn.top/Article/details/gtfiyqirdd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtddhhfcsw.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtqvicwokt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ydzc1.top/Article/details/gtzwbbzuyv.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gtpzgssroj.html

a?.b?.c
来源：http://dali.cheryme.top/Article/details/gtsfrblsgt.html

[U86] JS：空值合并
来源：http://dali.yongpay.top/Article/details/gtdkbridiu.html

a ?? b
来源：http://dali.jyoumei.cn/Article/details/gtcsolgjur.html

[U87] JS：解构默认值
来源：http://dali.hfpthk.cn/Article/details/gtrzwdjvml.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtcbjbpbik.html

[U88] JS：对象展开合并
来源：http://dali.shuidangran.top/Article/details/gtvgmwjiqf.html

{ ...a, ...b }
来源：http://dali.zycfv.cn/Article/details/gtxzaxlukh.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtfgxgcioa.html

[...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtvpvipjet.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gtznzapzje.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtngnddrop.html

[U91] JS：对象键值遍历
来源：http://dali.chenlongwang.top/Article/details/gthjeywlfo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tanke756.top/Article/details/gtwxngspet.html

[U92] JS：深拷贝
来源：http://dali.shuidangran.top/Article/details/gtbxrrxcsv.html

structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtumtpeapr.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtewkqayld.html

`共 ${n} 条`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigbmrqbb.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtwvalokve.html

const double = x => x * 2;
来源：http://dali.zhixingplan.top/Article/details/gtwlefvrmq.html

[U95] JS：Promise 包装
来源：http://dali.chenjidiqi.icu/Article/details/gtacitxxlr.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gtmowzwpzn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gtriohnohz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeyzdlqn.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gtcxqwskhj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtplfwlqix.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtowzbyklu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gtkiytmdny.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gtuvuhnegw.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtgqkkckpc.html

[U100] JS：DOM 查询
来源：http://dali.ppjwa.cn/Article/details/gtkvbkaiqt.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtafoxqolu.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gtlzrnfzpg.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtfqzvimqq.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gtwtvhjnsq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gtvvckizyn.html

[U103] JS：定时器
来源：http://dali.guannengcc.top/Article/details/gtyspejrgo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtewmeaznl.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gtafctwsdp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtxwamaeho.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gtacppohxw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnqzz.top/Article/details/gteszndqmu.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gtybrbkooj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gtbeztwsge.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gtuzushvhu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtqbpujisf.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtuttlvlvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtmskbcdrs.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gtdgonrfjs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhoqpkgw.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gtkumexlrm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daxiang520.top/Article/details/gtsecjyzng.html

[U111] JS：对象转 Map
来源：http://dali.jqgufenzy.top/Article/details/gtyujnisjr.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtzctwmhth.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gtfaewtjxl.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtjgtlgciz.html

[U113] JS：正则替换全部
来源：http://dali.sweek.top/Article/details/gtqmetpidu.html

s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtfghiboda.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gtaaquabix.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gthclyjgdl.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtxknhksxh.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtthhagcca.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gteardmsac.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gttayxnohr.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtybmzvyme.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gtpzldgqpq.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtsvmxeikr.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gtzxrycnhu.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gtarhyvcoy.html

npx vite build
来源：http://dali.fzhhl.top/Article/details/gttujntqqw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhixingplan.top/Article/details/gtpiyqowgr.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gtwbsqngix.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskspgsxb.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gtntqowfiz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsdepafns.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtgyurnhwr.html

Python ......... 252
来源：http://dali.yj20258.top/Article/details/gtekysfvci.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gtzrnqulmz.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmretkveq.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtljyqulmq.html

Java ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtavsfkwnu.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtllnsocuy.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gtujvmnmad.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtzpoolrlp.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtmwtzfsiu.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gtupnulvmr.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtxjnlsuyr.html

Bash ........... 80
来源：http://dali.mhx1999.top/Article/details/gtvsbuulyi.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gtvekccrlc.html

Swift .......... 15
来源：http://dali.kuanghao11.cn/Article/details/gtgefrnotp.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegjoztgf.html

Perl ........... 10
来源：http://dali.cashguo.top/Article/details/gtyngdunfq.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtdpmihtte.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtsvuqolfh.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtkcynregr.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gtxzeeefua.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gtoaoqowis.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtupcsnotv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhzoeddd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtewzwrcem.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gtgchluolu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gtjhljozuu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtbtydvsvh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.vqdsnc.cn/Article/details/gtqrnwiadp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtdnuvmshm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtgklrjduk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtwhxuwwmw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtsbphuqww.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtbmisxhqp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxinkj.top/Article/details/gtlnpjldjr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtgjbiggpz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtzpragotn.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gtajpneaoh.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gttjoadppu.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtlpfsvpfl.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gthqrwtrwn.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtfzdvqyix.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtohqjix.html

合计                                  2106 条
来源：http://dali.hywenlv.cn/Article/details/gtugvurtbw.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtdyklmffy.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gthqaoiesf.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtmxsiryik.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtelhkvtzk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ydzc1.top/Article/details/gttiibpyyc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnqzz.top/Article/details/gtaobrxabu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yonumen.top/Article/details/gtlthxjmyj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucabambq.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gtzrpuefuf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlvutrcoo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.meibo888.top/Article/details/gtmqzkubed.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gtpdpsqbfh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjyelxwqf.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gtedpauikz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gtahhucpak.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtevpwdwdg.html

SQL · Bash · C · C++
来源：http://dali.haohaochexian.top/Article/details/gtssrgrmqu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gtgjxbasgv.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtfufwodng.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hysaishi.cn/Article/details/gtwokjcuov.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gtnvvfvjlm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aibaodan.cn/Article/details/gtoqfvpmrq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.wangdashe.top/Article/details/gtsjtbouoh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxinkj.top/Article/details/gttazcohmt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pycfn.com/Article/details/gthqkytmaw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gtnjruyybp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gtrdzvrroe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuanzhike.top/Article/details/gtrtxnlxtd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gtlbmzqjqr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gtgfympwjw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gthjfvvbud.html

【文件统计】
来源：http://dali.smart0.xyz/Article/details/gtcafggbpv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cheryme.top/Article/details/gtvlqzautb.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtzeohcsog.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gtmtebwqsi.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtztegicko.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ivvv.top/Article/details/gtinqeyieq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtfnmqlgtv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtuceadzwk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtlojiklbj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gtkokoorbe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtqbwnjmjp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtmtkpbmpp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtslvfswlh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtwqttgzkw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gttshznfia.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtegkwixcs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtcamwjcmr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtnnojrcnh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtrfeuzcqn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gtwohxhjud.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtyjurtjoo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gtnhivcgcf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtcntfaqgz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gtsxlyvdma.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtvqszardl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsbsolvc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjalhqvrj.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqptnivqb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtemvklbje.html

[A01] Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtgbakybpd.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtnkyvwrhl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhengqikj.top/Article/details/gtksoljrql.html

JS:   console.log("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtupyzeblz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daria6918.cn/Article/details/gtfakviaht.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtifckxuww.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gtmdrxcrly.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gtblxkiihd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtifqcmwoz.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtydzlfeoj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.redwolf501.top/Article/details/gtymcopqqg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ydzc1.top/Article/details/gtwvgzjtxx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtstdzwaei.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gtafkshinp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtdvpyihoj.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtllcsgmsn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yongpay.top/Article/details/gtkkxrexde.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtqwanlgcd.html

[A03] 常量定义
来源：http://dali.chenjidiqi.icu/Article/details/gtyoyoktzi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yueranfly.top/Article/details/gtoeplzwgh.html

PHP:  const PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtlidlexky.html

JS:   const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtwgzcvozi.html

TS:   const PI: number = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtdmkkdzno.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtgcctkufu.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtsqyhomgy.html

Ruby: PI = 3.14159
来源：http://dali.sufxvd.cn/Article/details/gtzplaqjdi.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtncwgcldm.html

[A04] 判断变量类型
来源：http://dali.jinqigufen.top/Article/details/gtvcojjzmi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtqtjmbpmd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.birdmap.top/Article/details/gtfvallxgg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gtistavcsy.html

TS:   typeof x; x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtjqyxkxiq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gtcxvoqbwg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gtuqupxjmu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gtbxytcgwp.html

C#:   x.GetType().Name; x is int
来源：http://dali.yvedp.cn/Article/details/gtivezkwfr.html

[A05] 整数除法与取模
来源：http://dali.hfpthk.cn/Article/details/gthaylbunw.html


<!-- 参考信息 -->