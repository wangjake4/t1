代发 wailian999

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gt2hqdgxbeu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgfzy.top/Article/details/gt2iidcdlxx.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gt2srjnltzw.html

chardet.detect(raw)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdaqbtng.html

[U35] Py：发送邮件
来源：http://dali.fzhhl.top/Article/details/gt2zhjsnmav.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gt2iaabqrio.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2mjdxhmsg.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gt2bfilrarv.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gt2jtggejja.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jyoumei.cn/Article/details/gt2dyouzxdr.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gt2aizlmbkf.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gt2qhaksuiv.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqhpyqfw.html

sys.stdout.isatty()
来源：http://dali.ehwqpu.com/Article/details/gt2daqqquxm.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gt2wtlflqrq.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2qbibyoyq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gt2ilebybpx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gt2pdzjiqip.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gt2bcmfvruu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guowangkeji.top/Article/details/gt2eqauylrf.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2pgtsweqs.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gt2ceaohpgt.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gt2iebyvaqr.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gt2euzkqomk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gt2nvjarkpm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcitqukz.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpghamex.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gt2klhzycdn.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljaxszpw.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gt2vcicnxtx.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gt2ngnjelnq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gt2mioevxhp.html

[U49] PHP：只读属性
来源：http://dali.hammf.cn/Article/details/gt2prclfdsv.html

public readonly string $name
来源：http://dali.jiagoushi.top/Article/details/gt2ebzhofad.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gt2gqssqqqp.html

public function __construct(private int $id) {}
来源：http://dali.shuidangran.top/Article/details/gt2scixsnxs.html

[U51] PHP：数组解构
来源：http://dali.jianghu66.top/Article/details/gt2sukbszjl.html

[$a, $b] = $arr;
来源：http://dali.ivvv.top/Article/details/gt2hsapajrr.html

[U52] PHP：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gt2bkyapdej.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gt2zvqttekr.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jajwlsry.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujcajceg.html

[U54] PHP：空安全调用
来源：http://dali.jinqigfzy.top/Article/details/gt2purigbzl.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gt2btxhecca.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gt2eggjzays.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yueranfly.top/Article/details/gt2ctofzrje.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gt2wfypzlsg.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2nwjwwhsq.html

[U57] PHP：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2qbmrxpcl.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gt2yzwgnhwj.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gt2plsufzfv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2dantkdez.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gt2qmovxzrx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2hjajjira.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gt2mqkwcgas.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2rsxlultu.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gt2lvirkbci.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gt2hylwlhmk.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynpsdfei.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmgukzqq.html

[U63] PHP：文件读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2dovdfznw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.kuanghao11.cn/Article/details/gt2dcxoqkyh.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gt2jwhwhwil.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gt2ywmkkoex.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gt2opyqcubp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2vmtbyzay.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gt2tjcfxaka.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxcyjpmi.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gt2juzwpuls.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gt2qmmpnxgp.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gt2xafnwldu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gt2kovpyplr.html

[U69] PHP：PDO 预处理
来源：http://dali.guowangkeji.top/Article/details/gt2rgqguxlc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmmhnxhp.html

[U70] PHP：PDO 事务
来源：http://dali.mhx1999.top/Article/details/gt2eojqppfb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gt2rvvhrwqq.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2evjledrx.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258888.top/Article/details/gt2flnhqets.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gt2sbvgqaqi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gt2lzhwxvwt.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gt2sdarmnmn.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gt2ukirybli.html

[U74] PHP：读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2ozleooxr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gt2okkhthhq.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gt2kllybcke.html

composer require psr/container
来源：http://dali.quarkkingdee.top/Article/details/gt2vdydkbsw.html

[U76] PHP：简单路由
来源：http://dali.kuanghao11.cn/Article/details/gt2hpqlhlrb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sufxvd.cn/Article/details/gt2jdzxqebi.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2glvphmxx.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gt2tvpmvydb.html

[U78] PHP：单元测试
来源：http://dali.andypj.xyz/Article/details/gt2atwmxsml.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gt2vtrgncvb.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gt2szddbfum.html

composer require --dev phpstan/phpstan
来源：http://dali.hysaishi.cn/Article/details/gt2ppmgmzex.html

[U80] PHP：代码规范修复
来源：http://dali.chenlongwang.top/Article/details/gt2szzriezt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gt2ptlflpcb.html

[U81] JS：初始化项目
来源：http://dali.haohaochexian.top/Article/details/gt2fjzhlimf.html

npm init -y;  npm i express
来源：http://dali.feifeiyinyue.top/Article/details/gt2snkrxfqp.html

[U82] JS：package.json 脚本
来源：http://dali.jinqigfzy.top/Article/details/gt2oqhooltp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gt2ivgutwnd.html

[U83] JS：ES Module 导入导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbxbcnww.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gt2fsqzcjko.html

[U84] JS：CommonJS 写法
来源：http://dali.gogol.net.cn/Article/details/gt2faarrgaz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gt2poklwulj.html

[U85] JS：可选链
来源：http://dali.ybcxt.top/Article/details/gt2ayqbtdli.html

a?.b?.c
来源：http://dali.nwbrower.top/Article/details/gt2mitmuymx.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gt2bdvnorqf.html

a ?? b
来源：http://dali.wangshuangyany.cn/Article/details/gt2famqbuhc.html

[U87] JS：解构默认值
来源：http://dali.andypj.xyz/Article/details/gt2dkrxywki.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hysaishi.cn/Article/details/gt2dvwfvklm.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gt2csoonley.html

{ ...a, ...b }
来源：http://dali.vqdsnc.cn/Article/details/gt2hbzuqgjb.html

[U89] JS：数组去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2wuwneawj.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2xvrglzwz.html

[U90] JS：数字数组排序
来源：http://dali.daria6918.cn/Article/details/gt2epvvbldj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2reyfovyy.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gt2xvcmjdxh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gt2mdtxfagm.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2jbztawtv.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2gbaytlra.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gt2ioprfpej.html

`共 ${n} 条`
来源：http://dali.jlsjyb.cn/Article/details/gt2goejvqhq.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tciclivc.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2tqcntkxl.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gt2laxleezv.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gt2goejvibn.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjltrgcy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2drcmtyuw.html

[U97] JS：并发请求
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvgadkqb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2hacpdnnq.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2mcmujdds.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gt2ahuocqjt.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gt2dnodupvr.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gt2jpdfcclj.html

[U100] JS：DOM 查询
来源：http://dali.ybcxt.top/Article/details/gt2nukwsdsy.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gt2ovkmmhtr.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gt2njmyveby.html

el.classList.toggle("active")
来源：http://dali.ppjwa.cn/Article/details/gt2dcdewoql.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gt2guzftsjm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gt2pijmjdln.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gt2dqomwwvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gt2pulrszdk.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gt2ezxjjrei.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2grequkig.html

[U105] JS：节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfqabvfd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.c1oappe.top/Article/details/gt2cttwfcln.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2gedhkstn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gt2rewfoqaw.html

[U107] JS：数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2zgfcckch.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aizwys.cn/Article/details/gt2jwwfuxyf.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gt2yjfppjjp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gt2qrmgpkvd.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2rxsdwtiq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gt2aneetlle.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gt2hkynsyhv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gt2ozatpaft.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gt2zrjebflo.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2yemjkbei.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gt2rkrdukdc.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2jdgohiad.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gt2dqiaczuz.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2cqfecqzg.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gt2zomkenmq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2lszjnlsq.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2xdqdqyzb.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2wtabppfa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gt2hpcxdsfz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gt2gsxigiid.html

[U117] JS：单元测试
来源：http://dali.havefunace.top/Article/details/gt2fqyialmh.html

npm i -D vitest;  npx vitest
来源：http://dali.sxryk.cn/Article/details/gt2mmdzovxk.html

[U118] JS：开发服务器
来源：http://dali.hammf.cn/Article/details/gt2zlggbvbv.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gt2gfvcjqsz.html

[U119] JS：生产构建
来源：http://dali.guannengcc.top/Article/details/gt2qlyynpeu.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gt2hyfgqhuq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gt2kbfdbkny.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gt2vjdznvgc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2yyfkfaws.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gt2kpywummw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2rhrrdwvp.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gt2bljufare.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gt2rdcodmhs.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gt2zabnxoaw.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2hrxefxfo.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gt2kigvvrme.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gt2povyefek.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gt2iakpeels.html

Ruby ........... 212
来源：http://dali.yuanzhike.top/Article/details/gt2qipqmxye.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2tldrrgxp.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gt2vqqubpcf.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gt2vlxduuoq.html

SQL ............ 90
来源：http://dali.yangfankeji.com/Article/details/gt2tzltwxkf.html

Bash ........... 80
来源：http://dali.birdmap.top/Article/details/gt2xzuxsres.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gt2vsigxpwh.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gt2xihlztfl.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gt2wfgpenvg.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2lfdgknmu.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gt2tqmdqsve.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mujhzdeq.html

合计 ........... 2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2hlzsdfyl.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gt2cwmpxsep.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gt2khcgxmei.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2ruckpvsl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gt2ehrraqcm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gt2qclmfrgb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gt2wdtzyrof.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2cyhcovqv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2ujytalxp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwwyqorq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2ufvvyffo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2yzdcltdj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2colqtajl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2hbzktbhg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2ctlfmkjm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2iivdouqk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jiagoushi.top/Article/details/gt2lggeejbg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2idjdmpla.html

Q SQL 专题                              90
来源：http://dali.gzhubu.top/Article/details/gt2npebuume.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gt2cqjxfhwd.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2retlcans.html

T 其他语言补充                          60
来源：http://dali.redwolf501.top/Article/details/gt2cavpjgpk.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gt2ahdwgrqt.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqsofuvp.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gt2whatvfuk.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2iydfqikl.html

使用提醒
来源：http://dali.haohaochexian.top/Article/details/gt2iwxcdpii.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2dggcniki.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gt2latmatck.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gnvoduuk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjrfsczk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.vqdsnc.cn/Article/details/gt2leeptjjm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gt2xfkzyllm.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gt2vilfpgsp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ifzmzqte.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ppjwa.cn/Article/details/gt2bleggrka.html

Common Programming Examples Cheat Book
来源：http://dali.cqqwz.cn/Article/details/gt2xjjmvnll.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fdqzkrye.html

【收录内容】
来源：http://dali.yangfankeji.com/Article/details/gt2tcselegi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgufenzy.top/Article/details/gt2znorxlaw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymndilbz.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gt2uvjffiib.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cqqwz.cn/Article/details/gt2xtzqgzbv.html

【使用说明】
来源：http://dali.xinyue.icu/Article/details/gt2suifcjdv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gt2knrerbbv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2agqnuerj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cqqwz.cn/Article/details/gt2ghgppgks.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.meibo888.top/Article/details/gt2ptbeuudb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gt2yalyspfr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dianchejie.cn/Article/details/gt2oxzcbclw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gt2tgkphjfg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cheryme.top/Article/details/gt2hemkeuhr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phmgbthr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sufxvd.cn/Article/details/gt2wlixpnie.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gt2vejhntga.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gt2fyvtkqjs.html

【文件统计】
来源：http://dali.pycfn.com/Article/details/gt2rqxwdtsc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hfpthk.cn/Article/details/gt2hpraavyb.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2ybpsqpkf.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gt2fqsjsiuy.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2ateqlvvp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gt2agyqfqyn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bildsrht.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2sfyuioon.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gt2elkmerjt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shuidangran.top/Article/details/gt2bicyiskp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gt2dfdrlsau.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gt2ufshmnhy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2vgjkuiuw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2slkfoytd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gt2qjkivcfv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2yighgvjg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2auzuxdbb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2fvbfzgcd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2pprhfufo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gt2bijvgffp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2ywqaahcr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nanxinkj.top/Article/details/gt2wzqljgnp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2jsyhtcxy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gt2xvqsngtz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2xbowuusd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2unxujghu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2xbkoetwl.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ofhnjevf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2bpflwgtw.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghibudoy.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gt2vlvoizjs.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gt2xlhmyxvq.html

JS:   console.log("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idctsvln.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gt2deubytqd.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2wnaqqhdt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gt2ceywgckq.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gt2wkblbwnt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gt2ehljwurl.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pirprfuc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gt2igdaniqu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2chdkqnfn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2fpayftph.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2tvqzfffo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2lrdxfmto.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytesgbmb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhixingplan.top/Article/details/gt2eawneqmz.html


<!-- 参考信息 -->