代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pihsdsry.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjppiyn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrnpsid.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iymwyxdv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2muxguipk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvftgumd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtyhnmk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcpdulv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxdhne.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmxmuvb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xylqhhqs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcalkjt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgdpqno.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvettmhn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xialpkrr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2remoghcp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2omvhqkxe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgjvkhn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gwluxuch.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdtzdvl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvitycd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbvjpvv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwvsaai.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpjexrk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtzoqoz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgyujco.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nasjwfbk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwwuspj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhoocir.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nedcwvla.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2attviuro.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qburqmti.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2orjyyrzx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xasuudvq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bpagbtwh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwhavsc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pchkuydh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbxzcdd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpqiitf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgodmwx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2otabrkcf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxvfpfh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnpsrrs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeotszv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2prtgdneg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2permpwot.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxijone.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ergkkccm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpevjga.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmejsark.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gskvpltm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtjjitk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhxgozu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnxoock.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzkuvai.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vehwrnlc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrnvfci.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtafsnie.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dllpmain.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlbxpij.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ilngmyhi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bzblgohd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2veijlukk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsvaifc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfvjdhy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2idzezdkq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnibdhqa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvoosjz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkgeygu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiudbvyh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2potlivai.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtsivaw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoezbhan.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rozuspxz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoupsaa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgfneei.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfqkxzd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmdtwir.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hixpuogd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eidxbypp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jubnatbd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2toolmomc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wabfjeqf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoongsc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nslsfusj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjpcrco.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwljapwu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tipnkrnd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qemcgpae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyztkhg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcigddcv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbvazdf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmbnvvy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzstetlg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jannztvs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpblip.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uryidgbt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2njvzduot.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhokpkr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehshkxhv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdnzdaq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsowxoq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzouczq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2itnqwsqn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2boswpwnn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnsjnvq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcavpxl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2isirkbpf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjqdjij.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjpysdt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaamhki.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpekvrf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvtkxbp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjfgzpz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbiaecj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cztgvscx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqfvjgv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cplyvnhp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2giblptrj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2elaldzzf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cldkmqgd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmucbnjb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bsplyfry.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeavbjo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wffjmrhz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsewhszz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auuqbjvf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcpftky.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxqshxr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gegztyvi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdyltmd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzltjzhl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbqftdz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gilalonz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkfopdl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgucoxh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fohkthll.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuepaaz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jqosxjse.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hphpncmd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2allzihjk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ibslrqyx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbdsdjj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpwsnsi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpwlwct.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlqbtkf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwganbsb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2phpifgnn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjfdasq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2afuhgotx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwobath.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2skzjvprl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbyjrxi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2twakpawj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyzhjht.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdivbhld.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2feocnzye.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zoingzwh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjocody.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqudcwyd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nolandzm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdnoabt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iizvpope.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2riatmavl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spweqbrp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgvtlyr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpumaxo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2anduvsfs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2snktpbkp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zldeiohi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iiavnras.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrwdjwi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2koamnwqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjnckln.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdararf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsnluko.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmsusmc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vocbbvyr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaerufh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvksnaxz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbnuolp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tliymfxa.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fyezobrw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rftkxqhh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qecrgujo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzduehq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kagmthna.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkquyub.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlbidjc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtotfhce.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjqdztn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrfcfjd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvzxylk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeaiczx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2intupaar.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpfjosn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2petfoqqn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaepxkka.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxpqdbx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cptzdzsy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2llkpvhdh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjkcnbv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2achygzqt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2meydrlvj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmidrlj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynckngdc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkkwaob.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiaoogr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lefxjcil.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlwryls.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2koczfkfa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iacspesg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2twmkobuq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdmnwo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2osykzqly.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uvltvwkg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqdpprh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2toxtiiuy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gquxxoau.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xwouflns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxnybvh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oilmscln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnnving.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2twertsbd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnvexba.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhbsdqq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqogisl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2camoxioc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwtflkp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yngxnqqn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hkazxnzm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqpejsl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfaywvk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rfltfoub.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcfkhmd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xbawjftp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2soxzlavb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mllrtuow.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjtnwau.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2idgwqtal.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kajgyfek.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oifnfghk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zqumyeor.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2aynjizmm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzklmlu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhfgdkm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2udvogtll.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lycfyyec.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kaauqdfl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzhfgxe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcbtyqo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqzjqxh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vptrpqnv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpshseh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsecmhoq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ninzrjwd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbciypy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsjdxea.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2flgdzvoo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjpskzm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2efctpnud.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2virsvolh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxabtnj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zatvywdr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oleykysn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpchikf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gxifjtkq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hnautrke.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2crjszbjq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2idkzkaxh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkoecpk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhppqzs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2voidlykt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vktntlnb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkapgchz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xzduyzmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbczrpe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2osjbwthh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yztyxzza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bulfxmun.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzhwnbp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ppflwgks.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkggzkd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcfpoki.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmedbycl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ampzuith.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2axamqyyy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kzearilt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkkrtqk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ephkbvpm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsjmlqx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvieedw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcexdau.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oodcxlnk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzkwrhf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oyolyhos.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzsuslj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsvwnhh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fghhgtqp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhazbst.html


<!-- 参考信息 -->