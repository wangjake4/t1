代发 wailian999

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtxxtctovg.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtvnjdqqsv.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtgarilzya.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtsqibmclt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtbysyudai.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtbcdnlbmu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtjbntcytv.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gtbgrrzsba.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtgkveraaa.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gteuiomktn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtavsqweyw.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtyooxtocr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtktgahouh.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtcrllbgjz.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gthhfysqpv.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtsnnaihik.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtrkgkobhz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpisboouc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtxuqsrihr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbwhaike.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtsyxhviti.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtjpcuhgak.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gtlvrtxpwn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtitvrtbau.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtkxnnmerx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtbjjszhca.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gtoiuxwhqb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gtnxlbthrr.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtysmehqeh.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtqnmaghov.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtpcbmqpoz.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gtaanjrdjt.html

[U07] Py：反转字典键值
来源：http://dali.chenlongwang.top/Article/details/gtqclyhssd.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gtaiaqexnk.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmonkrpv.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtihiztder.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258888.top/Article/details/gtridoxzps.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtrlesunjf.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gtxtdxjwgf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtxlctmgkn.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtzgunzqhz.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmpevart.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrqnxqxh.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtwdkjfgnz.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtfhevrier.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gtrjzrhfub.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtfncntvld.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtwbzakmhe.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gtccusndql.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtxiaywhgr.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gtxthusxdf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtlujvdnou.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtagdtycgp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gtkpzidwkb.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtzsyspryr.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtdjndbccv.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gttwzcfjdo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtjawukpue.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtibkijxfg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtaxuwywjk.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gtqzckecuv.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gtliipftgm.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gtdhvaxgyz.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gtusiwkuzh.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjkrqger.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtrlcrfbes.html

[U24] Py：路径操作
来源：http://dali.jlsjyb.cn/Article/details/gtawmqahgr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtwhxhrsct.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtqutptscl.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtitavlftm.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gteneizvzj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gtlzzunqts.html

[U27] Py：异步 HTTP
来源：http://dali.cdnleiting.top/Article/details/gtyuvsgnhh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gtmbihkkyc.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gthwiajqzh.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gteuhiqxhs.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtwkacgpoc.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtplwuogro.html

[U30] Py：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtlnzaldex.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gttevdqywn.html

[U31] Py：单测
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgpykqif.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtnpzickaj.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gtlrlhtyvi.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtiljypvmz.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gtdnnntrhd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hfpthk.cn/Article/details/gtmydxtcbm.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtqyxpbzng.html

chardet.detect(raw)
来源：http://dali.cashguo.top/Article/details/gtlzndlsfe.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtcawooebb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gtucxxsdlz.html

[U36] Py：定时任务
来源：http://dali.316326.xyz/Article/details/gteftxeeyu.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtwzneaoqq.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtffgtcvzu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtoldlmhlz.html

[U38] Py：获取脚本所在目录
来源：http://dali.gzhubu.top/Article/details/gtahvfkvjl.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtcobeqlen.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gthhtyovwl.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtpfcbrnrf.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gtfksdfyzi.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gthluevsdd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yongpay.top/Article/details/gtxaakjfrl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtusjykttq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtwswftlqx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtjiscirok.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gtjemneabq.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gtaxmbvksc.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gtjokqfzxg.html

declare(strict_types=1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjylhfxlh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gtwoalabcu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtvwmjbigs.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtmydsckot.html

?string $name = null
来源：http://dali.zdqjudy.top/Article/details/gtmpljcaom.html

[U47] PHP：联合类型
来源：http://dali.316326.xyz/Article/details/gtbvvwcmao.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gtzyyuyayy.html

[U48] PHP：纯枚举
来源：http://dali.yongpay.top/Article/details/gtelofcyxs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gthrgfotph.html

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtzodrkknz.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtazahvfef.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtqqredvbz.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtlwrhgrna.html

[U51] PHP：数组解构
来源：http://dali.bjfxy.top/Article/details/gtdxdetjhr.html

[$a, $b] = $arr;
来源：http://dali.yonumen.top/Article/details/gtqulwjubk.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtbtczvmpq.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gtfltpvtjh.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gtgmvhwpty.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtqypptgtp.html

[U54] PHP：空安全调用
来源：http://dali.yj20258.top/Article/details/gtqmugbnig.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gtfealorol.html

[U55] PHP：match 表达式
来源：http://dali.aibaodan.cn/Article/details/gtrfpqzodq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtosycblfw.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtyjndrgrg.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtzkibyzhz.html

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtavyxzxox.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtbuazkwym.html

[U58] PHP：数组三件套
来源：http://dali.nwbrower.top/Article/details/gticjvhdts.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gtijspsimn.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gtbdioxvvo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtltbjpeki.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gttxkybfsn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.iojbl.cn/Article/details/gtcwlqtcml.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gtoisktqnn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gthqsagift.html

[U62] PHP：日期对象
来源：http://dali.dashuyun.cn/Article/details/gtwawzmpee.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tanke756.top/Article/details/gtgugjtgei.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gtxojxdfjr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtewhhdtta.html

[U64] PHP：目录遍历
来源：http://dali.dianchejie.cn/Article/details/gtoaopegpe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtoccistop.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtcpzrijtd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtecxcnhim.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gtfplwxcxw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gtnygzkvtz.html

[U67] PHP：处理文件上传
来源：http://dali.0kj1m.cn/Article/details/gtiauebpih.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtcfmcnhpw.html

[U68] PHP：PDO 连接
来源：http://dali.ivvv.top/Article/details/gtjegucxpf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gttqiuhpva.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gtcoeduwwo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gthzluxiij.html

[U70] PHP：PDO 事务
来源：http://dali.quarkkingdee.top/Article/details/gtaejwoogu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gthykvfmvq.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtrgxvfgvs.html

throw new RuntimeException("失败", 500);
来源：http://dali.316326.xyz/Article/details/gtwrxrlyhm.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gtnzivepbs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shzxlz.cn/Article/details/gtlowkuqsd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gtqqefygwt.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigfzy.top/Article/details/gtxtxmcnls.html

[U74] PHP：读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtavhsxnyp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtelisoppp.html

[U75] PHP：依赖注入
来源：http://dali.zhengqikj.top/Article/details/gtzqwkxzlu.html

composer require psr/container
来源：http://dali.svipenyu.cn/Article/details/gtdnlzrhzu.html

[U76] PHP：简单路由
来源：http://dali.chenzaomai.com/Article/details/gtmlkbqicz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtfxgqpbds.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gtxunckhgo.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gtfgjutuli.html

[U78] PHP：单元测试
来源：http://dali.fzhhl.top/Article/details/gtykboebcu.html

composer require --dev phpunit/phpunit
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmegnuis.html

[U79] PHP：静态分析
来源：http://dali.jianghu66.top/Article/details/gtpynpdzko.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtgvfwotax.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gtyroinjgu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxrynles.html

[U81] JS：初始化项目
来源：http://dali.yuxming.cn/Article/details/gtqslncmop.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gtecjrdlnv.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtdinnmmyc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtudxhlfch.html

[U83] JS：ES Module 导入导出
来源：http://dali.snrcjt.cn/Article/details/gtsvletvgh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtbtpvmpsq.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gtfolkgfux.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daxiang520.top/Article/details/gtcfjxxdws.html

[U85] JS：可选链
来源：http://dali.guowangkeji.top/Article/details/gtctgnduuv.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkgnnvup.html

[U86] JS：空值合并
来源：http://dali.zhixingplan.top/Article/details/gtxqtqhcaw.html

a ?? b
来源：http://dali.yj20258888.top/Article/details/gtduqynvqq.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gthnkokwlb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.haohaochexian.top/Article/details/gtdpwmoabc.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gtlmukuczs.html

{ ...a, ...b }
来源：http://dali.birdmap.top/Article/details/gthqlxicuf.html

[U89] JS：数组去重
来源：http://dali.zdqjudy.top/Article/details/gtkeybfxjv.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtvhdyrucn.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gtoegsuwbu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtwgdoluax.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtqhbbjnsy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtjtjzqeco.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzdoqhue.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtawmicbcq.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gtiuavgtfo.html

`共 ${n} 条`
来源：http://dali.gogol.net.cn/Article/details/gtzxbkfvyb.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gttgwcdsmu.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtcanyswrn.html

[U95] JS：Promise 包装
来源：http://dali.zhiwuduotai.top/Article/details/gtzmizarvw.html

new Promise((resolve, reject) => {})
来源：http://dali.zdqjudy.top/Article/details/gtkehvqnjw.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtuaugofgl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtxypoytad.html

[U97] JS：并发请求
来源：http://dali.316326.xyz/Article/details/gtzxlwjjxb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtkefjwxdj.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtacpzsklc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxuanxn.top/Article/details/gtowpftbsx.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gttrmotmeq.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gtouacdbbv.html

[U100] JS：DOM 查询
来源：http://dali.ybcxt.top/Article/details/gtdjcyqext.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtcrvcfbyu.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gtpqvbagqr.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrultfly.html

[U102] JS：本地存储
来源：http://dali.ivvv.top/Article/details/gtywbcoosq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenjidiqi.icu/Article/details/gtrpjtkyjr.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtncdyhjvl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gtexqrhpkm.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gtclquffou.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtqkmxpsrn.html

[U105] JS：节流
来源：http://dali.yanxiufei.cn/Article/details/gtixbcnvcn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hammf.cn/Article/details/gtdnbsnccp.html

[U106] JS：日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtlnzgmena.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gtqnhfuaeh.html

[U107] JS：数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtouyyybwi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gttwwaweys.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gtlmngzeiu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gtrwksylth.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtjqfukyxd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwurhihr.html

[U110] JS：数组分块
来源：http://dali.nanxuanxn.top/Article/details/gthnujdjou.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuxming.cn/Article/details/gtoxkfrmxt.html

[U111] JS：对象转 Map
来源：http://dali.ehwqpu.com/Article/details/gtkxqiziaf.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtarwcdije.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtacafjcjc.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtdbfmfvke.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvycnssw.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtulkyuktc.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtxkqhpgrk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtjedovfxg.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtlbdtevvo.html

crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtswlzjxid.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gtnzrnxwyj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gtcjsjlqov.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gtolbcqkqm.html

npm i -D vitest;  npx vitest
来源：http://dali.gotoacloud.top/Article/details/gtuaqsvpth.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtlltipibq.html

npm i -D vite;  npx vite
来源：http://dali.xuetiantiany.cn/Article/details/gtgeouqxcn.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gtohxmxqhx.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gtcwvoblyt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gtcfxawjnt.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtufchagge.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmshthhqd.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtdzxohrir.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtoxxnxmje.html

按语言统计（条）：
来源：http://dali.jinqigfzy.top/Article/details/gtwqmnvpfa.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtbfpedhcm.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gtcgolwjmg.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtlqlnwxwd.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtpftzvkpq.html

Java ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtgfurpixm.html

Go ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtfepvdpwj.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtkmstmnsi.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtzslotecl.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gteqyzgsns.html

C++ ............ 30
来源：http://dali.hongshengwenyu.top/Article/details/gtdglawenl.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtjtoocmah.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gtxdsbmznd.html

Kotlin ......... 15
来源：http://dali.yuxming.cn/Article/details/gtdismzfyk.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtujjimpnm.html

Lua ............ 10
来源：http://dali.aibaodan.cn/Article/details/gtkacqqllw.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtnyvrgdld.html

Scala .......... 10
来源：http://dali.mhx1999.top/Article/details/gtirvpxylx.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtvwammhyh.html

合计 ........... 2106 条
来源：http://dali.jinqigufen.top/Article/details/gtnhjafasf.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtqpqcxtgw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gtnwmhorse.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtmslkuvff.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtisoikaab.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gtffpwmbej.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tianlin.xyz/Article/details/gtfvsrzvog.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtiimzuihk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtojcahdzg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtgclucfvz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtvhaoehtt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjhsbzwz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtnxslntho.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gteglxvjni.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtcivznehu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtkgpuqqqj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtbmkscnrh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtwnzvehum.html


<!-- 参考信息 -->