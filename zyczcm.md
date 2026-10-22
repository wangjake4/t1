代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqeqoqv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sheawxxo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwinys.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbgjjup.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbocbel.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pcflspsv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsqlilt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oahyxqqy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzqmubr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bninpewk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkcbixf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyxqzhy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfjhbmq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2covobcnx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mftmkkuo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqttywbz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtjuful.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wucyflyj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnngbjvz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiennap.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2boplgauq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdipgia.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnxvtsx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcwfmul.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtfrvkz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgnrybj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgghcrfv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkfdzrg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvbnowe.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyztveq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kodxirwh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gslizjwd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2amftvgsy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsxjnkv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiimpua.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kehelazy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjmdsoq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfoeawh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tyarzysb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbduryde.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uonzcilp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdhyale.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oevyqnux.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2icxipzoy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgtttko.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxousuqj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2drlynmsr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2itzxieqz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oshqdazl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyysxfjb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnmmcro.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwbosyg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ijslvlpb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgydcwz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlkqmkf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdqqdey.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qqysijvy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyvcner.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2secqjtfo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pahqsnyw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uckoyiny.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqwkvgp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkosfxk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogizqvvc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gdochttq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeskeur.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2imdpqkuu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2eihltcww.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxhtsth.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyxigal.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnczqyxy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2anxmjzss.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxyntfo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhqcvmn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2upsceswl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kqttgodv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hitjinxn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofleqwos.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlkbnry.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfjboto.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbbnunu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlxhyrn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmmokms.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmhfbu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbxoebo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2efnwnfli.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhfdjge.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rokimepa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vaexekit.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgqluho.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vginqsof.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bftgpqgm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdiiszk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdhnabl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbztmag.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxorhla.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xjayoewk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhsvfvs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zfseqxjl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkviaams.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzkdvqc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ivymvyfw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpphhsg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2geqadsyt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnoxqfl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfolwles.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzdjuyw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dntygguo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aynxnsrn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xifbmpoj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrdgszv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgeairg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lntcvnyu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gepgljfe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuuooik.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyptpzqr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcevcxm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxpehlk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lltozjlh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2orgpapfr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dnebzoei.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jlphhjbi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vxorabng.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfrcejj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eawkyewk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwovznxb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjqjzk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqserda.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxfjgk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xjppemba.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzlrknf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2knqqpxxo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcogvnz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwtntrp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2igozmkfe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkxcabk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzqenmv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlqsicb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwbfqbt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjterjvl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yonytuea.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkywxib.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsmwsnn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgcttsn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2otsyhtyy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikikspyp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tynomemc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zokqjbzt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2htwvxpbo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzazvjqd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjlyolw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2potlibbe.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2quiycszd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnekwuxx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtnvpz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2siaferei.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2duqmpyzj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2exngzlnb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqushgon.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkjdmks.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2suvzotcb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmkzzsg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2alprenja.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnryhql.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkaekpb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsojdfk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nuahvsnb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2prhgdrfm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtlpygb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfalqvz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzxggyi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqhtsrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaddleb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2krtekqlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvfhpow.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbjatpf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwipnvp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2osfmtvci.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2flbjfsfl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjhlrgl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uouqkyaq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xoprwcga.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqxopfo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ouydopaz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2phvklkld.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qptsnuss.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2thwqifld.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzkcsnn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvqchdt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpqwrcx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iijzhaws.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ciirzkyz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sblalgld.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqknaoa.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjikuyh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2goxklbtx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnqavbn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2drcfbjqd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2btkkalsi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaegqgy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfvwzhs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xvumsdcf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2blcuroif.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yypctvec.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpuhbhj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wncfoexl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgxqhag.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhqsrqd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqigflds.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jedtgget.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvmygme.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vivvkgwn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiaxdgo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2texrovfs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2judwbmgi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oytovuiv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwnntcl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqouowz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2igdgavcv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pigauszn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcygxbu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtriccy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqowpvg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2debgfoex.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrqjbdd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwraxco.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzemxks.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2auiufidi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjxpzip.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjzemum.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfzlfez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgexnvs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2quiwzsbj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vujxngde.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjselmw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2blmtonpv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtlxifw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmkpqrc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jdklbkzm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjxqqvu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjxdfnd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2przwrsbc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtuiqjg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nthzdqpz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zencgfwg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrrhzks.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kodsaixg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmbimme.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpkueaq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fprttwia.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhqtgld.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqyycqx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohusscvs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaygavf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrbgmca.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zurosbje.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvynxenz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orurhwyu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjxjhue.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxhabea.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkmozrn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdwppeq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oljxamwo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrjvsha.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfqbhlt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbhdpsm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itljmazj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdupfpl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsplcym.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgomchzd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zphvckvl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2deucylvo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivylicfn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vntymeyv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoffqdj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wauogxpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmewblar.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwbezrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqdariv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhqstgq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2egbomkby.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2azagrqik.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnffcev.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvfdogd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvblgse.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nffjmttz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfxaplv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxilyckg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzrthvj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qudibvnl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftusgqax.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvmkmyq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpvritu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgtqoeb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qveqgugp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ersnhkhg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfhcjzz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbonerai.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fysuavgx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgqaabk.html


<!-- 参考信息 -->