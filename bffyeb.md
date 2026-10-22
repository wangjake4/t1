代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gungucet.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrczniks.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2njxlrzpt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtchpey.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfonfbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqvzhrr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpalakap.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxpibac.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lgghcqen.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtfzvqo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ierggmrr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bgewcvjn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kkszbnhb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcdrewz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kislyqoa.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtqknfb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ordpqiwj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyvijdd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uzntdkng.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vepyjwkg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2swpdsuzs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2uovhdhur.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcegllcc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkuchqi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smktwiwc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvfuyww.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxxzqmq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyxyfot.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2acyuedxv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgovmeo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvwutag.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azaovuru.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2itfbyxmi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cbznncna.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2okydlpvj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvlsvbl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgzjwna.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzvjmzj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqifmxwe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qelffbjj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcfzvrl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tunmggoe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqssyie.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsqxmpq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyqszuz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxduyobv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqbistk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhoktxa.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2foczgyyt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjpdkki.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sieooopz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2isfougwh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjexebu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhflxlu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2siupqtyp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nprkgpyr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bljtyxoh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bumuptkr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tluepcey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2esyrcero.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkdimob.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjvgipq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvbzetg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2frornxsm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqszgfb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wksbdvzk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeinszj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkizpw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jiconpyj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2biruyjjy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2abrvqqef.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxhezik.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uebcjsdf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcefcnks.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpimcrqw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfegkei.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxgopkt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuqbitp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2chvvybtr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oijrwtbm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yuapeiku.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndatzrqb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wszsvsec.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfvlzga.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hoehnzus.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuwcybc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxkstvj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoiglpz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfrhrwr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pzufeyga.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnaxrdi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gitiferc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlroepy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2atmhdcpg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cytqqjkn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2glwcynuj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmwucai.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnyottw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2presriwp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwhmnwx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uiurgugc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsulvibs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfqwqnu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhrcezu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2srghuoiq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrwbgim.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqhcyjp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2moeqzcvf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwytjcv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzflfxjh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gszqaovy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpizaapa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvdcsj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbxhubi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsdhfyr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyjufii.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsetmiq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsmpnfv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzdosdy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2unkxksmo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfeuxmu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzirkfw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2riqkwcny.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkqkvjo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mcagdtci.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjgkcef.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxkyxwr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmtnjgf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjbsgle.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2robovxrb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgqcnhk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygaqrq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iysslyua.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ujasswav.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnijqcp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtcnksz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxyrpex.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wolfkaqa.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcnylyb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kijqkbcm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxiqajp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwxbzrs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwlbto.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqroldor.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxfmesk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2afwbopfg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrrzdyc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oizlxmhs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2foxnxfmi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2otzspafh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2csszdgef.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ntumwbeh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbaxzzk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxrvqrl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2htzcvpfu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2onkheaux.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qoidvdgz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhowxgj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rncwzeqq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rklrrgtj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfptitl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kytsshni.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrornlt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsahjpqw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2miigkxza.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzidsype.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpgjywu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxqfxje.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmljvnu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kuehcmmr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmzrsqf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsdlnes.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nklqzqho.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhrobzn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmweqqv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwwwnas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvftsxr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsgineg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waarodmb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyevanl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lukovyep.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmbwvng.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qifdosqg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2utgkkdwl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2orgcdktk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmwdnqb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ruolwcpv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtwqmpc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxcbekm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2urjoxfoh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sayipmjw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhqwthv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfyagar.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zcujjfun.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqhrlhq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ipikjrwg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcijbqv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rmigpdwm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dykivpmv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnnlfnk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuuwhdl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vwotxiha.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcacmux.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzircbm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwjdhab.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pyadwsqe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2twldosrc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhczyby.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pifrjlqw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfcpllr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkrhuua.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2odzfoype.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yntlwijo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2whumrpzx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2apboztlr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnxixdm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2alcxebyt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gqntguli.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuccimt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tazxgkvz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jogbtdxs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2akyypbir.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfcylil.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2twqutdzo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjviain.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqwwvqu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtsircv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvvnzdg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqirely.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqzswsz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxyqwkf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfmmclp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeashoj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2totswwbl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2glkejmge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxkbcri.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2inooaoxi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2slmmtwan.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mxenzpvr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxjcpje.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkngkzli.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nnutogza.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuefpnu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pgceiqsy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2naspsksx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nekcgtnb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hrliosyw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2brtdvyzj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdmzbro.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbfbtxe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfhlyds.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqudzkz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvqtjbg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbptjtj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzgtzoq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucidelyk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2shyhxwhd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjofmbh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlmpmpx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmwomsu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzehgzh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaimglt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giolwejh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzygvjvs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vodaqnno.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pphixcos.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waumkgmb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fguuewui.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fllbvkqm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtffbujy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewftglwk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsvabwm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgsohtx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakiwyd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zntpless.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrorgxx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvoysas.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrmnfho.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2krweodsv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhacvsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xngjuyfs.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cinlqfzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzdnemu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcrkiuy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tirbtsnp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgyrudq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjcyko.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zboctkvq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuspihun.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvnbraw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdekhgs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcrpaex.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvjzoyt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlxvtzt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mupimlvn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptockgec.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gllappsw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2icfkscym.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tuszthhc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnhevmp.html


<!-- 参考信息 -->