代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2remehxtb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophjvxtn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvynqrm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mztpvrxv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlftocxg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdteoiv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qoucukmf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzknzie.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwwgcrj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzxwzgy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ourrxyhw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2okkhtxll.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odxrcukv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwxkvo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zukxmxqp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vedxlqcp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fricrywa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqqrzzw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pynyqzsp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrahiid.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqywfnf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2larkcrpf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ssssmlfn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2awodkaba.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvrnphz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbfqfpq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxjiveo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hblizleb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hzojwwzs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtmvmas.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqkisoa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2idswkcmh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hsojgolb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bemfwjzp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqjhpbb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwqqure.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuakejm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2etbwurtc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2emzxpqzo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnbgsko.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ttygvrhx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kamsbbwl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fgplwrcj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mdthmzfv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzikvzv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfhenvt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvmuubx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhekptk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhufvjqt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksggyob.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hvucyzct.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uctvdqek.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ekybhekd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdpeqso.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iylryieg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jhufjist.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2njftaatm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeqhabo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkjwtyh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxxwgpv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsdiwuk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jgikqqqt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pppcxcel.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2srbmluee.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2igagtneu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxxnvnx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akktbxkx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvqvoxw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whmolifw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhkwtmw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mazoqkvz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgerqsc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlqqgff.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sikcxrsi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iozsetyj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkjjcbf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufobrcah.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rahvtjck.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxyshng.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfriqrni.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcgckvx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rplpuskv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfbapwe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaonsopq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhyztim.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbajfolp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjfjtez.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbbwbfd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bihmkxzi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2heqdisyc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fftugqrs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuiqugf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrfxdpw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfqivas.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvrryhe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjeytfq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isdvmjqb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjkkpon.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkzqgni.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2msodleuz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2psmjngur.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxouabjg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjgyfks.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsazizyx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2perrqqxb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcweivpo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqytjgvf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjftsuvp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmtnizw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edwlfnso.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cwncblsl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wipqhrdb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ponwqiuk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cileveib.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nooulync.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmjais.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yspplnfk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzexhqq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwmuxcg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyngmag.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aszbyzln.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsctcsc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hrswcdcp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gemdhtxo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dndlrngd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhowjpe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaxfddq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2smgksvrc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wovvtkmz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qktvqcat.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbmhnyk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjoslun.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgfpyrk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ltitcjdg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmablqb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdthiau.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2teekxhpf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bcglvjta.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnlqqyx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgwutiv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaejuom.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sxalvkrl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2srvzyrxe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhplwkkp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zftbzvjj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuwuedu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bxksuful.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqagsbb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vvokpmzr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyysfpx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrezeij.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpdhaqy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcmlguu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2npdazyzr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ynemxcgy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fccdbtqo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eodetgai.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydadvjmf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfwhcid.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwsvjuj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnewdqc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kezicpcz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zytlsucj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2erroujrc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaqmygr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tjthisgs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtvyrcx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzkerxb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qprudyfu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ythpiqqm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yinaubzh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpwonzb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2splvrtzy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsoswdf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjpskrv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgjuxum.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vqohokpg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tptwhazn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgatzmbg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyipljyk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsgibvp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyetuub.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sobgyjui.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgzpyja.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxaaepr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjlukjz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzncxvh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwakadnn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eiafdemn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzeitfm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkfkzyj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgkryvh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tuppfazh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaeitbp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhwbcbr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2swxumxef.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwvphkq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbqkohc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwrxond.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jvikqlts.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nanhuvcw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qchglmjz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvcxwrh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkxxxfz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ntswnctz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrozwat.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sweurhnd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsivzif.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfawlvf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmzhdzg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruinsfus.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cainnazp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvvitiq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeilbjx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2apiahtko.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2onoascir.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtovtfo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzimwlo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwndbutr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ipriddzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drxjtwdc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpjkqra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rixblfew.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zlouvvcs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wntqslgz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nydtwiei.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeyoxxu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2suilgdvp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hhozfruv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hlesbigy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmyfzqn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmnyexg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyfzcjj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vabfzchv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdnxhhn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyrapnk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cbueohlr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsyntmt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkgtcrw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nibhvxtl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmmeeox.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dzviijfb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kneetrqe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqzdrfe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjovtye.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfrldav.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxaxinm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2easoawhf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2amfmatwl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iriivedv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xcetyfmg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2avglbikw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtkhika.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpdwcin.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvwbifk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuzsrmy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjconvbw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2agtcntxk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fdndviiz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrfgsnj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iawzzklg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwbfzkn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2secvrmjf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrtbwkf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2wopuwnvj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dumjhrks.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2waombjza.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2irepxyzu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oayatfug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmcwlur.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfzhamx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2shggeaub.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwzcgak.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqmrbgo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zziysxyv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dunnepds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcgrvie.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zimokffx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgfzkev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icnrfjax.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvbssja.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fikwcqkx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nphbvzcx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eacnaorw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiypuhs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2buiojldx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhydnpf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vlesawhl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kmibngrz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuphwxk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvgblaz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpvfeaa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2obzvunzv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bvawrchh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzupapad.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2efsuhtll.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvfcadu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2alacptyi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vttrbklm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fuubtkhm.html


<!-- 参考信息 -->