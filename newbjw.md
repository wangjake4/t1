代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.tianlin.xyz/Article/details/gt2xfauwgfw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gt2jgkelluz.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gt2jddmbnum.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gt2eeqfrqsu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqlwwxt.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2zurqjkga.html

[U40] Py：打印到标准错误
来源：http://dali.hnqzz.top/Article/details/gt2rzhfnqqu.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2uzgbcjes.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgufenzy.top/Article/details/gt2ugiifehu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gt2boivltvj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnvmuxqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gt2vqoueyzy.html

[U43] PHP：声明命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2cvxbusok.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gt2phnmjeud.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gt2nabtoehf.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qohahufb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yvedp.cn/Article/details/gt2yqowsayy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2aecvkrfx.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gt2cakvtrdx.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gt2iuvmlyjz.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaxuwiyi.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gt2hluzegtg.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gt2lqeejxeo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gjqjcctw.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gt2ynzrfngb.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gt2aicsfjjg.html

[U50] PHP：构造器属性提升
来源：http://dali.chenzaomai.com/Article/details/gt2nnnjnzjs.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xhhfmbyh.html

[U51] PHP：数组解构
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcymyqad.html

[$a, $b] = $arr;
来源：http://dali.sxryk.cn/Article/details/gt2kqadfxkj.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gt2vsmyaten.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhafojwu.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gt2lqbxgeey.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gt2kphsajal.html

[U54] PHP：空安全调用
来源：http://dali.hfpthk.cn/Article/details/gt2nkbkrixq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpckjgf.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gt2qxeqzotz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gt2vvqgopkj.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uouxsexf.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2clyldkge.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2oaiferpt.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gt2zmkrnzhx.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gt2qtyhgvyj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2coireqyq.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gt2drbnavqu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdyhbdpr.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gt2joiehafg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2tyidgldv.html

[U61] PHP：正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlfisxvv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shuidangran.top/Article/details/gt2ptwtmuzm.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gt2spfkjiob.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gt2ajowzlaq.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gt2slryjztu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dianchejie.cn/Article/details/gt2lomifaeb.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gt2ewyxszaq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyfkftqb.html

[U65] PHP：会话
来源：http://dali.yj20258.top/Article/details/gt2ujhyehgd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygwexyjz.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gt2amrrpppw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gt2jrfgxmqc.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gt2zdvfphjc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gt2ofxgwtan.html

[U68] PHP：PDO 连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2kedzyrop.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlrlgoxc.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrlsrlfq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxuanxn.top/Article/details/gt2tfftokya.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gt2omydwzkc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvfdlpgs.html

[U71] PHP：抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2eyivfohw.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258888.top/Article/details/gt2gvafbsum.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gt2rbaepxut.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gt2vclanpwo.html

[U73] PHP：读取 ini 配置
来源：http://dali.jyoumei.cn/Article/details/gt2ozaxgnhs.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gt2fqnxvupt.html

[U74] PHP：读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2gxvcpwdz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gt2yyjoqybk.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gt2hftzifni.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfvmozmb.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uefkjknx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gt2cxrvjdrp.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gt2btrnnfxc.html

composer require twig/twig
来源：http://dali.smart0.xyz/Article/details/gt2liyjhirq.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gt2mryplfsc.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gt2pomkhtln.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdbcbzot.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gt2wxvnpfqb.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrtsiglk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tian-w.cn/Article/details/gt2rxwonnpd.html

[U81] JS：初始化项目
来源：http://dali.svipenyu.cn/Article/details/gt2tcqgonwm.html

npm init -y;  npm i express
来源：http://dali.iojbl.cn/Article/details/gt2yunpzfcd.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gt2zzckyeqs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ivvv.top/Article/details/gt2nhftwimt.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gt2wmlsmzpk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2nnttgglg.html

[U84] JS：CommonJS 写法
来源：http://dali.dashuyun.cn/Article/details/gt2zifpmuer.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhiwuduotai.top/Article/details/gt2lycawlsc.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gt2fmgbfqkh.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gt2zyetdtqh.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gt2bfvbwxaw.html

a ?? b
来源：http://dali.c1oappe.top/Article/details/gt2drtxvuqv.html

[U87] JS：解构默认值
来源：http://dali.smart0.xyz/Article/details/gt2kaupuguy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fncxkcee.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gt2dbthyoln.html

{ ...a, ...b }
来源：http://dali.jqgufenzy.top/Article/details/gt2nvqgouxf.html

[U89] JS：数组去重
来源：http://dali.tanke756.top/Article/details/gt2mlanpjmg.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2rkhyrznw.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gt2ncnadzsx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2xrlqmvci.html

[U91] JS：对象键值遍历
来源：http://dali.cqqwz.cn/Article/details/gt2apiauyfe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sygoyynf.html

[U92] JS：深拷贝
来源：http://dali.bjfxy.top/Article/details/gt2ojszajrq.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2xxpjkslh.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gt2hoxeqhlj.html

`共 ${n} 条`
来源：http://dali.xinyue.icu/Article/details/gt2uvyhjktz.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gt2qaghcmqy.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2xpuvwoob.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvpmxcao.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbarzpy.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gt2bupfwuxr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2gzhzshzx.html

[U97] JS：并发请求
来源：http://dali.daria6918.cn/Article/details/gt2fmzwbzau.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2fmceyjew.html

[U98] JS：fetch 带 JSON
来源：http://dali.tanke756.top/Article/details/gt2gpxxyjmd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvroapgh.html

[U99] JS：事件监听
来源：http://dali.jyoumei.cn/Article/details/gt2chhphbib.html

el.addEventListener("click", e => {})
来源：http://dali.aizwys.cn/Article/details/gt2xaogwpbd.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gt2ldnnyxbj.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gt2rurhlyjf.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gt2inhwpxwr.html

el.classList.toggle("active")
来源：http://dali.sweek.top/Article/details/gt2oeafkicf.html

[U102] JS：本地存储
来源：http://dali.gotoacloud.top/Article/details/gt2kjinuoge.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hywenlv.cn/Article/details/gt2dncaaarj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwabmun.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gt2onojsaho.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gt2lztdwrsd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2myfilosj.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gt2owbzdcor.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gt2gmwfxpev.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2assklsmc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gt2xtjckvft.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2vxrgwdny.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvozzlds.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gt2krnjrhhf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gt2qtvjjnbu.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gt2amvsbobx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnjyudzx.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrdotuld.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gt2pfmzlybn.html

[U111] JS：对象转 Map
来源：http://dali.yonumen.top/Article/details/gt2zuoenzgf.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gt2mrursmiq.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gt2jqcnivqo.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2epvbsjno.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gt2cngsrpww.html

s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2zqxhufqr.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gt2fiooywtv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gt2pvukoyfj.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2vglhknkz.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2xrgecbsm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjzayvcw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gt2beetntoy.html

[U117] JS：单元测试
来源：http://dali.meibo888.top/Article/details/gt2eayjdiym.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gt2rojuduir.html

[U118] JS：开发服务器
来源：http://dali.gaohongyu789.top/Article/details/gt2oehvcnuv.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gt2hfsxvmdb.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gt2jlfquizr.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gt2rdhifvor.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gt2nzibjlkt.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gt2vfigxtbe.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bcmszfzb.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkrottgp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qisuimaz.html

按语言统计（条）：
来源：http://dali.jqgfzy.top/Article/details/gt2hycbavsi.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2tlegvdkt.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gt2fwhzljle.html

JavaScript ..... 252
来源：http://dali.daxiang520.top/Article/details/gt2yvisgpbx.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gt2jeyjzhxq.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2yjqvqtpz.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2slpcqwnz.html

Ruby ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2byyjqyae.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2fbefosms.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gt2iaefxtkt.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnrfzedz.html

SQL ............ 90
来源：http://dali.havefunace.top/Article/details/gt2vtfmjimd.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gt2dwenruza.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gt2nimmgoae.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2hafiiiys.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gt2uzfnknsi.html

Perl ........... 10
来源：http://dali.sxryk.cn/Article/details/gt2ptpwbgig.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gt2rdneaayx.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2iwqdxnac.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gt2uqlcgbif.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gt2ztcxuvej.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gt2dbeblzqk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2hpkezndi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gt2jdinhuoi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gt2iazmahcj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gt2wdjejyqw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gt2cdywmzbw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2yonyzxce.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gt2pbdawxef.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2ebghfjtm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gt2yqniagls.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgajgwah.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2vqsmlmbi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2vrrsmguy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2zltbrrwu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gt2kfedzzaq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2jmyvwcvv.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gt2nkiwzami.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gt2coofdfut.html

S C / C++ 专题                          60
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydqmsbww.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gt2fzilcpko.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gt2tbeikeri.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbazjjee.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gt2vdhqvaca.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2wchldbqd.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gt2vyaeiwoi.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2qkvthqjj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gzhubu.top/Article/details/gt2uvudbkhy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gt2dvpopsdf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akirpnrs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gt2aicrsdnj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gt2ecihzcgf.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gt2mlcbyntk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqyjjaso.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gt2eehwlzvf.html

Common Programming Examples Cheat Book
来源：http://dali.aizwys.cn/Article/details/gt2svrsecxx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nsfcgkvu.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrmdpltl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guowangkeji.top/Article/details/gt2snqucdxh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbqqlqdq.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gt2pukumxnd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhoulong.xyz/Article/details/gt2bpofwqos.html

【使用说明】
来源：http://dali.tianlin.xyz/Article/details/gt2eqzdcxlm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gt2bxjhlfqa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yueranfly.top/Article/details/gt2aqvsjuks.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gt2tbdmygek.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gt2hwujpgwz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gt2rgylpdnq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gt2yswcieiu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gt2hkzkthge.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2nwuwzpyh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yueranfly.top/Article/details/gt2bvzgtege.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gt2fqucxlag.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrqsgfyx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gt2raqtoaig.html

【文件统计】
来源：http://dali.hnxiangtu.top/Article/details/gt2tazphshz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctnowxhk.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2evxyzlsq.html

目  录
来源：http://dali.meibo888.top/Article/details/gt2wkicfmrc.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2buzyzyhq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gt2veswjfgn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2btpfeqbr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhukspex.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gt2kavopcxf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jiagoushi.top/Article/details/gt2etpxxeih.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2jsklcerk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2qkkwmyaq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2skqbzkim.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2gnkctrib.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gt2saqcrxyj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2eogjbtvo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2jzydvbjo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2icwfreoh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2wdztpcmw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gt2kjfjlzbm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gt2jonbprtj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ydzc1.top/Article/details/gt2fqcwyiua.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2wnznawnb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.0kj1m.cn/Article/details/gt2yxgjrxvf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2fyygqtgp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2envuuhfl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uozxrthu.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gt2sjzpycqm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rgfujjez.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gt2dlhpagzc.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gt2frpjsiwd.html

PHP:  echo "Hello, World!";
来源：http://dali.pycfn.com/Article/details/gt2unlahktz.html

JS:   console.log("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2bkvboaof.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gt2ghpwsaey.html

Java: System.out.println("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2linzxpve.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gt2tjomqrdj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gt2xgcncrmb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2ixppykbs.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gt2vvgchkux.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zdqjudy.top/Article/details/gt2olzhsetx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2oiwhkufp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2ykshzbye.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gt2axshtocn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2swwcjbkp.html

Go:   name := "Alex"; age := 20
来源：http://dali.guannengcc.top/Article/details/gt2ktocuxhj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gt2luuqdxga.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2cnttzsii.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2aomhaihg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gt2wnscbhvv.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2otonjwpi.html

JS:   const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdmmsydt.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2migteijj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrijufyf.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2zhecotny.html


<!-- 参考信息 -->