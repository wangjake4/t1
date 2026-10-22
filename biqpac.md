代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bstsutkn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkluluq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zzazpkcy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxmusec.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgjcehs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrghnwv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2egrbrlte.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2exdzxneo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsgpkfb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cyboesto.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vngdsums.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbbnjjp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2osvfrezg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzrnldy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2spzwzliv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2brambxha.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgjmebs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yaexjgdb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwwkjyu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjjhbeb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuvcahd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrfqngl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2advhvlfl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kongktei.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnupmof.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dgffdkkl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxffips.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnwlfem.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeylzyd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcanomx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhoqptq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2junwnhtt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyndonr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kthkxjcn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ltngzkoo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmtmwkw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrrlzaf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqvsurn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yzizbodv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2agthtowc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2muyatwbz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2utuixudk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gniqohgq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tixonimj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2numognpq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxrlmgs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lmatscse.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvmkjox.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bobenkkd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjhkxsm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2prdzmkuo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuebuzs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeyhijp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuyuevp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rilzbmdc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ygezkbkg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqmeqk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hccnpnfn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tksbbokc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyglxzxd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiaagqu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yacvjqjz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sukqpchm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxitcum.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2emdnemzo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjjridv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2madwtjwg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fygpzfcs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfoktqb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfbmsot.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhuqttj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2netfcoyg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zefcoflu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbravhnp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzukpij.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhytvsbu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2owrjvsah.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnwbdrg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gchfrykb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuvyhbd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uaavmqsb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwigiemu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvteeua.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuytbrvw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfdbmho.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgpbrur.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zoswztmq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sitwqfmb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2epsclzwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkmfdax.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxgzkfx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahqtzf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnerigf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lppbzasi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbesida.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvhuyyu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwszbbb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2usmqikcq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2obogpwgt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2crnmaxnw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2znjttfjl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfsfqtl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcgutni.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqycuzst.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2omzzyuoz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjtwyut.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxhblvc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2expucygi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyzxzoo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwfvnio.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpgwdkq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2baajyply.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwwkmu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpguywx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jhizktuy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2przjuyal.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hliqwlxq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwzuder.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbaibfj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qztbgcea.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2afaffliz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pwesxoqr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoibuab.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hmavjazv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xaluajya.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nfluzpel.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ieumamfj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskazngu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsorszx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmyymjo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gyasrvqz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2grjwkpjs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yegdkuqq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuygaso.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtahlwyp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iivrxcad.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsfvzui.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwlfwl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvajtde.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zldcaiss.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fvquojgd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqvpbet.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrtvdkq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlkitvp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nschmwtc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwccroo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbhrbvn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtziknqg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uleamsfj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cidbsgoi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyurywu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nizwllgv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlabqon.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeihekq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgfvnoh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshnbbyu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsnklwo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pffsxeak.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrhtitc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvmaary.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bztlyiip.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2urtxcwer.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgjltgm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbokqjl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxsmger.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqysjtcn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbhmwil.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlirknml.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2crexaxze.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydchowhq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2glmiagbh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anbzbrhm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oleslsab.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pahkqegy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gohirafn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbdhwqv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqlhlrr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzzyjzi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2etdutiwe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jasygwza.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ntknkyvn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxshggij.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzkvtjq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeitanr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lscercse.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqigpky.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nebljryk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxnznxb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlxhwul.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ellhvqnk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2moeasliz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtksdvby.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzwceoe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrkgzxv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cigorgvu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoectvx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ezapzqze.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eczugbum.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdzenoh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fujgiiok.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qczthsfx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nsspzrwa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjktumtl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ufttiuxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjnskbr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gosasoce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2katghdjb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rjytbgym.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ahngwksl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zrthachx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwdqfkj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wquynjqh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fujrjsoy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2datjnmta.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwphhadi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbrsmub.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ameejovz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgbpekh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvwsifd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xyisarvt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfewdex.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fclnohce.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ojghvhjp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2waxumjsj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfgcesp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qukxzayy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2njiaoaie.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxfsrtj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrwooxy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2btpwqyvl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtdhusi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkaqncg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pefchfmh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwotnol.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2thttyeoj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoumimr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdmippr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjtnkoe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqstwis.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmvqbnx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oigchgqn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yudyhrnx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfzkvjh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mnowulol.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwpwvdy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ymglzbkb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyehhlu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuosjtu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mdykvfux.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyyfhgj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhtbmru.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mjguuuzy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2czgsxuhf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhvcar.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvkded.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpksacah.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgbwjdt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdpjcij.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgrchrz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cankwwid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvmzpql.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2asxfwqqp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rbahvidf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqmofos.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2olanbhqr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2erhpetmc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2axmwfqir.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjjabfy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatxieq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxmyner.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzdtlul.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gwndebzu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzsmlmt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmhctap.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkqobpo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmmxspq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvwegmc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhnhrue.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yoodnfqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcjhvbu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2scstbnoq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbriduu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqfqwva.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2skjfstww.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfzbcpm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2truwbynz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2varxgrxq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2detzcxws.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrbkhqg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbcaozd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owrgibij.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wauxnnac.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxgnfym.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpegpiym.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hihsvasu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abojkrek.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2onryufyw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sinrpjll.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edptaofk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlcnpze.html


<!-- 参考信息 -->