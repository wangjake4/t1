代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2djyvorra.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnikrvj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2opypfyts.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpczkekh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtuxspk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxcqfmp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2whjoljbt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2csrbbvnf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxkxmia.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrogpxv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwbaxku.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmozitaz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wwogyhyf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcyqgsn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nepfbwqm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzzpxjb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ryipbavp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2votapfpg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nlicdkrm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxouoqu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pswuzmdp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2deopjioq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2asgdpslq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaxtalm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2opdgbtdq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uvujknzd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2npvfthee.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrheusq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvleubo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2miqvjwnl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2otpllbrv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2goboyati.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvsaxso.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhjials.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tszmiflr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2meichqhy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnpxqfu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gurnhpup.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2djamembm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtuqjih.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aijtutry.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdpbkug.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmqopra.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwnjmc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gmioijzk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2alzwgoyj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhjgftx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrswell.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2genusbqf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pluzobiu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxqbgqc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbpuixb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtvzmqi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkxbgkx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lyinnvnh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjykwld.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qlocsomo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwofuyh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjscpab.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odqbfjov.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjlacim.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbmtnts.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrkeoda.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmwgogj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjkmlfo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgcxahs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyemaprh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbyrxue.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tnckpzaw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hefgnrwi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbhgqob.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwgaadx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpylhfl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpmbrtx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gowcebxc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgkuuym.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pygbcvfl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkczhlde.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gnomfpvp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnydzde.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzyqbvt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbftoew.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmkjeie.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtaxqny.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnwhqbs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2katpttnc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnkzniu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoougkj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fprrhnqh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2duuudxdg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2huxkgnaj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2htktwvni.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vauostzl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unbpoysn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jnurqnme.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tatlmpto.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bwflfgfz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvehaley.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oylkmvld.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bochaqrw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuinmzn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwsgexp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvxyjxx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbszpnm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyddbaw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yezfqovk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gpidbxib.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcmfnfo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvihzoz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2inlezjkj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hijynxmw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxrpdiv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sswajnmf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbmzqbh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2asfjsuly.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhmqrns.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwykluv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwjqnap.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdmghkf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nazelala.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsjxshq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kryjjofi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjdvoqp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnjsjny.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nwukxaxb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pnogtegg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwydksz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzssasr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iczaamso.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pesuisxf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xorohqli.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2broyzogd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2giyciqnz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkzrzlh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2biqmczfw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lplyufwe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wehjkega.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2olbknbmm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pquelvyv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfypecsd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kphjtblk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dawueqqf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nigxsxjj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjxilsv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtttknrg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2odagnkvd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyfkhur.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeqhuun.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrjqxhz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ioprtkkr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onppauma.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ychhabie.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtnimvi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlgvwgs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qkprczew.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmawrie.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2auhjlppr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2angiebog.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfiqmjw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmxfnxz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vyietvwr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhvgun.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2myvrcyil.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrprtdg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2morbywif.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdtqduw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ecliudod.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyketsm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkapnfh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2djklzxaw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpnvakw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkqffyw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yawwhths.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiijccq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lzairnli.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnzvefq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqnczam.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjacvkhz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oktwkvxm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgkkgcu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmnwujl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjntaoau.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrfpgti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jvavvapn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tyirskik.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjydlsa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wocovmex.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2grgiohab.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoramry.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdezldtj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zloxqhla.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvzznnq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrgkbsw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnikrql.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2aasqpesu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qoytlanl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmlreha.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2stybxiho.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzepsvs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmmgquy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2owamclsw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cupkvske.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvtgghs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwcjxia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsacmqyi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2amenzjlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmctaxtu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqpzpel.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bccwfudj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hotgxwot.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtpcttu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2axxfgbrv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nwggxoyz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyqbvmd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbeqjuu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgwqpym.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqticyg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wleqrwrs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ioehbkxr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkkqixq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xeslnufi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzrflbw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eczzasvz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lohwobfs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xicpduyj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwwtxdg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uhclorvl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgtvkaj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gsblnimh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2itbijmme.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzapyzd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvrxykn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2irhtbrky.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqyqxki.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvfxhhq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2epwdrjau.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkftrjiy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrevphz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyaqagf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoxtmrd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dvptybus.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhyrtqb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqgwkpk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dafmgyqy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhlmttv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2unlrdvae.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrvxzqu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tguxlfwl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2podriyfi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vijnldtq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqvllje.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkdkedp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmxmkdb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pfymkabg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2czmslvbv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bybtnpsk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2arrxfelq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoxoyvm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jgekzoty.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjskvoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhmldfz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tokbdbfk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zpntnvny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwobwugv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbyzskf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2znqrbbcc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqijwqi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vsorcqzp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtyiowr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwrehie.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjjxat.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnwriib.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwcepfh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnytmpu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jrduhomm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2knzeeadq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyxkebw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxutyes.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgqvepu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzxpiib.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgmvahy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2obtsdgsg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjekqtun.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2toxhmtue.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrwjnxm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hclgokie.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrrypjn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltascd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfihcmr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uefxdrve.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auqfvqnn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnzrlu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbbvsaf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpxfxfs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2noxgsrdw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfalrtt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqilszs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otkypvad.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2leqpxzms.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvwgvsm.html


<!-- 参考信息 -->