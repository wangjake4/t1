代发 wailian999

[U49] PHP：只读属性
来源：http://dali.yj20258888.top/Article/details/gt2wlrfehaw.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gt2ebiwurai.html

[U50] PHP：构造器属性提升
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhtdhfab.html

public function __construct(private int $id) {}
来源：http://dali.birdmap.top/Article/details/gt2cnlehalc.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gt2eywrlbng.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gt2wlgtbwbp.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anbjeuya.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gt2hbilzolw.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkoaogpz.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gt2mkbzieuu.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gt2mowxreyh.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gt2ignnjyqq.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gt2viowwzeu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gt2umdoadti.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2jjwpjxor.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2zyodhvpb.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2zzidrdby.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gt2acacvidv.html

[U58] PHP：数组三件套
来源：http://dali.gotoacloud.top/Article/details/gt2jxjtgrtp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2zatxcfnp.html

[U59] PHP：自定义排序
来源：http://dali.yj20258888.top/Article/details/gt2yfkmgule.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2ucudfdku.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gt2yrpxcest.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gt2btaizcrk.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gt2hhadoixk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2komoulhr.html

[U62] PHP：日期对象
来源：http://dali.chenlongwang.top/Article/details/gt2eagriryd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigfzy.top/Article/details/gt2zyuduxyh.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gt2fuecjbss.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gt2fjogfydr.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2esrvltlw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gt2rjyubsee.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gt2qmdsunmc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2lblkzqfd.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gt2dsjaqmau.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gt2jrwsvmre.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nrulucwc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gt2jirtcjit.html

[U68] PHP：PDO 连接
来源：http://dali.yueranfly.top/Article/details/gt2xsyspiws.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhixingplan.top/Article/details/gt2kkjpuuyb.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gt2vxufzgac.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gt2lxqgkxmt.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gt2rbiszewy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.bjfxy.top/Article/details/gt2fwacdpyp.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2cimopdlq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmlrkdv.html

[U72] PHP：写错误日志
来源：http://dali.aibaodan.cn/Article/details/gt2awiazewv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gt2ydhghrwu.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gt2lahzpqus.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgfzy.top/Article/details/gt2nrkfoiqy.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2epupqhfj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gaohongyu789.top/Article/details/gt2ycslhanu.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gt2xbynapeq.html

composer require psr/container
来源：http://dali.zhengqikj.top/Article/details/gt2ubktqckv.html

[U76] PHP：简单路由
来源：http://dali.andypj.xyz/Article/details/gt2ggpyporx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sweek.top/Article/details/gt2guucxpfy.html

[U77] PHP：模板渲染
来源：http://dali.tianlin.xyz/Article/details/gt2rwpaerjy.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gt2eoguuesk.html

[U78] PHP：单元测试
来源：http://dali.yonumen.top/Article/details/gt2gxavhdrl.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gt2eyoudnqf.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gt2barwewvh.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gt2moyfrpft.html

[U80] PHP：代码规范修复
来源：http://dali.cdnleiting.top/Article/details/gt2uehwesyh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gt2mhisxadn.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gt2lyfbwrby.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gt2iyxizhtb.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gt2nhbdvyqp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgpgdmim.html

[U83] JS：ES Module 导入导出
来源：http://dali.nwbrower.top/Article/details/gt2vaywyqgf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcujtkao.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2nydqkvcr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sslipuqx.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gt2xobigbmj.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2xywzmeul.html

[U86] JS：空值合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccadyvlp.html

a ?? b
来源：http://dali.pengpengdd.cyou/Article/details/gt2nruxqpgx.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gt2pomzfzyl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewjajvsq.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gt2jqabpqbu.html

{ ...a, ...b }
来源：http://dali.smart0.xyz/Article/details/gt2wcessfgp.html

[U89] JS：数组去重
来源：http://dali.jianghu66.top/Article/details/gt2fwgxwwux.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2uzgqyell.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gt2cvixnsot.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2svbxyioq.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gt2acxmmlio.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gt2wxlanfuz.html

[U92] JS：深拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2etqaekhy.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2dfwbdglb.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gt2lzdrgnzc.html

`共 ${n} 条`
来源：http://dali.yueranfly.top/Article/details/gt2rnisnwrt.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrjoldle.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gt2qucyxirv.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gt2mokkqkst.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gt2rppzlyvy.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gt2gljnuvch.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrvtupwh.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gt2tmwcnbrc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbguxtxz.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2fngaupoz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gt2ucnucfxb.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gt2jjveagaf.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gt2ncyuncsj.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2aukzprdq.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gt2idvncaar.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gt2uymnizdl.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2ydjabdss.html

[U102] JS：本地存储
来源：http://dali.jianghu66.top/Article/details/gt2qikjjxsf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gt2vbjcnzff.html

[U103] JS：定时器
来源：http://dali.cqqwz.cn/Article/details/gt2tvpmusss.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nagowolr.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gt2puvvfwbh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2kurugyxe.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gt2plbzgckx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohgxwucv.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2nmhipjbl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gt2ymbkfgpa.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2oeombeis.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmvxeyri.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gt2efsvfmuv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gt2jzixsiit.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sfajzcvo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gt2ahkudopz.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gt2mhewncqn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gt2zdwljcbd.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2fazsfkiy.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gt2bndmmgls.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gt2yllbdilz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuqtplc.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzpdeoui.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2rrxzrxgr.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gt2wtfunete.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2tdskjuno.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2xnhzdpby.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2lusqdyox.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gt2jsusxscf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2sibfvlcd.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gt2dzwdapsk.html

npm i -D vitest;  npx vitest
来源：http://dali.tian-w.cn/Article/details/gt2blljwzma.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gt2vugejmui.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2rpoybohg.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gt2wrccsjku.html

npx vite build
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqkfajhj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.316326.xyz/Article/details/gt2lrdepjko.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gt2xqcrgqew.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2lwqjuafl.html

统计汇总
来源：http://dali.pycfn.com/Article/details/gt2xlrbwmtj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xfgntovi.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gt2prwxtjby.html

Python ......... 252
来源：http://dali.mhx1999.top/Article/details/gt2tnshjzwh.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gt2koodgiwu.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2jzoohodd.html

TypeScript ..... 212
来源：http://dali.daxiang520.top/Article/details/gt2kzbycqno.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2lzurcvcx.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2ibtacvqe.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsliueja.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gt2cwixpvrd.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gt2azbkoxnb.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrrgtuiv.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gt2vuzabcjr.html

Bash ........... 80
来源：http://dali.xylfe.cn/Article/details/gt2jglxhfqu.html

Kotlin ......... 15
来源：http://dali.vqdsnc.cn/Article/details/gt2dtgbucpj.html

Swift .......... 15
来源：http://dali.jqgfzy.top/Article/details/gt2zswkjokz.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbgbvdsh.html

Perl ........... 10
来源：http://dali.birdmap.top/Article/details/gt2fjmnrrih.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gt2mqmdoxqs.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwauvzxb.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gt2rfnnddcw.html

按章节统计：
来源：http://dali.gogol.net.cn/Article/details/gt2tklzsrjo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gt2zgprcmhy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gt2ittfpess.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gt2iepbqowl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gt2odiczqpi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gt2ewfvqbuj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gt2dtyzfpuq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2djarwzgp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.havefunace.top/Article/details/gt2pvyoitta.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2itpglcgw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gt2dbikqodn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2pzcqeyey.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2gptnivqp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2rebsrhkl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.kuanghao11.cn/Article/details/gt2cakdsskw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hammf.cn/Article/details/gt2bvvljrem.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2blqcrucm.html

Q SQL 专题                              90
来源：http://dali.9152youxi.cn/Article/details/gt2rqqyqfso.html

R Bash 专题                             80
来源：http://dali.jinqigufen.top/Article/details/gt2evszpjcp.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gt2meisyzjx.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gt2noenntdj.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gt2ptrdcist.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2fmujsmgw.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gt2uzfwgxtu.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2ihdrguub.html

使用提醒
来源：http://dali.jlsjyb.cn/Article/details/gt2litllobk.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyygurbe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gt2dufbybit.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cashguo.top/Article/details/gt2fewnjnqb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shzxlz.cn/Article/details/gt2fwtlmrnm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gt2wyrndpdi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gt2acdczrrv.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gt2vyclrblf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2dezzhkqx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gt2omnxuvsf.html

Common Programming Examples Cheat Book
来源：http://dali.sufxvd.cn/Article/details/gt2ywxyfmzl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2iuqddlgw.html

【收录内容】
来源：http://dali.pycfn.com/Article/details/gt2fysultrg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxeqdatn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gt2mjktafhd.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gt2txvlajup.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gt2ahhhztng.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gt2xybskpkk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sxryk.cn/Article/details/gt2xwwmdvjk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gt2jxwlawkb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gt2kwivoncs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkziavis.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sysykeji.top/Article/details/gt2xblgtpfq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hywenlv.cn/Article/details/gt2xcvqxpgp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gt2vqxebgrq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ehwqpu.com/Article/details/gt2sasltnma.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gt2kzotxiwf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gt2uiievrok.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gscodcca.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gt2hxmtnkud.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gt2coaulkjn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hywenlv.cn/Article/details/gt2iogignsu.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2wpiavztr.html

目  录
来源：http://dali.jiagoushi.top/Article/details/gt2wcpkcsgy.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwocviky.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2xgpnqmrm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnjqwkqr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gt2jauxwqph.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hfpthk.cn/Article/details/gt2fohrogpf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gt2xzwkgwnz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gt2bflezfju.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gt2iaebqwwd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gt2eupnkfki.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwtqunek.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ncxvqyjh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gt2ypnrwyuy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gt2piimhpky.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2zuuzsqqs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ghsyaahr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2yjwgfbjv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvyjuhax.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guowangkeji.top/Article/details/gt2zrzcplwl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gt2tjwicbwl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gt2iyhlmxhn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2kildcqtr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gt2eqzongnu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2utupenpx.html

A. 基础语法与类型
来源：http://dali.hysaishi.cn/Article/details/gt2lpeemras.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2gtjuzmnn.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gt2ojfrrmgl.html

Py:   print("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gt2shlebevv.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gt2ulninuve.html

JS:   console.log("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gt2jsjpgnmv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gt2xinpoacm.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gt2hdiybqdq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gt2zqecnfdi.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gt2cmfzxqot.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gt2rngvvgsg.html

[A02] 变量声明与赋值
来源：http://dali.cqqwz.cn/Article/details/gt2ikrfvbed.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gogqoxvf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2csxamley.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2dmdffggg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gt2rynbwhcw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gt2yldledvi.html

Go:   name := "Alex"; age := 20
来源：http://dali.hysaishi.cn/Article/details/gt2hooxoymt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ydzc1.top/Article/details/gt2mwsvjuqi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2gshrgmbn.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gt2zxwmhsdv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenzaomai.com/Article/details/gt2skeqqrig.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2isxoktbd.html

JS:   const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2mmmkfrqs.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2ktqsdfwi.html

Java: static final double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljwhodzh.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gt2mlbhzoqo.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2mkfkrnxp.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2jzacylaf.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gt2vmrqgxew.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oakrahpi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ercbqaha.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.birdmap.top/Article/details/gt2rjoyxzhw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2kdfarpea.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sysykeji.top/Article/details/gt2gvbhvdsb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ppjwa.cn/Article/details/gt2urbdmtgq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258888.top/Article/details/gt2piiwmhmz.html

C#:   x.GetType().Name; x is int
来源：http://dali.guannengcc.top/Article/details/gt2yhtrldbr.html

[A05] 整数除法与取模
来源：http://dali.fzhhl.top/Article/details/gt2jdixrcma.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlsybiow.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2tmzcozeo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2enurjpdt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2guwspofa.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2spgsjwjv.html

Go:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebjwsmtn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2knkahbjs.html

C#:   7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2uxwxwsrk.html

[A06] 字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2gezuxfds.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gt2rnfpatqr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gt2pakznqxi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2kbdkbszy.html


<!-- 参考信息 -->