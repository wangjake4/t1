代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gt2mddlmohl.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gt2mwyohbea.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gt2xbejkpsy.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2mwgfryfu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ehwqpu.com/Article/details/gt2kzykytol.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gt2fphfxvnf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tianlin.xyz/Article/details/gt2qzhqdklu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gt2tcykuqra.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmvoukuf.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gt2gutvcizx.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gt2njnjezdm.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yodjavyv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.vqdsnc.cn/Article/details/gt2jzvxhzlo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2jpvoxdpa.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gt2gpgjewit.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpxmdxwn.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gt2fhmuhrjz.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gt2wycklvqp.html

[U48] PHP：纯枚举
来源：http://dali.redwolf501.top/Article/details/gt2tllkyxoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzimjjvf.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gt2ziitbxdt.html

public readonly string $name
来源：http://dali.nanxinkj.top/Article/details/gt2ldlbnxvk.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gt2ygtenweh.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gt2jglylgkk.html

[U51] PHP：数组解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ullmwxeo.html

[$a, $b] = $arr;
来源：http://dali.yangfankeji.com/Article/details/gt2merrnkec.html

[U52] PHP：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gt2rqxhekdj.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gt2nmfzthar.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gt2xydlnykx.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gt2duhgbwez.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gt2xziebgns.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gt2htxjvtwg.html

[U55] PHP：match 表达式
来源：http://dali.bjfxy.top/Article/details/gt2lxvhbgql.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyaqzweh.html

[U56] PHP：命名参数
来源：http://dali.dashuyun.cn/Article/details/gt2kfrhajus.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oruouhzi.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2xuzgfbja.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2ttzmynkp.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gt2yclnltvq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2fxwqyfvy.html

[U59] PHP：自定义排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfokteut.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gt2hhpoqcsq.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gt2adhhaiau.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gt2wmllolvh.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gt2cfyjonjb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2gnydkssc.html

[U62] PHP：日期对象
来源：http://dali.vqdsnc.cn/Article/details/gt2nqxacxia.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gt2jtulhpgg.html

[U63] PHP：文件读写
来源：http://dali.birdmap.top/Article/details/gt2gtabsurv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gt2nyzlqybu.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gt2rtipkart.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gt2uefujagt.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gt2fwonpqsh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.redwolf501.top/Article/details/gt2yfwlzduc.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gt2rwrooedi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gt2uedynpgh.html

[U67] PHP：处理文件上传
来源：http://dali.daria6918.cn/Article/details/gt2obtsppok.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gt2nwqbztxm.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gt2ajwzaepb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gt2kqvbczat.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2vajztpde.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gt2vtraiypr.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gt2izhahstl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gt2mltduald.html

[U71] PHP：抛出异常
来源：http://dali.zhengqikj.top/Article/details/gt2kepzfxzx.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2lamjncup.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gt2czeiheku.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gt2pdvdsnyg.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gt2mvfaretz.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyvnjtwx.html

[U74] PHP：读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2acpazuty.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hammf.cn/Article/details/gt2wfdbmiox.html

[U75] PHP：依赖注入
来源：http://dali.sxryk.cn/Article/details/gt2ujhsydcs.html

composer require psr/container
来源：http://dali.tianlin.xyz/Article/details/gt2cndcwtpt.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gt2juveekov.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuanzx.com/Article/details/gt2grraanob.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gt2dcekfyse.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gt2ledflram.html

[U78] PHP：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2krsvtnbl.html

composer require --dev phpunit/phpunit
来源：http://dali.chenlongwang.top/Article/details/gt2evzatiaa.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gt2dptcfhvp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gt2hnwkrajn.html

[U80] PHP：代码规范修复
来源：http://dali.mhx1999.top/Article/details/gt2srfsusmi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnqzz.top/Article/details/gt2jvuzqyws.html

[U81] JS：初始化项目
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrrkcezj.html

npm init -y;  npm i express
来源：http://dali.daxiang520.top/Article/details/gt2ypoxnobe.html

[U82] JS：package.json 脚本
来源：http://dali.hnqzz.top/Article/details/gt2nxhjietd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daxiang520.top/Article/details/gt2onrmunmi.html

[U83] JS：ES Module 导入导出
来源：http://dali.aibaodan.cn/Article/details/gt2wunkjpwp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gt2tecobfgf.html

[U84] JS：CommonJS 写法
来源：http://dali.cheryme.top/Article/details/gt2rvymgzwm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtmvvii.html

[U85] JS：可选链
来源：http://dali.ehwqpu.com/Article/details/gt2xnkhqtwl.html

a?.b?.c
来源：http://dali.jinqigfzy.top/Article/details/gt2nuknmadi.html

[U86] JS：空值合并
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyyjfhbb.html

a ?? b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmivhgdw.html

[U87] JS：解构默认值
来源：http://dali.fzhhl.top/Article/details/gt2nxmrxcxj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gt2hnlvbscs.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gt2ahpafhdm.html

{ ...a, ...b }
来源：http://dali.zhengqikj.top/Article/details/gt2bpnmiink.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gt2ffmjybgl.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2nmirigwj.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gt2bcdftppl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2zavhrkvc.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigufen.top/Article/details/gt2ebopslhk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gt2pwiahwto.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gt2xrwmbnmi.html

structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lknqhjnd.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gt2wjuajjaa.html

`共 ${n} 条`
来源：http://dali.ydzc1.top/Article/details/gt2ttiygozc.html

[U94] JS：箭头函数
来源：http://dali.jinqigfzy.top/Article/details/gt2titnnowe.html

const double = x => x * 2;
来源：http://dali.sysykeji.top/Article/details/gt2zdxevvxv.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gt2ttcpnfke.html

new Promise((resolve, reject) => {})
来源：http://dali.gogol.net.cn/Article/details/gt2ysfjxuqu.html

[U96] JS：async/await 与异常
来源：http://dali.jyoumei.cn/Article/details/gt2rijxmfsr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghxszwvp.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gt2sfltdunq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2bqhnyluu.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2zxzgecul.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gt2xgwdgyms.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gt2xhtqwndm.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gt2opyhywtx.html

[U100] JS：DOM 查询
来源：http://dali.vqdsnc.cn/Article/details/gt2vwlfglxb.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gt2zxorcwus.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gt2unviwukp.html

el.classList.toggle("active")
来源：http://dali.dashuyun.cn/Article/details/gt2jjaopdex.html

[U102] JS：本地存储
来源：http://dali.chenlongwang.top/Article/details/gt2ikbuckjf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gt2ldnlzdpq.html

[U103] JS：定时器
来源：http://dali.wangdashe.top/Article/details/gt2ocrnovmt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gt2thlceyfw.html

[U104] JS：防抖
来源：http://dali.ppjwa.cn/Article/details/gt2atdcbone.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2fgnkqryu.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gt2orzdgjbz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gt2viayjarw.html

[U106] JS：日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2haylrpzr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gt2ncwpebyu.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2xwfhpjkj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2uuyprbvw.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cizqkigt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gt2kaauouzd.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gt2boclpuqr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2rijbkhzi.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gt2thkeayog.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gt2tebbicwd.html

[U111] JS：对象转 Map
来源：http://dali.gogol.net.cn/Article/details/gt2iwmscyjz.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gt2xgvakiof.html

[U112] JS：字符串补位
来源：http://dali.cashguo.top/Article/details/gt2izkxejtc.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2vwjcvpuq.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gt2hsotnula.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2elrutvyk.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gt2nhmqaiie.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2ksildnjv.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gt2qiozzuee.html

crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2xkbpnphm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gt2wcnvqznn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxdqesjg.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2esidybth.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gt2yhbfscip.html

[U118] JS：开发服务器
来源：http://dali.aibaodan.cn/Article/details/gt2wzxxbjfr.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2qcgnyznq.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gt2jkbakogh.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gt2cjrlyzjf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gt2tdupkxkj.html

import.meta.env.VITE_API_URL
来源：http://dali.guannengcc.top/Article/details/gt2jhvbtxrp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2npncejrm.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gt2abijzdld.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2pfqzxrkc.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gt2wmrccvgv.html

Python ......... 252
来源：http://dali.aibaodan.cn/Article/details/gt2wpvskyqj.html

PHP ............ 252
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkhlnpbh.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gt2owwhpnzq.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gt2kfsadvng.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2ckvzykpw.html

Go ............. 212
来源：http://dali.yongpay.top/Article/details/gt2gfehlmzv.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpvsqiia.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gt2bdevnwug.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gt2iycgfkru.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gt2dzdpclmu.html

SQL ............ 90
来源：http://dali.yuxming.cn/Article/details/gt2lmyfjvlp.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiwfwdjn.html

Kotlin ......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2zvmvmufc.html

Swift .......... 15
来源：http://dali.daxiang520.top/Article/details/gt2iyyvkwce.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gt2qfbbwemv.html

Perl ........... 10
来源：http://dali.cheryme.top/Article/details/gt2gnuiaeoo.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gt2fkfovnvk.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2oczjmkds.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2jgvvlvok.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2kscgdkuc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2abjhzaut.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2dliqddwb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gt2gqtpmxvl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gt2xihlyoya.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gt2sdldpric.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2wfwzuumx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2rzcfsutd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gt2bvvslbtk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2xrlvqied.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2hdigdgtu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2ndtzuzbb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2gvyngxjy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfuvalec.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gt2spggatxf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hammf.cn/Article/details/gt2ydclhzpr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2ckizsyqr.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gt2wksmyvgv.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqbwbjwy.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gt2oizeejvq.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gt2ujnemyeh.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gt2skevzwgy.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2hgftsnis.html

合计                                  2106 条
来源：http://dali.andypj.xyz/Article/details/gt2rvosqtcy.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2xisgfgxy.html

使用提醒
来源：http://dali.jyoumei.cn/Article/details/gt2cnhvewbi.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2nogpuzoo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xinyue.icu/Article/details/gt2xoeaabmo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtmtkceo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jggbxnzi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gt2hvginppq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gt2kxuhcpeu.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gt2eqwbxium.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2vxfciyhq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gt2nbvlmqhe.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gt2ltycmoqe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2sbobzsvx.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gt2hcwymkxz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gt2zxohzatg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gt2cmllbsld.html

SQL · Bash · C · C++
来源：http://dali.yuxming.cn/Article/details/gt2rsrxurpv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gt2kdjzxlas.html

【使用说明】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blzumgbh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gt2apjpvpre.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gt2hzyymdzf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gt2qcdgauda.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hnxiangtu.top/Article/details/gt2zqgbowhj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gt2bjobxevb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gt2tfxulwrg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ivvv.top/Article/details/gt2gvvvcijm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gt2lyqirvcq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gt2qrvmxuwg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gt2tavrwwia.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gt2gcjecomj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gt2jhzpqbxs.html

【文件统计】
来源：http://dali.pycfn.com/Article/details/gt2vzhqopci.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbyeumkw.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdvwldzj.html

目  录
来源：http://dali.yj20258.top/Article/details/gt2fedzelkk.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2iikswqkl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jiagoushi.top/Article/details/gt2riixyxwh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gt2vtythdge.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gt2hkwggoxj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2cxiccxld.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gt2iwqsacqp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntateqte.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gt2bcefqwra.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gt2gzjmoxfu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irybycbr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gt2nxwyeihl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gt2jkpbckwj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2hhgdrdgp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2mtdkgrdi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gt2zkfmdbma.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gt2yxutlblj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqryvayk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hfpthk.cn/Article/details/gt2wmqqzuzc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kthfawpj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gt2njfdzmnl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2syqyocxz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gt2kpqkpbtf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2npswevao.html

A. 基础语法与类型
来源：http://dali.nanxinkj.top/Article/details/gt2hlpdwafq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fgczobza.html

[A01] Hello World
来源：http://dali.jianghu66.top/Article/details/gt2mhifdtqc.html

Py:   print("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gt2hkjrmhwe.html

PHP:  echo "Hello, World!";
来源：http://dali.birdmap.top/Article/details/gt2xvxkmqtt.html

JS:   console.log("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2vixwfapz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyygmdyo.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gt2uwwwhaez.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gt2bjtzbmcf.html

Ruby: puts "Hello, World!"
来源：http://dali.cdnleiting.top/Article/details/gt2cjsoaqro.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2vlnjdryy.html

[A02] 变量声明与赋值
来源：http://dali.gogol.net.cn/Article/details/gt2vuffhflo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.9152youxi.cn/Article/details/gt2enyinbvp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2ruajtwxm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2puuhliky.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xinyue.icu/Article/details/gt2rwlpvcqa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2ruqdbhyx.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gt2vcjmgyfo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cheryme.top/Article/details/gt2swqhgtdf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2zqzonnkp.html

[A03] 常量定义
来源：http://dali.jqgufenzy.top/Article/details/gt2cnashcgk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigufen.top/Article/details/gt2cyuustes.html

PHP:  const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2xrfaqlih.html

JS:   const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2aeheszuv.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2rsyopbqn.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2sbjecujm.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ooxutzcz.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2vrbxqhxf.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2vovdepzf.html

[A04] 判断变量类型
来源：http://dali.snrcjt.cn/Article/details/gt2mwplldpw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gt2xvlkwnfl.html


<!-- 参考信息 -->