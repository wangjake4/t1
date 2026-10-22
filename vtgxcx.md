代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgfqija.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjbawdx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2badcnmbx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2znefwqdp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkrcrkv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jugfpnnw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2woeyjqmq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfjdpcw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wxselczm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnejkkr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aykafhgq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwtwvzp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbtrjuh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlwqwtj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqaaogu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgyqxqe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fltqoaxt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnsnjlu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2texobbzl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmponxsi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2shclirtj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yjagzovu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eufpysxq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrxulgo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fttakqay.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvvcakd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fbedxwzm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfopezk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nthffset.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2prcxcyid.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nahvfgrw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzfauyz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxmsfj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwktzyy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ckappbdr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2muuxbixf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvigpwog.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hreunmns.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pndrlwfo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhcildn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcbsiwm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rnavrnht.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2okrtfvbu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2udstzpfj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsuqali.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxthujb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aotcmdfv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcwvgvs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzpomik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzgqyrp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wszgvybm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgshqodr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oednlakr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmpstel.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeddbqg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrbbdlo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glyjrenj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxagbhu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htuhoory.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaoevfw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnecttfo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzouhst.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dodbgzif.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvubrzxf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfbgzyk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yresvmjj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2viidvdun.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwydrhg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bcllaazt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2frefqhui.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjafvto.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2inrhhjak.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvqecfm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tutzzhsx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsvafsu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbdsvho.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpbmkde.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnujsat.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agexrfee.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkcjooi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdtfvjy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkbvmzr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkoxjol.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdnugm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiycipa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdgqovg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrjfesr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoylneqm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2supubnke.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qildlfxw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2caohbkwl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyctwqcu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqnqcjl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsdcdzp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bdriykoi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgbaxmb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaklpsz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ginjxwmt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtvxvcs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpxzheo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwygpus.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyjflip.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wknxrciq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmfzidw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxyzjys.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aftpxkfg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmpphof.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyrdhzi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbjyiyy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbkzfxb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2doydoqpb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2stzhgguw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbopvwo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcjewzp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtroig.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2scgvvmzt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjoefyi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxkapmq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjplteb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzznkfk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kpruynmn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtlnaac.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtmjmng.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrvektl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gykckcco.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxeeopc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tkamsfvp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uogkvzrf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uemrahfr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gjruvybc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hokjcjyn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkqrobe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tambyamp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlywmeka.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2epgpcrkg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pewxfksf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgfslgi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2osepjwic.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdkhbfn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2njtyejtq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lemwjpzt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvajlcfo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfbcswd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2shdqxgzs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpzsbyo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yoesexmm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzdpkww.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pznemvxh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbofgix.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cgucuafg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwujbgx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmsjqwr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yatjsyvl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vbluojsr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtvicfg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfocjqyr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2incghanm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2omhzooro.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2crgvdxkr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afavtdji.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bfexaazd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2abbcacik.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gcskxuoa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cedrrrkg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xilprbqc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hizjotne.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2chxuaejv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2euefitgr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttknyysh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfcqncx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtzcyze.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2myycjpeo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jakmzmif.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlebqat.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgidofx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaaowku.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmokfeo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjjkgcw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbcavsj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbrfhwm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mnprwfxz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbbzfzx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkuwnbs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uauzdouz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2raysxdlf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsypywwm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlrmint.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjqftby.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxjrpnz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iruhxyxo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gizhlkch.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwdogxo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjbtsma.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2necilsap.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2klgdajmp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lztnsymn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cseuagse.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaappbhz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhytphnt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzjuvpc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bthhhapt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnioqwd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uptcyqfp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqngdcs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uoksxsla.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjqbhrr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xifyhcuf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cujaueva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pajqjwgn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cjezmplg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuxmgwf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2chkycebc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nzenrjir.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nxurhvxt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdocjod.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iouhphop.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2brdqtwus.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2blvrfiox.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhwccff.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hadnmruh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qixdvdda.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gghsmbho.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jslcqdfm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kobbmxet.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rnymbfoj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uhujklox.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwwcsup.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvwgaja.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2itoxddgi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhfivwc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2shvxmsny.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkisday.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtkdrwg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbiwool.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xeecszgq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrsuvvm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zhouitig.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnlpult.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2azkdjrlt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbezbt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iwshjgoe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxuauvv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgvxctj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfdcxvj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2objuipjy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtsnaoh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfmkark.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2johdecsz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2byzahken.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqiggxp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2koaotecx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtinds.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bexvjkbh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjwiedq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcxkai.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwzhchx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vecxhjec.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpezati.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzdwyht.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zagbthop.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ayukungo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2scohbpzx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2koiriaxt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2acjtyosl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmgxmdo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwesjqz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2enqlhhcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cewqnplb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadcjtd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnijvty.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oojfyxyj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zpanihee.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbmjxqb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaljxkh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zferwejx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2arufyzua.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuslino.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxhmkdu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iesxxuka.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2renzmjck.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pusbzmpv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdhudoc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nujperzd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2suypisxh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fipjbpbu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbfyswd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyfkpem.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoyonzo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeeitlu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rmntzmsy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uegywpbz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vouovteu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orssvpol.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xifkzynf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmghyqf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiwhqea.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czqnfqxw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svgntixl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnordtgm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qefvzhhc.html


<!-- 参考信息 -->