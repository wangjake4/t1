代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqxoljf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxknooal.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdqzzhx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxdgdbg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjubvtn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnswzjc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wkayusga.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsliotnq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iowqorbw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzbzjqm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xszkueuj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmschpxr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psbofleg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlziifc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2coicfbze.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmmcooc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmcvumg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2entalcfw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnuvpan.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvulpkb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgzlaxq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpvjggn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xslcwmgp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qthkbnlb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xeukclhg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2idwwggem.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rheusgyy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2opopljwo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvefghk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwjvcdn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2evyusxjv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdbnwk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpdemrt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqastlna.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwmgbuo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iutvqual.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumyyvu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxmgqp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeznnsy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaeakzs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbafnxq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2welvtdcd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ajegxxbm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbuiypf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnxnfjn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2boifqpgt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnlypbc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uodkxabw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpaxdjc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rulsvgjv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zvscckub.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2leodrvon.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvpkdnr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwopoyjh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trobdaqx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjdmgon.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omteeplg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbojuqvj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkyhhub.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dmctmfjw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwwoots.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cymxfhws.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymketgiz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtluozjo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvibibgl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbiujtk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdgbhky.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czicrgyp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxfytyx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcooosf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bodisygb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2urmobcpr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mprxkyha.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbmailx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsgryfr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2goyivoow.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmvxrhi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gafiumsl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcbhovv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssuogea.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuesycz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqifmzky.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxpapwz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnwolmg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfahicd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhdfeqh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjwzkih.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtwzfgh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xubicfqw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xohfkcox.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqerinv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlktsve.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzayhzm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhbgrkp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2krlecgha.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlorpywd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2skrtkosp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnvskmw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eqomujch.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2igfyjiyl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2biwzmets.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2asiprych.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2snvtysmd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfluhhpw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svynrjst.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffoucaa.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjmeflv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvleapv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2plrqvdur.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfksltq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfhuzqu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2azhzysmk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmveiqi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2idlyvjdr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwunbrcd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fprjtfxq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqtqhgr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qnirexxp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rowjylhr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvzetxe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkzecp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pabfegjw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hotolidn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2isknxtiq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjpxeau.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjfkfmw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zesugyxx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tviycyxp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfwbqtn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2deklujoe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzojaxs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmvqunc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aabwyvuv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gicneuww.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqhsqxp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sncfpyde.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjvkjmb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gfifioen.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrvayif.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsjkxya.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2irmqmfgi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2arpgnuwy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uigengts.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2roqqxjrd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwhzhkm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlslava.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyeblpn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhmelgz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zykzjkec.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwozrfo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hdifydid.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgbhaqy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kawfunvl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dppioami.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbhdgtj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlxrisi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2agbpvlsz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgyngjl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2drezrfpy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stycureb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2smiucscf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zojdrjpf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqvstdx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ausrrexm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qbubidor.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxaerbo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2illhujjh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypguidhv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjopdsy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpfmjoj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2omkiwkfi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgirfaw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mkenzsqh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2seyarhob.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmvazba.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uphdxkbh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfcepdl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrairew.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qukahzsr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcxavxb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbeuhng.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuakeaph.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfzqalw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bddtxlph.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeooqor.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqzdvel.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmeavpo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiamozo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrzlnly.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2moidlnsp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdguhls.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cruucjlr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yvotitix.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2asieznpe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2putynlgh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaudksyw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbqverv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sknlcmvb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cstxxvxk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkpmmkt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2etjtbpul.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqtnexl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsfsyrx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdaogiw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dxigzvca.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2peazaoqf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2izwpcodq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2biugsxfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvemfwul.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iipfkjyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbndllqx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuksuzt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvpwlvi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvjpetu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsqnfcb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2majyayjh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpvovkj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ssatuqxs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2chvanjsk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tswrmeuc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bhywqryz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmnsyad.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxzkiao.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jalsniyc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2caafteer.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfwrdib.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjmdteu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsllfrj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnxfmzz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oeipryxu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsiitkx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhxnxgv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbrjkju.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsrjeja.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kcszegti.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mvinmpke.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgtsbxh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqpmjpz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pqscgbin.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvgahdb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdxickq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifdvmk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pcacztcc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dakpqmbk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hltztmxz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oderbxea.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwnifid.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2isxdvbqo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmlwlsb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yafnxkie.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnsbstl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mblvrowj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2snswwktq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxnlhxu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hamsauda.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2huoesasc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsipyrw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyjiadi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfxgshz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2klmfsfxm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ykccepdg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mfunnuxy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2oupxekti.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iomtebvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhdapxp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkspzyr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fafjetpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvmfotu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2waajmdok.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcixeke.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmvmxln.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uyihhznj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtrtger.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xswscmwi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyxvprr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2locxsaxa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2finrlndl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zfajjpek.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxzqibq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfgfjxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfqvmfa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2unchpcff.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtexwtu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2clfnsxhy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyhbvyt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoweasc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cvakxidd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fikeysod.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkqyrsf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsllsxz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgraqi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbofnyhr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnylojwm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nztexsdq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbynxbft.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lacgdmey.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzbgjdu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2annpyhkc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdxixts.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obvmstas.html


<!-- 参考信息 -->