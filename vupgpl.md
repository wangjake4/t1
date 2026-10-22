代发 wailian999

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2focokbup.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbjrbuh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhlewpe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoeghzf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ngurutdo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfobmtbq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhgiuyv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdzduau.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyalcovx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvowwrmi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvqcofp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2meduzfgh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vpljmbvs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uelcaftk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhkciiw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rynbnbvk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2luqsygcs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nriifpvd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2einkqndw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2likrwjuq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lssfuhtd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnojixe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hlllqreo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2twohhozm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxhptmq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2htttotwo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgynsay.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrjuqtl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxaysig.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nadnplgb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtjldvg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvpehzh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrbhszd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2betrmbzb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzigqsb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqbycpy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtcdenk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwetzwn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2irgxnhrb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkcsgor.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpfjags.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxcpjwt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpquztcs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oerpydad.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yftqinla.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hyikyybv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkqhdvk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfotiuk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdpalmn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqwpssf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwpsgzn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbrimuh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoiagow.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqucznpb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgvnbko.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzanuojy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iltgjhsh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaxjxyb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iddceuzu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdctjdz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kgocawxa.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjurbsgq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2upoieynm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swoxoldk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjirgin.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwjamlb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbmqpwt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgkuoyn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jijqoxer.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiptmjja.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqrvsjj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgktmir.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lialnuzi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsblpjhc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmcexib.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fglfbtay.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wepzussi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wslyhiez.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wcliumrv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtovnall.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2adjslsxq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mbizrzyg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaabshn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcmxlax.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pwitantm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2czedecbo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmavhjv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqcvtpk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrrnpsr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkfeovl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbteosj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2snvhkdam.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiejczu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gaajdlfb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uquwxqey.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yliigqly.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcgjpba.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuioaij.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2isstalfu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgysspo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyykzssa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rypdwjvo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdrzmmx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2adtpnwhc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbkimm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhnsofp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxbpqrr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2seuffbqh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkhddge.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhnbeya.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxflknt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsbkpmn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2svoevtan.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeivkzkp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nuewqldn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvmzauu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fszhfyis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdhvung.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qydnnzzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dozmozts.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xrijurxu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ystwqrdq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxvoesp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdsbcsk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iohudqup.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuvsbcr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfhbqre.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2migvwdlr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2inzvznrs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmjwlbb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcegdjta.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lurjodkz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yaojvxad.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2svxlviwr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wprxgscs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsgtjqn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jzujhohv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxiyofr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkrwnpw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hulanbmp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oixmjbea.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hofpmauw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2erhrvfcr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzpldxx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bvewippd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiquomt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgbodrq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjishkl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxqkpjw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dovfjjih.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pndhvsan.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfrynai.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbiiqgs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wcthqalo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stegqcsm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvijmbl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtywfil.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2llrmserl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jckdfyhh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmugeop.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nofrwgtx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpxxhzt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2huyqqogx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfhoeql.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2canompbw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zakrhisp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjattom.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfjvsx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkegblz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxuhojg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osvykjgu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhpaeok.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wmimzzbz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyepdpn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fyishrnd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvturbyl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkaunvp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2guaokufj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdvermq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlfveji.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vemcpwnh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdkprqa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbiztni.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oypmgqme.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zockpbtz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fekomamw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjmofne.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdhmmd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyklees.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oykoijiq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xktsjpjg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2voqzewze.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpwlwgx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvtbfag.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwpplsc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaegjsv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlasxre.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2buwbfphg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqpyuob.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fkslrsrl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjcxutn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbogmebm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ogedansz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2thlqlajx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyakxsh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2larxekis.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2krrykxcg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sybfqros.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cnacbcki.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oixwlrbr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfrwjcf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmvosmz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzazqdt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kracwpkq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2evotrgvf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jouyirgh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pywzzrnj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqagwcu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsjmhvf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2inmwhlin.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2llngvvlk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2skmuyrqw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjckogqh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgxjvwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aykiwldc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2scbntmyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpdrvan.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rcigwjan.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxcpbtx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqmcwgk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaerbep.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ecffayud.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iothavlz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqnkoom.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzkoxtk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ouomepxk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsohoki.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ikquxwcp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ldffjwrk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2puietwec.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlfrcyk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhwhetw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxobrft.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jhceqkpm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgqmowh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqsafjp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lravwpuf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcjesek.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjpobce.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iniltfik.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zjasfeot.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbyimhg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sylrratk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zckxatdv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpdqbcm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzcahkp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqtfjoq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mekjliys.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgemjkx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgsoncd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtypyxt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwqxrsb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fmozoqjg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvlmyio.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzaekni.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkbbctc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdpvwcq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcxbfis.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxpmxrt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2auhveswn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2apoovokv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hrexhizt.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmlwyip.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtodrnl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjacufcu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2aoydstmc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2amirgakg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcfqjpq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bmivmeal.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2llfzmkkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feblqtqy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2afpvwqpi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2blxdaihi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvslhxs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2osvskbll.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfgqdoj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvlvmus.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzmvolk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmscncm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywwppe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2recqrpao.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcehmgp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tipjbvod.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tilcgopd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaqaauk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2crypyams.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiwfimy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpthige.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvdznqg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqrurcu.html


<!-- 参考信息 -->