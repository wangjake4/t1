代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gtouuuxqjn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangdashe.top/Article/details/gthvxzsqvo.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gtprfhzgjh.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtrhcdtxsz.html

[U57] PHP：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtontxavgy.html

"值: {$a}"
来源：http://dali.yvedp.cn/Article/details/gtvpxzhakx.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gtbdksgqkx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gtapsdzfeg.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtdvfkykrx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtocnxrncz.html

[U60] PHP：JSON 编解码
来源：http://dali.svipenyu.cn/Article/details/gtmhpdbtno.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtmpwqxgeo.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gttkjkjvca.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtmbqyesao.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gttjrozfsl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xinyue.icu/Article/details/gtvisbxmnh.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtomoddcdz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gtkvfzvkiu.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gtmypbslju.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtrtzhpauj.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzinrngp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtqkqgdegr.html

[U66] PHP：设置 Cookie
来源：http://dali.feifeiyinyue.top/Article/details/gtiuxzovud.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtegvqpxzm.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gtdzvxtizi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.vqdsnc.cn/Article/details/gtxmklrgje.html

[U68] PHP：PDO 连接
来源：http://dali.ydzc1.top/Article/details/gtpkjsodjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gtlunkwlds.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxuanxn.top/Article/details/gttjfshrmf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gtuyannctx.html

[U70] PHP：PDO 事务
来源：http://dali.guowangkeji.top/Article/details/gttulpwsit.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gtswfcxhst.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gtohwasqgz.html

throw new RuntimeException("失败", 500);
来源：http://dali.tianlin.xyz/Article/details/gtdnhpocjx.html

[U72] PHP：写错误日志
来源：http://dali.yj20258.top/Article/details/gtvzsxprbv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gtksfmlcmi.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtfvsjhlsc.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gtkcowrvcm.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjkcpphf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhixingplan.top/Article/details/gtlkfmrohe.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtzzzumjms.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gtaawbaxcy.html

[U76] PHP：简单路由
来源：http://dali.wangdashe.top/Article/details/gtexvcprjd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tian-w.cn/Article/details/gtmcbzvnao.html

[U77] PHP：模板渲染
来源：http://dali.hywenlv.cn/Article/details/gtefmojujr.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gtcvoqennd.html

[U78] PHP：单元测试
来源：http://dali.xylfe.cn/Article/details/gtwsmiseca.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gtiqpbgazw.html

[U79] PHP：静态分析
来源：http://dali.zhoulong.xyz/Article/details/gtnmlbdujn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gtovipyane.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtbjxvholz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivrufnaa.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtvtjnarik.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gtrighulfp.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigufen.top/Article/details/gtxbazocod.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daria6918.cn/Article/details/gtvhbpncjy.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtmnncgpur.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtmlhymiux.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gtkjakonpn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gtydlwzlwz.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtkqcgasgx.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gtiohhuunj.html

[U86] JS：空值合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwofanwxi.html

a ?? b
来源：http://dali.cashguo.top/Article/details/gtaetjsvgi.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gtnchuezle.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cheryme.top/Article/details/gtdydjzgoo.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gtayjbvvig.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gtjhoqnrdt.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gtfairnnxu.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gttvhmiudt.html

[U90] JS：数字数组排序
来源：http://dali.dianchejie.cn/Article/details/gthortujbh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtaevbwlqh.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtqkqyfnxb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gtpmvgwlka.html

[U92] JS：深拷贝
来源：http://dali.sufxvd.cn/Article/details/gtlzcahppi.html

structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtrenmilhp.html

[U93] JS：模板字符串
来源：http://dali.aizwys.cn/Article/details/gtypskqmhv.html

`共 ${n} 条`
来源：http://dali.hysaishi.cn/Article/details/gtbvqelaki.html

[U94] JS：箭头函数
来源：http://dali.ivvv.top/Article/details/gtamdahfey.html

const double = x => x * 2;
来源：http://dali.hywenlv.cn/Article/details/gthmaaitwo.html

[U95] JS：Promise 包装
来源：http://dali.guannengcc.top/Article/details/gtokrqwhrg.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gtwtgkxzae.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtbxfyvgrb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtmslzpmxw.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gtgqwvawya.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtgvdpyfkp.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtzwyrsqij.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.iojbl.cn/Article/details/gtydllkhnc.html

[U99] JS：事件监听
来源：http://dali.cqqwz.cn/Article/details/gtlzvblckz.html

el.addEventListener("click", e => {})
来源：http://dali.xinyue.icu/Article/details/gtwlokolrf.html

[U100] JS：DOM 查询
来源：http://dali.vqdsnc.cn/Article/details/gtawdfrjqb.html

document.querySelector(".item")
来源：http://dali.zhiwuduotai.top/Article/details/gtpbbiafnu.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gturtascsz.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtjlmnjaor.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gtcmsubbjr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gtphquxxob.html

[U103] JS：定时器
来源：http://dali.hywenlv.cn/Article/details/gtgfgetdta.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gttnzcjedl.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gtwzjbspcn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtoyozjtvl.html

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gtmbjzsjsr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtjlwpvenh.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gtilyvsyrl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tian-w.cn/Article/details/gtidqnybrm.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtnjhlupxh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gtrrrpzell.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtdiogapdy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gtsspexppi.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtfxhcdfdp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtgjlnsyvc.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gtjkikoskp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.feifeiyinyue.top/Article/details/gtztvwyfrj.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtusosokru.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtyhrcnbhy.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gticdhkwvz.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtzklxgdui.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtjabxsfpe.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtjregiddy.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtzoygerpp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbtgckqna.html

[U115] JS：生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtdsaqzttu.html

crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtusdmkddx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gthvqkxaof.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtsdjifdzi.html

[U117] JS：单元测试
来源：http://dali.gzhubu.top/Article/details/gtudqzzykl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhixingplan.top/Article/details/gtumspceya.html

[U118] JS：开发服务器
来源：http://dali.nanxuanxn.top/Article/details/gttzibcdep.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gtamrvwxlv.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtmmuyypii.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gtrzlvrfjr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gtcsavxppa.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gtspozstes.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtflimuwny.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gttphmdvyj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvjuxhbbp.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gtoghwsxtx.html

Python ......... 252
来源：http://dali.jyoumei.cn/Article/details/gtipygawqf.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gteygqwjpm.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtcshdswfe.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gtchbmkxzc.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtzqhizdrm.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtmwwnxgkv.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtcboofbnx.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtjxqnhqxx.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtlzumsnrd.html

C++ ............ 30
来源：http://dali.hywenlv.cn/Article/details/gtjymnhwpu.html

SQL ............ 90
来源：http://dali.gotoacloud.top/Article/details/gtixmnnjtl.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gtxitbtqph.html

Kotlin ......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gtugwcoaph.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gtutyaxoyk.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gtkmcrorwp.html

Perl ........... 10
来源：http://dali.redwolf501.top/Article/details/gtufdeafwl.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gtfqbaznyh.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtkomgoqkd.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gtgsxyxucz.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtcdrhnwnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtythjhmbv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtfwxloyoq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtqxnqwspd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gthiowdbsm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangdashe.top/Article/details/gtwxnmjrpt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtcehtudyh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtskmakgdt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gtnnwupypb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtbcswbris.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gtbnfnsvog.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtppzzxpwx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gttcvkffds.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlhfzqut.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtpplrvgfa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gtckiyothu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtehrkxjrt.html

Q SQL 专题                              90
来源：http://dali.nwbrower.top/Article/details/gtewhsjayy.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gtwdtwmaon.html

S C / C++ 专题                          60
来源：http://dali.gzhubu.top/Article/details/gtpfsqgtyh.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gtbvuprkuz.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gthdlxtzig.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohqpwani.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtlvcdrzkb.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtbkloosjl.html

使用提醒
来源：http://dali.guowangkeji.top/Article/details/gtrlymgxdm.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtejzftqnt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gtjhrgfnjx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gtgzdcfual.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmleumyo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtwtenhthr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gtewjeyyxg.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtijwibwta.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtcmxmlksu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pycfn.com/Article/details/gtnbtdwmqz.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gtwmzeakuf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpxueiafi.html

【收录内容】
来源：http://dali.haohaochexian.top/Article/details/gtmkkafulc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.feifeiyinyue.top/Article/details/gtjxtqrqcf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gthozjyctv.html

SQL · Bash · C · C++
来源：http://dali.tianlin.xyz/Article/details/gtoxnzehyo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hywenlv.cn/Article/details/gtxeflonjn.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gtmojyirte.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gtmivgkllt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yongpay.top/Article/details/gttocakxjn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gtpbrveuuh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gtoxnkpzco.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ehwqpu.com/Article/details/gtwizeilau.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shzxlz.cn/Article/details/gtcbnyzkxy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gttekalrkx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gtuqzwqudp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaprimpu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxinkj.top/Article/details/gtgwkgbzcs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gttlndwpvx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gtnhqwvmdd.html

【文件统计】
来源：http://dali.gogol.net.cn/Article/details/gtwbkxvris.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gtvnfxines.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gttkkqxsaf.html

目  录
来源：http://dali.sysykeji.top/Article/details/gtyrkkodrl.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtsghpwpzm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtxcpqdfce.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gttgbneccj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtxbgsbtpf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtvunbjzms.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ydzc1.top/Article/details/gtpvwnywts.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtdpzwcrvl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtrwwdvijt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gtikrrwwul.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtbvsbzarn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtzmdoitye.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtagebrant.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtdxwvldyr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtdcemncbz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtmyermqws.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aizwys.cn/Article/details/gtmhcnkrox.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtqioukitr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gaohongyu789.top/Article/details/gtlouybdke.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xylfe.cn/Article/details/gtoiluszzk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gtztxkmpml.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gttwhpqtxg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtsevlnqlb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttlvjbfrw.html

A. 基础语法与类型
来源：http://dali.yonumen.top/Article/details/gtcwzwltlc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttokmaltj.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gtsgitoenp.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gttphstios.html

PHP:  echo "Hello, World!";
来源：http://dali.zhiwuduotai.top/Article/details/gtbhwyqiip.html

JS:   console.log("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtilavkjue.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fzhhl.top/Article/details/gtzajxyuhe.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyhtnqtq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtoprsdasy.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeegovhx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtxrrbrmll.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtnbdrhzbs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gtuvexwxwa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtcarjdkxj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gtaylpapjt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gthdduyhrr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtjcsvofxm.html

Go:   name := "Alex"; age := 20
来源：http://dali.cqqwz.cn/Article/details/gtqwwcotdy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gtofzdomlj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtqsfbgpgb.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gthixqhuso.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gtuuldbjjc.html

PHP:  const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtmrrtmdxd.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtywyyqiwg.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtpwxalcja.html

Java: static final double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtwfoqflpe.html

Go:   const PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtvdruuslv.html

Ruby: PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtepuwally.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtjsscfihx.html

[A04] 判断变量类型
来源：http://dali.aizwys.cn/Article/details/gtgbgatvbi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.haohaochexian.top/Article/details/gtpfmnqcee.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenlongwang.top/Article/details/gtjefmfpxp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtubzelazu.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtaljppaez.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yangfankeji.com/Article/details/gtvlqnplnl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gtvxdppgqf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcuqtuax.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gtlhhhygtm.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtyiwecbsw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hfpthk.cn/Article/details/gtjcuioyqu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtximmcmpd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gthiodbkew.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtggmbikcf.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtdfffxcyb.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtgaybsxsm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtlcorbjxd.html

C#:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtyzbypbmk.html

[A06] 字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtjkiftbjk.html

Py:   int("42"); float("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtbwiqaydx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwqcmnwi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtpxnppkfp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtfjrkwupy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.bjfxy.top/Article/details/gtdedvwuyb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigfzy.top/Article/details/gtmkvyqlzw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gtjlkhhklg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.bjfxy.top/Article/details/gtkmggdfuu.html

[A07] 数字转字符串
来源：http://dali.xuanzx.com/Article/details/gtjbkbdcnw.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtzwllngad.html

PHP:  (string) 42; strval(42)
来源：http://dali.sxryk.cn/Article/details/gtxuutsmgr.html

JS:   String(42); (42).toString()
来源：http://dali.ivvv.top/Article/details/gtgbaptpeh.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gtdldmnqsq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtplzadjih.html

Go:   strconv.Itoa(42)
来源：http://dali.jqgfzy.top/Article/details/gtpoqqwsfp.html


<!-- 参考信息 -->