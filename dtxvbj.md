代发 wailian999

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gtpencmeac.html

public readonly string $name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndsremob.html

[U50] PHP：构造器属性提升
来源：http://dali.guannengcc.top/Article/details/gtehtozvyp.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtfabskqpd.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gtqtjhaynu.html

[$a, $b] = $arr;
来源：http://dali.yueranfly.top/Article/details/gtmscurbai.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpwnbrqp.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gtzjvluksw.html

[U53] PHP：空合并运算符
来源：http://dali.ehwqpu.com/Article/details/gtsqegejze.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gtudnvjjbb.html

[U54] PHP：空安全调用
来源：http://dali.hongshengwenyu.top/Article/details/gtevhzpfbh.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtdvfivjkr.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtgetzjxkr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sweek.top/Article/details/gtdookeooc.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gtohdewbrj.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtkdbkxuca.html

[U57] PHP：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtjiqdzfbj.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtkjrzhzbx.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gtlvhztzqk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhixingplan.top/Article/details/gtpyayfufs.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gtzocwfisu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtpalbytoy.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gtwomfunga.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gtajyvtmgz.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtsvhrlvfs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gttqiwsmus.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gtuifqujqn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sufxvd.cn/Article/details/gtiaevqhox.html

[U63] PHP：文件读写
来源：http://dali.snrcjt.cn/Article/details/gtcfvvxrio.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttonxxjwm.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gtodgqbwul.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gtoxlnnluv.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtblrywhcv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtxaujjhxz.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtlbdvyvpo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.redwolf501.top/Article/details/gtqgibqodo.html

[U67] PHP：处理文件上传
来源：http://dali.yongpay.top/Article/details/gtqcvkiypp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhongyouzk.top/Article/details/gtshrtuxfy.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtniwkytih.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fengsongda.top/Article/details/gtfhoyqldg.html

[U69] PHP：PDO 预处理
来源：http://dali.bjfxy.top/Article/details/gtrnpfusxn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gtjjqiymtd.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtgnzcmoam.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkonnliiy.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtmwirqkjh.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gtjztjlhoy.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtzrpusodl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtrgoerdti.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtlsjsicgo.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gtnvnhmsod.html

[U74] PHP：读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtiyddjmwb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtskybjote.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gtcucczkvg.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtvjzzuouy.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gtfbqsgane.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtuchqozdz.html

[U77] PHP：模板渲染
来源：http://dali.fengsongda.top/Article/details/gtcmnuqnpe.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gtrfbjcheg.html

[U78] PHP：单元测试
来源：http://dali.bjfxy.top/Article/details/gtvxnzqtns.html

composer require --dev phpunit/phpunit
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcejbrbw.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gtbuyetnsj.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgufenzy.top/Article/details/gtdurhbnxn.html

[U80] PHP：代码规范修复
来源：http://dali.bjfxy.top/Article/details/gtaprogutx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gtbygicgor.html

[U81] JS：初始化项目
来源：http://dali.shzxlz.cn/Article/details/gtgxrbznuh.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtgogqdifg.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gttvwpgdpz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.316326.xyz/Article/details/gtldgannxl.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gttfleaeui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtucvxwbfl.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtbpqrwycb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gtovcvlvyr.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gtjdkwrcrp.html

a?.b?.c
来源：http://dali.sysykeji.top/Article/details/gtxdrcdhpp.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtduooplhx.html

a ?? b
来源：http://dali.ehwqpu.com/Article/details/gtgqowgbwc.html

[U87] JS：解构默认值
来源：http://dali.pycfn.com/Article/details/gtnhfxtjns.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtvqqlsuls.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtwlsttsfp.html

{ ...a, ...b }
来源：http://dali.tianlin.xyz/Article/details/gtaoemwuny.html

[U89] JS：数组去重
来源：http://dali.9152youxi.cn/Article/details/gtbfkcdyck.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtdscbadvb.html

[U90] JS：数字数组排序
来源：http://dali.pengpengdd.cyou/Article/details/gtdctcpmku.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtncigwrvf.html

[U91] JS：对象键值遍历
来源：http://dali.zhoulong.xyz/Article/details/gtfzhazckn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtykqnhnqr.html

[U92] JS：深拷贝
来源：http://dali.chenlongwang.top/Article/details/gtxcyriuwp.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtvssfmnwa.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gtrvpagytv.html

`共 ${n} 条`
来源：http://dali.zhongyouzk.top/Article/details/gtpgueuima.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtqoiazqkj.html

const double = x => x * 2;
来源：http://dali.gotoacloud.top/Article/details/gthjhnehip.html

[U95] JS：Promise 包装
来源：http://dali.daxiang520.top/Article/details/gtjbrqxwei.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gtjumvoecn.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtbuihnjkd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtcmbvtsmu.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtdowuopzd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gttwvkvomv.html

[U98] JS：fetch 带 JSON
来源：http://dali.redwolf501.top/Article/details/gtzxtbpzsa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tian-w.cn/Article/details/gtbxxgzkgb.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gtrnuhliak.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtrtnjmojv.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gtwxulbjyb.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gtyetrgayw.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtzdadogmq.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gtoewwwecl.html

[U102] JS：本地存储
来源：http://dali.xinyue.icu/Article/details/gtnufragrg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gtdrqpfbzv.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gthaewfour.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtwmihrmlt.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gtaejjgjaj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtiaqbells.html

[U105] JS：节流
来源：http://dali.yvedp.cn/Article/details/gtjwywjhpe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtnztphtff.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gtoxgwfzxv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shangyingyoupin.top/Article/details/gtrjwaqaqi.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gtteckwnat.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gttjjxyuys.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gteawesxxz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gtnldfxcoj.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gtcxmciewi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtqjyjmcgv.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtpvbmvmcw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gthjkfmhmi.html

[U111] JS：对象转 Map
来源：http://dali.sysykeji.top/Article/details/gtdumjlfsf.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtevgobrzy.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtzepcfbbq.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtsbdzqsfu.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gtfsexsymr.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtlookmtxc.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtkkrnnkbw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtkayjmqes.html

[U115] JS：生成 UUID
来源：http://dali.iojbl.cn/Article/details/gttrbqvfik.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtcgbdjsho.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ybcxt.top/Article/details/gtxtftbpep.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtfxphyqte.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtbgtgouvi.html

npm i -D vitest;  npx vitest
来源：http://dali.chenjidiqi.icu/Article/details/gtdbcxxsbe.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gtyvexuddq.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gtysdudrfm.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gtjygxgsqt.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gtnjhklswo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtgvkaahgi.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gthbzrgjog.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjwvwdhlw.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gtqokmtqvn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlwcmoqcf.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtnofteypm.html

Python ......... 252
来源：http://dali.nwbrower.top/Article/details/gtckdsbmpo.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gtaepeqaxh.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gtlorjpzyi.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gtbgmauhml.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gtlfqhsfep.html

Go ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtvzpbkehw.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtyuyxmtrg.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtkgoqhujh.html

C .............. 30
来源：http://dali.jyoumei.cn/Article/details/gtuxlvqtme.html

C++ ............ 30
来源：http://dali.meibo888.top/Article/details/gtrlwihegg.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gtsovlsueb.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gtkprlenxc.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtwokeyrvx.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gtswnfobeh.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gtdivqhtfb.html

Perl ........... 10
来源：http://dali.ehwqpu.com/Article/details/gtdydoomds.html

Scala .......... 10
来源：http://dali.mhx1999.top/Article/details/gtelbwsmok.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtreulcgol.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtyvbzxjbi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gthxugbivj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtsglinmqp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeibhdkr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtlwisovlm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtruvfikxm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtyolltmcs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtvsfhwgym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtfpdwvvtz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gtaoamavok.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtbcsqdiyw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtavogskfj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtsopqhgwo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtcvzljeqh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtpvfmhxuh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtzoepxhpr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gteqmkvzvy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gthlzjlsab.html

Q SQL 专题                              90
来源：http://dali.fzhhl.top/Article/details/gtfqecctma.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtdqdfuwpo.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gtxkefdmmd.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgcdoilw.html

U 高频实用片段                         120
来源：http://dali.pycfn.com/Article/details/gtxmjlqltp.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtotheasva.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gtcndwkqnc.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtevjbqozh.html

使用提醒
来源：http://dali.hnqzz.top/Article/details/gtwnwmwmko.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtyvzriyuw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.redwolf501.top/Article/details/gtvhntixqh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtqgiugfwi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenlongwang.top/Article/details/gtllgbboiu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gthwhtexqr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gtsklhuijx.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gtaiqjalle.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxpwwbfjl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gtvsatbkyp.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gtyfqrowxk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfigkeftv.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gtjoewdimf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gtjddmwnti.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtixxhjfhg.html

SQL · Bash · C · C++
来源：http://dali.shzxlz.cn/Article/details/gtemrswmjt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj202588.top/Article/details/gtvajxdxoo.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtnctzxvct.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.c1oappe.top/Article/details/gtgmupucxw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtujfmlvkx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhengqikj.top/Article/details/gtvfikbndi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guannengcc.top/Article/details/gtpcvpsezo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gtelnrpiav.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gtqaqsqudm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gtorwtgioj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenlongwang.top/Article/details/gtbkizlpnk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gtrvccnuut.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sxryk.cn/Article/details/gtppqpplvm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fzhhl.top/Article/details/gtracskrom.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gtuhhbakki.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gtksbopayf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.haohaochexian.top/Article/details/gtuneevzjp.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtijbppmou.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gtkmvtjixc.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtsdmcwypn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gthkejnhrj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hammf.cn/Article/details/gtabrpzhil.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtebtemwhr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtzororcuf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gttodbzyto.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gttuilzfnj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtwnqotgsg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtnaptcgsl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtnnxjhygz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gthgriyxuf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtnbksqozg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtaavtamgn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gthzhswcpg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtpiyalanm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ydzc1.top/Article/details/gtdnbcyxdm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gttasinjdg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.iojbl.cn/Article/details/gtvwigwytv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtanjxzfdg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtllskabyt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtpyyavdzm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtrgbozhfm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfpzcovqn.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gtgmonkufv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvmgqzoqd.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gtfcamgomi.html

Py:   print("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtdyelwzly.html

PHP:  echo "Hello, World!";
来源：http://dali.kuanghao11.cn/Article/details/gtiaqssryu.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gttkktajvg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gtnlxcedjt.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtpthebxzj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dashuyun.cn/Article/details/gtirmshwda.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gtgjulfxau.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtsuhpkqhu.html

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gtltrtring.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hysaishi.cn/Article/details/gtfkmzvrda.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gtcotxojhs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.316326.xyz/Article/details/gthddvrdth.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gtoboqnvbt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtalxdseto.html

Go:   name := "Alex"; age := 20
来源：http://dali.c1oappe.top/Article/details/gtjrztbfqa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gtnydpqlrz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmexalgze.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gtpxbxjzce.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gtsjupaftm.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtvrrzstyo.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtophcelng.html

TS:   const PI: number = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtjewhfdex.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtjmiwdyvp.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtxianuhzt.html

Ruby: PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtqcyjmfhk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtskzdytmg.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtkhpnmtit.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shangyingyoupin.top/Article/details/gtcdrczxkk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yongpay.top/Article/details/gtqmylepng.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtbscbgeww.html

TS:   typeof x; x instanceof Date
来源：http://dali.mhx1999.top/Article/details/gtxsjtqdms.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtlodofwkx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gttbiwiqol.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhengqikj.top/Article/details/gtcrlntond.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gtbvewntrj.html

[A05] 整数除法与取模
来源：http://dali.aibaodan.cn/Article/details/gtjwjbdsjp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yuanzhike.top/Article/details/gtgohhrgjq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtuehkarqd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtykfiswsc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiszeuhdg.html

Java: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtbrofmghi.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtgdycreya.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtssnybrya.html

C#:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtoiqoyhcz.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtenlxbzrq.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtdfxzglbv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cqqwz.cn/Article/details/gtmitkruis.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gtmnzcuvns.html


<!-- 参考信息 -->