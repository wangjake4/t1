代发 wailian999

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xocbobxd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqrbtav.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brmznohv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjocbql.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbmdbry.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimzcxab.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnyyrml.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xygdjlvk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpqkxnj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtakoei.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvhfzmm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2shaiulvb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnarwnr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yucnckbe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cshajvwz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rghuzzjh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2whdwsqxg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqofnejk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkglhgb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsoqoat.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iipcmlpf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jocteeip.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ervdrjip.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcppmqou.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrxyepg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwgkazm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2osquduot.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqasskv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmlkhno.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jtezlaag.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnrcmoa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmtvbwn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jreniyli.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oricnoiv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrtzkoy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgpljgp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcxkog.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oalxmwcy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwkwebh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fhptwhpv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oclfvqmh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqszmoa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2usaqngdk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhlajls.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2evwuutdz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjzxynj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2msxgricc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrvxuhi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxppmjo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2atiotzmj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2itbdacjt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhcasdy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrcszki.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpeivju.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yikyzmyq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgschgrg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgspgri.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jkncalxr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxbkdci.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2czwisups.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhbhtpj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgazmb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zsraqcxo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdlgybn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzfjdyl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2chmmjsno.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zgluirvr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbkjngj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzkksra.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwzklb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrupzbv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuqkyxs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2einpddkr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhrbiwc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2parzruwg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2crhjenjp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsgtuzd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbdlyja.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rosvdbny.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dckrtprp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2waegcmos.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oecwhobs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rnanjdgj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miljablb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhtlwkz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfokdpaj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvsbfwh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuhmfju.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfzeici.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjjgran.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfarvsui.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2glqrgmzi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnkbktg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hriepayf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhazsfqo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrslhdf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rorhedhb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvrxmqe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bbznogja.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgacpeub.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uowalopl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2azpnizlv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfxdzbk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2beclvjit.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzosdwg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjwsamz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrzzbni.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rapnjryy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkhtzpx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wghpiljn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phhzvftc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vatwvtkx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqfjeui.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsrlrci.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eqefczxp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkqzjsx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbbqnyo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2osilvtkf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bihlyboz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpkaflg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vblcfxwq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fervmdvp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjpasfv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwzgmug.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcjfhnz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwskwish.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcdnmzk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaekolq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtsfito.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrxofla.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jngcotai.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkbbrtg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxtbkas.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgzzzkb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mauyhnuv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaczjmze.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrfwtgx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xycdtygj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiprxkh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2elzzhhea.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpsnmsi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gexemzjx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sxspyvwf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cavihgep.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fccobqea.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iojbozvp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbiknkt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgukfg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2geiofnwv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzbmlxd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2susovrrg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkqlczj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwnkpbc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kapcccei.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2otepoklv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2emhntcum.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzdzzlx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2upxsnewg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iiieqlwa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcxgkie.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbjuuob.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnufgai.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdomtkn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuunrxfo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqtyryu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxvdsjv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zolqpqif.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhsdogq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flcvznpc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfameli.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjttsoy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eawzpuic.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhdzyxp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bshzewyp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpwmxua.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asmlmbvh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2llfflcef.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsugoan.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2udqezyid.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zbikgmnp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2saaxjvvj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jitgxbeq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crjmbseb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrndfjfu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tavsamag.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jggkewev.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2epdxcuni.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnofjacl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2romtrkgw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fikmfszi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvjgbaj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbrjsgv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pedzjwyr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lstkywlw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2orsuobxq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oputwsrx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnahnzu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2krbuqgdo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxdcofd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkrhqgx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwowfzyt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykknkuyk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmmuraa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhncjuu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aouwrzvf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xslzbsic.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcovfcbq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgegvlab.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbiynrv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpeqdko.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llsabdie.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnlzgyt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yitatwrg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouistgus.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2owewhqsn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osfikqic.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaxmmdm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xscklgrz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qafyicxu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqsmzvr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2feqitihr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnfickr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2onzotwwy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgbzdyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcehlyc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2arfelzau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uedazpfe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cziukbwv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oaadksmt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrthaer.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsdzeph.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdnyyvg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwlbdrp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjbpegs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlfjif.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjkqbvg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2larylbde.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsslgle.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvvnlpo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhcruko.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdalfol.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgkjlee.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjyycgg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxesfmx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jbffgodn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2htfnfmbo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rzistapf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2byusoury.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqpvukr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzjybwj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2toevsfga.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtxjcfp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cakegxve.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhmarzu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zgznsqhu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnrjuvw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2exngavre.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnkwqyp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2anyjmzsb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xqachujq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstbrir.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhrkbxi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2oazfsken.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjojbdf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvpmozc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjzehfb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ethdljac.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fhurzuku.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mamcpnmn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sysdzlfz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmhpazb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzausxj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2styjioft.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oztpqrqg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrdqhti.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yabxqogn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwtezaj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2obtnqznp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gclewqra.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuvcryr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbdgnak.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgbfvb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwgpzhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdijmku.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uajzvvpw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmcsipx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kegitbwd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2juoanusp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xuywalzc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qawdqtju.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwofjod.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cttbdtdq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpgtmay.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfujikb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyzkubu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpwlgng.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2odacbnqy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfrpzwq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwesvwb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcpkxsi.html


<!-- 参考信息 -->