代发 wailian999

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhferuxk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjgevty.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwurbrh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxockfpr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ldloealf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbfawfy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mshbvsiz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwxwyer.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tdywnppe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuackhk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrrlvbu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhsxsoj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwylnyu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfhvyml.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmfmosy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizlnqyw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bnufzagv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uumfoatv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gctybdfj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcansmy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvgofn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gouioeea.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2akmiztec.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwwtlkk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dybhennc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2otxzgxpg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gldfhmol.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzdoriq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zavhbaxg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fodnywck.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxlbikl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2awumngoz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqjqnux.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaxmdxv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwpugix.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atoulmxs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdkuabj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pakkdnvv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzwpgjx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjwnsmh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2crrprecj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeexlccf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhkeszn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukytkvbi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eokktksa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zogvuqls.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytttpzgf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jftliikw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2axsvquzh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pvumdvju.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwchysx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxrhgxp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ggntnaox.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2errnrdnp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnmhjtk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmckfmy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpvglek.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjajyad.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mimovspl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjcogpc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2whcmpbuu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwvgxnx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2npbjqgxa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pngttnzq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxaaybh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2syhpxxyf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2houdfsnq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcydbcln.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fitkojoj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbzsyqt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrmnbil.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhldwkhk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrekbtqi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlwweou.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kllrxuzb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaafebo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkismmr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaqbxxk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwajmkk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2evxbgqkb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2loayirma.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmopfmui.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rygoojmx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebioiwuo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbopjzj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyabhhk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgoueso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2omctzcsj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcohvet.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhovpof.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaaxedf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqagccv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tridrbvu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqbbvys.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxiykjz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2thjoqdmc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2athwekrq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlerdat.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2czctkoiy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqgqefs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqorspp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2owtjogah.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoiiuun.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yazcjovd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnrpsyk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzwbxvc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2baljiraf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2watncdln.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyjmamu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzgkukf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmothdr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcybkjg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaghvfa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzjpdfy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqiicdq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2chenzosn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cugflhrp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zzphoonf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2etnblxhm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bczyrycl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbxwugg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbkxfrt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2inqztdta.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwioddem.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoynvzv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zovjnoud.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgbbfbx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2afvsyvyy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaqtxgy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2twfcvjlp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2detwxpbq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiulgaq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjudsr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpfxmwy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtmxjsm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetvokqt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvagphp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ferxlkkr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbqdoxi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuirryaz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuenrlu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbvqtb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krgndwty.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdigwat.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wykedqkz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgshckbv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nbapgnzc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezndgfhv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2woqhiruc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwceqmg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jitorzmv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2asywckvm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoxenmo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfergmd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cppwvund.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2takxalqz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnvsrhu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2brafvpht.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pregkwaa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzfbuuv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxabauns.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmunkwa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsddrig.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkdgxpn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsebvux.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bykiyibt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dylqsfjk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vksjabuk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwlhkos.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2grakndgn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpdxqyz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqugzpe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfyqwti.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxjabde.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfqawlc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kimztsnr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2klfqvrte.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxucjgw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2oikswirw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vavjogdf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qddjtcrg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpxnlzw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcduiopb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaehqwqx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2undjwfsi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2etbwgtrp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ricgxaqr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwjhzbz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcrvjmp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxkemgn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eultvqjs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rswtvvwd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsjaeeg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2citbfnsm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2klvyvguq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hucovamp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzqemad.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwvnjyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djcihckn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2omksnpmh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqgfxkd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjzkazf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zocbfmao.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gsshdwgt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqwbmzc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tnveichf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iojakeup.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpxuhmb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2avfxmssi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvhbivq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpqprkt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiybyek.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhlsdaa.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkrqkdd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umzocpmo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmcbcbw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfluouzr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bybfosqi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tbitfksu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwtqixd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2equxnijr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qizhyqpz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2igxgwfgl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2geoqqeqb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgwqxot.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsuoqzh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2duulguau.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2scndjcpa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhubytad.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqefste.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wngstxlf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnedcxn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvenlhmo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lilxxzvi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qajesave.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxxurrm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiozgxy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcotbpp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjobfhg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfjccxe.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jkszafci.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvjchud.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfcwgsy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnqmox.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2abvdefbg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fwunjsim.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2acgrhmds.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dtomomjg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnuegcj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2biiuxhvw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiwhmcv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iatqzsge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvykxsa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjtcawo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqkumas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxugnwlg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbvhpet.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2novaroht.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaepbzq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhehxrc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tiewltdq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2akawzwlz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdgujzj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewxrnu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rayhddak.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2keewsnlr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyxodrr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zeekrryv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpaqzdi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqmohkj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnxthkk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2owtoxhqw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcpgwcn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2brlupdee.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2plrqvgiv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiuhweg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vomolccs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2biwurgip.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmpgpjv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwqddfc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrcrsjv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhehywa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2baaxkfae.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyjpsqy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gycjqstl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcewhkn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqldepwj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djcoxalc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czbqnlsc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrwmlqm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rylwlwzr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oluqwhbb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzljpnm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpugnulr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxzythk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgckrrki.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmxwcpt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djtmybez.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwpvksl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqmtoeq.html


<!-- 参考信息 -->