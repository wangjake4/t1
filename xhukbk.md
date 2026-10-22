代发 wailian999

[U51] PHP：数组解构
来源：http://dali.jinqigufen.top/Article/details/gt2wqjtajys.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gt2tmjuaikc.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2suktyamn.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gt2xkbhtdqm.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gt2whnflqoi.html

$v = $a ?? $b ?? "default";
来源：http://dali.hammf.cn/Article/details/gt2drjakdhz.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gt2yqftzclt.html

$obj?->method()
来源：http://dali.cucudq.cn/Article/details/gt2bimlnztd.html

[U55] PHP：match 表达式
来源：http://dali.hysaishi.cn/Article/details/gt2zcpcqsui.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gt2vmlptmmf.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gt2pibfxgck.html

f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2uladxykm.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2mnsmbadv.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2yzlwwmsq.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2catxdxej.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2crpnnrhq.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gt2zuvzeqmd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2dyfmtkdy.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gt2qijzwsmz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gt2pcliejfb.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gt2zkiooiyv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2prxbftxp.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gt2yjjuwnsv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gt2hsuuugkh.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gt2wnuvnxhy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gt2fywwgnln.html

[U64] PHP：目录遍历
来源：http://dali.redwolf501.top/Article/details/gt2plbdlcqu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dianchejie.cn/Article/details/gt2dbxyjtri.html

[U65] PHP：会话
来源：http://dali.shuidangran.top/Article/details/gt2yzvwlnva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2nausaygx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2llsfykha.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2oaebtphb.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gt2wnzqxsvz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gt2vajzesyd.html

[U68] PHP：PDO 连接
来源：http://dali.guowangkeji.top/Article/details/gt2tnugqakl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gt2uupewyir.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2gkwrvkgk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hywenlv.cn/Article/details/gt2yaldrrjy.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gt2pguhizlm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258.top/Article/details/gt2cfynnoid.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2eblemzcu.html

throw new RuntimeException("失败", 500);
来源：http://dali.yueranfly.top/Article/details/gt2bqangkej.html

[U72] PHP：写错误日志
来源：http://dali.chenzaomai.com/Article/details/gt2cvwvsgzc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gt2zipgnthi.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2esjxvwtk.html

parse_ini_file("config.ini", true)
来源：http://dali.dianchejie.cn/Article/details/gt2doptokae.html

[U74] PHP：读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2diiwangg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxinkj.top/Article/details/gt2cvgkqxvn.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gt2sbnhcrts.html

composer require psr/container
来源：http://dali.hnqzz.top/Article/details/gt2upnjbynj.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gt2klobdbwg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2kdkyepur.html

[U77] PHP：模板渲染
来源：http://dali.chenlongwang.top/Article/details/gt2tqgpauyp.html

composer require twig/twig
来源：http://dali.cqqwz.cn/Article/details/gt2tnssdofc.html

[U78] PHP：单元测试
来源：http://dali.guowangkeji.top/Article/details/gt2qreojgtz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2wcinzldo.html

[U79] PHP：静态分析
来源：http://dali.chenzaomai.com/Article/details/gt2vupktkfb.html

composer require --dev phpstan/phpstan
来源：http://dali.haohaochexian.top/Article/details/gt2szimttcm.html

[U80] PHP：代码规范修复
来源：http://dali.dashuyun.cn/Article/details/gt2aerajqpn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aibaodan.cn/Article/details/gt2xferuqdl.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywlrgfev.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gt2fsfyjrwz.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gt2kxbzqtqm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ppjwa.cn/Article/details/gt2avlyubcz.html

[U83] JS：ES Module 导入导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2arqlqtml.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2plwrieqg.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icgwyrqj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gt2wbjxdaqh.html

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gt2ivnytrwz.html

a?.b?.c
来源：http://dali.zdqjudy.top/Article/details/gt2nrzuslyv.html

[U86] JS：空值合并
来源：http://dali.xinyue.icu/Article/details/gt2vcchdfrz.html

a ?? b
来源：http://dali.jqgufenzy.top/Article/details/gt2gdrqvtlk.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gt2gxjweytv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhoulong.xyz/Article/details/gt2asgnpvgg.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gt2kemxinyt.html

{ ...a, ...b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppbaqimu.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gt2cgqgbwlu.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2autmaury.html

[U90] JS：数字数组排序
来源：http://dali.sysykeji.top/Article/details/gt2bflfsuvp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2uqjkucme.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gt2pargxsew.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigfzy.top/Article/details/gt2zfpxnnqw.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gt2fsbujwzt.html

structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2tfimynla.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wopuyrnh.html

`共 ${n} 条`
来源：http://dali.yonumen.top/Article/details/gt2ldrtdxwa.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gt2dkqnhryu.html

const double = x => x * 2;
来源：http://dali.gzhubu.top/Article/details/gt2rdwgfnyu.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gt2egowrvil.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgufenzy.top/Article/details/gt2jhdimtpf.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gt2rjiwarhd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qliiiitp.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gt2spqcdcjy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2mosazhhf.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gt2zvvqmxkg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rabhpzlb.html

[U99] JS：事件监听
来源：http://dali.aibaodan.cn/Article/details/gt2daglafpp.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghxwurde.html

[U100] JS：DOM 查询
来源：http://dali.smart0.xyz/Article/details/gt2esgfvzwd.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gt2mvcajzsj.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2expupuzq.html

el.classList.toggle("active")
来源：http://dali.xuanzx.com/Article/details/gt2uhzzokdo.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gt2zultiwjj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cdnleiting.top/Article/details/gt2ehpkwhrl.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gt2ykqvdmoe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gt2klkeorya.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gt2similddf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2unrysxyk.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gt2jqcnuzog.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnmvnazy.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2hpqsylze.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gt2yjtuytzm.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gt2kvdopwuv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2nwlpdesp.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gt2ctoeejtr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.pengpengdd.cyou/Article/details/gt2cropugqw.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2oygbelbw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2zkeyvrfl.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2kpnpgqrv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gt2taqanwqh.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gt2gspuhekk.html

new Map(Object.entries(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2ngifeyti.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcvvlahf.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiltxbwz.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gt2jdkobtsb.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzinirjf.html

[U114] JS：JSON 深比较
来源：http://dali.jiagoushi.top/Article/details/gt2vsbdhfqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2zekaiear.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gt2mwxfzfvr.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmilrduk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gt2qrrhgpxs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gt2zehkxini.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2yttkrebg.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gt2rgbryzdi.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwdqpudi.html

npm i -D vite;  npx vite
来源：http://dali.snrcjt.cn/Article/details/gt2gupxdgvz.html

[U119] JS：生产构建
来源：http://dali.wangdashe.top/Article/details/gt2yhjusdbj.html

npx vite build
来源：http://dali.zhoulong.xyz/Article/details/gt2xvfyhjft.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gt2zgoxnqpq.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gt2pwdwoiwe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2liztgjmn.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gt2xupsqlgm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2frjskhpf.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gt2fbncrtfr.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gt2cwqvxwbd.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gt2lvodlyql.html

JavaScript ..... 252
来源：http://dali.pycfn.com/Article/details/gt2mcsxdnia.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gt2zmsqmrlb.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2vvmryeed.html

Go ............. 212
来源：http://dali.fengsongda.top/Article/details/gt2fxfnfpnc.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2pacxwpja.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2glayuokj.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gt2sojgvftd.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gt2pwfqbujr.html

SQL ............ 90
来源：http://dali.xziqi.cn/Article/details/gt2aqmjrxbc.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gt2uabgdwkw.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upphgeha.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gt2ebuvmhkg.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gt2mxryicmz.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gt2odsdqacq.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2raoofdos.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2anowpian.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gt2lmhlqfan.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gt2thymexwy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gt2svdlwkvk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gt2llzwwcin.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2dbbvgbru.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2wfsabmdf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmuczvxn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gt2vrfhqvje.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivkzcajf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2hdbkckpq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2dntujfsd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2rhmfnxjw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbjgzgxk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2pckdwcsg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2dadwyult.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gt2dzdcpyql.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gt2qclaqjmi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwfmlhzn.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gt2ohgwqtct.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gt2bubjdwuj.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gt2cqlgxgde.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gt2qewiqgbu.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gt2nhyujvoi.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2rxseciis.html

合计                                  2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luvqccln.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2ljdaczek.html

使用提醒
来源：http://dali.aibaodan.cn/Article/details/gt2frazsbhk.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gt2ttnjcrke.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gt2mkrcssaz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gt2lfgmzsis.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxinkj.top/Article/details/gt2vdlsooiy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhoulong.xyz/Article/details/gt2mmyhlzpv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gt2dehrchbw.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gt2optcyioy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2roqapnux.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhixingplan.top/Article/details/gt2axskabwo.html

Common Programming Examples Cheat Book
来源：http://dali.smart0.xyz/Article/details/gt2ebvblcpd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zirtfixq.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gt2xaazhdko.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenlongwang.top/Article/details/gt2kldovyhm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2dvtbogau.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gt2rdpzzwid.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tian-w.cn/Article/details/gt2nnhvqncs.html

【使用说明】
来源：http://dali.316326.xyz/Article/details/gt2aoskknov.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gt2zhtykdvr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zioiiaar.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gt2nizjbsvo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gt2zjbjrgqm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.redwolf501.top/Article/details/gt2wgsjtnwk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrpdqgds.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gt2jlcebbpk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jyoumei.cn/Article/details/gt2wmwqzyau.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxinkj.top/Article/details/gt2atdgigoh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2eqafjvei.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gt2cisihhvw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gt2whgewkka.html

【文件统计】
来源：http://dali.sysykeji.top/Article/details/gt2dsexjlms.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.c1oappe.top/Article/details/gt2rquchjlm.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2iquheagz.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gt2wyyundqq.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2twzbyylv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gt2zblgnzno.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mttjuqva.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2smuclqff.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cqqwz.cn/Article/details/gt2prfiefim.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vblwmubf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ariygeaj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2jesjlcws.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydbdkfff.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2jrfxzyex.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2xduqunjo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2psukhkfz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2cmjdfawa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ivvaebbb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gt2qwiwvnej.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fzhhl.top/Article/details/gt2wnobremo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2cmsyjzyg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2uxcdlwdg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gt2tminslfo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgfzy.top/Article/details/gt2mhilxync.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2wmmjzbwn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yvedp.cn/Article/details/gt2irsehhel.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2piindhip.html

A. 基础语法与类型
来源：http://dali.yonumen.top/Article/details/gt2yyoqzisq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2znlrptde.html

[A01] Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhkawqfr.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gt2rzqdbwdj.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gt2nwgyrlyt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2iedhduhm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gt2cokwzqml.html

Java: System.out.println("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2fnjirufk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paeahxrr.html

Ruby: puts "Hello, World!"
来源：http://dali.yonumen.top/Article/details/gt2jscptwuo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gt2tyavgxxr.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywfjitfz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yonumen.top/Article/details/gt2rlsbiuop.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2tojuayol.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rloxxdod.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gt2vxguxvfi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2rnmizbln.html

Go:   name := "Alex"; age := 20
来源：http://dali.nwbrower.top/Article/details/gt2kpoajhxh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gt2crrjwdtc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2uixvzqnv.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gt2brvhzmjy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gaohongyu789.top/Article/details/gt2ruiguocl.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2xmyaxtwt.html

JS:   const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2stnggnox.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2ibjunmod.html

Java: static final double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2gzvzlfka.html

Go:   const PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gt2xkeggckw.html

Ruby: PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gt2ibxsmbir.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2oefzfmtk.html

[A04] 判断变量类型
来源：http://dali.jlsjyb.cn/Article/details/gt2qmnpzifx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gt2tjafvpeq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258888.top/Article/details/gt2onjybdud.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffgozvrq.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gt2chvxwnij.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jianghu66.top/Article/details/gt2qyvpjmmx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sufxvd.cn/Article/details/gt2uyaivqrn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gt2jtfnzwzs.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gt2ntfoxwok.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gt2gssjtnrw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esvzzuff.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agbmcfzx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kelglukt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2iaxjmrwx.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2lnafngrd.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2zokpbwcx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2tiiqudkl.html

C#:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gt2ozkjszdg.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2atpuwtvu.html

Py:   int("42"); float("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsmspdby.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aizwys.cn/Article/details/gt2kxoyolvl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gt2yinytkiy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndicjycv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pycfn.com/Article/details/gt2wsuuntxi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pratbhqr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gt2wowfptvv.html


<!-- 参考信息 -->