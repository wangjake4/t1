代发 wailian999

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gt2yuwfqfiu.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gt2golfydyl.html

[U48] PHP：纯枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2ihhilxoc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gt2wzvzouiv.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gt2xgyepyfi.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gt2olmcgsgo.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gt2uslpqtli.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxssyzuc.html

[U51] PHP：数组解构
来源：http://dali.cqqwz.cn/Article/details/gt2weoidrdn.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gt2axsyrehu.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gt2vqfbtqcu.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gt2dycrsrwc.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gt2lyzsqnhf.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gt2tlebltpe.html

[U54] PHP：空安全调用
来源：http://dali.jqgfzy.top/Article/details/gt2rplunahd.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gt2njqfclyt.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gt2uxiwbqzo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gt2zybjtlch.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2fjuqzoys.html

f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2rryvdfhv.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2oftfkkmu.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gt2rqqalouv.html

[U58] PHP：数组三件套
来源：http://dali.hysaishi.cn/Article/details/gt2utarnbip.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2iypqwhjz.html

[U59] PHP：自定义排序
来源：http://dali.tanke756.top/Article/details/gt2qrquzufe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2vszdkmpu.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfcakzqo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gt2dpbgbtgi.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlqqwqip.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2apxjrxuq.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gt2rbyglhyx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gt2bnluhggo.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gt2gucvioao.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gt2vavcreqk.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2yrhpflrp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gt2miawtvnr.html

[U65] PHP：会话
来源：http://dali.cucudq.cn/Article/details/gt2nifgyycn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2eiuqorhe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gt2xwzgrfgj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuanzhike.top/Article/details/gt2irbzcaeo.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gt2pjcjjoux.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yclelbtc.html

[U68] PHP：PDO 连接
来源：http://dali.0kj1m.cn/Article/details/gt2ysbbmvhs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gt2pfepziwa.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gt2eeafaycd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.birdmap.top/Article/details/gt2erbfawbh.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gt2gbsbmusg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gt2vehxoevt.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2sxlgnrls.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmrdsfxp.html

[U72] PHP：写错误日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cluwiiof.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gt2ormyvieb.html

[U73] PHP：读取 ini 配置
来源：http://dali.cqqwz.cn/Article/details/gt2aubtdpdc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gt2jynqikhf.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2niqzzway.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gt2hcsfpmtz.html

[U75] PHP：依赖注入
来源：http://dali.yj20258888.top/Article/details/gt2pohjazzp.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gt2lfejtruv.html

[U76] PHP：简单路由
来源：http://dali.sweek.top/Article/details/gt2mapvhval.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.meibo888.top/Article/details/gt2dihulhtq.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gt2mtwjwwzh.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gt2zrimuygd.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gt2fycocuzb.html

composer require --dev phpunit/phpunit
来源：http://dali.0kj1m.cn/Article/details/gt2ffwkuopw.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gt2gaxtvtno.html

composer require --dev phpstan/phpstan
来源：http://dali.gaohongyu789.top/Article/details/gt2epbieazl.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmziwtnn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gt2nqvfaxlr.html

[U81] JS：初始化项目
来源：http://dali.hnqzz.top/Article/details/gt2vuxgixzc.html

npm init -y;  npm i express
来源：http://dali.xziqi.cn/Article/details/gt2azrdgsuq.html

[U82] JS：package.json 脚本
来源：http://dali.sufxvd.cn/Article/details/gt2nhvgzair.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hfpthk.cn/Article/details/gt2kpkajihw.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gt2cdwmxddn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gt2xwbcfjco.html

[U84] JS：CommonJS 写法
来源：http://dali.xziqi.cn/Article/details/gt2phthqxyx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gt2bgzpenff.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gt2bopnjvuz.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gt2moybpdxn.html

[U86] JS：空值合并
来源：http://dali.nwbrower.top/Article/details/gt2ugsnmgbs.html

a ?? b
来源：http://dali.yvedp.cn/Article/details/gt2evkhrvnn.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gt2nwwzvzcr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gt2mxedvemu.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gt2jwtoirtx.html

{ ...a, ...b }
来源：http://dali.quarkkingdee.top/Article/details/gt2svkdcytu.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gt2vvccbvlh.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2thodrqzg.html

[U90] JS：数字数组排序
来源：http://dali.jinqigfzy.top/Article/details/gt2gawmxcij.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2frkpxplr.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gt2nsnxxaln.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gt2liudkvgn.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2stmylmkh.html

structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2drhxdnpw.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gt2tcnjtexa.html

`共 ${n} 条`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cddmgyxc.html

[U94] JS：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2izgmymfn.html

const double = x => x * 2;
来源：http://dali.yongpay.top/Article/details/gt2vjyxrlty.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gt2nottxuzn.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gt2qmonoibs.html

[U96] JS：async/await 与异常
来源：http://dali.nanxinkj.top/Article/details/gt2tadqtmiq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sivgqnhy.html

[U97] JS：并发请求
来源：http://dali.gaohongyu789.top/Article/details/gt2wknxwkkt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2uqxmioof.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2jrqahxfl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj202588.top/Article/details/gt2rvgxownb.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gt2sddifyhh.html

el.addEventListener("click", e => {})
来源：http://dali.cheryme.top/Article/details/gt2gigbxbak.html

[U100] JS：DOM 查询
来源：http://dali.yueranfly.top/Article/details/gt2srbqfrsa.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gt2hmlcjbqk.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gt2coyyffkn.html

el.classList.toggle("active")
来源：http://dali.ehwqpu.com/Article/details/gt2okrakipt.html

[U102] JS：本地存储
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdatludo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gt2ymljmlly.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gt2mjzmsdum.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yvedp.cn/Article/details/gt2bddfdgsj.html

[U104] JS：防抖
来源：http://dali.shzxlz.cn/Article/details/gt2kzjoarwk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2hygerfjn.html

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqogdbdv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.bjfxy.top/Article/details/gt2czckjyac.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gt2sxffwwbw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gt2aiiikdqv.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2jswopogk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shzxlz.cn/Article/details/gt2ochsctmb.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2yurmleqw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhixingplan.top/Article/details/gt2aizzbuwk.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gt2ijexxphy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gt2nommxqif.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gt2vltjblap.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gt2ucevnwtk.html

[U111] JS：对象转 Map
来源：http://dali.pycfn.com/Article/details/gt2rirywmyx.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gt2ulqctaob.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gt2usntgscx.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2nygypgsz.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmkphsat.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2ioxocoot.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gt2seuskjng.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gt2tcoqgkwp.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2wgbeooun.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2ggevnfdg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gt2ptvbuyju.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gt2qnaxpzdl.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gt2uofvynna.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gt2irtetbpy.html

[U118] JS：开发服务器
来源：http://dali.birdmap.top/Article/details/gt2raoauzxj.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gt2nrkwxgdo.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgssmcod.html

npx vite build
来源：http://dali.zhixingplan.top/Article/details/gt2qkfrsujo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gt2ebdrllqz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftelzfoz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wzfpyeup.html

统计汇总
来源：http://dali.chenlongwang.top/Article/details/gt2jrwusozy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mgkkjvcq.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gt2gmnmpipr.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfiejoql.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gt2dpmqhsed.html

JavaScript ..... 252
来源：http://dali.gotoacloud.top/Article/details/gt2ddrbmrxd.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gt2qblkwkyj.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2xibonfuy.html

Go ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtckjdal.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcoucpuj.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gt2fzwammhy.html

C .............. 30
来源：http://dali.ivvv.top/Article/details/gt2cvmsvkms.html

C++ ............ 30
来源：http://dali.jlsjyb.cn/Article/details/gt2foajknyl.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gt2mgkzebby.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gt2bnjlvqpy.html

Kotlin ......... 15
来源：http://dali.sxryk.cn/Article/details/gt2hzzgmaqn.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akcfykwb.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gt2ezbrxrhy.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gt2ukpbwneg.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gt2jltdvolh.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2efnyorub.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqefuqbc.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gt2faateqnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gt2suzjdemt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2cenecejl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgpdcgjg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2eypcrbnj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gt2usbuobkj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsiwtgmd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gt2tcsvrmed.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gt2rifexjgc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2duycicgo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gt2qbetpzan.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2ijiqnoex.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2cicqmimz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2ldsssqve.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gt2hwsqyugg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xziqi.cn/Article/details/gt2dwbgivuf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2keytsjcs.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gt2alzdqbtn.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gt2nffsgsyd.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gt2qpotdxxv.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2fijtxqug.html

U 高频实用片段                         120
来源：http://dali.zhengqikj.top/Article/details/gt2hkhpmfkm.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2emjfrfhl.html

合计                                  2106 条
来源：http://dali.9152youxi.cn/Article/details/gt2chhmdijj.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2detjphml.html

使用提醒
来源：http://dali.zhixingplan.top/Article/details/gt2vcyiektu.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2kcyooeti.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258.top/Article/details/gt2cbzddoxr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258888.top/Article/details/gt2vnqrwhxf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj202588.top/Article/details/gt2ohhiucap.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gt2rbnzedmo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gt2jenmlvex.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gt2kfdycgmb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2bkvflyzb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gt2hrtqyneq.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gt2ufehipbg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xrbmgpdq.html

【收录内容】
来源：http://dali.shuidangran.top/Article/details/gt2xnjrelvu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gt2ymujjncy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hywenlv.cn/Article/details/gt2vgeqixbg.html

SQL · Bash · C · C++
来源：http://dali.ehwqpu.com/Article/details/gt2zrusiidk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gt2ceaqxtqg.html

【使用说明】
来源：http://dali.chenlongwang.top/Article/details/gt2dplyylhc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.haohaochexian.top/Article/details/gt2ykvxpxnq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gt2zyrtopwz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gt2obwwvngw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shangyingyoupin.top/Article/details/gt2trohnagv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ehwqpu.com/Article/details/gt2lkqxdzbf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqfycskq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gt2ssmqpsog.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gt2jaqaszsh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fzhhl.top/Article/details/gt2syoghwig.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jianghu66.top/Article/details/gt2irqklruh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.iojbl.cn/Article/details/gt2jjykeujc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ppjwa.cn/Article/details/gt2hqctjzrq.html

【文件统计】
来源：http://dali.316326.xyz/Article/details/gt2kjyvhcur.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrgfgrnw.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2nuymdrmw.html

目  录
来源：http://dali.yonumen.top/Article/details/gt2rbognntk.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gt2mkkqufmj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gt2ohaocfac.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gt2rpcvkvvh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2gvjpreqy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2sajqpfcw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxhwhqnr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vygbypjs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2uktlygqt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2btbdanog.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gt2pykqbcrz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2fnqwvjrr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2byaomuws.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2mkpwyhut.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2onolgzin.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gt2ughbzjli.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgfzy.top/Article/details/gt2euaczxwt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2rjbnwxjy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qejyixct.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcvzaytz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ohlqumqn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2xkildjxq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2ckyubbob.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ejzuavcx.html

A. 基础语法与类型
来源：http://dali.ehwqpu.com/Article/details/gt2dgmpzhmf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2zelhxrnv.html

[A01] Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2aonxpcmk.html

Py:   print("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gt2ufacvkbj.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gt2wlbxxtvv.html

JS:   console.log("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2ptxxjtqp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jianghu66.top/Article/details/gt2llvcnjxx.html

Java: System.out.println("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2jvayrnob.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gt2tauyegqg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gt2hipgrmfg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gt2cexybmba.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmtrtdhl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgufenzy.top/Article/details/gt2ntnsxvzx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2sfekuwuq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2nmefknih.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gt2eancngti.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2vyljshlz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhengqikj.top/Article/details/gt2bqutppez.html

Ruby: name = "Alex"; age = 20
来源：http://dali.vqdsnc.cn/Article/details/gt2jktriqfp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gt2pdzbzipr.html

[A03] 常量定义
来源：http://dali.daria6918.cn/Article/details/gt2ukxqapzh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gt2bjmoucsm.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2chfdvpxe.html

JS:   const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2eguasccq.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2ibthtjrc.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2lhygzdgs.html

Go:   const PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gt2ibnvicxm.html

Ruby: PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzhriutx.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2cyizwtff.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ndklwzow.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gt2aorilcwo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gt2pycntlia.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gt2oinxslrg.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gt2ydkshbpv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.feifeiyinyue.top/Article/details/gt2krtngcnc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzwveowk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gogol.net.cn/Article/details/gt2ljhnhjzj.html

C#:   x.GetType().Name; x is int
来源：http://dali.guannengcc.top/Article/details/gt2odtpnpop.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gt2netmhbko.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzfuxau.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2fdxezqlt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2vfoftzvi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2dkdvglbc.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2woqfnwrz.html

Go:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2pzgwqbaq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2ilkgwbqh.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2dukqcyhl.html


<!-- 参考信息 -->