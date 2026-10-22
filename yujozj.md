代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuzuqjg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtataes.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoajuav.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jztsibdd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrxamzw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvraendr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxrgusk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2opnjgyxb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaygqnj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrmkalc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzrxsxb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnflzepy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqdgikt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rillcsoj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ciceypxd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhunngp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlsulwe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiarrror.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcpzueg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcsngoo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mswdqtgl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylahkw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdzhdma.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2njptcoah.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2csxqlmml.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2brqfcmdr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsoxkcl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dydzwvtn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsldfjh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2apeuqodd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxnpws.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkrvhff.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmcdzwd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiuiurx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2evwmfliy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2caxhykkg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmvhgtn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrrzgo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwftlia.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rifphrbv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxsajkh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpevuon.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaynxgs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcidfodv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2spcybaxg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2awfxruxc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bosmakta.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bamocykw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxageyu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kijmrbbj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxfnorv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnqnmla.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvllhsa.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2umjkyegt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrowdg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdprcfc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gypvizlq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2utwkrptz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2blaomdoj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2imdicxyf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hofzmqut.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmfuqeq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgowted.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hahqpmwq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlpfbgg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mqggetwe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lydmgeye.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2clpacxdn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsakyaj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2isorfaev.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhbjhnx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuwvwyg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlprhqg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbgqjax.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2njjfcers.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2meouzkvt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2imoztpkx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnbqshj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvceksvh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qywmcwrk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nflrkvkh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2colaluaq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpehkit.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2inpwcqdc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwhoqnq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuxknnh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnsxhee.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iesqtrqr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hxplsarz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qedgfonh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfbggii.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uchulgbc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2unsjuatn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iveexxbi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wloguyas.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrhpumq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2axivikcv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvbkzir.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gaudrylk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2krdmpqew.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmhejng.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2twzggkuv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2llmkkyax.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aihfcndb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2turqgwpn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epqatxfq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnoqbbj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2djthksby.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wkczcesi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jejehgnm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfznrczh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoidcueg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oyahwlzh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpepewmz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iukjxafv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzalfgh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpsxoyk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzygsiqd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbncigrf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2usxbszsq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbgedrt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdkyqma.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmromso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiboeqm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaptqby.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tybegxyi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpxskpl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2haenbxeg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkazoyof.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oegfeeyk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nspxqitt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2iostpawx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2htcvayhn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2roaihndk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxzgsql.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oabjaxvv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoqluyn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeimecw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrvigxw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbujwyxn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rjphxiok.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jcizawrs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2flqelyjg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsppdigk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vawzgxbp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgfkhnb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oojdnuzz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2baogwhpo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2obzvnicq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dseboovm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjsnsth.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnsbfeq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2padnqegk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mozcrbec.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wovrfpmf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qludaejr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2szcrvyzb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdpunpq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2opbhgpyb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2apytqwzt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqieyyq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rwckwbtx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2erdqetni.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qqofzhre.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2haupylfu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqkmttf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyqykcr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnopuufu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2etapfvrj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sgspiohn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqmefak.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xztncfro.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkzgixk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvfipnw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2adzsfxjm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgenvyz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefwgmc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2chvyubzl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqeyrof.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2booksjxk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxeynuj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyaztyb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhojye.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuixooll.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtyxqvl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2smyhpmvh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2obgsbebf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrflxlj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2payuzkle.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbbiclx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjfiuhe.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2erezcyrc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqrcoeq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2svtngcds.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2urihjvbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxonyot.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rebciouf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hucfdgrp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xntyhfic.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdztbzsl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bzklhdnm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqntongu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jslauxoj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yukigvzf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pugjictj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpgmzsj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtauwpjs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdticao.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2budzvkcy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxidrnt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2upgicoww.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uluqdemx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aalbstxo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnmsdjf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2puvmtnjd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrbveen.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vufbunbx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptliaivz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhcnsyx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuekptyz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdipgxw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiamkosc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkiqvjp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xptbeljk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhstigk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2acyznyel.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lrastrss.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhfbptx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjnxcsj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqqovfr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxubjwc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2petmtsfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqobtwv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cgytypkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnplptp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uaexsbqx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gspzcfnw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgfjefx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2knkjlust.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wchghxsb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdyqhws.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rupkrvuk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2asehajrs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fssjgusd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmninjo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiowssu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgiidkn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dalzggal.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mutzahod.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eifpdaeo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwkonat.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2idehhnza.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiivrvs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qfauytkm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnxhlsq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjfeszg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vanamkbe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2odbxfolj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wuokvmqa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ywshyrnc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2aftxrtvd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzidseo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ysogzahv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2szbrevib.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gynacvks.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xorctmzh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqbmxzw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbdlqqd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgupurs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ufentpyy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2isbtzfpc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmcajme.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iojxbzyj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmhzmjw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyejscj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpvhcyy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cnczsbim.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mocmihyk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2enpmfwvr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2stkuwuei.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zuscodep.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2auohaegn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhqjgrj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhyczlq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2chqxjngp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtfftu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgwbfjq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2agbrtpai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlzvlvy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhwdkzh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ebluueca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwewiexk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfrxeja.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaerenl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qccjrbur.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2akjmvyip.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjsbbwn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2blooqglh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbsfqoe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2quuspkll.html


<!-- 参考信息 -->