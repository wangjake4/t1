代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.hongshengwenyu.top/Article/details/gthbkeaify.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtlgenblkh.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gtdbtanwsd.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gthdkaykxa.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtrkngwmjh.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gtlwuyhhxm.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgcxvzpq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuwjulpaf.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gtlnypuhvr.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gtkquafkvt.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtwpzstvqm.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gtzexzaoil.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtieoyzbhl.html

[$a, $b] = $arr;
来源：http://dali.jiagoushi.top/Article/details/gtsnqjnhir.html

[U52] PHP：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gtjszlidof.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmqaqzxf.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gtnpekjvuo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gtaplnzxxx.html

[U54] PHP：空安全调用
来源：http://dali.xylfe.cn/Article/details/gtrelhtnpr.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtyjuhldaz.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gtbjanoumn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtyhkxvuxi.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksrhhbcc.html

f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtsfhhqykb.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtuauzfwpb.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gtgrkxtpsw.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gtcbzmeblb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hammf.cn/Article/details/gtckkmtmvr.html

[U59] PHP：自定义排序
来源：http://dali.tian-w.cn/Article/details/gtxqamhczz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtpcmhgggr.html

[U60] PHP：JSON 编解码
来源：http://dali.fzhhl.top/Article/details/gtpcbnzcvg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gtxtmvoaiw.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gticimersl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtiholkgow.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gteuboukde.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtcwxwdpdj.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gtclvgubcf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangdashe.top/Article/details/gtmcmqtlaz.html

[U64] PHP：目录遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtkyksvqms.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gtlznawzbg.html

[U65] PHP：会话
来源：http://dali.9152youxi.cn/Article/details/gttuacrcng.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxasxsqwp.html

[U66] PHP：设置 Cookie
来源：http://dali.shzxlz.cn/Article/details/gtmilizskw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gttaavchyp.html

[U67] PHP：处理文件上传
来源：http://dali.ydzc1.top/Article/details/gtcxuprgxi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtkkmxfkwz.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtcvfimxhf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gtwpcfdruf.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258888.top/Article/details/gtykttefdu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pycfn.com/Article/details/gtepsjfdfx.html

[U70] PHP：PDO 事务
来源：http://dali.xziqi.cn/Article/details/gtsbbrruoi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pengpengdd.cyou/Article/details/gtncthicrw.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtfnycekpj.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gthqfzroua.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtsgnfqtwk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.vqdsnc.cn/Article/details/gttaaztlof.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gtybzkchhf.html

parse_ini_file("config.ini", true)
来源：http://dali.aizwys.cn/Article/details/gtgckpgrqy.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtevzhieqc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gtgcesldvu.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gtfvdkwbyo.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gtelwipfem.html

[U76] PHP：简单路由
来源：http://dali.daxiang520.top/Article/details/gtqsjzxkhh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gtgsrorwpx.html

[U77] PHP：模板渲染
来源：http://dali.chenlongwang.top/Article/details/gtupwmqtgj.html

composer require twig/twig
来源：http://dali.haohaochexian.top/Article/details/gtzcundijh.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gtieimqkur.html

composer require --dev phpunit/phpunit
来源：http://dali.snrcjt.cn/Article/details/gteqmhtekc.html

[U79] PHP：静态分析
来源：http://dali.zhoulong.xyz/Article/details/gtjwxueret.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gtxwdibeic.html

[U80] PHP：代码规范修复
来源：http://dali.ivvv.top/Article/details/gtostwqzaz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gtuebqhhpc.html

[U81] JS：初始化项目
来源：http://dali.jinqigfzy.top/Article/details/gtcqszvfoq.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gtlnrciqbn.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gtufpwalbm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pengpengdd.cyou/Article/details/gtjaduqsep.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gtityyfvfd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtytodznts.html

[U84] JS：CommonJS 写法
来源：http://dali.ivvv.top/Article/details/gtrezbqfgx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dashuyun.cn/Article/details/gttwuhiqti.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gtkqrgtsys.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gtdlcwqvpn.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gttvhursyk.html

a ?? b
来源：http://dali.kuanghao11.cn/Article/details/gtwfpynzzf.html

[U87] JS：解构默认值
来源：http://dali.sweek.top/Article/details/gtgkojiomz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sufxvd.cn/Article/details/gtbpqrnxbv.html

[U88] JS：对象展开合并
来源：http://dali.zhongyouzk.top/Article/details/gtghxkweir.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gtqfkwvdtr.html

[U89] JS：数组去重
来源：http://dali.chenlongwang.top/Article/details/gtxfyticdg.html

[...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxdjhxzo.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gtqkbwsyak.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtngkxkquf.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtkveffdad.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gtyiilbbwz.html

[U92] JS：深拷贝
来源：http://dali.yonumen.top/Article/details/gtwdynpbiy.html

structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gttilztrhk.html

[U93] JS：模板字符串
来源：http://dali.xuetiantiany.cn/Article/details/gthbtstrvt.html

`共 ${n} 条`
来源：http://dali.pengpengdd.cyou/Article/details/gtfzyreiqi.html

[U94] JS：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gttraowgvw.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfywxlkhy.html

[U95] JS：Promise 包装
来源：http://dali.9152youxi.cn/Article/details/gtvatdqdkk.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtzgjnyntr.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gtqxibnqjk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtqbbuurzk.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtanihtpmx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtdsnnphdb.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtproxibyz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yueranfly.top/Article/details/gtgzsgwjyi.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gtvzglyibt.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gtmjkhtkxf.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gtqcyppsje.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gtvbbhrlox.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtdmofoytz.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtlqgbhtwg.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gtogyuuftn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpljgfaf.html

[U103] JS：定时器
来源：http://dali.zdqjudy.top/Article/details/gtpbljqepj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gtstqjefbs.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtbylbnmwg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtdflxsbbn.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gttbovxbbp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtgiwezxrm.html

[U106] JS：日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtcfitbbwn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gtgfdjpbyv.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtgtwdpuqs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtzweuxhew.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gtejjtmesv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gtziflonyt.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtfqycnkls.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gttqvhdblr.html

[U110] JS：数组分块
来源：http://dali.yueranfly.top/Article/details/gtasjftfif.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gtbroyifey.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gthrhzpdll.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gtkmktmrea.html

[U112] JS：字符串补位
来源：http://dali.iojbl.cn/Article/details/gtxocousfy.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtfcyxhhzo.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gtcyxcpjfi.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtavfkoxfz.html

[U114] JS：JSON 深比较
来源：http://dali.aizwys.cn/Article/details/gtraodstgh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtrysbhmzw.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtcyktkaqk.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtspcjzyri.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gtwkppednu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gtphvzirzt.html

[U117] JS：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtkvtcoawo.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtuubgouxr.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtootqpcis.html

npm i -D vite;  npx vite
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfwfoeaw.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtfibznwpt.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gthkzrtbxz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgqqjctj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gtrdgdljff.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmzgjanzo.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtkkwobwih.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtggqhtxoe.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gthdwdxnoq.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gtbnbimofy.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gtxifdrcif.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtzelrhmsq.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtbpabryae.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gteakvslmb.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gttpbyecxo.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtnssfqpve.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtvpxuifyy.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtbhobaicm.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtpzogqyxs.html

SQL ............ 90
来源：http://dali.cheryme.top/Article/details/gtxgdpirax.html

Bash ........... 80
来源：http://dali.sufxvd.cn/Article/details/gtkwaoitsg.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtooiydtre.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gtqxtceggb.html

Lua ............ 10
来源：http://dali.pengpengdd.cyou/Article/details/gtgrskjdil.html

Perl ........... 10
来源：http://dali.hnqzz.top/Article/details/gthdnxyies.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gtuudqtglq.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtghmfrikx.html

合计 ........... 2106 条
来源：http://dali.andypj.xyz/Article/details/gtkqgxwafb.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtppagimav.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtsqqumubb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtfwmeynma.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtkcnndoxw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtlokgxyed.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gtfunffuor.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdkhabdi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtkrlerzlm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtjztickvh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtsdplbcdu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtvlfhsrht.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtpneingno.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtqlhmzhut.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gthehxvmky.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gtsiajulmt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyxrhorl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtkbgeybwd.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gtmtacpsjs.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gtadxyippp.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gtjscwoomd.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gtzlxixsvh.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnicfzsd.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtrnocnzvc.html

合计                                  2106 条
来源：http://dali.aizwys.cn/Article/details/gtgajiieir.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtuiaykrdf.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gtuhtdedzg.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gthlcvlvsw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtfrgpttdg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fzhhl.top/Article/details/gtawzxfmxi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gtkmhwznkx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gteiskfdxa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gtxpcedgou.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gtgjwkcwha.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtljhrfsyg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtkzezwyai.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtmqhuigwl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwyrgbpao.html

【收录内容】
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhrahubm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gtlogckrda.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqhuqdnt.html

SQL · Bash · C · C++
来源：http://dali.zdqjudy.top/Article/details/gtzaweldou.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gtkuerkpth.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gtloxnjhod.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gtxdqqbqhq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hammf.cn/Article/details/gtnldrldsp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gogol.net.cn/Article/details/gtzlrgteic.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.9152youxi.cn/Article/details/gtydysxjoy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gttooarwls.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtcgakryft.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ehwqpu.com/Article/details/gtlvlhbzte.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtvzgkqxry.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtlcwclfbs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gotoacloud.top/Article/details/gtkjwoavfc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmgcjgkb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gtfnqjhdwl.html

【文件统计】
来源：http://dali.pengpengdd.cyou/Article/details/gtbsezbtsl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkyftfqk.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gthfuxurmf.html

目  录
来源：http://dali.yj202588.top/Article/details/gtxmqklwmz.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtpohfdemv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtavktngzz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtixjdsotn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtwvxzuofq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.9152youxi.cn/Article/details/gtjuqslcvg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtplqyjdwy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtzglsjymo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtajhfcejy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtksphuvre.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtispryadj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtgxviqifg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtgrrqqtac.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtgurryqdk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtxjffczzn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtwdqtotza.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.guannengcc.top/Article/details/gtvdyrzgqs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtwmzafver.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtviiwvewc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gtaylyjepf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258.top/Article/details/gtraxtftce.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtfjzbjlnd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gttbfliiwh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqssvkztm.html

A. 基础语法与类型
来源：http://dali.smart0.xyz/Article/details/gtyimmfpcl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteqgrdlil.html

[A01] Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtveyvbp.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtxyycasjc.html

PHP:  echo "Hello, World!";
来源：http://dali.yongpay.top/Article/details/gtgjxwvpmc.html

JS:   console.log("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gtlhnrcozw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daxiang520.top/Article/details/gtlpzkmvha.html

Java: System.out.println("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtywhuhuvn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtzezpkhkp.html

Ruby: puts "Hello, World!"
来源：http://dali.ybcxt.top/Article/details/gtqrlzkzhi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtwqxikggg.html

[A02] 变量声明与赋值
来源：http://dali.snrcjt.cn/Article/details/gtcenkvsqe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gtqhzhxpxt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtpbyozird.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtpfnednhu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gtaqpaluaj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtvtdbcjvu.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gtuahonfdf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgufenzy.top/Article/details/gtqmionavc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtwfkbpcey.html

[A03] 常量定义
来源：http://dali.yuxming.cn/Article/details/gthgmfezcg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtcxrddztg.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtgfpsepfg.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtzeaxasux.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtuthanhlb.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtqybupges.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtxwtfppay.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gtnqyjljmg.html

C#:   const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gttqpwrxiy.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gtfajemllz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shzxlz.cn/Article/details/gtvbdtgarf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yongpay.top/Article/details/gthotuqhxf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtelilfyaa.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtyobnbhsh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yongpay.top/Article/details/gtdarskoai.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gtweeooqoi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gtpuywpjbl.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gtjcptvinw.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gtzcaiwexq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtzbxwubtz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtcghnzkao.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtsrjgnikm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtismdoqhg.html


<!-- 参考信息 -->