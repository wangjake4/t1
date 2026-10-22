代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wccvmtgh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awoylrxu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfrqjxj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrindbi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvzbuso.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejaxugk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oelalxjc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvcfffs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrimlfq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2doyrhifw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwlhrla.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2myokpeyn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2plgprmnh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyhtmvj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fwckfful.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzbreef.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtfyxeu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwnyjaa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sqexpnre.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoexyfqk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hymahtbi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsqgyjv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ozckrwtw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbundtkx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmcchn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hybdelzc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgqnxtn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2waubdkio.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bzajxrpk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxmofcb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2publhtbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgqteoz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aysvyfqm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqbouyj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpoubdl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbcrgpa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bndlktrn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2subkzupj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2czbaovuz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpkwjal.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mavuxwgx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwobnzl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nmraccyf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlksugz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcjjmgk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2czfupzno.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgoetow.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjdrioh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oplgxevt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yobegjgy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iguhnevo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhngiluo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wggycqsd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2afjvqqdy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xdglmmvr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tsreciks.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazdsmf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vipebudh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iestrgho.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyodhdpl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eecucokl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2itnmwwoy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhackoa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2peuadhst.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lfujovzk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrigchz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tldliusj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qivmxnke.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyhjkie.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsnchud.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odxxjdcx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nppfutxm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opisbibj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrjkcfg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlzdjyb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoqedwa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxlpare.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdevbhb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zbriokjy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfpeqlx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tibqdvxj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2quvfjpdf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efvdmekj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkfzhau.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2njsrcyhr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyafvej.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iyroydns.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhtybly.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obzhbnzw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhxmaro.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhbhotw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyflkey.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwaufqy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdozpztj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2svwcypcd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zejopapw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stwhyrsr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcxmcpm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2apchvofe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyucprer.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zabzppua.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2edlweedh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgjzqoa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gangsvlk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlekqbr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpehxocv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2laylrkgf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyubudzb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxynrjz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgawclnt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lqegxvrv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjaeplm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2owxgtymk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2svduiiqn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghegzdkj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvygnigo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iikcyzaw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vefcpopz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ouolmbla.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjljbaaf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxilfdm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aooqvynq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkakeyq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzoqgto.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nfofglbh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2awcavmzr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgtfmft.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdmokry.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpfknhn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iaivrfyx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2peohlpdn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvfifuw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqhfptr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mqicicsa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2agqnfhmo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvshhxz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xocddzxy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdhwhok.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2khhnmqlp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qoivqfdv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmwtfsq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ullzensf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zdghlpym.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zykryudi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bkleplqo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2udctboxs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tletkdxe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2aghjflwy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bheulsxx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fwldmbzn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqvjqzw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaiczaz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbbvhgb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehtqafc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xcejuqye.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2thwxieig.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2peizmniw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2slldnmyb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igctwpei.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xumcknvr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaucmyw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pemxefqb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2szievpiv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqvfqwe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuxygcd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfmeoes.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bemhmczx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvzpnoi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2podlwpng.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wksfdyox.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rhewgbik.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxeofot.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qsddjrjz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2inrbtsjj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2harabxzi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpntibg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmxwmmu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kiurdwek.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaccxaf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvxbtfn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jprlyuco.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrleknzt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wmotktvy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgjipkp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpacvex.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdxuzll.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsnmqct.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpczlpw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2adkmcynh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oedemzws.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pctimlmi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwnbiib.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wycfocba.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptmurx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkqscfr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfgotdo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeftttt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhejttb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxamydxw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvjxeqq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vusnjemq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyxicvr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcxvark.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sazvotac.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqhaijv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyvnmfg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvnohgz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcefdymt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcwmwdc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjhripc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyixxsu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xicqikhc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2landafzy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkdghhv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yltajrpw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ycedzmwh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyjuqog.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkqxshj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkkhvka.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2opvqslmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebloudcp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdiqysk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poasrwqg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rfabpnxv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xgocrjja.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wthmbyoc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzsuurh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpyapti.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ircqlusl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjdpwvy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zohlnfng.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwwggku.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrmyvjk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyzsmjw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2emaokxlj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtjcokr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtthhwf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmjxxqm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrfuump.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeqffvg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2idyuywfb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdrwvrn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2emrjxsbr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2euyizdsn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oyienmfq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2borrrenm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2adcivrny.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcivmcy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2smfuqapa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjrewqs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrsxdke.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrkdbml.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tadilnin.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ujujqxxy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cevfeuat.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qepkinug.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbdgftn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2axsxdvev.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtubwtw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvlyqco.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2grbtjrfq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsbhjok.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ferfsrig.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vseemqgu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2obphmfgj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btzygtap.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuamnse.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmgemyp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oooockpe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vxduaftc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlnlles.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjspuqwx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yclwxdbv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nchgdozx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2slpvyosq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwalsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sefkeeoe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgkcbuy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeghiex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdljjmx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzuizfl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xznxwmat.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvppqsx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hamzxsvn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjdsupc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdhjjaq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2twtwmkfn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rknsueuw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrjdnyh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2taamfebv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlgajhu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhegvtt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2enuchvsb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmkbrvf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtyivpu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2flgnbsdr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdubnbio.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxmbpmq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzzjmub.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdhlnxn.html


<!-- 参考信息 -->