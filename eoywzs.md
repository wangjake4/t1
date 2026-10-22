代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfxguf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyphlgi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2awgdjrkm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvcomlq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjjyuoy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2imygzvbj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyniffk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnlmkxt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuahkhd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffphmqme.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhqjcde.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zurftmwr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpsyfrs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgudassb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyrqaur.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdybyiqo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2udfvqqzf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgbbwyt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjtssdn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmddzqkx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpewzqbz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bcduchvm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lymcxhnf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufiqzzh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2onnmoeqe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmewctau.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sfefvbmh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvbdczk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2njbvlrqt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkxkosh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtwbaui.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmzekfe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyatsmc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ktajskeg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnfwrqp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2chaisxuh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxcwsjb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xphvxxyb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxrsoqg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gtemmnyg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nitfhnrw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yknswgrl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dsboswmx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gauwvuvi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xickimzz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrqsqfi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2emiyjmey.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzmuxqa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2htijifgq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjkgjl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2orvmdzrw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uusprrjf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2maehxhos.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbqscqv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkvjgsx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eciywayb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsztgnh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtqizxj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbhczic.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqflvor.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ovycbawv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vawjwdns.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mflyjrlb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2efdmvbqk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeqjbqe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfgikru.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrexaupn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qowmrsym.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmhpmqp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvmtyiu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2owvsytpz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlilrav.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mesxzkvz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pifxmeav.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ljufjrmc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klqtcjmv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tunfydrg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafnwgvp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeerdgky.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjitcv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwwfbjk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsoulbl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvxjsgo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qufrnimq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wzewyplo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkdhrin.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pskzqqay.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aagvcqze.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdifyohc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyawuhjp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rjccrrnx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyfsaed.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umotrapi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiwonzz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vghjznen.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgttpzvs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2abfmqgrq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbwtadx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgighwa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2djikiohn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmhcugj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdsvwa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzxukaw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndephuls.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwhwsar.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qehvsioc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjrgvzc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khshurdu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqtpcit.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsprmcyf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoinknk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdywbxze.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnucvxz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hncjwguo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kufvsthn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsxngxk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2taanqpxl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxajonza.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twojvurh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lohassbo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvdgfya.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdajqhy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzabrwj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwjoeor.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoqjpim.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vunufogk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkoztym.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfkzjta.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ffygznbt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2retqwath.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyjiygt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhotvwo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nbedntqp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2shayghvb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2opdrwswi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sjutinbb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iwejnpul.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2trrvlhhz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqwzfsi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvcoesr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wfihbinb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpcsonp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2thujslyh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuecwmj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uztyddkl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tamxmzcw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ffouwrtn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lelyfjul.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgbqtt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnlewlv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2omnehdxr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcgkzau.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfewmkfk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yguxpsuw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjsprzm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqfskac.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnuegst.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2imefxthc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jcawdvtm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsriipxa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsdmlom.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zidxkkpn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyuyasp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxenthcb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zldetctt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpkfeqe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwvpvbz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meqyfvin.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhbzdiz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjskpzlu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujxbga.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxxuxbb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jaarmkbw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mpurkzag.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skmpqmof.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnrrlcx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlarsua.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2meczahrk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2twmgeamh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eobnwqzc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqsbvig.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkslngkk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpvmrsu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zytcqagm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yesqxznb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2baaclbwm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yljykrqv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lgybmwwb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyscxfy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxakdxkr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2grcptrjp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wlijbfwr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxuetsr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2apyehrub.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mpytphqj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kplydhvh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jerzmzja.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fefnyuae.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2baatdjuq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbcczke.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yigyrznh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsvhaha.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixujulnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutcrwty.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2swogsztu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjobdxzy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdmuudn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aiirfozs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wggoibyx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bwljrwsg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxvitg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xugaagza.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2keioirup.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cistarsh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaxgyik.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgrfsio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unghtumo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcpjfnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsxzpcb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ootnzshp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yhslkpmk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iaenlree.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2posvfulb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdcgsy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2odxlhurr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bieyaalk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcudegv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsdulma.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdkjiwp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmoyelu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2csnjetyj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xjolumzu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rzouhbxl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gtakebxa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzqriyg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuypxth.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2anwpgapi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aiegpdtk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gzobtrbx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuzjyvj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcyigu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2autpynil.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jidtubxw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhaxxen.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2elboojoo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qqilbyzk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2orzrtucs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fsanxmpz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoagmvd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cuatejar.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vegvqhed.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pafeqkge.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqwlzln.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dysnhmzl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lprqpysz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxexatqb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwqhhcj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hszbhlpp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pyckpmpa.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lgznhetw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hraswhaa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obmjriif.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrxrafd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2exxwzafo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnxjkxe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmarpho.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuqluqb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wxynvnwb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcdwfjp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcprzzc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fobvsrii.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2drwijkma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiyufbb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xozqhztt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jegvjxin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bisrujbd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2flyihawq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkhqsem.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qiammjal.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzstmnm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2puhxzwiw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmmkzmp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiumgfp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fktfjdtd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgutsyj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmqdnjg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvbfizg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgnzpjp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cfastiuq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ivviwewg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2knlyxmbq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2riprnxzh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbrzcen.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvqrnyn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrnexgt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hanpkcye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxkctbu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwozauv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btopyaim.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjifdjul.html


<!-- 参考信息 -->