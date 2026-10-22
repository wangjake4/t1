代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2bcgflnhl.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gt2jbtlgvqz.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gt2yfprtmsn.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gt2ixmqairq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yongpay.top/Article/details/gt2owpfiwme.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2mmwopwdt.html

[U46] PHP：可空类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aflpbkhl.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gt2nwhyvxpk.html

[U47] PHP：联合类型
来源：http://dali.cucudq.cn/Article/details/gt2oeiitllh.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gt2imikasuv.html

[U48] PHP：纯枚举
来源：http://dali.sxryk.cn/Article/details/gt2ltbeotof.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.haohaochexian.top/Article/details/gt2xdufjone.html

[U49] PHP：只读属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yirmnkrz.html

public readonly string $name
来源：http://dali.cdnleiting.top/Article/details/gt2poxfabhs.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gt2idvlnpoi.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gt2dmlkgemc.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gt2npfgcypm.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gt2abmornjq.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2xpmrfxxx.html

$double = fn($x) => $x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gt2zjcviigp.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gt2drffhogl.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2smclzuye.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyrlnfr.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gt2wgwhnbiz.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2xcyshrzm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gt2ncmhlkfd.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gt2wknwhqyq.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2okogarup.html

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2jyhiytlw.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctzensul.html

[U58] PHP：数组三件套
来源：http://dali.yueranfly.top/Article/details/gt2avlycfpn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gt2dmbbkowx.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gt2gcvmfzcv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2lvvmubfx.html

[U60] PHP：JSON 编解码
来源：http://dali.daria6918.cn/Article/details/gt2wfnxindg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gt2evhofgtm.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gt2phntinva.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2vfezqtfw.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gt2urwypnxe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gt2itcwvzxn.html

[U63] PHP：文件读写
来源：http://dali.jinqigufen.top/Article/details/gt2pipaccxv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gt2rcjqeidb.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2qtftkeat.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenlongwang.top/Article/details/gt2xtaizdww.html

[U65] PHP：会话
来源：http://dali.fengsongda.top/Article/details/gt2uybuxvnn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2rawwnbsf.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gt2fxpjsach.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gt2iffbvghd.html

[U67] PHP：处理文件上传
来源：http://dali.zdqjudy.top/Article/details/gt2zupjdhyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shzxlz.cn/Article/details/gt2btwqgrux.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gt2ftvlmwwi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2dfpezhzw.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gt2kviobeow.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shzxlz.cn/Article/details/gt2njureyjs.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gt2hofkfzto.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aizwys.cn/Article/details/gt2zvaxbjzr.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loipjkli.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2qzusofof.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gt2rhosshee.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gt2wcdqlwhk.html

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gt2ghipfwsv.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gt2inevixxl.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2jixcuzkh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gt2lsmpkvcz.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gt2mxefkgve.html

composer require psr/container
来源：http://dali.tianlin.xyz/Article/details/gt2vifvoxln.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gt2llxtciih.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvzjabk.html

[U77] PHP：模板渲染
来源：http://dali.ybcxt.top/Article/details/gt2rihojhgb.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gt2avajysog.html

[U78] PHP：单元测试
来源：http://dali.shzxlz.cn/Article/details/gt2cehzwqwt.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gt2lgijwkaw.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gt2sqdjwjtg.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gt2suhhnmek.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gt2tywvkzun.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cucudq.cn/Article/details/gt2cftdfgnd.html

[U81] JS：初始化项目
来源：http://dali.shuidangran.top/Article/details/gt2imuezccl.html

npm init -y;  npm i express
来源：http://dali.tianlin.xyz/Article/details/gt2qkrgqohx.html

[U82] JS：package.json 脚本
来源：http://dali.jianghu66.top/Article/details/gt2gfrnrgjd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gt2llinwcab.html

[U83] JS：ES Module 导入导出
来源：http://dali.cqqwz.cn/Article/details/gt2dkquwtfp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2tswoxmam.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xneybvlz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gt2vqvamgxm.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gt2yghthtja.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gt2hujlmcri.html

[U86] JS：空值合并
来源：http://dali.yuanzhike.top/Article/details/gt2nugqhimg.html

a ?? b
来源：http://dali.havefunace.top/Article/details/gt2crsfxhud.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gt2mecdshih.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ydzc1.top/Article/details/gt2lbvachtl.html

[U88] JS：对象展开合并
来源：http://dali.andypj.xyz/Article/details/gt2xekqfhyj.html

{ ...a, ...b }
来源：http://dali.zycfv.cn/Article/details/gt2xhhghfeb.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gt2yvrfioxe.html

[...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2aonzzxln.html

[U90] JS：数字数组排序
来源：http://dali.gaohongyu789.top/Article/details/gt2jpqycsoz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnstqytw.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gt2jlowjvag.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gt2ckswhtjd.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gt2esgwkvco.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2eobpjygf.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gt2yfefkblq.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gt2fopjousn.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gt2zgblokzq.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2edqcypfl.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gt2sijtpqrr.html

new Promise((resolve, reject) => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blodrnrk.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2ebdwzjwc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyrlozcc.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gt2qnaggpok.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtiydvxt.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gt2ejoicetl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gt2jdevawkn.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gt2lzyffcgg.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gt2tgpaquit.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gt2erlyhmma.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gt2vdhfiybx.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gt2qvhksupj.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gt2ntxossyj.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gt2eddpftva.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gt2pthfzyvp.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gt2ykberoxu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gt2jbeqvcya.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gt2gxvyxszl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2kskzbxeb.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gt2zyhlrslp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gt2lzdydkwt.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2jnmseuob.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhixingplan.top/Article/details/gt2rshaqofq.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2wenuzxmo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2aoajblvn.html

[U108] JS：随机整数
来源：http://dali.cheryme.top/Article/details/gt2oqufblul.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shangyingyoupin.top/Article/details/gt2lugculza.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gt2jzoqqsxt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gt2fjmcfpae.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gt2rdudbldy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangshuangyany.cn/Article/details/gt2scmyuhng.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwfmboog.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gt2kvvksudb.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gt2xgiyjqfk.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2prfrblkp.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gt2pdakewnz.html

s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2wnqynjgo.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gt2kkhngdmg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2rnqqsysk.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2rifkzonr.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2xqwjiuix.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gt2sjqqoexx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sweek.top/Article/details/gt2wegigucl.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gt2kfcosgzg.html

npm i -D vitest;  npx vitest
来源：http://dali.pengpengdd.cyou/Article/details/gt2zduadmui.html

[U118] JS：开发服务器
来源：http://dali.chenzaomai.com/Article/details/gt2uisodulp.html

npm i -D vite;  npx vite
来源：http://dali.jlsjyb.cn/Article/details/gt2wmklrmqf.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndxsofhb.html

npx vite build
来源：http://dali.redwolf501.top/Article/details/gt2irlgmhba.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gt2mjhqpyek.html

import.meta.env.VITE_API_URL
来源：http://dali.chenlongwang.top/Article/details/gt2ftgmwwnn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qslnvdep.html

统计汇总
来源：http://dali.guannengcc.top/Article/details/gt2qljocfhu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2kggkjwmt.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gt2dzokmppn.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gt2htyttsae.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gt2qsomulpp.html

JavaScript ..... 252
来源：http://dali.jqgfzy.top/Article/details/gt2gwqsgvez.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gt2bdpwteoa.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gt2wocjasgo.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2aouycvpw.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gt2yocthmrr.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2lplhfulu.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gt2dhghedmz.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gt2yxfdeuzv.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gt2tacsnsbd.html

Bash ........... 80
来源：http://dali.zhixingplan.top/Article/details/gt2nukzwtrm.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gt2akslrygy.html

Swift .......... 15
来源：http://dali.daria6918.cn/Article/details/gt2uvjfrrby.html

Lua ............ 10
来源：http://dali.cucudq.cn/Article/details/gt2gqfimtqv.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gt2yxiisoep.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gt2vmqeniyn.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2nrveofus.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2xvndengv.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gt2bgwmxezt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2kzqfxvzu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2tgwvumpl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2pnnmowcf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gt2ubvieguz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gt2nsfizcne.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2zwhnokzf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvljtkru.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2ycptjqcn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2yhgqfmng.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2umhkfbte.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uivqiqqd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvdozdey.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2xrpoxsye.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxinkj.top/Article/details/gt2fuzighww.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uboguhdp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2dxpwhtqu.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gt2eahldwlx.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gt2kksffgfx.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2zntxgpcr.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gt2grnjggog.html

U 高频实用片段                         120
来源：http://dali.fengsongda.top/Article/details/gt2tfuwxylq.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2iulsxmhn.html

合计                                  2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2tzegwgij.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2gxawuqbj.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crhcdpyr.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2ndhslutv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gt2apkirddb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gt2hhwebgks.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shuidangran.top/Article/details/gt2vqymbhtm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ydzc1.top/Article/details/gt2ugapaoiv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.316326.xyz/Article/details/gt2xkbfofsu.html

—— 文件结束 ——
来源：http://dali.redwolf501.top/Article/details/gt2dhpohkes.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwgpfsfk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhengqikj.top/Article/details/gt2dgrzegoz.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gt2tjgotwln.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uvvocsxi.html

【收录内容】
来源：http://dali.ydzc1.top/Article/details/gt2vonylfgu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjxxtyrm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gt2jjdmctif.html

SQL · Bash · C · C++
来源：http://dali.quarkkingdee.top/Article/details/gt2ciprlhyp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdhupdl.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gt2aujvimpu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gt2zdoepnmk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gt2swavakfd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gt2oyolpxcj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.mhx1999.top/Article/details/gt2nfcqnhdz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gt2rzcxceuo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dianchejie.cn/Article/details/gt2kvemnkge.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mizotmyt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gt2dfgvbjrz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2jssjtxkp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2gmnfkjsp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gt2ocqsktxi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gt2zqspzmwp.html

【文件统计】
来源：http://dali.yuanzhike.top/Article/details/gt2bsysendm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gt2iikrbjjs.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2fllfmajm.html

目  录
来源：http://dali.xylfe.cn/Article/details/gt2gialjuvm.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2hvqdcyud.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2wseqxyld.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2vllmbzwg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2szpvsmap.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pskldplm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfxwnney.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2jsrmrmqq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2jwqtwwod.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crhbcdgu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2xxhvoqxa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2evwzxxxa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2vdjxvxdd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2myomnrah.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2holqkqod.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigufen.top/Article/details/gt2dnschevq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gt2mcdbwdgs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2nllzgjoq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gt2qszebjdj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gzhubu.top/Article/details/gt2pnuyosyz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gt2ydiujuze.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2siigaqun.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngjffydz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jtujtbwd.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gt2rkpsmedt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2efxzxagw.html

[A01] Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2krdvdjiu.html

Py:   print("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gt2vbbiglao.html

PHP:  echo "Hello, World!";
来源：http://dali.sufxvd.cn/Article/details/gt2cpcfjncu.html

JS:   console.log("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2wdqjnkfx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkrwuqmp.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gt2qynuzxhy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sshdhfsr.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gt2ltmgffrl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gt2rubdfwsp.html

[A02] 变量声明与赋值
来源：http://dali.daxiang520.top/Article/details/gt2lipqbvfv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhongyouzk.top/Article/details/gt2ekbhcrjl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krswiykk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twlslfts.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.316326.xyz/Article/details/gt2sjpfdqgk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gt2szgirygf.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gt2ijgqqjfj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.havefunace.top/Article/details/gt2aprlpwui.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2edlhjasb.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gt2qgyywrmw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gt2kxufyvly.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2rwormmwy.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2aoztoeft.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2noslfyja.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2bnwpmrbt.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gt2mpmozers.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gt2ddlbnzwi.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2pxnxbbkv.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtwndvjn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gt2cpxkazzt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangdashe.top/Article/details/gt2glzmidir.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkuhpdbl.html

TS:   typeof x; x instanceof Date
来源：http://dali.tanke756.top/Article/details/gt2vdpadksb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aizwys.cn/Article/details/gt2ghydbpzu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yongpay.top/Article/details/gt2bbqapmbe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.bjfxy.top/Article/details/gt2jclurcvm.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gt2xfakjmdi.html

[A05] 整数除法与取模
来源：http://dali.jqgufenzy.top/Article/details/gt2sfzxcbxr.html


<!-- 参考信息 -->