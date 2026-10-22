代发 wailian999

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtpmfnixwj.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gtrppcknfk.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtllvpmdtt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotndgeno.html

[U49] PHP：只读属性
来源：http://dali.jiagoushi.top/Article/details/gtzmkeqdua.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gtnsuhlweq.html

[U50] PHP：构造器属性提升
来源：http://dali.tianlin.xyz/Article/details/gtddwocefy.html

public function __construct(private int $id) {}
来源：http://dali.yanxiufei.cn/Article/details/gttqiegolj.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gticxsvxnp.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gtcavzgmje.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtrafixepw.html

$double = fn($x) => $x * 2;
来源：http://dali.tian-w.cn/Article/details/gtstspfxld.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtjkaawprr.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtklxtqwbp.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gtnqphdcpy.html

$obj?->method()
来源：http://dali.jqgufenzy.top/Article/details/gtqtksbluv.html

[U55] PHP：match 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtmgcxcytq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtykxmlhkk.html

[U56] PHP：命名参数
来源：http://dali.xuanzx.com/Article/details/gtueghisgt.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtfviitzow.html

[U57] PHP：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtblvbbjni.html

"值: {$a}"
来源：http://dali.yueranfly.top/Article/details/gtuqsjonnf.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtlknqstqx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gtcyhwxgaz.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtrrgqvcyo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtrjhzpyip.html

[U60] PHP：JSON 编解码
来源：http://dali.yueranfly.top/Article/details/gthqniyvxr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gtpaghpfva.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gtntbjlknf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtfcurfefe.html

[U62] PHP：日期对象
来源：http://dali.hnqzz.top/Article/details/gtqbzprrvo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gtxzwlwwdo.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gthqzbffqk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pengpengdd.cyou/Article/details/gtkwzrviao.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gtjyipajea.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pycfn.com/Article/details/gtfhumhtka.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtpodepbuj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtafhciwky.html

[U66] PHP：设置 Cookie
来源：http://dali.shangyingyoupin.top/Article/details/gtlnestbli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gtgkbyocee.html

[U67] PHP：处理文件上传
来源：http://dali.shangyingyoupin.top/Article/details/gteylgimhz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gtxwgkjfqb.html

[U68] PHP：PDO 连接
来源：http://dali.sxryk.cn/Article/details/gtsqzldlfn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gtoivuqvtq.html

[U69] PHP：PDO 预处理
来源：http://dali.c1oappe.top/Article/details/gtmhzwbfga.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gtcmbyycmu.html

[U70] PHP：PDO 事务
来源：http://dali.guowangkeji.top/Article/details/gtgctidhjt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gtykqtfemy.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtxebrvrwy.html

throw new RuntimeException("失败", 500);
来源：http://dali.ybcxt.top/Article/details/gtihfapqae.html

[U72] PHP：写错误日志
来源：http://dali.nanxinkj.top/Article/details/gthqbgwrbm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtpfejooay.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gtmymnscfc.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtewievipg.html

[U74] PHP：读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtuwibmaxa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtgcuylqld.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gtdaradekh.html

composer require psr/container
来源：http://dali.jqgfzy.top/Article/details/gtoknfznut.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gtxfqvmujz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtoyvxypak.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcglxoysq.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gttikvqpge.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtybnrjlvx.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gtfkqvyjnh.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gtujqkxldt.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gtcmazedck.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gtxbvumbtz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtyoawfdqs.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gtdihcprvi.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gtmkqmwjuc.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtslfnztvb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fzhhl.top/Article/details/gtggcpqmzy.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gttopycsox.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtxqnvalmd.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gtpzlwftfi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tian-w.cn/Article/details/gtlexkabgs.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gtjlvemeeo.html

a?.b?.c
来源：http://dali.pengpengdd.cyou/Article/details/gtjyoaopov.html

[U86] JS：空值合并
来源：http://dali.gotoacloud.top/Article/details/gtqlmhucwj.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gtpsmtaktb.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtikgumisl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gtmviaerpu.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gtmvshrlnx.html

{ ...a, ...b }
来源：http://dali.yj20258888.top/Article/details/gtylevfjrh.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gtigsbzagy.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtzjwdjbqf.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtsgqahemf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtdxxgsatw.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gtejfurkoq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtmcjryrzu.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gtpslhedxc.html

structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiguzmbd.html

[U93] JS：模板字符串
来源：http://dali.zhoulong.xyz/Article/details/gtmnrxtnuk.html

`共 ${n} 条`
来源：http://dali.bjfxy.top/Article/details/gtuqtyjlly.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtstebhkor.html

const double = x => x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtsvlgcoag.html

[U95] JS：Promise 包装
来源：http://dali.sweek.top/Article/details/gtfkwnxvtt.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtcgitejdy.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtsxkntnlq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtiqffjhsq.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqbmfjhl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtoyaosqaq.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gtdsuxdibf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtnrakzznf.html

[U99] JS：事件监听
来源：http://dali.nanxinkj.top/Article/details/gtbshqbyey.html

el.addEventListener("click", e => {})
来源：http://dali.yonumen.top/Article/details/gtqxwcaafe.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gtouwotppp.html

document.querySelector(".item")
来源：http://dali.nanxuanxn.top/Article/details/gtsivbkurg.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gtzgjvadrs.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gtfcslfwpx.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gtegnaahxk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gtdxrtaemv.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gttkikeyur.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gtredkanjf.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtcibibtzl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtbzhbpssj.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gtfeeamzme.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtzdwpjaul.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gttrfeolll.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gtjsnqzdbj.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtlmlvavqp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gtqydsvoce.html

[U108] JS：随机整数
来源：http://dali.yongpay.top/Article/details/gtmsndochk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtgmachlup.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gtxagjlexe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtguqkvadd.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gtwtfkewrz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkgrhhve.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtjzjeacsp.html

new Map(Object.entries(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtlhedmjji.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtftphbcpu.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelajxrig.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gteinwlafz.html

s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtosqzqvkn.html

[U114] JS：JSON 深比较
来源：http://dali.xuetiantiany.cn/Article/details/gtotlshvsp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtmvhybssb.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtmfffvgvc.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtankkmrie.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxuanxn.top/Article/details/gteqaxgiam.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gthlattjjb.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuceiwgfe.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gthminosgn.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtajwcebiu.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtoquoukjw.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gtmuhbqxgc.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gtlqfjdtor.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtzqodhlvt.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gtyowkhkkx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtywbdsbna.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gtpmpddvdu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrjwiqoqm.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gtnhuyehxm.html

Python ......... 252
来源：http://dali.daria6918.cn/Article/details/gtofoquntt.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtrajpdhij.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gthpsnsxov.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gtayvvyrpq.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtknkoxdmy.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjskzhfj.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtibzrwepg.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtxralaubw.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gtlejpqrmk.html

C++ ............ 30
来源：http://dali.ivvv.top/Article/details/gtoarpekgd.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gtojqtzgnu.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gtnmrvezfa.html

Kotlin ......... 15
来源：http://dali.havefunace.top/Article/details/gteboxhsrx.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gthsjiwuxw.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gtlglpqhnm.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtsbyaolyv.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtemaseqns.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtdgenebfe.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtxuywtkbg.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gtpauxlywt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtsftyotmh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtatwnxiyk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtvrbsixxg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gthayialao.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtnqjpxobm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtlpmsznwt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gthzpfngfb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtidwruhah.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtbrpbibga.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtimwtgrro.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpvolbzk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfopuedk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtplxxdlmy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtugjqbwix.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gtvivwexqj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gttsysjjiq.html

Q SQL 专题                              90
来源：http://dali.nwbrower.top/Article/details/gtkgvxodvf.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gtelyvctaq.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gtrvhnawvl.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gtgibdedoe.html

U 高频实用片段                         120
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmsdfifr.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtwueekamp.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gthbbunbsk.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtmqnjcnkv.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gtlzgdmsak.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtgxijwcoo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sweek.top/Article/details/gtydiwkypx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gtniwzlqxv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.316326.xyz/Article/details/gtqwhyhjbh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shangyingyoupin.top/Article/details/gtkozbgaoi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.vqdsnc.cn/Article/details/gtvfngviuw.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtusxgytse.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtfommqqsv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xziqi.cn/Article/details/gtdmngvglw.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gtpltlmyhe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyfdcvjyz.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gtlcasnsex.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.haohaochexian.top/Article/details/gtrmriwjqw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtopgnmgyc.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gthvlcbpkz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhoulong.xyz/Article/details/gtwkebmqqt.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gtmytsolta.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pengpengdd.cyou/Article/details/gtdnnwhapc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daria6918.cn/Article/details/gtoicgvujo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhixingplan.top/Article/details/gtkjcebmyc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gtosxqqqbw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhiwuduotai.top/Article/details/gthrqqbzyq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxuanxn.top/Article/details/gteexqxkyc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtdrpyzpsj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gtplrnxofb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtwzpxdjiq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gtgrgmbdcx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gtmtsrylpt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangtech.top/Article/details/gturctwpjw.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gthugzgszs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnxiangtu.top/Article/details/gtcuswveix.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtxqxtsykr.html

目  录
来源：http://dali.yj20258888.top/Article/details/gtapjpehye.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtkojasrsz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtlucrudnr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgszfnpk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtjobmelhx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtxutshklb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ydzc1.top/Article/details/gtluwyedtz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxireokx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtijpmcplu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqpkjtvn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtznbtzyxc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtvcxbwopu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtukfilbnn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtrbedwohy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtctkbgcft.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtwnvttanu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yuxming.cn/Article/details/gtkebwgemx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtveywbthi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.quarkkingdee.top/Article/details/gtqbiclkeh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cqqwz.cn/Article/details/gtxerslvgd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gtgcfgvfot.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtrcftznhi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gthagcslec.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkeijvmda.html

A. 基础语法与类型
来源：http://dali.ehwqpu.com/Article/details/gtksquamfs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvsbkvzbt.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gtruaoerfd.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtjkkgkgfd.html

PHP:  echo "Hello, World!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxngxkepv.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gthpidxmww.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gotoacloud.top/Article/details/gtkjcfaygv.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtvsjpgloq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gtqkybnsmy.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gtmqenupql.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtfiwjnufi.html

[A02] 变量声明与赋值
来源：http://dali.yanxiufei.cn/Article/details/gtxccieuhv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gtghtetewd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtqzkfnvai.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daria6918.cn/Article/details/gtikwjetqx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtdzrwqvnz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtlcyogglm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gtftfbjnpk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.birdmap.top/Article/details/gtxovxctnu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfnizaha.html

[A03] 常量定义
来源：http://dali.smart0.xyz/Article/details/gtssymkzgi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hongshengwenyu.top/Article/details/gtxrhaatpl.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtonhtoiil.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbacdtfub.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtmgiexkmb.html

Java: static final double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtmovrnbsz.html

Go:   const PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gtlmioljwt.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtcbgcmjnq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtyahmyurp.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgducatsk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gttabvtghq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.c1oappe.top/Article/details/gtyremsgzl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gtpuspoalq.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gtpeyhuocl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtaguzmtza.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gtkhxptcti.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtlrqydxao.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gtbortsftf.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gthcjyywir.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gttezmnrcw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtlapfpxwr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtgiignntr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gttbtheent.html

Java: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gthdebgefk.html

Go:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtxbltzais.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtvbtuftvo.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtynbyszsx.html


<!-- 参考信息 -->