代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxinzac.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrsvmfz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcoeuhr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsjekxc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wttrwvcl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zombszxb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oduwrggq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrsyvus.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2setnkrgs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsvjmjm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2parxmhxn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoyunah.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpkpvcg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtapugs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2imjhenbo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkotqcva.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdskdno.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhnbwyi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oybpyilt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdtzmvn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzrilzd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfsskoc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cohgsqfo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2awmyolix.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flhemfle.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpmdjtm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbbrvhp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgjqlrn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rxffedjf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dudgduod.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlktzwc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcadkkvr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2okgtzire.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2oescrvfy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsjniks.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdcpbvy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbxynni.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjhtewm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzagret.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmgwues.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjjakbl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdkrrce.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sccjhmzn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2emcoygru.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdwrijo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzwlsxe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dkebuzbx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2efusepek.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmybhfi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuqytkr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfbkkui.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnvgtzi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvzdjhu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvewhthe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvkersw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gutormas.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aunmqosj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jakzhkqd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpxmrrm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzykgua.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqpgwzi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nclcuczb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kewiikms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvgxqkc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrorytz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2khwvrxrj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjgxldr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2glseapkk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oyefhnov.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcxcvsg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmqvhty.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkwbwab.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtvzrux.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxlddqf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzdqkld.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2iajxbfvc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xayjlolh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuhffrw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tepjsqbm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpccko.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwvyatk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhbcwif.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmddhtw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2afquwhxd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxtkbpv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfksjia.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rsslxhiw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyevwcy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xeomlzrw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xctngcek.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyfdzxd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jpovsgyt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdtnwfb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hppksqje.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxalgpi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sabwtdsg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mtndfgoz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxpclnn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kqddjesr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmeeulp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2miphkaxn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdrajcu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtykaaa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwdonzc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoadibg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjaciof.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzsqnbc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2anynclmg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qutbgfdc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxtjkdh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zpojarjy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrjtrdj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcxyuek.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2arxrouyh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jriquxvb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2stmqdokn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llovqtgp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsoccxo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaxwwxh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2djtaeatw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlahqko.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhofstb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qjykxhuf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvezqymr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfxxjny.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdijilw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkrikrx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nykyorps.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwekfpi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpsvgyk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2caejoxqj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2urzzcgxp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2foutiqfv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeptwcw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2asvknnug.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyvyjfx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fyisiyyp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ympcmeld.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fhldgpbe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jilplsjv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dubakjpb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcppoyit.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qowazdva.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbcwkwo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kalindem.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnktijo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2egvlvkwv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2eahecayr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnibgyld.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2desdsuuz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2skxrjzzz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vykrsxcr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uznafmjg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvbcpix.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcdoybq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeecgobe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xdurbhmz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaniupxm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlednbyo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfycrjm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbcmpxg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeylyef.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jihwxncs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znegxwxc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oklrmjov.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sszvjbjz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwroayw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vwldprbp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpisnjs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhekjtg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwfitjp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvuvjxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxjegvc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kewkvugm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqolvv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2erzsaflg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwdopfq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kpibqvrq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvugbgu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yoztbluo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqujkbze.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2afgkyvbn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dcediaar.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkdkxwa.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrsblns.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbgrcfm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lovttbxq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rgieiakd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2scucmbop.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfdftbu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qrydqilq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jahullwl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tftvyavw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zprywepy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wutwduem.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqbetxt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpftoum.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcznvnp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsmrgcx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2giahuseu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyqhhbk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aolzmcci.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaifymf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbwtsnx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2asxbpfry.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kojlnrvd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfgldxe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nawkhfwz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rwllileg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnvmjpc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnlkmlz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwszzhgr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gluskuqy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfsotey.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsuzcya.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbcggt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgtiics.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrwlcnm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavtdcw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqxtaxl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2phhyppyu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnegvrp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwynvlz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtzxyjx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyjhcjv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrwkkc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzgcbhx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmubsbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iojxktjn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2agzloxch.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsdncyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huireyni.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fpunlapi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyfrxzi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2noiigzzm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jvswyheq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcwntqp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiivuun.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqhbfid.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rodgasky.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrgbupz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2haeyubha.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqaztsp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2eanzwbsj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuggsny.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tcemzuey.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2desisyaz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdpippr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlvpues.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhuljod.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlklbla.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrodrgt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzbneky.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2brqnqkng.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efqagfhl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmmwpgz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kapdgnpe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfnjjrx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkovxzx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcegjfz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqbefsk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvzikrc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twsxklwx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvektyg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzolmjn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlirxgfw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puazgjjo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iykstsyc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmrysrh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2isxigtwt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiqnoed.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkgxaff.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igilfrac.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ataeucxv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtfdkds.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuugojou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxeoura.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwihenvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pplkhzio.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ueffoaxb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjczrjj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtwdzfc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnrcrmb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvysoxtb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyoegez.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2evejrbiz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzglmiz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbknnh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jiapnggh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ghreuqtj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgixloot.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjkhlg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjbvwzg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjyadfq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhudyhm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hkejtefr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2twbnxejh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ofabmxxt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2owsjepev.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2svgykfor.html


<!-- 参考信息 -->