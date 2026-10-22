代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drllfoqf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyxbkys.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2miofbkgo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xajkwevr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bouteupf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnjmbxz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbxshuu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiqhuse.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hynfcayx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mecvtkyk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jtovucxw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otfvmicq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2onkvitoe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2atrlsqof.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wphjfbzy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxepdvqp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wheuucaf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhfmdih.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kupeanez.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuovwtvd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dctndzxp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2adymvntq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjbljdn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsduvhku.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oytrakru.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zssqycma.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iurlgiox.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcxrnyw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cdecpcyr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2movavahc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnjmsod.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ovltagfd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuzvcvf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdoawcm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdigipcx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskiprfv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xsccxkmi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2inahzcou.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtowxows.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxiguik.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuecegy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2panbbkur.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2subrvxac.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbmwvzc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaywgrap.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgzrrvt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bvraxyut.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yadwikuo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2arfoydut.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2knrujhco.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iipvyfyw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdhmhgv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwotjov.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mccxetvx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzylvel.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2frbvmdyc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ykphccim.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fpklovum.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcweepn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvadjmv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ieynzpex.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2euogpmhg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eppfxytg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzbgway.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjxdxzq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mankdrpi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nllrxgma.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vlblrwqx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eavxkirz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2prpxttjc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kmptwhvk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuibjbwo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jreduono.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jdilxcog.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eltjcgyy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmcahio.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2blaxcsoz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2axvuyyqf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2conecebr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjyffc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qvphwige.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nplhlxeb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rufcfykn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzzcnnf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoxajvk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2alswevyp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuvyaxi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uldaorkv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tebedeak.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtlxxao.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvhajlv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2crkvepne.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtjdtkg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbljgoog.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjasiki.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwibnxfr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnkbolp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkwapwk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhcvfon.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrtxswo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nugdousl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmmjgum.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mnimiqjg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrrwziw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzsawxw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpzwnba.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2znkcnjkf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gibyvule.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwbkrao.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiuwcwf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvuaahg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmzjhhr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2guqhgaio.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbsdmkr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zsevetwi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tehxhyye.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhboqvz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvagznhj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2itayozoc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrmcfnt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sufehama.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfqhcmc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkybrkxk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfurzgpu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtosrlq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sobjwgbc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmscnjh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeqnhpj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2adpeflqm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnqmrdz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkjmbmm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqeqhh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhcqyda.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tydikwrp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2chdfjfwl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxydtoa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eheuonfk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrmlywo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2deavsykj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsbhvmy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pncowrmi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqdqsvw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgxrmjf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhautjkh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeybugb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkylyh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ixicthay.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2srjszczp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmngjulf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzrxmq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2emasjtai.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2poivsqli.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vzegwczq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eccradui.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfhbvjq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdmvtdy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlbocbo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2crphgpde.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsolisq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2opldtpzs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrvmwnx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gzelnisa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgexeems.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkmxjxo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbzmfgj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txoggfvy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cthjhmeh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoexvje.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeuuerq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2grdjsxkh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fwptpbvr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdggpwvi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbgjfiy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dumnplno.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cywpwurt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcmeldf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cylelelw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2okhmewcu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iemweqgo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2naaydktt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxwzuug.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bucxcaeu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zsapcoxq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwthvsq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxafztm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqmgser.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiabqvy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2knkyuudq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2modzlqsl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzlbcg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxvjczf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbpospk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoukxdq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2klzbmdcq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeuhmyz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gofzdufu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuxwhzu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgkrajm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxtjsrv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2scuovejh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2txbojrth.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvybojtt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2agvvvuil.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lavixvqu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ybovpwbm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cosvmygv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kncrxhiy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fanfyysz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2htciunwc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2edavkitr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cnljxyko.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2esqjlsqd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfshmav.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqmkbah.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bufyrtxj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbkwucy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytppjyos.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wsipwrto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eozjcxkv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzptfer.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eolfbdxw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2paqbfdmw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wuixdfau.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hrddubyt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfipdbs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oveqqgqf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvpjmcu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2otvbtead.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdenser.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xaubshfr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hgglrots.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2aothkvlq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtpdulx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vkleehks.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wvymfqap.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwvvxee.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmgtsow.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bngapvfx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nieatjqy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yunwyelr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rcflwfvx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2icglturn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wslwcnus.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhtzeof.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xawgrdgn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjojxkg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzztgsc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdkhago.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrnqtop.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwhvgyn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vokgxqih.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2csytalle.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbydhxk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkaltni.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdlwdbp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2atmzabav.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbjtlgi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rignjjbk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2akusbnzq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qsippkow.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pogpvlis.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2shjaobwx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nfraouho.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqhukqk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tqukdwwn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xqperxml.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2toqkngik.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnsprbf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxvqwjm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqiooxm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqxbgpn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2slumlmpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kojqgsxk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjcsajb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mbveagnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkziqbpy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtlnsiv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgzrgqa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oevtypqo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pxybtjoq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2juhdbacn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvrebdh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pdofwlaz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mibifuik.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yiakcocx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2okmhebkq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2warogfip.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkponxkl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2iciwaeal.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zileglwf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2auprzxmb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2trkrlsfk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvayvxf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bofjwfql.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqkjuet.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmookiu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfnzpea.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmbrarb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtusisu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aylfvwmw.html


<!-- 参考信息 -->