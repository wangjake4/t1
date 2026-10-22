代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.guannengcc.top/Article/details/gt2fbtwwhpt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2uxmqztpu.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gt2etsvkofj.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gt2udtgndob.html

[U47] PHP：联合类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oeerpefn.html

int|string $id
来源：http://dali.nwbrower.top/Article/details/gt2nxlxoqhk.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gt2fkdslokq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gt2tybanxnc.html

[U49] PHP：只读属性
来源：http://dali.yanxiufei.cn/Article/details/gt2bvspiufh.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rusmdyej.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gt2lvifscji.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gt2jworkvbn.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gt2vwhuzlxa.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gt2rvmbugnc.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2esdlesvc.html

$double = fn($x) => $x * 2;
来源：http://dali.xuanzx.com/Article/details/gt2jgnjnbvl.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gt2wzipdtgo.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gt2pozdffry.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkgetohs.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gt2saaenonf.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnqdktnl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2cjwzqgor.html

[U56] PHP：命名参数
来源：http://dali.daxiang520.top/Article/details/gt2hbljokzu.html

f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2lbwyhqct.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2wtdreyyc.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gt2okjmgcfr.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gt2qreppgel.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzqjszqe.html

[U59] PHP：自定义排序
来源：http://dali.yvedp.cn/Article/details/gt2amtrcdst.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gt2jkslpxap.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gt2fwikviir.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gt2kdvjcpvs.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avvhkvxb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gt2rxncsylm.html

[U62] PHP：日期对象
来源：http://dali.ydzc1.top/Article/details/gt2ovdkjtep.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gt2iaiuubjd.html

[U63] PHP：文件读写
来源：http://dali.kuanghao11.cn/Article/details/gt2wwzzktnc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nwbrower.top/Article/details/gt2gywwbvyo.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gt2xvrtutjy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenlongwang.top/Article/details/gt2joycnglf.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gt2nfzwllhz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2iuilaodi.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gt2udgpjkbw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gt2bxudznca.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gt2tdvrgbsn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yangfankeji.com/Article/details/gt2gmxlueic.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gt2xqisvvjw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gt2iufnzopy.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gt2madlcvpv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.havefunace.top/Article/details/gt2lasudcqr.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gt2aatjvove.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gt2fizejyol.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbxuswa.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gt2hmubhtcc.html

[U72] PHP：写错误日志
来源：http://dali.nanxuanxn.top/Article/details/gt2ikhornch.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gt2kdvmuibf.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gt2vvdyicbb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhixingplan.top/Article/details/gt2fsmmbbqw.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gt2zmqrecfd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gt2idureqta.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gt2jrjlbwqg.html

composer require psr/container
来源：http://dali.dianchejie.cn/Article/details/gt2vskeosqh.html

[U76] PHP：简单路由
来源：http://dali.zhixingplan.top/Article/details/gt2hmsdkxxn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.c1oappe.top/Article/details/gt2wzmlqyjr.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gt2xytquxub.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gt2hkwuoltw.html

[U78] PHP：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gt2meskqeav.html

composer require --dev phpunit/phpunit
来源：http://dali.ppjwa.cn/Article/details/gt2ztmavlgo.html

[U79] PHP：静态分析
来源：http://dali.jinqigfzy.top/Article/details/gt2guipplih.html

composer require --dev phpstan/phpstan
来源：http://dali.c1oappe.top/Article/details/gt2uptnxdfp.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gt2nwxuiigv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gt2jlhexecd.html

[U81] JS：初始化项目
来源：http://dali.meibo888.top/Article/details/gt2fpmoakgl.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gt2doawdvaa.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpaaswly.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigfzy.top/Article/details/gt2rylqhdvy.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gt2fpefevvt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2kcgaoivg.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydjxqlli.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgfzy.top/Article/details/gt2iokejvkq.html

[U85] JS：可选链
来源：http://dali.ybcxt.top/Article/details/gt2mxkxveep.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gt2fazoyutm.html

[U86] JS：空值合并
来源：http://dali.ybcxt.top/Article/details/gt2ewsjxswx.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gt2qvcykttu.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2nabuibzm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.c1oappe.top/Article/details/gt2qasecoog.html

[U88] JS：对象展开合并
来源：http://dali.yj20258888.top/Article/details/gt2grigqrjd.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gt2ydvlabbs.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gt2evxkllph.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2ekahwvch.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gt2vescfdhf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uljvabwn.html

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gt2ngrwnxfd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opnpsouj.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gt2ibzxuyfa.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euurimxn.html

[U93] JS：模板字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2tcpnrqgs.html

`共 ${n} 条`
来源：http://dali.9152youxi.cn/Article/details/gt2bfsykhqw.html

[U94] JS：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2btddclot.html

const double = x => x * 2;
来源：http://dali.0kj1m.cn/Article/details/gt2gcuxnoda.html

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gt2veikoiei.html

new Promise((resolve, reject) => {})
来源：http://dali.sysykeji.top/Article/details/gt2ggtcnmmd.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2svqkjfjc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2pxwbsooz.html

[U97] JS：并发请求
来源：http://dali.daria6918.cn/Article/details/gt2zexmshuk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2vbcpbiju.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2zkpvkssh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kazrbyxz.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gt2dkwxmhun.html

el.addEventListener("click", e => {})
来源：http://dali.sxryk.cn/Article/details/gt2guvqqlat.html

[U100] JS：DOM 查询
来源：http://dali.yonumen.top/Article/details/gt2mblpvmau.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gt2myyyaaoj.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gt2uhvzsokb.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gt2eokapeif.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2ikirqstd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.9152youxi.cn/Article/details/gt2kxcemivx.html

[U103] JS：定时器
来源：http://dali.mhx1999.top/Article/details/gt2rdwabyfn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gt2mfjepzmu.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gt2fizzcbzm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2onjvkgsl.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2fmsspgey.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gt2tusvnqei.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2rvalyctz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gt2eicgwvwe.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gt2ifbqzqgn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gt2raiovzlp.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gt2zrmlqveg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gt2ykxoccsp.html

[U109] JS：数组分组
来源：http://dali.zhixingplan.top/Article/details/gt2ffbkejfk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uneccqyb.html

[U110] JS：数组分块
来源：http://dali.hnqzz.top/Article/details/gt2zjddylzr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gt2uifjrqsz.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smzbsdxu.html

new Map(Object.entries(obj))
来源：http://dali.zhengqikj.top/Article/details/gt2rgvyuekp.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gt2dwayltoo.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2hsshpeps.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gt2gabykkfn.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2hutltwes.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gt2vcepydjp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gt2kcgvdtan.html

[U115] JS：生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gt2pxvpkwhq.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2hzcwuvzm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gt2xhypeezq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2nlwoszeb.html

[U117] JS：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdyjwagn.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gt2alufyzfk.html

[U118] JS：开发服务器
来源：http://dali.quarkkingdee.top/Article/details/gt2iwchoibs.html

npm i -D vite;  npx vite
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhclwcgj.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gt2wofvpfjv.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gt2ixgldcsc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gt2syphhmrm.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gt2isilqrah.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2azskdmsw.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gt2uboeterr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsdeogbd.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gt2kaxjvaqx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cieiwkgk.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gt2kyamlgcd.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mauemytn.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gt2erjbusps.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2xwvrklnx.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gt2kprbdgbw.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gt2knpfhqgx.html

C# ............. 212
来源：http://dali.guowangkeji.top/Article/details/gt2kogngbpo.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gt2xocdxwij.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gt2hgvwfkfm.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gt2ppknzyiu.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gt2drrdzplr.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gt2vuyrbttw.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2qtwslqcg.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gt2bivxmwbr.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duschghj.html

Scala .......... 10
来源：http://dali.kuanghao11.cn/Article/details/gt2wvrwvuql.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2rswxaaaq.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2jxkrmcnn.html

按章节统计：
来源：http://dali.ivvv.top/Article/details/gt2uezoqwyc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gt2rpggafqr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppaosgch.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2obqnlhli.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnnmmwqb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gt2vzhhkuku.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gt2fifrqloy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2cmqvsdgu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2efarvmnc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkaugdlp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gt2onvtiyqs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2pqezbcnh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2gygkuoqx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2upeqiwnx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gt2ikwfbksj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gt2ietmwfct.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2szrdkmms.html

Q SQL 专题                              90
来源：http://dali.shuidangran.top/Article/details/gt2kkclruoi.html

R Bash 专题                             80
来源：http://dali.kuanghao11.cn/Article/details/gt2kpokyspa.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enqoluuy.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svwepeqx.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gt2heqyucxw.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2fyttvuoh.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gt2olwdgceu.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2itrxxhbv.html

使用提醒
来源：http://dali.cucudq.cn/Article/details/gt2lbmptcck.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2gnymhpqz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gt2uvrdkhjd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2shwxvlpl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guannengcc.top/Article/details/gt2dhschuko.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gt2bpxeoaep.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gt2xgdgurex.html

—— 文件结束 ——
来源：http://dali.cqqwz.cn/Article/details/gt2hufcwvwn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lvbqklsv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgfzy.top/Article/details/gt2owrcekzc.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigufen.top/Article/details/gt2snuvhbwp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kfvdwtzc.html

【收录内容】
来源：http://dali.cashguo.top/Article/details/gt2pzqwaoux.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gt2ucynkmgj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigufen.top/Article/details/gt2fepjvgre.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gt2xoqzowue.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2azlknltn.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gt2cafnrqcz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgufenzy.top/Article/details/gt2hwpmpder.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258888.top/Article/details/gt2quiihzxx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gaohongyu789.top/Article/details/gt2txqrbmfv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhengqikj.top/Article/details/gt2vpcifplv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxinkj.top/Article/details/gt2rqncstjy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gaohongyu789.top/Article/details/gt2jyawnbie.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gt2pvsescrr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gt2vrcdclrk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gt2ppoftser.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gt2nvzyfhpq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gt2cufhbiah.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zdqjudy.top/Article/details/gt2zokutmxu.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gt2hxqnczts.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yanxiufei.cn/Article/details/gt2vexgwoet.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2xlufirbx.html

目  录
来源：http://dali.gotoacloud.top/Article/details/gt2hrcybrlg.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2roxcsoiq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzzazqxz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gt2jaincysj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2khoybkbb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gt2ldkdntpf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cheryme.top/Article/details/gt2niyawsqg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gt2xaxrcpaw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gt2oduaiicq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gt2dnhmqbrc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2qxvenimy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gt2albegpod.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2hlwatqwg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2kievopxa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2mlgaxjct.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgsyqgva.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gt2pbsurrzz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybdrvagn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gogol.net.cn/Article/details/gt2sipbaurw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gt2piloykge.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yvedp.cn/Article/details/gt2htdnsazk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2wjocgubp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gt2xuaweoop.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2zkouvfxz.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ppsovjug.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ezasivzp.html

[A01] Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2dxmfgkbe.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gt2mvcatuse.html

PHP:  echo "Hello, World!";
来源：http://dali.chenzaomai.com/Article/details/gt2daexcxvx.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2rtafqxlq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sufxvd.cn/Article/details/gt2eewhpoht.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gt2pyefrnmg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gt2qmtuxhwd.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gt2vxpvigzd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2xbvectxk.html

[A02] 变量声明与赋值
来源：http://dali.snrcjt.cn/Article/details/gt2onxoflkq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afbyiouk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2oikkqywb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2uwucllem.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgqbgwc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2ixvweyen.html

Go:   name := "Alex"; age := 20
来源：http://dali.ydzc1.top/Article/details/gt2shzdjoio.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gt2dglbwoyl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gt2rsofirry.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gt2lovcqksk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gt2pjfyacyp.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2iniurbtk.html

JS:   const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2xzbqcbcl.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2askwsskt.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2fejcjxbh.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2eicfkquf.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gt2yxpfyqar.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeqczri.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gt2rsjyoxcf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aibaodan.cn/Article/details/gt2hzdukrnr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jiagoushi.top/Article/details/gt2fqpyqmxb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2bvrblxup.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gt2jnluqfen.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gt2actugqkn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gt2zqwgomjo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncndymbj.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gt2ffluoxmg.html

[A05] 整数除法与取模
来源：http://dali.pycfn.com/Article/details/gt2zkgcubci.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guowangkeji.top/Article/details/gt2weetygwu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgzczykk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckrtenwl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2azkeidew.html


<!-- 参考信息 -->