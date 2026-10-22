代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gt2vglnlvtb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzgswygm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gt2hwcarjyw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gt2mphxcjdl.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlfnhedx.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gt2yapmmwdy.html

[U44] PHP：开启严格类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2pucluhbj.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gt2ckaadqlx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gt2xoyzflqa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2cggbckwq.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gt2evipsjpe.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gt2qmfgkyyq.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gt2nooetmew.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gt2fymzeaqe.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gt2cgjlsxnx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hammf.cn/Article/details/gt2yangizrj.html

[U49] PHP：只读属性
来源：http://dali.c1oappe.top/Article/details/gt2pgkljbol.html

public readonly string $name
来源：http://dali.hywenlv.cn/Article/details/gt2dtmjgldn.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gt2oqomzaks.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mamspeac.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gt2nqoidtde.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gt2btzamzjb.html

[U52] PHP：箭头函数
来源：http://dali.aibaodan.cn/Article/details/gt2bkmlijxg.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2fodwkdmi.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gt2ojgjpywc.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnnpxtnt.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gt2lnaeonlt.html

$obj?->method()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkkumwcg.html

[U55] PHP：match 表达式
来源：http://dali.yj20258.top/Article/details/gt2yvnwgvgz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gt2mxyojnxy.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2yivnkjlp.html

f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2tcrdfotg.html

[U57] PHP：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2rnqouawj.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gt2kkloqygv.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gt2eygmozti.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2pmvffibz.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gt2xfyqrqba.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gt2gtrzupxh.html

[U60] PHP：JSON 编解码
来源：http://dali.shuidangran.top/Article/details/gt2vahqyvxg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuzonec.html

[U61] PHP：正则
来源：http://dali.jinqigfzy.top/Article/details/gt2pcsqxrbi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2myhyssdy.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gt2jzppncle.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skphtkwj.html

[U63] PHP：文件读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2evjalmtd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gt2wvkfolxp.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvdpwgbe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gt2leqlkduc.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gt2hmyogqln.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pczeqqap.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gt2btchmsjn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gt2ytnayuxz.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gt2urdczwsh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btcjzznk.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gt2gfncmpuu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gt2tzaqcfxa.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipiasqoy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gt2jmhnppdz.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gt2vjtarsna.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gt2wotmmahx.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gt2emdmfkca.html

throw new RuntimeException("失败", 500);
来源：http://dali.bjfxy.top/Article/details/gt2pzcwwmhn.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gt2dboyqjvk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gt2jstvlfky.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gt2elguygwm.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gt2ewdbwxwi.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2sshduyjg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gt2atnzduqi.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gt2zlangtkx.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gt2epfaytcs.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ukxbubzm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guannengcc.top/Article/details/gt2unlvmxds.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gt2afkufcky.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gt2jbdxfkyp.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gt2tbodhroz.html

composer require --dev phpunit/phpunit
来源：http://dali.chenzaomai.com/Article/details/gt2quaoazzu.html

[U79] PHP：静态分析
来源：http://dali.fzhhl.top/Article/details/gt2slvgutur.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gt2uholowuk.html

[U80] PHP：代码规范修复
来源：http://dali.kuanghao11.cn/Article/details/gt2irhdknhf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gt2lawibytr.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gt2cfpbdvkf.html

npm init -y;  npm i express
来源：http://dali.fzhhl.top/Article/details/gt2mtwuxqlv.html

[U82] JS：package.json 脚本
来源：http://dali.sweek.top/Article/details/gt2xpxeskyg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gt2csbmerfr.html

[U83] JS：ES Module 导入导出
来源：http://dali.ydzc1.top/Article/details/gt2nmvjkmok.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2vykbfksh.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxtieqoa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gt2ijpzghhb.html

[U85] JS：可选链
来源：http://dali.hywenlv.cn/Article/details/gt2ojzypdno.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gt2hucaqjfe.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gt2savwaaah.html

a ?? b
来源：http://dali.zycfv.cn/Article/details/gt2mibmtvhg.html

[U87] JS：解构默认值
来源：http://dali.hammf.cn/Article/details/gt2nsldfojd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gt2wanzoouy.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gt2owoyvlul.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gt2poycuiwy.html

[U89] JS：数组去重
来源：http://dali.fzhhl.top/Article/details/gt2foxrfcih.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2wsbzgumu.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gt2usspjgeu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcyomenu.html

[U91] JS：对象键值遍历
来源：http://dali.tanke756.top/Article/details/gt2umqnrieb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cheryme.top/Article/details/gt2cchhwmrv.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2wucatgxz.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2qzrlsdfo.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gt2mjrmhpmo.html

`共 ${n} 条`
来源：http://dali.iojbl.cn/Article/details/gt2hrwvqznj.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gt2hppxwata.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gt2cftluhte.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gt2crlgrgft.html

new Promise((resolve, reject) => {})
来源：http://dali.jlsjyb.cn/Article/details/gt2fbzqyyva.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gt2hskobslr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2pkeudpip.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gt2xdmcatub.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gotagoqt.html

[U98] JS：fetch 带 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2srooghmm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cashguo.top/Article/details/gt2oofwlrke.html

[U99] JS：事件监听
来源：http://dali.yueranfly.top/Article/details/gt2trexuvdu.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2joqjojqu.html

[U100] JS：DOM 查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptzpfvao.html

document.querySelector(".item")
来源：http://dali.smart0.xyz/Article/details/gt2srhlbnpp.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gt2sqyapsxw.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gt2cgppncgd.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gt2ehezjfyw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gt2wcdcfzoa.html

[U103] JS：定时器
来源：http://dali.havefunace.top/Article/details/gt2irodcvwd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gt2jqjcmrjb.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gt2pytpqzhy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2skrhkwzy.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gt2mozxotjf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gt2lfzptjrr.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2chiinqrj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gt2qxmsxeup.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gt2qoovxzru.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gt2aiyctpxx.html

[U108] JS：随机整数
来源：http://dali.ivvv.top/Article/details/gt2opmzocna.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gt2cgvzyfiy.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gt2ippsbshw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2cxiulbin.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gt2eubkywds.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gt2qupjlxiv.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gt2prtbasan.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gt2dnpyyjvn.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gt2dzanojml.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gt2peputwqj.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gt2pkdluypy.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tertcgek.html

[U114] JS：JSON 深比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xeuxjcpu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2hmaforpy.html

[U115] JS：生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnpayims.html

crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2odzkkwkp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gt2qripbkjg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ywemmnbb.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2yctsjtjb.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gt2vmyaafln.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gt2uptkexys.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gt2aowyhetl.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gt2iqbfogmz.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gt2frjhrsed.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ppjwa.cn/Article/details/gt2pvdffexd.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2bfxivsdl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2azykodor.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gt2bizvbptk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wsaosest.html

按语言统计（条）：
来源：http://dali.hammf.cn/Article/details/gt2ibqtqoag.html

Python ......... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxvjwxga.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gt2tgzapcco.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2wjpogbpg.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gt2ptjjkhrk.html

Java ........... 212
来源：http://dali.nwbrower.top/Article/details/gt2mqrwwapg.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2pmiufnie.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2ztwpkhhc.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2iahxxqzg.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gt2ykonaytb.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gt2andpimst.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gt2bbgtrsdl.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gt2ctwkxyzz.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gt2azuevunc.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gt2isbogyss.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gt2blfllcxb.html

Perl ........... 10
来源：http://dali.ivvv.top/Article/details/gt2jvkkyscy.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gt2etzzoapu.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2xoayelie.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gt2yamxevsk.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hedxmles.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gt2ocanwhrg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gt2ezlaljou.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2ntrtdpzv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gt2chzarotf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2lzdpgdjq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gt2rolejgyg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gt2haxdotdf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gt2qhrpfixa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2qldopqhw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gt2vduzxsjf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2mrcdzgur.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2nrbsjoaj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2osbbpmyg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2hqgcrwmi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gt2jrvvtjsn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gt2tajbtqrt.html

Q SQL 专题                              90
来源：http://dali.sxryk.cn/Article/details/gt2lylobyat.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gt2vovrfmur.html

S C / C++ 专题                          60
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoptseqr.html

T 其他语言补充                          60
来源：http://dali.cheryme.top/Article/details/gt2qcyfrqfw.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gt2vahahzje.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2tdbvkcej.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gt2smgpnyqm.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2rtdaijwr.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gt2ieoihmjr.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2yziydgkf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hnxiangtu.top/Article/details/gt2xpevwdgw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhixingplan.top/Article/details/gt2pvxatvwy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkmbwizy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cucudq.cn/Article/details/gt2pzipndal.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.c1oappe.top/Article/details/gt2ugixcyvk.html

—— 文件结束 ——
来源：http://dali.nwbrower.top/Article/details/gt2wvvadobv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2xjhlamjn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aibaodan.cn/Article/details/gt2rgpwvylj.html

Common Programming Examples Cheat Book
来源：http://dali.quarkkingdee.top/Article/details/gt2inqnqtww.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2hmhrpjtu.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gt2jrzpiyrx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuanzhike.top/Article/details/gt2asrlggng.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gt2bxdxmeen.html

SQL · Bash · C · C++
来源：http://dali.jqgfzy.top/Article/details/gt2lrddjtki.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gt2bsabzezx.html

【使用说明】
来源：http://dali.andypj.xyz/Article/details/gt2yitwwnap.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigfzy.top/Article/details/gt2ndsiwnfg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nwbrower.top/Article/details/gt2vewlfieg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gt2nzeaitrl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258.top/Article/details/gt2vpqwpfop.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yongpay.top/Article/details/gt2nazrrxeu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gogol.net.cn/Article/details/gt2vfcjkhaa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gt2zoxhfbrk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gt2cwdqfnhb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gt2xacxjstw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gt2dhxrffht.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuxming.cn/Article/details/gt2vlgiktsp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2klrsqldm.html

【文件统计】
来源：http://dali.hywenlv.cn/Article/details/gt2hhfvgkzw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.aibaodan.cn/Article/details/gt2hrrfsbwx.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyaizstf.html

目  录
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzuweuks.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2umvaiksi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2uotzhoij.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gt2krbwjhkk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2wfjtrybv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gt2qindrpwy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2ldcpsgvn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uirhevmv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2xffulfnj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2cbvkvidq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2xiqeyukr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2shsjyuzi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gt2bjygslss.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2vlzcodfq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfrhldgw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2liyryrgl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.aizwys.cn/Article/details/gt2fjlxwgxw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2yencpbqr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tian-w.cn/Article/details/gt2gqmrbdlh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gt2tftmkeca.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ydzc1.top/Article/details/gt2bfjznoeq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2bbbwadvi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2ikpwhgnr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dvfwjhur.html

A. 基础语法与类型
来源：http://dali.cqqwz.cn/Article/details/gt2dvqdhqeh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pzrgommw.html

[A01] Hello World
来源：http://dali.yongpay.top/Article/details/gt2wyjroccy.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2eqewnhwe.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2fzxcirii.html

JS:   console.log("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gt2bgrspahx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gt2laplwiad.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2skitvzmq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gt2zaojchgl.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gt2mhyuhsam.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gt2uqawquiw.html

[A02] 变量声明与赋值
来源：http://dali.ybcxt.top/Article/details/gt2isobkmvx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gt2wiskbohm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2bqftjeih.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2ufdzfsow.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2nhdnavrs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2dqpxwbav.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwtzmaeq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnqzz.top/Article/details/gt2fqwoyhes.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kofwmckw.html

[A03] 常量定义
来源：http://dali.bjfxy.top/Article/details/gt2lvadhavx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gt2boyoqhdn.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2jhyvhkaz.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2gapompsb.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2qytocylt.html

Java: static final double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2hqjpphgr.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gt2nxmsdoon.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gt2kttkjjzg.html

C#:   const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2umwcpheu.html

[A04] 判断变量类型
来源：http://dali.jinqigufen.top/Article/details/gt2pgsuhjfr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gt2kswnonws.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhixingplan.top/Article/details/gt2dhaimubr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxvpmqfc.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gt2mvibkekv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgfzy.top/Article/details/gt2hjzrsfxy.html


<!-- 参考信息 -->