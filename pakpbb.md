代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gt2pbxcijhx.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gt2odnmtnip.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gt2addqhslz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gt2xyaazyvt.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gt2vlbpdxnt.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gt2nbpqdaqj.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gt2zstovxsz.html

public function __construct(private int $id) {}
来源：http://dali.iojbl.cn/Article/details/gt2vohfdcgw.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gt2wclkdyre.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gt2ebbgegjv.html

[U52] PHP：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gt2ehizbncb.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gt2befqomdi.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gt2nwxrlpqz.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuxming.cn/Article/details/gt2jvkkjkhf.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gt2iltnfaqb.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gt2rqjlusll.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2lhzrasjn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gt2ekgrjqor.html

[U56] PHP：命名参数
来源：http://dali.fengsongda.top/Article/details/gt2ckpkners.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2qalisaqw.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2outiwibb.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gt2jpmvsxml.html

[U58] PHP：数组三件套
来源：http://dali.fzhhl.top/Article/details/gt2pebynuys.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zriiumdq.html

[U59] PHP：自定义排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozqsnmdw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2rmixfcwu.html

[U60] PHP：JSON 编解码
来源：http://dali.yj202588.top/Article/details/gt2nrqwsbja.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gt2lkjopzwb.html

[U61] PHP：正则
来源：http://dali.tanke756.top/Article/details/gt2vwlndrra.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2iawldvwo.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gt2apwlhgcm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuanzx.com/Article/details/gt2gmsefpek.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gt2pygalmbd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yongpay.top/Article/details/gt2axavpirs.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2lmxrjpff.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigufen.top/Article/details/gt2fgzoypzt.html

[U65] PHP：会话
来源：http://dali.jlsjyb.cn/Article/details/gt2pyhfxhhd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2muxwevzf.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gt2jvlpwoon.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gt2vuhfyhka.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gt2mvvyctls.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnakyzcm.html

[U68] PHP：PDO 连接
来源：http://dali.jlsjyb.cn/Article/details/gt2jaisoqte.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gt2earzqrvm.html

[U69] PHP：PDO 预处理
来源：http://dali.yangfankeji.com/Article/details/gt2kanofazy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gt2palwhbyg.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gt2kkgeectt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aizwys.cn/Article/details/gt2vwadbtrb.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gt2ydoephly.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gt2zwgmlxgo.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gt2fckezpea.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gt2oihzpyqv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okcxfnrt.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gt2xixpfcyv.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2kqqeclwl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gt2oafbatul.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gt2hkgfjctp.html

composer require psr/container
来源：http://dali.jlsjyb.cn/Article/details/gt2zrdgcdxx.html

[U76] PHP：简单路由
来源：http://dali.bjfxy.top/Article/details/gt2dyvvaayt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gt2enfnfyct.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gt2riuqizvn.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gt2tcftalyr.html

[U78] PHP：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2peiqksaw.html

composer require --dev phpunit/phpunit
来源：http://dali.daxiang520.top/Article/details/gt2aglfpjby.html

[U79] PHP：静态分析
来源：http://dali.c1oappe.top/Article/details/gt2tgqrwfis.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqzmmdyl.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gt2acgikvyt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftbqflpd.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gt2bucdyqky.html

npm init -y;  npm i express
来源：http://dali.chenzaomai.com/Article/details/gt2pvaiufgk.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gt2ydsorjqb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.meibo888.top/Article/details/gt2nlaonmbt.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gt2cmxuatac.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gt2stvpkgqo.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gt2qvluvkqx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gt2qnvlveso.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gt2dxgtheiw.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2bqawiqgl.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gt2ejornets.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gt2yyjnthyc.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gt2fdvqlvck.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwxqtzxp.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gt2ihiaprpy.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gt2gnubsjsk.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gt2qepktsne.html

[...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhrytrrg.html

[U90] JS：数字数组排序
来源：http://dali.nanxinkj.top/Article/details/gt2ftpaqnhm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2khkkcujy.html

[U91] JS：对象键值遍历
来源：http://dali.yuxming.cn/Article/details/gt2jwndutfu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gt2kqakhrwx.html

[U92] JS：深拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2mckkphke.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2vonatwqc.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gt2xlonniir.html

`共 ${n} 条`
来源：http://dali.hnqzz.top/Article/details/gt2qnjtwcyo.html

[U94] JS：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gt2terjifty.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gt2qdkqfcpc.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuombjjj.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gt2dcgowfqi.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2qphmeuxg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2veyhqntv.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gt2vvhbhbjd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2qrfuooom.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gt2uhlogocf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gt2oxzjnkmg.html

[U99] JS：事件监听
来源：http://dali.zdqjudy.top/Article/details/gt2rigpzeog.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gt2goveckak.html

[U100] JS：DOM 查询
来源：http://dali.vqdsnc.cn/Article/details/gt2qyyzhjhq.html

document.querySelector(".item")
来源：http://dali.zhongyouzk.top/Article/details/gt2orkbcqpi.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gt2yvhiwsiw.html

el.classList.toggle("active")
来源：http://dali.hfpthk.cn/Article/details/gt2smtxqwkv.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gt2upbifrgo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hfpthk.cn/Article/details/gt2xqxprzng.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2holounvk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gt2yluvmqzn.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gt2upupozur.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjsjpuno.html

[U105] JS：节流
来源：http://dali.smart0.xyz/Article/details/gt2qjmpiqhq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gt2bnyfuros.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2yhlmgeax.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gt2pechmdlq.html

[U107] JS：数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjubkspr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gt2xhvyoouf.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gt2vwnxjmab.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gt2yoypbikv.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gt2qhethnhd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2qevsslgb.html

[U110] JS：数组分块
来源：http://dali.guowangkeji.top/Article/details/gt2kpmqwpuq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gt2qlgkzvss.html

[U111] JS：对象转 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2uzrobnso.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gt2arizwbjl.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gt2wfxcedwl.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2ibpyjbrm.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gt2dnklbpos.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2zlbkfdas.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gt2ubfxqfsb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gt2ymezcjsm.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2crsmeuqq.html

crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2eruayllt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.quarkkingdee.top/Article/details/gt2fayizplv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibrmdqqf.html

[U117] JS：单元测试
来源：http://dali.snrcjt.cn/Article/details/gt2yppsumpz.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gt2pkntibvc.html

[U118] JS：开发服务器
来源：http://dali.fengsongda.top/Article/details/gt2jpwgoule.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gt2xrffjbqu.html

[U119] JS：生产构建
来源：http://dali.jinqigufen.top/Article/details/gt2winrnjzb.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gt2knztvzwz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gt2dtyyidxz.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgyqndjp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmrtugoo.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gt2mjwpesuw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yuzbifkz.html

按语言统计（条）：
来源：http://dali.jqgfzy.top/Article/details/gt2qusxbgcj.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbvgzhdr.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gt2upavpsba.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gt2rlythdzp.html

TypeScript ..... 212
来源：http://dali.cashguo.top/Article/details/gt2xdpnvylz.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gt2ylquhtvt.html

Go ............. 212
来源：http://dali.yj202588.top/Article/details/gt2rustygea.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2fnqddgxg.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gt2yvjpscyh.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anxsnssh.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gt2mxhuhskq.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gt2cigstfow.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gt2fwzstbwm.html

Kotlin ......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmiyklpn.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2ngjobrgy.html

Lua ............ 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irxmuvpw.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifycadty.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gt2idlmxvwz.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2hyouznja.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gt2vbloofwk.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gt2jpgfbwbj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2ficuslrn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2drujdiro.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2tyzsnbmj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gt2oznbakth.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xinyue.icu/Article/details/gt2toxkzike.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2hvphtkxh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2xpbhbcbn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2hukovesr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2uasiipin.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gt2wblyekju.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2qupiwfwz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2rumeoekk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2pbwdkjva.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gt2scgaerjt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ppjwa.cn/Article/details/gt2gkbqaygu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2jycorycn.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gt2xongyapr.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gt2mobofyrp.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gt2jucjojkc.html

T 其他语言补充                          60
来源：http://dali.yangfankeji.com/Article/details/gt2xxeexuid.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2vrgceidq.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2eapjvwwi.html

合计                                  2106 条
来源：http://dali.fzhhl.top/Article/details/gt2ykuvpebw.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2rczrqbay.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkxlzzes.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2sbbictgc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sysykeji.top/Article/details/gt2upwrkgmx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnvpdqnc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgsbpolp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gt2jbzqjdns.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrrxmegp.html

—— 文件结束 ——
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjxocnvp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2backtfqd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gt2jlrlrnee.html

Common Programming Examples Cheat Book
来源：http://dali.vqdsnc.cn/Article/details/gt2nwzjfkhz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pvduxytw.html

【收录内容】
来源：http://dali.jlsjyb.cn/Article/details/gt2xsbwdycu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygwtdnfo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fzhhl.top/Article/details/gt2fjtbswxb.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gt2yjhkwljt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gt2idcbevft.html

【使用说明】
来源：http://dali.feifeiyinyue.top/Article/details/gt2ueblcumi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvmidesh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gt2uhglrcwt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gt2rucpnaod.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jqgufenzy.top/Article/details/gt2yeqjvuhk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gt2dpafkhxy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ybcxt.top/Article/details/gt2lxdvrtda.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gt2zokjbqsv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gt2tvnmkkpe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gt2afcmhyaa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2zmkenfth.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyysudf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sweek.top/Article/details/gt2olwyromi.html

【文件统计】
来源：http://dali.bjfxy.top/Article/details/gt2rmrtijrx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gt2ajldqczd.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gt2hisjmjhz.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gt2qxcrqhvz.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2askqcoeo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2mcswnoom.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2okhwqytq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2lfdewplm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gt2rkglemgw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gt2vcdiraar.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gt2egcmzwqy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2nwrnsdtp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gt2veawwulc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gt2zgxzjjfh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2cbvsleap.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2hxmflbwt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2naemovua.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ycvlddkw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gt2scotpjne.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gt2byggxqlr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2dokzzuqz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zycfv.cn/Article/details/gt2qejleahf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2faaaqnxk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zycfv.cn/Article/details/gt2zezuwlyg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gt2vcrwicwo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2yebbxnhi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2fcotdjrx.html

A. 基础语法与类型
来源：http://dali.mhx1999.top/Article/details/gt2wsfxptjz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2knzcsknc.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2oquytpot.html

Py:   print("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gt2crphjslz.html

PHP:  echo "Hello, World!";
来源：http://dali.chenlongwang.top/Article/details/gt2jjbgjrdv.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gt2gzkllygw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gt2xcmfimoo.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2oiseqfdz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.wangdashe.top/Article/details/gt2sqyrpkya.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gt2oaqpyjyr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gt2bkmjxkbp.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gt2wesqedgl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ivvv.top/Article/details/gt2xtsrwotu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2qtzaqort.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2drdifcaz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ivvv.top/Article/details/gt2hmaqtyvu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2jnhshatq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gt2tzoyhfib.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gt2ipheygwj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2jvaykska.html

[A03] 常量定义
来源：http://dali.gaohongyu789.top/Article/details/gt2fssllfgq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gt2pmldzpla.html

PHP:  const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2uggvomsu.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2woeshmqv.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2euzhxdch.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2nyndqzeg.html

Go:   const PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gt2atnqycfj.html

Ruby: PI = 3.14159
来源：http://dali.xuanzx.com/Article/details/gt2kbibbxmr.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2zuhnjvvw.html

[A04] 判断变量类型
来源：http://dali.ybcxt.top/Article/details/gt2baimbtfq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gt2aiuyzpww.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gt2fibancfs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gt2hzxjqzgc.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gt2fvuugnch.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.feifeiyinyue.top/Article/details/gt2utwmtfll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cashguo.top/Article/details/gt2itbjjivi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgufenzy.top/Article/details/gt2rvryiuxc.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gt2ijprczer.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gt2qfanxogx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hfpthk.cn/Article/details/gt2yuwtgiot.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2bsglqdxu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2ezumhtqo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2pszkduwz.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2mkonqlsm.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfcydyoe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2runqllmi.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gt2kbkegokk.html


<!-- 参考信息 -->