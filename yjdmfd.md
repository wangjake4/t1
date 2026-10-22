代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gtrtdudaft.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.snrcjt.cn/Article/details/gtibezclpm.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgphxzaqa.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtifdydhld.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtmqlzwjqv.html

sys.stdout.isatty()
来源：http://dali.yj20258.top/Article/details/gtrpmzohnl.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gtyvpqawan.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtruoebuce.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtywxxrqsc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.aizwys.cn/Article/details/gtpqnkiwin.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtxktqutay.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.svipenyu.cn/Article/details/gtbvhlvzsg.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gtfkdoxlhy.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gteeeclfxl.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gtvjsqtiux.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtjetfkrjm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtokmmyigz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtdogpfwee.html

[U46] PHP：可空类型
来源：http://dali.andypj.xyz/Article/details/gtmzeanahj.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gtjzsgwqbb.html

[U47] PHP：联合类型
来源：http://dali.ivvv.top/Article/details/gtxryeyafz.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gtbxvyorcn.html

[U48] PHP：纯枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzitjfrp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwarwqxn.html

[U49] PHP：只读属性
来源：http://dali.quarkkingdee.top/Article/details/gtqwitaqwx.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtnwnotjee.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtdpvdnwna.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtlighpiej.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtapocufka.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtpoxwnkhm.html

[U52] PHP：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtmmnqodbp.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigqmubtp.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gtbdfwiivu.html

$v = $a ?? $b ?? "default";
来源：http://dali.xziqi.cn/Article/details/gtddrkmkqp.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtiaavvfxm.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gtcjfmfnjr.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gtjcweaugf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gtzoavzevp.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gtjthkzmdn.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtsgwgkapq.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtyesznncs.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gtysnablce.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gtxtnvlnap.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gtnhprxkua.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gttpoblzpi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gthcwotwek.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmtefwei.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gtmljgfbzp.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gtcywadmpp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtirltwhay.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtloeysbvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dashuyun.cn/Article/details/gtmzjgiado.html

[U63] PHP：文件读写
来源：http://dali.bjfxy.top/Article/details/gtfaxsvjqd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtaojdukgm.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtpfbxownw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gttdnsoygl.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtbhscviyx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtcsulvgmo.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gtllvjjauh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ivvv.top/Article/details/gtkoangduf.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gtrwofhbrb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gtonmwhvfq.html

[U68] PHP：PDO 连接
来源：http://dali.guannengcc.top/Article/details/gtmqkkbvve.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxinkj.top/Article/details/gtpwcxufaj.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtqpahkddz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ivvv.top/Article/details/gteukklnxe.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gthrxqhqfz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gtbgsguyls.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtfqagxsac.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gtiegzzyrn.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtxttrnsuo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yuxming.cn/Article/details/gtaepiizqv.html

[U73] PHP：读取 ini 配置
来源：http://dali.andypj.xyz/Article/details/gtyriiqqom.html

parse_ini_file("config.ini", true)
来源：http://dali.gogol.net.cn/Article/details/gtouvatrdu.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gthmcuqdmu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtipciomxd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gtrvwrltfe.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gtwlggnkbw.html

[U76] PHP：简单路由
来源：http://dali.feifeiyinyue.top/Article/details/gtujhyklcf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtogmsxvoh.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtuqysteuq.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gtogcpozyp.html

[U78] PHP：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtltlzfjpw.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gtafrqvgrl.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gtrmkaeark.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gtglgghtpy.html

[U80] PHP：代码规范修复
来源：http://dali.kuanghao11.cn/Article/details/gtgksflnyq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gtlhvwfxaw.html

[U81] JS：初始化项目
来源：http://dali.daxiang520.top/Article/details/gtwmzdgmtw.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gtaovknfbb.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gtevnsaxbq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkywdsch.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gthwvsscsr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtbeslassx.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gtrgnvokal.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gtwevuwclk.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gtebmrkzkz.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gtrepebjbf.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtyiicxmbz.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gthsgrldbl.html

[U87] JS：解构默认值
来源：http://dali.chenlongwang.top/Article/details/gtykhpgsjw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gtamjjibxu.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gtopffcsxf.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtvlblxrnk.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtefibtb.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtuoixvhan.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtgyqsxloy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtpryjaunr.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gtdaoludlp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ppjwa.cn/Article/details/gtxbpxujng.html

[U92] JS：深拷贝
来源：http://dali.xuanzx.com/Article/details/gtmoiiteab.html

structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtzbyqussv.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtocauhcga.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gthbhqwiap.html

[U94] JS：箭头函数
来源：http://dali.zhoulong.xyz/Article/details/gthpdsyeez.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gteltitbwu.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gtrwfldwlc.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gtuwdyooqj.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gtsmhkshgl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtibtamsru.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gtjwgdevac.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifdbbbhz.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtohisixgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.redwolf501.top/Article/details/gtlukwmaui.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtnugvzjky.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspkqbjty.html

[U100] JS：DOM 查询
来源：http://dali.sysykeji.top/Article/details/gtysdadroy.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxpufhce.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gtycapldfx.html

el.classList.toggle("active")
来源：http://dali.xuetiantiany.cn/Article/details/gtcbmbtxne.html

[U102] JS：本地存储
来源：http://dali.ybcxt.top/Article/details/gtyviphxya.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuetiantiany.cn/Article/details/gtwicmycng.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gtgkabnzck.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gtyvebhphl.html

[U104] JS：防抖
来源：http://dali.tianlin.xyz/Article/details/gtknundeki.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtldezevze.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtdixdesvk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtgdihoqqr.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gtrxxzjfag.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxinkj.top/Article/details/gtwhzozqgr.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtvvpyfgyn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtksfzvhhy.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtspudzpsi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwappcclh.html

[U109] JS：数组分组
来源：http://dali.smart0.xyz/Article/details/gtnedxtxsm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwnwreot.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gtgtknpkrq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fzhhl.top/Article/details/gtryscuvfv.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtphycqyyi.html

new Map(Object.entries(obj))
来源：http://dali.cashguo.top/Article/details/gtwfviigkk.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gtdzvfftir.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gthwlmnrra.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gtssqnslxq.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtidomqblq.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gtfvrgtwik.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtmfjtfamz.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtphmbqzic.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtrhwdmiab.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtwnppcohy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtianlnvcv.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtzlgbppmo.html

npm i -D vitest;  npx vitest
来源：http://dali.316326.xyz/Article/details/gtrqejcmyr.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gtibszkmxy.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gtvuskguyq.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtwhfvqeal.html

npx vite build
来源：http://dali.xuanzx.com/Article/details/gteaoelxpj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtaadzjyed.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gtxdesmafx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgfncqvnp.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtkxrrkntb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttvvynzlg.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtmqbyopcf.html

Python ......... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtwxbyocee.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gtgxwtyslk.html

JavaScript ..... 252
来源：http://dali.ivvv.top/Article/details/gtbgmrfwat.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gteqyosgvb.html

Java ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtlizlraum.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtrgpefdjd.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gtzuexlcoj.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtkbtwyzrj.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtopsnpnkg.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gtqortckwp.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtyybxlokl.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gtjziafnue.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gtgmgbdvfc.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gtpgsskisp.html

Lua ............ 10
来源：http://dali.c1oappe.top/Article/details/gtbdfngemx.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtfonfuqib.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtafhanyvi.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtynkzneed.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtuwwirsib.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gtzflvucqg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtxrijspbx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtzfuhjgoa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtleiooazx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtedbiukdh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqcuajcp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtygxinzvn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtrfebqkug.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtxizcaasw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtbvcjxapm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gtcxlzxgbv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtjxazbfcb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtubduubml.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtwybvrwic.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtnskvnlez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gtqpfwwlwp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzslkshl.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gtfmvjndbv.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtxphytsfq.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gttxmpaxlf.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiqrfjtg.html

U 高频实用片段                         120
来源：http://dali.quarkkingdee.top/Article/details/gtzifiilim.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gteaxgkmub.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gthzhsevvz.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtchnyromt.html

使用提醒
来源：http://dali.yanxiufei.cn/Article/details/gtguvkoguo.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffnnibkr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gzhubu.top/Article/details/gtxoncitzf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gtezjbvshd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtanzwvwrc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yueranfly.top/Article/details/gttbnksgfm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sufxvd.cn/Article/details/gtrnyrievj.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gtwvekqemk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtybnfgqsz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgufenzy.top/Article/details/gtxgdpqsrp.html

Common Programming Examples Cheat Book
来源：http://dali.smart0.xyz/Article/details/gtaguyqwqb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtimjmhslj.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtzknxglfr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxinkj.top/Article/details/gtvqfpzrvm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aizwys.cn/Article/details/gtlafnxdsm.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gtkynmyvrz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tian-w.cn/Article/details/gtdvikwtry.html

【使用说明】
来源：http://dali.xylfe.cn/Article/details/gtyomabxzb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.bjfxy.top/Article/details/gtiyytykig.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.9152youxi.cn/Article/details/gtsqicslgo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fzhhl.top/Article/details/gtmndjwojs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gtbvphqqtk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxinkj.top/Article/details/gtiiurjwes.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gtnqyxtdpt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hfpthk.cn/Article/details/gtjieznyxy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinghuilouyu.cn/Article/details/gtulnerthr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cucudq.cn/Article/details/gtyphmlxtl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatqdejqi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gtceapbkup.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gtcuorxopo.html

【文件统计】
来源：http://dali.shuidangran.top/Article/details/gtudjbbzmt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkgrhomi.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtiedvtyrk.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gtayoarrci.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtymesemor.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gtdpowzhbs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtpwvcfsrt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtivvzeyol.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtyjlephau.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtdlajodoi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtupsdixvc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtxeinznep.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.birdmap.top/Article/details/gtexktchxp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gthswgusnd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtwmsyxjnf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtnflsnmxr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcahuioho.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtipzmaypt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtpigcvckd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgypijgoe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtpqyyyfig.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gtrvdzbfhj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gtzjcflslz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgfzy.top/Article/details/gtortxwdqw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtzkquqkel.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqszzhqe.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtadxmghlc.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gtpyhxrqce.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwbxtducn.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gtjxvzkfur.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gtxpowobxk.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gtayqfjmxf.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtyvcdqutq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtdkdwzxns.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbjsiwqe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gthjpejgnr.html

Ruby: puts "Hello, World!"
来源：http://dali.cheryme.top/Article/details/gtxygvfzoe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtkeqyzudy.html

[A02] 变量声明与赋值
来源：http://dali.9152youxi.cn/Article/details/gtnujmcyrh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.9152youxi.cn/Article/details/gtxjpzqhoi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtcxhbbbpt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpfjfeqm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtyeazecah.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtuccrwdww.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gtydzdllfx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gtcnqmbicb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtctouwgws.html

[A03] 常量定义
来源：http://dali.jinqigufen.top/Article/details/gtkzszcszf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gtyydzkjya.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtlxtvtrsl.html

JS:   const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtdoyweecz.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtdojactnz.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtygwcnkwa.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtjaazeqej.html


<!-- 参考信息 -->