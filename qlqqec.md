代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmfypyz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdffkgl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2buivaxje.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvffxekw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxzpigu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjgrux.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gnujsjjm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgzbzcr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpodobv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2htcgeuuq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2duyxnxqp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkebbxm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdassdu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ricjusmv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiiqbbn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wanfqfkp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nidfiftt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2byyclepx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2txczqzre.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabksjbi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hccpbjyv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnzxtqi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2thohzvyv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2irfasacu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaewygl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bianathk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igfcjkqb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkpkpcu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjeecgu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbyjcfi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhrxpix.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqecxvsc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cltcgnfn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hypvcoky.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vukxpsvl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eheubhlv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2evsohclb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyooabxa.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yntzhqni.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpqlpls.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tewmkkfx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmsixfx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjhztba.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfgyjtm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2atsfdwig.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdplhwi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfcliom.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrfexmd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2awjcxjjz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgyfmzs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rdffgxuu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cimxdbvv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqjbxfd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjvrypw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cehxfxfy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnapnov.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnxrmqx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rncrxtdi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwykhqw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhdgaqp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrofwmv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2itnjcvpf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2modvnver.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyliyizv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrbztks.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvgfuvx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsqmize.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnvgsdu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyqmkwt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygddlpbh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2enlybmlj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsauyvwy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjvtutk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xknzbanu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzpqksq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hipjqcvv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxwmohp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbzgjve.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mipwjrmv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rftovvuq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwerlki.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciafbwqy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abqfebkz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoebgrcr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uhholgkx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2codseowm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnepwxr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkhbcxo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dutnqmsa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnxyyzi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jwltiwfh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdaodea.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2odvmtitq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2khnsppmo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdhoooy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ahczmhay.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhbukqw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2usrdbles.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsyxegj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2joxezvyk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uwswekjv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlikvwr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiegjqi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwukudc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaoimwj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfnpvzk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nfswazew.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrfzsnp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuswknu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2eouwmesi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2elmtykdt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqxlkkn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyepaww.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vehvuybl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmbbayz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyvvnzq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efsxsmls.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeowzlc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2drkuogmb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kafujict.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2isrcxydk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tykqwobw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2voivrwbx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfshstg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuaxlgk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2exyysdfz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqqucod.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdffgocd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhownbf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnydkwgw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rydkmvsa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfirqjl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkjych.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sswiikfa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sejtpobp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwdqsds.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bysnhznu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxwcwoy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhrbhcw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwycovhe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuocgqk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpzxdfs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzpozkt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpkkkrk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2smrezaiq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2doeyemdl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2focxhzfh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uioiwqle.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmbfvey.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebssabe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcjibgz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlliceb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rsprmktm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiuulxt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tkylorvq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwsbieq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeyblwp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyeducb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdrmeqp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrukjzsq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uwetdrha.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wptcuill.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2smipnqlg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyenruq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zagjsjrx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpxwqcx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2odanvktj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlxnhit.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2noygckby.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bbizmzbm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsywbvj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvvgqqf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwoluys.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhrcowx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpyzcrx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2numdizbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svigvskq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcdzmiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqogzxk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyemcre.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mopezqeo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsqkgqp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbxcdvk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2flwouywd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2orgvslzq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2erkagiyf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaotuwd.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iesmctrw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2admmymer.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dltcsspq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiucffm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2frucznxs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhpsgcj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbclrla.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhpeksi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2myqotfge.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mdagpfyq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwjukiz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mrykoblp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2luwphwxc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxgqmpo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2abpxjcgh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vimgfvvr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpgtjhh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2stkphvho.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2csxngnkc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tlafhpiv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2urbkkgtw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnxzocm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gqflabsd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxggkwcd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsroacm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwsyais.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rscuwrbb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzdiohz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bslnscen.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtgqmsh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhzqkbp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2egigzwri.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kscsboxz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tztepeqo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjdgjzw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjqtjaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2intyhwht.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2buluomdp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbpjuqw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqflqpy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoqhjck.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qccmlryv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2snpzrzvh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjknmis.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ticujpfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwtvods.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nagiauae.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkzjets.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifibgaae.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsoeqss.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeqpgqy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyuntui.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdaeghi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplriws.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2tkonddug.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fazgtjqo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcjxpxs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuloxsz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlufqie.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wzncmljj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpekson.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcrqvns.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bllnkrgn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mgynvxfn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ablcsfnr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2inrygapk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dllkulhl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrsasbp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mbadsxua.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pppjxcrh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhroqwo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiohpda.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgsksyq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlcvycm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzfvhrs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgdwafb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmfapnx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjemvro.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwngpszz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zngijakc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfnpmuy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbfyzly.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkimixmk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrmmcij.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mprapuhd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytadfqaw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfnslad.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbnfziv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeermaj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aydhmfhf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvllewho.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueksegti.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtbpqnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enrgspri.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkohjul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utlksbxg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2refrkdrh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fchrxiwj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dacinmrc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpjbbmi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhldydf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqctccmp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzxirsk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcutdfx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2awvzjfvl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzimbok.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xwblfxee.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2imiqlqld.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzsvtiv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryglbasa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbwbrsq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnaqeod.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ppneiplr.html


<!-- 参考信息 -->