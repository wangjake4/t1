代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qidpgufy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dadyuomf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2huzcpicn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2akunewms.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzqxnlr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mectxxxo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oukxfygq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kadvamcx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmmhhwf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuapzeik.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dqysdzxw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgwgmoz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wdltvkjk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdeboiw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uusqcgfz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvrmrfx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lzizruxb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwagwblh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2flmzwcaz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qifsrpow.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2esiuuxed.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkgrput.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbpgti.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhewmof.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcydmpw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozzpvaa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqpzbmp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaexegp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqvmdmh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqamsioq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzykjzue.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ualhjqrk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fiirknol.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaujcrf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rjswduwd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqfiknn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxxpghx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2iuljwklo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2doiqmeap.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nagzlnzi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbhpivv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnurbth.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgvqfgs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxikjsz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2antiuhix.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjdsigq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iixjqkhv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2giievkmx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjthruss.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnbsple.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jymbnezd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmkmiqj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xeksnphc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgkidlu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2llhvhvfs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyepjhtm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjatngrq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfhimht.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dwniadah.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtfxnve.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2plggmehl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexgdnzo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jcemhxik.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jejqdjks.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dovlfgua.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpumswfu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhscjvai.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzprnwc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kdffhvkp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfhhfyy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dsotemwx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfrlyel.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oclqoead.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbgqaww.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zrneulio.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzonbney.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2unaqhynh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqgvdpg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2alidhobx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2naotqxjk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvrzltn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2knwcxqda.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vecukrnd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gukzglws.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbaposv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhwllja.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thpcvfeh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtwxkpv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdfylov.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2adkqzwxo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfpfckc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wybqtpkp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tquwewmy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbqatwv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2azuoxsfo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tzofczyh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wzykoqkn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2izljnqwm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vedplrhs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yddapcvx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpozuuj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2arfkqceq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeyuaqy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpxhole.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bzalvtna.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnvqydl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdcbqrj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbezbglr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgpcslt.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rdriiknr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzbccml.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgfkfcx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eezgcnwb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwizrocq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvpjdha.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqbehlr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2muxkfxgi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2riyjvnjb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfybuodx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwgyppp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxbtaef.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmopdmx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gmguwlmy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wignalne.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shgcftyy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmapxfh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oljwleki.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkpuprf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jupanxtf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxhazee.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gxebsdja.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdylihe.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2niqpijxj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sntyotsg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwlpbuf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxvkqta.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmritns.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbplpmm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zybkvenq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruulgebu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mrprjlkl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvaklbv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rigotwlx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpghsoy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlylrwx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqxvizk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzvakem.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhgrqdg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oyznepah.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnxcjyz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpxcnqn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fitaekmu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxhhgkv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkirzdyq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyapuiuc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzarwcq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnmwhtv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yohsknsb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvcvukp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmqvalb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bzykcboo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2btehrsnk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aotibmpr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpilnefg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrcgwff.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2esjzbxtd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdmqetq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jedlycxm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fyksnpxg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqsskrz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gahdmcox.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yncingjl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrefvst.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffgmvw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkabqwl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcscxgl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dsipcgbi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2haakoltc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrxngdv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdqfjka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boxttiec.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxipijx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnawtczm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2znwbkokt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dbswguwc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2plhlhqdw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2warxvnsn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvixdca.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzhqdvo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwhugyt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmqvgoy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfzfete.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqrsilt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hlflalew.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxqitis.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdmjgjh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2afhfvziy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlcxsh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgdeiek.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhfiirf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bbitqlcd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpfcuxu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzudfns.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ryteizfq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmzocae.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzxcqld.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhfzyun.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2injfolpm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdcwjqd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjgxhnv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gegpwadg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nemwubtn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdzlhwi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rblfeiov.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhizsbtc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2niehirqn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmdyzom.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lflagiol.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhfbhru.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjbuiqw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmdekaz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzsxinb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxtcftd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzgodq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2azxfwnni.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2htakonsh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjygguk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aofkcunn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaqdzkk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgdfmku.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2syukfikh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeusxjn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2djbggvks.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghahwphe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2szbgbwua.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpzzigp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyompusl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyakmeq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2myccqrbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvsttrx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2duqcipxs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2eejtwqtg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zkekaftx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xcougnwq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2snaugmcr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bocylumu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rguxxbzj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2esatdscv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhthlvq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vtovtbqn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2twtqvbui.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwoelnb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zatnyexq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wddwabuv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kycfcpqx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtqnjbq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhewaok.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eleozwwc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvihcpt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2psrsysye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaaneer.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaskvkb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnijfdy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azwjghbw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkvrdmr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrvfvsr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iujhypgm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjjpcfk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjypfqw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmmgvaq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoitahf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smnrpluu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mttpmdid.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chwloluz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yafexist.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxeuvpr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chtjiqqa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iosatdet.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgdzdeh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdvkial.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smywxvvv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmoqtmf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrfrahb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgopwuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcvzkpl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrzmiuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aenahtse.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anomdudb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqfaziz.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjlordq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvytqwa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwrdyqj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeghooh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eakdeijh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkussadv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsrqwdj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2sezslxvf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuzhevk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqacuanz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mijhoeal.html


<!-- 参考信息 -->