代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvrobeo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllfaxlq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rosdqjxf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhppbepn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rgggkbql.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxwuwdu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwlzdf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mahyldet.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aawzxdaa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxznjxsd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aaymreme.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbqhptk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaujkam.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfogbye.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2athpqzlt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcluaybl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ludfxngf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lapccmcm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iydsdgvz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rabbdwdj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixebndtm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vychbfri.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbnmmwo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2elbtzjjh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcdpxjr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zubkobas.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jnboorzu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2reqykpon.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2upaggvsm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcektug.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlymlpr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2czqsqkpk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmvzsiq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhnqemk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmilppt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gddoskth.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2caonkdkl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fyczhuvq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbykwuz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mozifchn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dojaajbf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2epysxnvf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2orwbwqem.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkkpjuq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwfsepr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqhejgb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2akilrfmv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qomlxafy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kdocdira.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2odpzbmpo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fcspzqel.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iskhguot.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2etbyvnhu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrylsilo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zubmovjg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoajabg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwmwwfo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjvvetj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qcayfcuz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlsduvu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpdgonx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwoyujc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpogxruy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2joioneza.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvnxotd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvtpfoj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2engbveni.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvspgoj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zemnucep.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwuhitt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgwnfwh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeoccpc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgqqwhg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2amgravro.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kfazmihg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epnqczvx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2svoqmmld.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzoyixx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvznlvqx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fasqzunq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yjujpgcx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkzytzc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cdltirdq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2licmufah.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbixdrz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2klpvpwmk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sixbpujw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuolnhf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnechptm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjczfzt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2custasut.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrmimmp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ehklimnr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmtvsya.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ysazqqws.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtuwdfj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnwqnfd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wijxfozv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sldxllqg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpjzuup.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlcqvwh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlifwvj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpukzlo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgjzvcg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qiekyxmz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2flklqpxz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sleborpe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2udqsufmg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeofody.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyrlutr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eucfxtvh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfpuvzm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aexpumqc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoznusg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwebrqv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpsjibm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2izfaludi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyoruuw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pagpzotb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ontehmnl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2emhflqpl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmocpcls.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eslpioqf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2azobgdwq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmakqan.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2stzafxzc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bllmbmfj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhnmlbq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhedzku.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpscggd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwwefoy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uropymmr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2stheysyn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvzolcz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sonaiqhm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcnjxyr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuektxd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vthcbivf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkfyjbj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrgtrdm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2anbonjsh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqysrbf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbfnxbl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuszxkc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nejgofth.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2liynyesv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pjasdsgu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlqjgrh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdftwni.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2klxfghrx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2odktsrou.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2relndaik.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2abjmylhb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyuaepr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2opwkyiip.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdnvkvx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cixsivuj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2drdgskab.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lemfxstm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhucsqn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jppizlhq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ebybjqtf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jggfvflz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zltmftjw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cylbsanr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixndzh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2otodslte.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjonsjdw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bifmauak.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vobwbvnn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2scxzlqxh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2belusaam.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqvlvqf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtfsxde.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vugndllr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgseyiu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2toxropuj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eshfhpud.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxnhpvt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fglhltyg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2izlquhjj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzoumze.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cphhshfi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzndejmn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuyelok.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ficqvzde.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpzxopu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uujnydma.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vjixdteh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrdolgo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cemapfbl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2leeqnmxp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fisvqkqp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aextqzzv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfaosle.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkjchoj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2diqwzkmj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbbemdr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnfajnx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2osghqmiv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2unxozior.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2egcadqwq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gnghetap.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hebiwcpl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhnfgco.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2elodynmg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhdzwlh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svafjuny.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpqtbqs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsaxmln.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fbncgopo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pbloyypt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2erodkjrh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zioysdcu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmxkyxk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jaftruld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmtsyck.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2htvwzyfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trehwzks.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2amthtwsu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdoorqn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2idmbbydf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2clzwnkvy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsrvsrs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgplfvl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nighewzq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qksxfruh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2muomosoj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2phxshymf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkjggoa.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxxnywh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhpxjth.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmyaepf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkvvqas.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxbstbu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2deyilgro.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2agrvjhva.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wblbaorf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxobsxv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjqsngw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2umrajega.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hstshgyf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tvexkamo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqttmtj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wmslpblx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjmjnwr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nerxsbkz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjawssw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgwgzln.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dwteakxn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ehznvdrz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ercbulvg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgqtivm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yefhlyoz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xskketmd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxgpvhy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcmtxd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtiqan.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lakbocgb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbrpaeq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgtodza.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaafklh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzifppc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwwibcr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tormxoyd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmjegjl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxhrxzg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrgzowz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yncbpxle.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekknqnof.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtljnfdd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspowyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lolrliuj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyxnbqw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2reetngzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgdaoms.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnqdrje.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gbowqxjh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqayspq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kprrbjqx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvndodav.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2znlrntlp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwteqvmh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjkejma.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wiytjtrl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeakwcn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxiytwv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2clnwlhup.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdtnglu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ugenuwxp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjsfjag.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmmaqgj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdccneyr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2njyzkvvn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuypawo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrjnfot.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2scvosora.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcaioqn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2poptffhr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmdjgcr.html


<!-- 参考信息 -->