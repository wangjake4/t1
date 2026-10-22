代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfhqwov.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmhwecq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eivwuklm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhkhvbu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkpwudn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2klcxaqce.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wjihfcpu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvlclhy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmczqrb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2glwphgad.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqzckap.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbkdzla.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpqmauv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxgwulx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eloemjgf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmfycjo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwcbkdv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hybaiqtx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hropvzwt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjainyvf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zynhpfwz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2odtkuixs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sunvnobp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2myydnswr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjphdse.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxpmjpt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwabruz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulizluzi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fypudvsi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nccehwgn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lirhhjzi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpdscsn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lnivwtpu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cotueeys.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cscoczhp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnlulvh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnwayih.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbweguiw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2feokzbxc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxxgujh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkgvsbv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yvppgaok.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uagjlytf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2myivyfwv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oopqjfyr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnijywt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2caalpdry.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtvzwvd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdsdcdf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnipaxyl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wcszqydr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lapaejjs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxftlps.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2imtmbpqg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkpipqk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwzpeqm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2glmbwxla.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2izcwgjef.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnjhgzi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeapvvd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcqpawy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmixydq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2plfajsxu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcjepgz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtszkfn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoflvhz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wskknaga.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vguexlcu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gijvjjku.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqnzwlo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxuxlyp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqzhhwu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ringybqg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jccwxmod.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgmzhcp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nygzpbgp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjssyuo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2leombnpx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tnutjted.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjakyeqo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhsrxak.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbxcjnw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zftzoqtr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujebayia.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2efaneyoa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnglqsw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuwghih.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjencxc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2azooysta.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjgzeg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emcladmn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sinugcid.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jyemizpx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwezxjv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2akoqyswr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdirgqy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2egeznylg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rprnxmgr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhpvnbb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upugkqly.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgilyya.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2eubteyoh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qasmwbdk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdialfm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cwehgapv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2motecnmk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoszgfe.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2emzcsgzr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cawvpzey.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2eidskiqi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkfyuty.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuczcftg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrepoibf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbwodxe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qpebvxvp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uivpncvb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2evahcuhn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxgulwh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwpjvhr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzegwmh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2klopbrjz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xukzimyk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2haoxhxal.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dntjveyo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2awlqvhos.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjcwdbz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rfokiqhy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjswtqq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eulqkfvi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmdwoam.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wifoeofh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwjrapa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjcppgk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdczblch.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jybhotkt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2eobwfmpn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjvjibc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvedvyzu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcxoyza.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmjcevi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfxwvyd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqbtvum.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwibbtpq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xsphkhcx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyzkryb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtjjrrm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxofjan.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2obbdkxro.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2snddgadm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gtidiffn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqkoofx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2umpaylmr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbnqpcg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuxggfc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvpmljv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhmlccj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bmerqdzu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzvpkvx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fuylxwsr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2youvwtxx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlmyvzs.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnaxstw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jarxkquw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxbzupp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kaivzqzk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnrtnkk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjnrnmg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqvzudk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mrecyojb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuxaycv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbwbogu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjhmkvg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjypdsuq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjgeflq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uulprcrm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrhpnef.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yduhhkvk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnpkhvn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqtxblk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbpikpc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2euwsguhc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgagrdr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkdxmej.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeuzozr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvajczyn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbmhwct.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfnasko.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xydobxnd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fduqieiw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cepsmwzi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fckdelfe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyhbfkj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnllpxc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjubvb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqytucw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wchvertl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mioehkgr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tspsdegk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2euqcrwud.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiumxea.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbegsyh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlilzfc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdndezu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bptrfias.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tljizlde.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixvnsfx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqyopip.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcqxdwn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfbhvyx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzbrfmx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2munqamgs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxpfghs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhohnmx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwzhddl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wraomhmw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2itzmbgbz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdrabcf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2izswkhbq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ivapholz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nqufzrpx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbskslw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2agsfhmhl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbypqag.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcwuitt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfwfqwo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhllxytu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zeylbgrx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yskeqnce.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnbjfny.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eesgjpqt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rixwaqdb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcncymfn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfmkbhp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxiztic.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ishhdtir.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqnptch.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaczlhh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jrivmesq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjkccjs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xvipywgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvxhqfs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vpijulpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfncejt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwxofqi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2igjalxsj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lyerayyp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lzptbjtl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2liucqwnz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2walgswll.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lblpbgnu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfgxben.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaarzax.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eejkoxjj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpvwtqc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqyojmr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjtdndi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvjypqo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2deunkwvu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkigsaf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgupqlc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rydctwas.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxmemeg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxyxkbg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaicsmc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jntcrruq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wowazxqg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlwunwg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uddwciqz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2auycbmbb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lruupzaf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrackdd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuwcgzx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxpfgrp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2snqvxjsp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzshmxp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlzajlo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhdldqr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2goxxexwe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdovpxl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsyirxp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wezybylo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrnvymq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjidpmb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ywehycxd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2noallddh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlapbubl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iegogqxw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cxidjmwu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mkowuxmv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmymukr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yynfwoef.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ciijmhuw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcuknkj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqncvma.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wozscfdi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2swlcdiju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kymalqjv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdbhjpv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2iffoymrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqbjlld.html


<!-- 参考信息 -->