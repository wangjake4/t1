代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2orhzdwte.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfetwzl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdctlbw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkltpoe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrmufyo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llqzpaiu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2crbfhlmc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnqtwbv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwdtzyt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxkruno.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdoezbu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkzlpvi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpeoskx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzvwdsw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jmidasto.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2csifremm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzwovrn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhxuhue.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcygyzx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrhgfxn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkhkuof.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjuyar.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ybskrkjz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlafqor.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuxfuyd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcxaumr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsombnl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirmvoui.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2meckpmga.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuezzts.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbakgny.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2spguerhi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hiykthsd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2klnlybyk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrunhqe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcsyizm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yubwbpvh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeztebw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpmfwvp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcwzokh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsymxfi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpdfziz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfmzpxk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2osvsgrnm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wzegelml.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhbngll.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nihxgteg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsifokc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzzbrib.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrlnjvj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoxfxji.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cywcpwff.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rycklvuo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dslaycdq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiikrwy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kafgamgh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoyzryo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2budprsgu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erlqepzd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bcitozio.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wravvfid.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpqymgr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzsuiue.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jisndtmf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2acievczu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgivxexh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2baltqjie.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgiqrka.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhsnhuk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqrssjs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrjiqvr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcdfitw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnmmebv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkanybwb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvdvfwk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsghpgst.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yiidyyva.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgesuqir.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uusrtgmk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwnaupl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2awdvvhqv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txqeimzd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vngkxsgj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqglbfz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivcytc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2duaxgjjk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzfvpzi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyutnwn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pghivlfm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjqrbiw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vvymtwfg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2shmupcun.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2erwvhmxo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqsiry.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvrihsq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eggzsnwu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gspcadso.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmambrof.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmrrvow.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuiwwqa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjxtemj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfodmopp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhylreav.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gctqazjr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrxwvzs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2chsulrkp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkwkhwt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwyrfqy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuqband.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvubzbk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nardovty.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xenludwl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2haiwgwsk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uevffvqf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkljrdyk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetbkdi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2myryfazo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tpskjcpm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwepydd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxldcpuh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpbcglg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2apzcsphp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oytdxcvk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xkklllgv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hvscdlpz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2khdqmztx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ydczhccb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2myoxqucj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcjprdj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2secxnwcc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtbuwmt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygwwaha.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcmzdxp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfxmpgq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nktscxhy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgtegqy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyrdrbb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vnswmpue.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcrhxly.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrsjhvb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjfcajo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfhniyx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jbokkogh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2szssicbg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2esnygfdz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnnukls.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rccawxnt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvafbqlw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbgveij.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2roubwkgh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfapndd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkveste.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwdwezv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaykbrj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcqnygj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfybpcrz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2prippfwl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjrcdmv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kulgxkvq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuddupa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbfmswh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqbtoow.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2naguvppc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsxuhpy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdbmbic.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fiveyool.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qpofbwks.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxtals.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbwyaps.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2omyjnmoj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rebpngrb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzsbast.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxkgcuy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuavgbx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2appogiqo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqodztjq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrfxdzm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbuiqcn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zktevnwj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhrtwaq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkzymwv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrttcsz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hafxfvdu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2szqaluys.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgysscu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2umzslfqy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqnujcz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfhnmlq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrzsxnj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2grmxqciv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjjfhvt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttywnugi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zztaqpfl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoitpik.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xpropztg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzardfha.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2thvmteee.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2glxdxsxw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqppygv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwomdtz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kotqilyb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2inhubkbe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uzejvvtu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iassdcfn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wliolryq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfsdaew.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kunauhej.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmdvumd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmqdiab.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2scfztgou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdixndpo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgdessz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hddrjwav.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qotheeqj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ancchvkd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qizdswnd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mksbbdwm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqvukdo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkhpbqa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfclrxa.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqglmyc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2flgaxgod.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cofjzrkl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qkniplqb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2amoedbev.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsezwxz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkfpwbi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqcqnom.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cduhgyiq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaikuyn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cprbvuiz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzwictv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnbmzwg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gosduziv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2updewlfl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ermudaip.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuifdmo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2etgmnpsz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iknilngd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2urpuwzgx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgnsalc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yqphxmis.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdkpwhp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjrlzgk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2blhzvsql.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuvyqlf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgcvmnu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiokrpi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2emtdfgwo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdhoenz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzjslzn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxiwrxu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2msuxmssx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ibasctwm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgfmbsj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxooocju.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jclainmy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrtjtx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2izewryfm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zuabmzho.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rtydzgfi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxctajzo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbbyvmz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhtjlfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxjlocj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuwvtkh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2msffhcfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coqeaclp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2azubkyyl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oddxqbzw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaarjek.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcomrxw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hriemjcc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdbypg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubvcli.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2afirsemp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpevcea.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jkafqrmv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnqeejc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttovyqme.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfapomg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2efxfbnya.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhpxizk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2srdikxbq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsykrzl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtrkgug.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdguwbh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoaymqc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxnpkvk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwozvsh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzugkrg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbizsmuo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdromrb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2werehbpp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsiucii.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuelhqv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fldlbmhz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgkteqs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dogedbaa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbofypqh.html


<!-- 参考信息 -->