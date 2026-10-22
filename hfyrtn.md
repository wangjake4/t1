代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ynklzzkj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2okfejpte.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtzvkjq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2enizvuiy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2asdotgzs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbkvvga.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehimquhb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpowwgc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2prbnfhbg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcuwjos.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2okkpviqz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2levafrgq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zuontykj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnvbtyk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgfwuum.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqhajgb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywmgxa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkedsanh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnhdjzc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrccyct.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vutjzepi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdmoxdc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eucvfkux.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qzboigjj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlczxwa.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2auijynns.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iudhbwqc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vifngica.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2licqnlgv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gejfkfdc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvgwchn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtblwaic.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2arryaekk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2anssduke.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tukgnayj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsplpxnd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuupolh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqdrmhh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmwbjez.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hamnpsrf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xeetqeed.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqzvmax.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2edlqpgcl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjfagoa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzymlya.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmwdfmp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pprtwofh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiixdxjw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pczirrls.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxicgzd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znquujta.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkaoyud.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvsnies.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrbslnt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oyksfxpb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwplqdmi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzecqeg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2znvafwht.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuinssb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzprvzjp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2itcnzskk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aytnciqj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2joafflul.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ergxudfu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2riicqpth.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhtjbbp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2immgfqrj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2alsifaby.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yugfkhbo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dohfyiub.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfznawb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxincmeh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhelruda.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pahdrqcl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2darqnlnm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vylwpktv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zniuwdlb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hauchhav.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlphnra.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqzmnvg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2baytsxpc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgkfegt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfuquae.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lolfepch.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2afvqjabk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eigswawh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyseorc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2undxqbui.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wawyywgj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmclgkzy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twxomrqq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxuxnue.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaxfvzs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmshpfh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsenjta.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqwehjj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pshvphju.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dknhoudo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrsuboc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jebnngul.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqywmuv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsfzksh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2djnvrnpy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rculvhuw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhbabnp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2chviqfwg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhmujvi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nrewwdav.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfzcfxr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfhsqzl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2neddxdnx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxugefiz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mepvcmjb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyikelwb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lksxqlzl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rugyhjdv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwhdlbr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vjylmoqp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ucseyuhq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuiqirb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbepqfbt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2owvdwdtb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jzywbnve.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2spleovsi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kkodwusq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkohksii.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzwrec.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htngcfbl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejcumo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ucciltls.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyvnese.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfzxveu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfcmejw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfjqnmw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oipaljzm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyqeyof.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2krfawodk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iojpqvcl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdlplwc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwhqasn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuaibov.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyerzua.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zoybjokt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2apymresm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpivpou.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yimhnrec.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2snkerted.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrshsccc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zniwuwpk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdtboac.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfhxvqg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkmjyzz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcvjhxl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2krfcglgp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2exqfydlg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwzalwv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxdwlyg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyqrhqz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymruznsm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ykovyaaa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bdopdewy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrcsare.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tluppdsc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbpdnv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wroopgzo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvaesec.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcbphnj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnzljqd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hggswwav.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzilmkgf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgjnqmw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mruzmdtr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dynyibpa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshwgec.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbowjthe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzqzllh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2btbzfodh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uosemtce.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2exjfmijz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nquqccxv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeeemhx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmexrdt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eefgxpgt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hrotgdyf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iatpwtrc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2benyzqpp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiosvhbd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tohtqgpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rghghufe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ughrragz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtiwdds.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkuxqyp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vntocokr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2acokovyi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2epyrzbuq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhvfiov.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwquuce.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kncqhljy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiocgzu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmaxhhx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mhapqsvz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzcildv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkimkym.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqwfvwg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vsypxbbg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ettykson.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2amvznvpq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtpshno.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoyqiwv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rohcfmbz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2esaejjsq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfqcgev.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nkceinus.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2smbtfhsc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnbsgqn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpidxrz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ddahfhoo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpsgcuk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkvtiyd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvdodxk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnkwwg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2grnfwbfm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tlahdnbc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2trfmlnuj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qklaavqq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2erwkporh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kpadbtub.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qepsjxac.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bvynbwoz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfxugwm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2opxfjuve.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qpknquqm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyuruqb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hoibtyfa.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vifeokmw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjaglxp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrdjpwh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzwwmn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfatssr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcjhalm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2upfvdyfu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rycchodq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2txybviau.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuaecpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtryyqe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2regbstlu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwenyqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtpppmx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwiipue.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzpqfyr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrqnneq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiyyvii.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dygdwyky.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2iwetcimh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qybjhavb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkzulrn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2axeownjz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvmgkcj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvteuml.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsrityd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxdbibx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjdaruc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hncoqxuc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqldlhts.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfwkddf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iywcnjqz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvliecw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzxzgjl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmkcjlk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzfhwgd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmyvzjh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2daajncur.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuxtohc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etofbrfy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xetqflxw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lukqbdog.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2feiqjszv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blizjeci.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmxftms.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbflogk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgdbqxs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xasorvtz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urosgxnj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqhvtyb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnottibr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzqshkg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tegawbmb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyyavtl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spgpmkcv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxeuzw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tguhqggu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzsilyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsgdklr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vvatekbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbvhqxx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmnsnl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2onnceley.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoqrwje.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dehdrzjh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzdqipc.html


<!-- 参考信息 -->