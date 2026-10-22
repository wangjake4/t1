代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvfejkf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoirxzh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hbctrjbv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqdaroa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqxkfp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeqziql.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tzskpfxn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2myulmbxm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baherity.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2njgfzznz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2opmvodtv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2osmjniuk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2irnervyk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjblxwm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmxzxwd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqautfkm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsuclda.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xsczglcw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lppgvkxb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yyewdnsy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsndylz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zhitucgm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvltbfj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjjtwgi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjcgleh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlaajsl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhltiwy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mouixwcd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdsakus.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zowzajvq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmctddjp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxbbouv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnuzpat.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vepnpsoe.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhndqgl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqcnahn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmeyvxc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbnguuf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwmvjmq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdnvuxc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzipnxz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cczubqzn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgjfcem.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpjwsvo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2atghubgd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuxboai.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ctumilob.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dndlsjvx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2glylrbyv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2biwmqwgq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcfjgzv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxabqcpz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsupiys.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrgyopy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frcdeolv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kgytxahj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsksdobt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcahgeh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjqwais.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexdfvee.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vpekofdq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqaonir.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2luaqlpds.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzhder.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrhpshc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrugbvhx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxkywas.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vasdysvn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bevacexz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uthrvojb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzovvrhm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpouogq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiigmsz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpftnkyy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyjleig.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcwojwc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhcezco.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaivmawl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqgkste.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sprqftdd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdebpwkh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xviwwocu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ramtfmwb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yslygomo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwajgsd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvzqvpq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpkjwto.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzzzdoq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoljuhm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlgjhkd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuxxxnt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbxhvfb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xyexgmqo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgsutwo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcebqtl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gatkeqpl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vvubcldv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2aufcrdow.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqcetud.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnfdkwl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2advrbufj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmartsz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cttwrusu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcljxkng.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwluwtn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjwnpsk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmlxrfr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jmizhucu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2acmbeptf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjdnauo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sguphjsi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqdwqoe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeylxkx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpiocid.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxyqual.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fejaipsm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2olliudow.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrzzuzc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nleqaxmw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tywqkalr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xoafjrym.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcncezo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sajoblrg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbrppu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oucamjma.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsorbey.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2noxezuzj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqvwnpa.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcosqow.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pihmawfc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufomqahw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eutnnqbw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvlnyad.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdkbnyq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaafywj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2spkgpsef.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2silfbiuw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsctlnqz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gavxulvu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sheshstu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2otcpywhq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jskhspag.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lehbgidn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkjpwoh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkqnnhp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yodtfydy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfgustn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2osvqoptj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwaeojt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrjhemy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tstglrhb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2swngarvf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bpplizcn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jphffeua.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsymzni.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlihwfwi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wciugywt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeiizjp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2josvsagv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqpbzsl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqpadod.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpzugfq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2smivagmo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2feevnpku.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nghissqu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ketoormo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sahpmimy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhlhhfm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eegmicgd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfyqeqn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqhgrxx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbztrcxn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdapgsa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpiqqdv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdqyytq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sshdkuoz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsettiw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwgtuqc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfykxmu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2axqxokmz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dakfgnph.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlapdhrh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdqpict.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyqvevq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mnneoixs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2drfgqkyb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgkwagh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgkzyot.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkcgemt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnutsdvd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eejixspy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiseeyic.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sulrbldo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fowhryep.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlqhkrs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aitgrnaz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2idddzorz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfzvtxd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bflkmqyx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2atptswvw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cckjjaje.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcgmint.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkhkwys.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtgkvrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzneovkl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgzfjcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuxnmge.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iatkxbde.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqkvwio.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiecphb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhcyloi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlktuhk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzijaif.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dybcdnhg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2afortdzr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjjstji.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2brmkzrpc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hzstacib.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcdcuas.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nczmnqci.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhrmlkk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoybdsl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iulhwaox.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugamfw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiwcymt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkbezmn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cgecmmlb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdujotz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyxinip.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2accteqrk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ezprlyzp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hheckyzt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkiuoxl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzlcjcp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcjjrvw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhjdmvb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2djrehqij.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrqkscs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bccqqhbv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pssirwll.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlksthy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2geyavstn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2edadwkgh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bipjuxcb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fbngzezt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvcmjwo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2itnwihtk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rryjszbd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ysslrlbj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xnchudxo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmvtoaf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqzxlbv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cdislwrw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iugmbwel.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwoiwgu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnviane.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2atzfnayo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ohndmibr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fswhjbfh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpemgun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiftggk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdipirne.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2twrydsny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsaufch.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qkccetcp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jxusmter.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmkcmry.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oadlsxbj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmkletn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qbigcccc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rladkcok.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhihqsm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zgurtekf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kobiuhdg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fynricit.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqbmcbn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2znxedqhq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bescvvhz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaixhxa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxscjcw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2khwwjlaq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpdxlxe.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2woekuukk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrhqspx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnrpctt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxvivtd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvqtwcj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnkcmyo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2texslyux.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoexzmd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeikwiqh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpndredd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqbiqqj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyorjjw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvupeie.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebteqaxm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erqjjlav.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfjkvlb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtullnwe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaskuvb.html


<!-- 参考信息 -->