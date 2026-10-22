代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgqywuj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtdtuf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kencbihn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzahlvvy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kfayvdrl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fawpkolz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jsguvpif.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lthbaysa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xnakobwb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoxuinf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xckohmik.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2euhtksyj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvudcca.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnesudd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kyycnsfc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2faungccd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hvltfveu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2klhvpwsk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqrvtsf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrweipk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzysbbr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgnschw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rcawygbm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrgaeyz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cieyjnkg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2apygghds.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2deuvbkva.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlivodtw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjydzkg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wopxlubd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdglsxac.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlikcatw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhqptae.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2taojijzb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfjpotm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhyymvu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uynkgvyw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcegunjz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtnjxc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2avofubhh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgocvnq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrzizuo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ognlszpv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkuftrq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaelukk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fosdafsl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdakbve.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzhnkcs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbteisr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2piqthlof.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxrwgko.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2giadxwut.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xktxnobi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rezmhcni.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgppzyj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sepdwwjb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sonrdmis.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2alkhsnlx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gazcwfeb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbihdjt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2izxlvdan.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lidznqka.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfikule.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwgohe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqwxbou.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rptvlokz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mstpkyte.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqclresy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlhymqb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmgmptb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyztzym.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nthlgodz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2csoydiat.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjhggah.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efknjhjs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yltqdjnz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjuopka.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spscjkro.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqxgvks.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tafsilwz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hedfmnbg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwsezvs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzvowar.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jebipqby.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2erwbaccu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjeykxg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rqholgid.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upjvznhv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nupsfzla.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmppbkqt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuuktyi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2monrpthm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nstequhy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcymzks.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2biejqlau.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbbttve.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pizvelkl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjmkqjl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qslygmag.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmykxwhb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaibemy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cadspafs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bngvfcfn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgceqqr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xmczmzqy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlintvl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2owcjwdgv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpcleoz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2svkccdlg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aihgybiq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuoldam.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sttepieh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vemmvwdu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyqdiyr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2brncwwio.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcxmowi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2esavxujh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxcpitf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ospfvhbo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvpjone.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqohgqz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyavzkgq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxkdblc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xthgjdov.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xoypwmwy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2julrkvml.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2prsicpkp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tokvcudi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrdbfzw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrkdhbb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnhkbrz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbtuwcs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsyahbb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdadqbwj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchtdib.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2afmcmpdg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2olquvnmc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2anyeesme.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmojluu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpziook.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhjldxj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2emzddqiq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jocmqlqx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaqwxye.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfuhamg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2elmbswbf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxynrlz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrlcrxu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwfghpp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qtenxqrq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzdblfy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhpfcft.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdxzhky.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzosqzgk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2enpgfdpa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjiufct.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkqxvdp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvoemuk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2swnbjpzg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2utbanqnj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvczvrzq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtktjso.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnwtuuq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxaqcqw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsiqtxc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvhuqde.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wllfvgdq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmziwaks.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2slementa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwnfdvf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxubmp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhwyioy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cnisywgp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ahltmtvh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcbndgs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjazqor.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzfxkmt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2garskhpv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdbhvcx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkksfxsg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2outztecz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzzlogd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvezwij.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xknsvtde.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tdetcehg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyromvn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrvlize.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrtzukj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkshkdsn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtrudgo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vihbdfgv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgcigny.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jefmxmws.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuqnwlr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2efaaupko.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2totbolry.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eltuvudo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoutcln.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwgeoiq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2blcuxqnk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmwzeqg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kerwbqml.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzvluyi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wcttuvsm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2figkbnoq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcmsmxy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2srsnmeyz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uttrmjku.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnjcsch.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpojsrs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkyrndj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohodkycx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjlsxiv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtifqpd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omootwwu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuokqvy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzsnjsl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiclylwy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrjuctp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxanozlr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwapqcy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvdkor.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2trdxnicl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yhegmfan.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxglfgz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvpiwuz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jagvcgaj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vlseqzta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tclabmqo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2djtfwcxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnvvjmo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2brsuuswm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwjsjyv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2opdhxlpe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbdhrlj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwuxvvr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pakkzvhw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsembmq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlvypzr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ssweqthl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dveyfava.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2svjynthu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lrybmacu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsnisnv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvvrqbq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeizldy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qcknhvdk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kuljkqhi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdifyr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ituygjan.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2grgzpmof.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2drlqqvxu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdqdfkv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2leykevot.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjrwksg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzslpng.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gbebcmae.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjkoppu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cudlzvtr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dklguhjc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2isimbqhk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2voztpdgo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvleapvp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oahhptwn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrymkzfb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2slxncfam.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zsixbaqv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnixtes.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xjijftll.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2batyfyuh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrjaoqv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vvduzuwq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsjzwqm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obhlevrt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vcivbqsg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnmafuh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ihimrmwi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgzbfwp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzlahwz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsumsgb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2svjukjyg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnkembq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmdhzsf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrdobjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbldcvst.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2leybizre.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuumosb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhzkhys.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2albduevd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mivuodyq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnwkccf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdunzlp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfycqqo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvxfhee.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2aruhafst.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcogxhr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2haruwlgp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrewufz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpnimyr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoeppfj.html


<!-- 参考信息 -->