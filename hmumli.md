代发 wailian999

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkcnpfgb.html

[$a, $b] = $arr;
来源：http://dali.andypj.xyz/Article/details/gt2aqyrxkky.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gt2ctqqldss.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gt2wixhrkph.html

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gt2wqmvqzcg.html

$v = $a ?? $b ?? "default";
来源：http://dali.cqqwz.cn/Article/details/gt2utacfpwl.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpogbsxa.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gt2caznarim.html

[U55] PHP：match 表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2kofsaaga.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gt2ygslbenv.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gt2stxksprk.html

f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2oonoxcnj.html

[U57] PHP：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2tsfigips.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtwirayu.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gt2kupyjhpw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2tvvmluvo.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gt2rrsvedmk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2ttdyzsny.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gt2pcybavnd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2hwsukzpv.html

[U61] PHP：正则
来源：http://dali.cucudq.cn/Article/details/gt2kfdqvqut.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gt2uwyicrhj.html

[U62] PHP：日期对象
来源：http://dali.0kj1m.cn/Article/details/gt2mpriocso.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gt2dhpotcvp.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gt2jglsaucb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.9152youxi.cn/Article/details/gt2mnohhhli.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2uquyfrtb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenjidiqi.icu/Article/details/gt2wopqrwzi.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gt2ugdbnvih.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2tbdnpypw.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gt2qphflvam.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gt2ripgkpdd.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gt2wvqqblmn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gt2syfdkuoj.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivukfowe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmlyrkmr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfthela.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsezscrj.html

[U70] PHP：PDO 事务
来源：http://dali.smart0.xyz/Article/details/gt2leiwypkv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258.top/Article/details/gt2fpoqryji.html

[U71] PHP：抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2dnaonylk.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddtjltfx.html

[U72] PHP：写错误日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnnpzkan.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gt2rvbrjohw.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvhkmpgw.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gt2aoammxun.html

[U74] PHP：读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2tudxruon.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gt2wwxjjclj.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubeorluq.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gt2vbkkcfet.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gt2ojkuulhc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gt2uinbtorm.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gt2omjelytr.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gt2avqjyhso.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gt2teplqatp.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gt2yqsstfkm.html

[U79] PHP：静态分析
来源：http://dali.aizwys.cn/Article/details/gt2mttbzyxv.html

composer require --dev phpstan/phpstan
来源：http://dali.gaohongyu789.top/Article/details/gt2btwsiwfk.html

[U80] PHP：代码规范修复
来源：http://dali.nanxuanxn.top/Article/details/gt2xjkmvlaj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.meibo888.top/Article/details/gt2zgsyeevf.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gt2pbmqpjby.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gt2tsxiqtbo.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gt2jguddxwq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dashuyun.cn/Article/details/gt2teblzwud.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrbiltvw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2tmsgxspe.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gt2ndbmnsuf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xinyue.icu/Article/details/gt2vyatxfet.html

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gt2jwqjgzlj.html

a?.b?.c
来源：http://dali.hfpthk.cn/Article/details/gt2uvjeutuo.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gt2teasmkuo.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gt2zunpblff.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gt2mtstycus.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gt2uzaajmta.html

[U88] JS：对象展开合并
来源：http://dali.cucudq.cn/Article/details/gt2kggmytgu.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gt2nqwwfwgy.html

[U89] JS：数组去重
来源：http://dali.jyoumei.cn/Article/details/gt2kzwtspzh.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2tsplhgve.html

[U90] JS：数字数组排序
来源：http://dali.0kj1m.cn/Article/details/gt2txfbgslr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2zcprhcdf.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkiousid.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gt2ctavowcl.html

[U92] JS：深拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxaamgwd.html

structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2odeudbnk.html

[U93] JS：模板字符串
来源：http://dali.shzxlz.cn/Article/details/gt2smswctxh.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gt2ilgjfmgk.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gt2bnefypva.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gt2hhtaqtxm.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gt2jhwuooir.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gt2nbmsrjta.html

[U96] JS：async/await 与异常
来源：http://dali.wangdashe.top/Article/details/gt2mmabkawa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2hghqpflg.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gt2razzzuls.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2drkshffz.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gt2ntfqtnhc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gt2tmpvubnp.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gt2phkwlqfb.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gt2cmbrruam.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2wprclzkd.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfrbdmbd.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gt2rjtjiotu.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gt2egfjzrpo.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gt2pjetrgzm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.smart0.xyz/Article/details/gt2edttmlom.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gt2qqxycrox.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gt2vejfnyvr.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gt2ysrnlixq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2oeilpcaa.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gt2lvbugxal.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gt2gkipobhr.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2xpquvlzz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gt2cqkizrux.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gt2ueqvllza.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gt2rskkflfe.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gt2todsveug.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gt2uxwcpypt.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2echqnerq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2wdwjpdtz.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gt2umsrvzsc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gt2uzxphyvm.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gt2jgowrnis.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2qyqqksum.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gt2arqdoend.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2mcyrmeok.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gt2jiuhrdza.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2acjnqdyg.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gt2dhlzrymn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gt2prjjhqjk.html

[U115] JS：生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2ipdbjked.html

crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2yfcjtfdb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gt2sajtdvmr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gt2upxitrda.html

[U117] JS：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiylsepa.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gt2vbztkkrq.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gt2cnvejdsy.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gt2evlhfeqq.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gt2xcnhhbzs.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gt2lppkctmh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gt2svpdorel.html

import.meta.env.VITE_API_URL
来源：http://dali.guannengcc.top/Article/details/gt2rrhfnsjg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2mzidemzi.html

统计汇总
来源：http://dali.pycfn.com/Article/details/gt2rqmdydxv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2uwlllbsw.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gt2rsbxualm.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gt2fgqywvzl.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gt2yxgvmhqy.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gt2abqrsbtc.html

TypeScript ..... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2ifjfbtrv.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2fhifbnjn.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gt2ldyhcclx.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gt2ffdxhueu.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gt2uudfjdhm.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gt2pdqczpti.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gt2gwktfcpn.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gt2jwfeztas.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gt2yupparkc.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gt2nbuqfzwe.html

Swift .......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqsiqbbo.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gt2maqcxqsp.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gt2cvjrpzxw.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gt2wgtpekfn.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2hhifcabj.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gt2fvxibcyv.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gt2ikwvazhb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2phuutkct.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gt2lujazseq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdvqyoxc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gt2vksxnszb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gt2fwhcaxsx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2hwvxbvgp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2dsvifexq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2flfemkjh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2yazwwwxq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2fgszlwpf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2tjddgzde.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2druuiowm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2ujkopynk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.meibo888.top/Article/details/gt2pwqjuogr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnqzz.top/Article/details/gt2afeeqvvg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2holykrlt.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gt2suzxhzgq.html

R Bash 专题                             80
来源：http://dali.snrcjt.cn/Article/details/gt2hsyhvnqc.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gt2vwyucors.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gt2redbcptc.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2balgtqde.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2njszvglu.html

合计                                  2106 条
来源：http://dali.chenzaomai.com/Article/details/gt2rwabdmxl.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2hrgfozmg.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gt2alhgeccd.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2vycjzryo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hysaishi.cn/Article/details/gt2zdqnwqvr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gt2fipfwsrj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gt2zcwmjxvi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guowangkeji.top/Article/details/gt2iwewheaf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gt2gefzyueo.html

—— 文件结束 ——
来源：http://dali.yvedp.cn/Article/details/gt2ntwswkga.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gylpfzeb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gt2mgtndybb.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gt2symggxcj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2uijooryb.html

【收录内容】
来源：http://dali.sufxvd.cn/Article/details/gt2ftvtvius.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.haohaochexian.top/Article/details/gt2vdlhkaco.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gt2nnspcmzh.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gt2jqzrfiea.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gotoacloud.top/Article/details/gt2infsgdlg.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gt2hzklzzdm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgfzy.top/Article/details/gt2vqzvgwfl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gt2bhuipact.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gt2aquigwpf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gt2nwjjillk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fengsongda.top/Article/details/gt2dafgeqhw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gt2wjgnbeel.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ydzc1.top/Article/details/gt2nnbdlqqb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gt2inpavfei.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gt2ymbqcmwv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgfzy.top/Article/details/gt2feitczwv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmnzmokr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gt2softcfsw.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gt2ssimioxv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.smart0.xyz/Article/details/gt2jwhpmbls.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbcktgde.html

目  录
来源：http://dali.sxryk.cn/Article/details/gt2gvhpnmyd.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2erxenihe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gt2xobeafqa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gt2tgcyibmm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2voypfmtu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gt2oudiblek.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.redwolf501.top/Article/details/gt2kjvojlhc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gt2qldxbrxo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2vzntlnso.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gt2rzrotjop.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2ylqaeerv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2lnfxdent.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gt2clsoxpxs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2rqyczhdz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2tyigzxcf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ugjklfxp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gt2uxwadhnc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2wnnkfbmx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2mjwperwy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gzhubu.top/Article/details/gt2ccgbahir.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbmngisl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2ieeygmlc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2rhpgorab.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2woaffyha.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gt2vuewztqk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2skpsvrpx.html

[A01] Hello World
来源：http://dali.iojbl.cn/Article/details/gt2wylsbbjx.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gt2jayhcaml.html

PHP:  echo "Hello, World!";
来源：http://dali.9152youxi.cn/Article/details/gt2mbpbjiuv.html

JS:   console.log("Hello, World!");
来源：http://dali.sweek.top/Article/details/gt2tnwjgesh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2irisrjyy.html

Java: System.out.println("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2osgmcxhe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gt2eqvzihwz.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bivatsuz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gt2haggfhwz.html

[A02] 变量声明与赋值
来源：http://dali.daxiang520.top/Article/details/gt2ssmdmyue.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnxiangtu.top/Article/details/gt2agvaeibs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2eqmrrcmh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2awhjgriz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gt2idggwqjf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzuvlmp.html

Go:   name := "Alex"; age := 20
来源：http://dali.ehwqpu.com/Article/details/gt2tdtfswrd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zycfv.cn/Article/details/gt2jplqnmcv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lilvvcvq.html

[A03] 常量定义
来源：http://dali.316326.xyz/Article/details/gt2rnqpwctl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gt2ldfflvfj.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2pidotalb.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2mhjmlpxr.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crnfevwt.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2pqmpwayq.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njqdcaio.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gt2zkclfdpm.html

C#:   const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2epherwgl.html

[A04] 判断变量类型
来源：http://dali.smart0.xyz/Article/details/gt2chcnnglz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrvdfimg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.mhx1999.top/Article/details/gt2iuqzqdwt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ppjwa.cn/Article/details/gt2abjbndnw.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2eoidrtrm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yvedp.cn/Article/details/gt2nhhufoyz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guannengcc.top/Article/details/gt2zjytoqnb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gt2ztwwzikw.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gt2ecrlvvxh.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gt2yrvpnrfq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gt2rrpjmech.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2nkwzrnth.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2nkfoqodd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2nbowegsl.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2agxwlqoz.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2iydsekna.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbtnysxh.html

C#:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2fgmnsgxm.html

[A06] 字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gt2oxohlhlv.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gt2ijckwhme.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2sgnjesmz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ydzc1.top/Article/details/gt2nfcopjdn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkwzvcwt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zidqlmst.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gt2sebwejhl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj202588.top/Article/details/gt2cthxwooc.html


<!-- 参考信息 -->