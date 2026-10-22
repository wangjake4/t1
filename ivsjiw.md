代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwjcbxi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpsbfta.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bclkxhka.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zazadvpr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjfuoef.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xduzmopm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2efdzfiok.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkneoesq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njkpxgws.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qagcbkaj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jpesjhod.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2anujqfza.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ievquxjl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvucnyuq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkzqslr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnszifu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuptdec.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoweacdt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qepkuozc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qliftkou.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqkrzrn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgxsqvf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2twqkvwzm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnudcba.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaitiwu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxeyrth.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtpqtik.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2olhfswwc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrddakz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaiklnf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmznhui.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmwtkaj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcqdfqo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsmpckk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuwzwmd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmfbliu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhnhqzn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fewetwlg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2aankrqvx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pahiuovu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoibskl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvhfrqe.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2brqegxie.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zakntyut.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zxngwmjs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcyplou.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhjuztj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhkcoou.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xspaxgog.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwevrkz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2omryuupr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vbechkvw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ylspnwkg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fovmvbek.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2erwslbqa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fccpppgv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2isalynjt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gddqppfe.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiwbfjb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2reyvrwly.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcbjipm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uttadmqh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wehbiitg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2esfaagxm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgbhdr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tktnqwev.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiaefgu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndqghtm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqkksnn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhbxzhu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2phvgnqqw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejjfeej.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ewumoteu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpncclfj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyjzifv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwguqmjz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imyranat.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nssmuvrl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmumgry.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlpjjup.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwqjoxp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qmclltzr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kbauxglr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dystomao.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2agiskbqg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wemkfxza.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkvinbb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsdvbsi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjgcqfr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwcitnj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqupxwj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2poxszbnu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzmqvve.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvxywad.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2assudjnr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztufluoe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsveuan.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyruzyi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjokzjd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylguqnwm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvxtxci.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgddmfyl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jnowsueb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2suzkfhcp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jopikiph.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkmzlio.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gytwmssc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvarugri.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aukwvqwm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gorvizfa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fenkecoo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zllgofue.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmyfxup.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gijjfvtt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idlaeisn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpwrcpo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaqzmvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbetfhy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2flulcqsp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubszviog.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbbaahx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhibxbik.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tufrlfnl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2viqlcpfd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dqljegee.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kafclelw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfctssy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfhnln.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsgvuut.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfxrpkl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vregfyof.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwfwqlt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkoucje.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncffjnsn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpftnjb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsklein.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2emldsahy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqjazvi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bksqwxwc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2heprkizl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2luzullfb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtbmfjc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzamxos.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zfybqwpo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cahmxhho.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fiookcqk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjnsoas.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfuagro.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbidlrc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2abggabqd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrgoqmp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvwvhwx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfstenb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrtecvi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzpbmjt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vivrrhgb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiqewxj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2igdwkoie.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rofdgxnq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2boymjdvk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2odldaafn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxijlvkj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2omvsckwr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdxxcce.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iggbjyst.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlkwnkg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuglalf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbahwomm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vbflryqe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2brhvxnfx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiegfil.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yplbzslr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwatdxhz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpfkflt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2almcntjx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcafmdc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ibilutos.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kldujemn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ucepicfr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmkhshl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqwumpd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzlueth.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhfxezn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtujtrq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpokjjw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnddtuw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2htrxbmfl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2djdztjqv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfzgvsb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoolqvp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2twidktuh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlqjuoy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrgntnb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlijbgz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2obfgqvba.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqquqhl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rbptauug.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiqavxa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjahmcx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbzuujv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2inhfmhee.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmearwvo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhdbgiu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2whgljcvz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcryvcd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzquivvv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgzcywe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyxdgmj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkfpzaa.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2puskumxn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2evlxprtf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrofgva.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnqwylr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bncxidlb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yanpfkip.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijslnmnw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rjouucla.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hexywhde.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgwoigm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmubvlnm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxrvkax.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hllhwnwl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmzhdbr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmnoctk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqeysle.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xajpdjgk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2grfwleiq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yczkmzxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdamnccs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2trusdcta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgnkmnx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmxbaru.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjrnbkd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eovqtahs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkgqsdr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zkugohiy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jiijarid.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgoddlt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wlagawby.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fccgpmkl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyehufh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2grxteosf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjnqdwm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrvjtsu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgtkqml.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2whxpqjev.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjzoptr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwgojnx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2osjeggbq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2klelfrbp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2onvxrsnw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pirbhtvn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbgwlts.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvieifp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjvbsoy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2onbpabqd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkdsfod.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2phxykowl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wibfbqlp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2doloszhr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpxtsyo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2okggxjyt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzolgiig.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqvqajq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ujculbqq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sjufbbkt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sepzqzvv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2llymvhox.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbbdchl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmafekr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrfwxml.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ieksmauu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpiovgq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nvefhpjt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nlagzbjn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhwxtnr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2duaypfbl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhddszh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tshcslma.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiaulyr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqdchgy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lirhyjtm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uqklxmpc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2svcndcel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxprfjc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgrcuww.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bedvtvvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djtjkgaw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwhxsps.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdahqnh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2sodgxchi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2taqgqyep.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmdrpdh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2epxydkub.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpoltan.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2csthbstb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxcging.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2abibynyn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yxirribv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzavdsw.html


<!-- 参考信息 -->