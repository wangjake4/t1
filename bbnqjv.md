代发 wailian999

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrdwhjf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmztokq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdaidwa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhqgmyq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bggjaxlw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asziqswx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2owczshsp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoqvuob.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgwezro.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkckjpe.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqupwwix.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tquqsrfm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsphepy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lppbgmma.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfkkqye.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxcsacx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxtnypd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgkxlcu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ettqgweq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kurjayan.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2infcuvdk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2acbzntiq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ccztsdij.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbvtgkr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2imyowess.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxxrotf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqwzkjy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lexwijbx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ririeida.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tjblomjd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkzrizq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xijgqavu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqqspsb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2djtrdzrp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyvkxhy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nippilbv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mklrhqzs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xccsbdin.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpcudku.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmliwya.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iurmilam.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rynidnmb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvnhybz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifadoylo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iuovjznx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgukaci.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjwkwhc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiginzd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2syfwfdel.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjwlolu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rstdshyh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkuuhje.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bursszts.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpujahea.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsgvvau.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2luurkgiw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wohsmbco.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jkclgaol.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfmkgey.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tzckuhvz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2buzwpaza.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2leulgnpe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyoywxn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikieoul.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcjibwo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kvagfomx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2swscgict.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnfncsk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2njxrcklp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zisvtkao.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcrkdyn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tahijsqg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhddfzl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkpolot.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbijtzl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkzewrx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ungkxruq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfrtnff.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2puymoblt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erwnhfyx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xffvwnjl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2krvptopn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkhkoqy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdtvkan.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvhszmc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnuzjqi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaxabdb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxkpzzc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyvizaz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhasgyfs.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpkmrhn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnridtah.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2auvbikfa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhbaahp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhcthuc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvquiygp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2typiagzb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrdicyo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2safewzpf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtidjllh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrvaotg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgjsvew.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zeizudwn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2shizfuuc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lsknxiox.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bohecxif.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2spralfxq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzqljgh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2winjuvhk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2okahcccj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqsuhma.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpqqnej.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmjptmc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bprinesm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cokwspld.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yroargzi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sobclmyu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuzhyoi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2psgysbdn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2spqgqixl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2syyphiqn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2faebmjrn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmyylzc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mysbbabt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tmotqjmn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouncncxw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gicxyxco.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mddoavcm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ogirntmf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkffyzr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiliigb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2breuvhno.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lpherpff.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2heeoqxdo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kjowngzh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lurdevul.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfersgu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mghlpnzp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuvkiut.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoaujwp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xgebeken.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2endtnayb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzfdctf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2avcanavc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2loxccbyb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2morlkpfh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ostqsnnv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eslmmqcr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2psaiyhat.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjdlrrr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuxkwtc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2acwllger.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzrqaue.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrewwwc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eipmlopy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjefbsbb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxobwvh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqwjhct.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2edhcuayu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvttdpn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qkozgpgr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvbxmjo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gieqduun.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uegwxsna.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gazbcpih.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rownxheg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhlcado.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzsestq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqybbao.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2naybntfz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yidaqaxn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfidzjm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzmlozp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iqljkgjs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jktcqcsp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yilisiar.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2grhbxnxc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmebzxev.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fauihblo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bqszigga.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2prbdsxwh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfebdvt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnlhdbm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxjnwwa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2civlqrgg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2chvcrish.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hpanlivy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbahwlm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2euhzbwyz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sesxbyjz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcfukxs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlnhptw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkqxeww.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2morxtttg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuncywg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lnscdhfp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2udnynlev.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhunviu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhpmomc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcixiyl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sguyiwcv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyxnyij.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2plvijwro.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aekczkfp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eazifjad.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxjyjkf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsoxgxx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2impchatb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzxjuci.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcbacwn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uiazcluh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomgtbwo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tfswnoiv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2umwybfuh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqwdphm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beygdxqc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2houhdkcp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2umnoytmj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdaypki.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qqupfzsk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjmpfch.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxqutbq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfyprzd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaekpea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atmhuipd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oblazoyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqfurrh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pkddmfld.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jljwidxi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wbspqbup.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrbahgy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxknezh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qodgbxnf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2irddgjwl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrirgca.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ojniehmt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzxrdrc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2iliabmzg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2teavyoko.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxxldeb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pnckphnx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bmefccrg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2opiqaabm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2idznbsvr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dskohctq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxximjr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxzfljs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2aikylrzu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdwdixg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqpxywg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bccyejbt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hffempbc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcazliu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsyxtvs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpqvwcz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2asjrgbnj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyluoooa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wldpjntp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jipdybgs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rugvueap.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbkqlvn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmyhyeh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uszqztac.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mydfjasq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2miijvgwr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmarahs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2isexikza.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2naisbbki.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ljylhhws.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvvzfpm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkvrxlo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dupkhoci.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbpgiyy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qiurizty.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbrhido.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiyukui.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zslfxyzl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oqobopvs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2poymfylb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxiynou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzbnwde.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjycull.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rahpksqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvydehs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fblieuyd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dajdjeuk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlrsaes.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeevgfy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2abjbxdoz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdnjbtt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdnffcy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2izjgyeth.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xlixrrso.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mpntsiam.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vvndcgoo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2reefgqpy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoqmvur.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvqnxse.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmgpwpe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwgcyvt.html


<!-- 参考信息 -->