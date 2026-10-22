代发 wailian999

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gtptrhfgsa.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtwnslklnn.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtfufyergj.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtlhcmijuj.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtqovkslow.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtisjtnmpx.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtsawejccq.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gtpjywyusk.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gtgqardzzz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gtlunwgtxh.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gtceyhonoi.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtnjlrhfgt.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtshqgmldv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtlifuisua.html

[U38] Py：获取脚本所在目录
来源：http://dali.svipenyu.cn/Article/details/gtykdxecig.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gtvvtfanat.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhklqdxt.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteexietwm.html

[U40] Py：打印到标准错误
来源：http://dali.guannengcc.top/Article/details/gtmloxfwjf.html

print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtcrduyhzt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gtzfnqltwo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdpfhvpt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtvdjdtiao.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gtfhxrgndw.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gthxpnyniv.html

namespace App\Http;
来源：http://dali.vqdsnc.cn/Article/details/gtjqqhiwiz.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtpqzigdvu.html

declare(strict_types=1);
来源：http://dali.daxiang520.top/Article/details/gtyijppxgw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gtgncpwkqy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtllpcakml.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtpmposxbj.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gtfjwmhtue.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gtxjlyflmx.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtsflekntz.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gtmetvvcad.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gthjnplyyw.html

[U49] PHP：只读属性
来源：http://dali.ehwqpu.com/Article/details/gtxksdyeuo.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtdrrothpu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhongyouzk.top/Article/details/gtrrdbiwuv.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtdmfbcqlh.html

[U51] PHP：数组解构
来源：http://dali.gaohongyu789.top/Article/details/gtfvtarcgy.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtixwlnhxz.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtgelvlcmw.html

$double = fn($x) => $x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtmejsdwgz.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtmrvvzxej.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gtxpaoywzv.html

[U54] PHP：空安全调用
来源：http://dali.chenlongwang.top/Article/details/gtesqimnbk.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtapclcvpa.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gtaunnbebl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtuiazhyll.html

[U56] PHP：命名参数
来源：http://dali.aizwys.cn/Article/details/gtqbwrqukw.html

f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtozfqzfpk.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtzvlyprrx.html

"值: {$a}"
来源：http://dali.zycfv.cn/Article/details/gtouwufasg.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gtgcizyjxr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gtqmkaqlsn.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gtlpmhrlih.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtzriertrj.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gtodeorjyg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cucudq.cn/Article/details/gtkfcwxkde.html

[U61] PHP：正则
来源：http://dali.yj202588.top/Article/details/gtomzythvz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ydzc1.top/Article/details/gtkiospspd.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtxelshtll.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cucudq.cn/Article/details/gtcgwaegnf.html

[U63] PHP：文件读写
来源：http://dali.chenlongwang.top/Article/details/gtgqfosyyt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.9152youxi.cn/Article/details/gtsljroacc.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtyrvhbngs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgufenzy.top/Article/details/gtzrxycftk.html

[U65] PHP：会话
来源：http://dali.sufxvd.cn/Article/details/gthehryikc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtzfluvtjf.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffspvdpc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtotrvchyu.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gtoeljfbgf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gttsdhryun.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtfyasxqsl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gtjssxovrx.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gtxgsjfjya.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gtvsocxgdu.html

[U70] PHP：PDO 事务
来源：http://dali.cqqwz.cn/Article/details/gtfhmxfymg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtzyimmroo.html

[U71] PHP：抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtrdjtaaop.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtgilhkjwf.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtnkoelaeb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtyeclmtdz.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gtbzcuoofh.html

parse_ini_file("config.ini", true)
来源：http://dali.yonumen.top/Article/details/gtqavwopav.html

[U74] PHP：读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gtarnczaev.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gtzwtcyssc.html

[U75] PHP：依赖注入
来源：http://dali.hywenlv.cn/Article/details/gtkjrrqmxo.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gtkcxhijln.html

[U76] PHP：简单路由
来源：http://dali.quarkkingdee.top/Article/details/gtnfzpxork.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gtemzctmdq.html

[U77] PHP：模板渲染
来源：http://dali.jianghu66.top/Article/details/gtszozuwdb.html

composer require twig/twig
来源：http://dali.cashguo.top/Article/details/gtxvnpqmxm.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtelcnbdsj.html

composer require --dev phpunit/phpunit
来源：http://dali.pengpengdd.cyou/Article/details/gtutxixfdy.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtdzbzdjet.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gtjkqbnhib.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gtlchveahe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtfkjdwzmp.html

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtjkanuznk.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gtogtdtcmb.html

[U82] JS：package.json 脚本
来源：http://dali.cheryme.top/Article/details/gthetkuawa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gtglahmktm.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gtwlomhtwa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtbklmfoiz.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtaxrylk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gtcwspangk.html

[U85] JS：可选链
来源：http://dali.wangdashe.top/Article/details/gtypwcdbvs.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtixpxoxbs.html

[U86] JS：空值合并
来源：http://dali.xylfe.cn/Article/details/gtskogpewz.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtjfxjzffh.html

[U87] JS：解构默认值
来源：http://dali.cdnleiting.top/Article/details/gttxlrngzb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gttkyyerdn.html

[U88] JS：对象展开合并
来源：http://dali.sysykeji.top/Article/details/gtvlskfuth.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gtnkbnzohu.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gtdqkjdudw.html

[...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gttrrrrbhv.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtizhnrwym.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtutomoyln.html

[U91] JS：对象键值遍历
来源：http://dali.yvedp.cn/Article/details/gtqymqooaq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinqigufen.top/Article/details/gtfbwejovn.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtvhojmrru.html

structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnujooex.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtrbmdiqrs.html

`共 ${n} 条`
来源：http://dali.shzxlz.cn/Article/details/gtzivralpn.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtvnlgsehj.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gtvrnqslai.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtoumgkzts.html

new Promise((resolve, reject) => {})
来源：http://dali.sufxvd.cn/Article/details/gtrmazkdia.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gtdmmcuawd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtkebszcya.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtjkzohyff.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtbtwksxat.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtzqdbgeeu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtxkmlnwph.html

[U99] JS：事件监听
来源：http://dali.havefunace.top/Article/details/gtinfoxrtm.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gtvdodkokn.html

[U100] JS：DOM 查询
来源：http://dali.yj202588.top/Article/details/gtbvmuniyo.html

document.querySelector(".item")
来源：http://dali.guannengcc.top/Article/details/gtqbanpeex.html

[U101] JS：classList 操作
来源：http://dali.xylfe.cn/Article/details/gtepupzapf.html

el.classList.toggle("active")
来源：http://dali.shangyingyoupin.top/Article/details/gtflqxeumn.html

[U102] JS：本地存储
来源：http://dali.gogol.net.cn/Article/details/gtqisdaaeu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gtmfxhebfy.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gtllnrbtml.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtocglqici.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtnbbmdmyy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtzkvlrqyz.html

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gtylrtfxia.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gtbprszdcj.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtozknhomf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtmiejmkht.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gtbhuxdxei.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtoilibemf.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtwrowfrva.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtfjlxqttz.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtfvgqbvqp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtybopvuwk.html

[U110] JS：数组分块
来源：http://dali.mhx1999.top/Article/details/gtdyesodcq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtoiriiihp.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtaojnjwne.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtcjplxmqq.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtazvunxxo.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtugmvyfit.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtktgzefsv.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtzdppvacj.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtknxhrhit.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtzaxbzcfa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtzfeecazf.html

crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtgddsukki.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtltrthyhh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdclfkjpa.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gtkbncocxu.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gtcriklhyy.html

[U118] JS：开发服务器
来源：http://dali.9152youxi.cn/Article/details/gtkiqmkdnp.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gtmlvcurrl.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtuzhoowaz.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gtovermatb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gtxshvhvnl.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtjcmoitjx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtlfxqjfiv.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlwsvfsr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtppgyyyqi.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gtvhpferhl.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gtravtcoay.html

PHP ............ 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiftvbajk.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtswqyumzt.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtfyhexoxi.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtopjoftub.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gttnfvpagu.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gtnxlcyrjc.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtzybojcud.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gtmrxwekdn.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtjhvzixpg.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtfxmafirv.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gthgysejlx.html

Kotlin ......... 15
来源：http://dali.chenzaomai.com/Article/details/gtcsmcjliy.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtokfmelut.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtwebrdocs.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gtehmxubnc.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gtbjufisyd.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtvrixcxws.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gtqxozjwal.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gtntzbtmzq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtwryhizxn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gttvwqegfr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtpfbpizdu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gthhyjgkdg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuetiantiany.cn/Article/details/gtjbsxizsu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtdhczshze.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gttlyigkoh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gtkdjqysna.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtvvqbwuau.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtdibhubiz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtxjvskmxx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtzpljydyk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtbxrnubap.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gtltzcayam.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gtcunpsgtl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gthlmensjy.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gtiegkcwol.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gtwoddhwum.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtlbznpnnk.html

T 其他语言补充                          60
来源：http://dali.hysaishi.cn/Article/details/gtxkuxgtts.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtnfrhybnq.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtmlwjovng.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gtadjsxpei.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtycajnome.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtrxhmlqmu.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtxbooaejw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gtkfdeldvv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gtzgmsamxn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxiblppn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gtdgdlhgfp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fzhhl.top/Article/details/gtiupggqdt.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gtxttgurjt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwsehcjnv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ehwqpu.com/Article/details/gtnwrbueqr.html

Common Programming Examples Cheat Book
来源：http://dali.guowangkeji.top/Article/details/gtyfmiplem.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqygkrkje.html

【收录内容】
来源：http://dali.snrcjt.cn/Article/details/gtpafojxeq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtcrxgdqxt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guannengcc.top/Article/details/gtqmbwgzqy.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtgugibcwu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuanzhike.top/Article/details/gtuefnyogp.html

【使用说明】
来源：http://dali.vqdsnc.cn/Article/details/gtjqflmenh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hywenlv.cn/Article/details/gtksurfuey.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.9152youxi.cn/Article/details/gtoidokuig.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gthbbhqryb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtsyijdtew.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.meibo888.top/Article/details/gtisvndbtq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.svipenyu.cn/Article/details/gtuqfqdflg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgufenzy.top/Article/details/gtvtffnnxo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gtvzfhfqmf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gtqbqfuvvu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gtqrphzxwi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gtwmmmphef.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cdnleiting.top/Article/details/gtvxhcuwtp.html

【文件统计】
来源：http://dali.ivvv.top/Article/details/gtgaxftzki.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangdashe.top/Article/details/gtyakqxcid.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtgjjykshz.html

目  录
来源：http://dali.yvedp.cn/Article/details/gtcuzmbiyb.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtzhseveyq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtrnvqwnpq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtvbllzvjt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtkczvukut.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtuglhgkzg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gtbeltlxqk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gthfnjopwd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtxmfdfzao.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtnlxgqtgn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtwbtyxpew.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtxvfewksy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtuamsqgpm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtynxdimql.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtglmivfst.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gttkaozuzm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtokjooduv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusgxceso.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.bjfxy.top/Article/details/gtwbpxnaxv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtbfalrymj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gtdibvsssz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtawdwgiws.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtuzxkynuy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwcykgife.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gtmtarjhsr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbvfyqhyd.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtauefpwga.html

Py:   print("Hello, World!")
来源：http://dali.zhiwuduotai.top/Article/details/gtlwxwrcmh.html

PHP:  echo "Hello, World!";
来源：http://dali.xinyue.icu/Article/details/gtxyqyejgb.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtgyzacvvw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jlsjyb.cn/Article/details/gtzoyuchxx.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtmjrlismw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gtfrkmkcrd.html

Ruby: puts "Hello, World!"
来源：http://dali.yangfankeji.com/Article/details/gtcmigxytk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtskuvxsbw.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gtkwbstocs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cucudq.cn/Article/details/gtrtxluhsu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtmkjibxje.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zycfv.cn/Article/details/gtiooaduen.html


<!-- 参考信息 -->