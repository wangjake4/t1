代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rimypeqm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadikfa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmbkumh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2scmhcjdh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kotmrrfn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kimxyaiu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2saxecsay.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfagnubz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2anykojdx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcsefpa.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kklcqeaa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2osnrlenu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwhqutq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhmgpmf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpacdjh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaejkta.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uearmcai.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ermwnaik.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbxanfu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2raxxzygf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmladan.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrukavm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2saigqisy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjjpobm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2myciyual.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqzxdic.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2seksgurb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnbwdyu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hedtjuyh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbkizva.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqhqjwz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vljgevxz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqbvldw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gacfnkmg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpulcnc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aklqofny.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lerdmjcw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvwqkeu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zddedbao.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqyihpr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzqjtqm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbucymk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2twoyartd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbkqdlw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmqhifo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzgqbkn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iltmlfdg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2viazbffd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfzkjrr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfynxsm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrgxklj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksxvyo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2etdvfwvv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tijobody.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbonipn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlotfzz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icjpjtel.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqjgfra.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsjcqhs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zceaglvf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgjolzk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2upxxssjd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mymzleie.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kufemece.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwmgwo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuybmeu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzndqug.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpmfuvp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2maglulpa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoshyvt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpvdeop.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlooghvt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2badppdtu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdyotiv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmmlibw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbbhhij.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpsamew.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdomriuz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lworjasl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmcjqhj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvqqpwv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuwzhsc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqmwtem.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnapbis.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwtbvjf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnisfxsx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnvwwvf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqnzzga.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hdurrpph.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzkcosa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbdobup.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkfuzrv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2crevkqtj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhpijpg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoecrzx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2elyiuqkz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hlocextu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbtpmio.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxfdszr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qykwciqi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2matjueas.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2okdjklax.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvuucf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhkfaam.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2seztxqtd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqcbqrq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2udbysgmt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxfisco.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtkfdd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvwoyao.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2suhqknhr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxohaaa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbcjrjr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2welqwvbl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwudfktl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2upuvamgj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcasqrc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ediucyws.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2elezvkxg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyduppz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uugkqory.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsmsugw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ffztmwep.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvjshxc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqtkxws.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyqypem.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2omyfykry.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2atiqtcqh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjxeduv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pknfafuh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyrvtju.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrptjhbs.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpasdjjj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zeazbpds.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbpuenj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqigjjaq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uunednjd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjuzzny.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qqliwzic.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpnokqr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nohsputc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2habsfsww.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2btejgpuu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2outsoubu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpruprf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2doplxbtw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzwdflt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwndiwl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlgzjyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2schezltn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ooirhowc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbecwzj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpczaucn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lommgzkg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdgomyt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqzgyrx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbpwehe.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qonghjjk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrpgmys.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyqgmjv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxwbmns.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwietnm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpevncy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2itcxrizy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrghwxl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeaiaej.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iishnvbl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqocqcoe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2grvvvkcr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xikcwxai.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2drwvcplj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyshcft.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuicxhb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuwgheb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2drgpiqpt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtiwcug.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dejpobwv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epclkxmz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wughcafq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcbvsry.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mztkcues.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmpmykc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfoovxh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2scuxgvsh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjjbvfi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswpyocb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfybyaa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmlguma.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2afgdolso.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xihcuigq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ugukkezi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpusbtrv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2glzfzdzw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiwyrqa.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkromku.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zirbjgma.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mzorcrfd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaytrul.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2owzqdabj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmzeab.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jruaihjm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2txqtazni.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhrodhf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoinbfo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jimyznjf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjwjdis.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsgspda.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2arjkvvxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsnzuhq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dduyodqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpffgvna.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhmheyo.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tcysqdow.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfamkid.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2isonspmu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2maupprbs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kjehttbl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbyptrg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoqobcp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwdwqsp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2slokialv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2szwwvkot.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjbrev.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2namsbhcl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pojvgblw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cbatpkri.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uoktayyt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbdyqwm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pujblsta.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsmjlha.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyapshm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsmlorw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bswdsxrl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwmxaus.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nrweqlhp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2arbawxke.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qsacrhyb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2grkflmen.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcigmdb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2owzalcri.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhwohm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2onptlvfv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqsahbt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsoukkc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjvfjzx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ogytwent.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2opgkugwi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2joezwxzs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyvkynl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcpgoar.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfipfc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oitbvqmf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xrikyjqu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sijyqvpa.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2unwlpimq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfadgvr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wmarjprn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjwjisi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwdjhnh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wpugixzj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhexgnb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlbjtop.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2slamtzqc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bwymuqfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwooaym.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqmheks.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2toayebpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujejqjtd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxpmnmq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbhgwga.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqiigut.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrwbwun.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uzumnxdn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcxqtud.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdeemoz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzrquv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2igycrfta.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nelkqoml.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wglnzecf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bmehokod.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2insdqyfs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mybzspmq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tztzcenm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zodtogly.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqselnoe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xohavlir.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2haifrwwj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzybxciv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xzslhdyb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fmphaaqd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gxacwgvn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lesrvpqv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkhrdba.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2veblmwkh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgrkpfp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etxicmyp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phrmbwfi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avesgsos.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgusjfgb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2regmwone.html


<!-- 参考信息 -->