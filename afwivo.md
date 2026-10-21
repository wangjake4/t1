代发 wailian999

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtgphhjume.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtzhyybkmn.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxsbsthu.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaclwbrx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtgvkljhek.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtlwdtgdwk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtcepmoxda.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtuvdidngf.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtotkdddph.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtgekofwuk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gtkdpgsbjb.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtrvivrndj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtbvlihwie.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtouoedhhu.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtlvkngcob.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtuhuekitn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gtjbqaypen.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfurxebmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtilhwpmtz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpgrowyhv.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gtlffgdrso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtynwptnty.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtcgvrvrfm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gttmxzhbzl.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbqcohfe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtcmslfktg.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gtktejtoli.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdermjhs.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gtkkoydthp.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtpnshzbjo.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtllhzjbdz.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtuemjcmbv.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gtpitodriy.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtzlficypa.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtzowlxkih.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtqhibtchb.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gtmjmjmagw.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtzsfuczlt.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gtlppexeei.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtcjmmgmep.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gtrnshfywf.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwlwmzpj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtznbzkfif.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtulninbvf.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtxboqbmut.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gtwhrupctz.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtqvckkzfv.html

defaultdict(list)
来源：http://dali.zhoulong.xyz/Article/details/gtejljvpwh.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtrjtrzeod.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamiaiekv.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtdwsiweko.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtwbohekao.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtvisajtdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gtiwbjhedm.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gtfayfxfpy.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gtqzlqrver.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtexsgqptp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gtnrpuvbnn.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtropvlfxk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtrrgmkuwh.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gtkompgcvs.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gtmwdbmodv.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxakkosc.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gtqzojnkmt.html

[U23] Py：分块读取大文件
来源：http://dali.aizwys.cn/Article/details/gtwgihdhbl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hfpthk.cn/Article/details/gtswccxbma.html

[U24] Py：路径操作
来源：http://dali.guowangkeji.top/Article/details/gtjmlwhghq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtsskzzodu.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gturxeiusg.html

csv.DictReader(f)
来源：http://dali.zhengqikj.top/Article/details/gtoxiilmhs.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gtjsydjmsm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtfphuqepm.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gttzeqiofl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtyobdaplu.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gtnyfsgrrr.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtyfhypjym.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gtmbihmlal.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gtmtvltmdm.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtevatugbw.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtvzhvydmp.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gtmcyunjri.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtfvkfnddp.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gtpkxrodnh.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gtombomigi.html

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gtcldzmvuk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gtvgcbafcf.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gttvqudvvh.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gtjjcbeldl.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gtjajnjwys.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gtxuxmomoq.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtjpbhbeko.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtogmamrim.html

[U37] Py：读写 Excel
来源：http://dali.xuetiantiany.cn/Article/details/gtmzupvytr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gtovdehdvy.html

[U38] Py：获取脚本所在目录
来源：http://dali.snrcjt.cn/Article/details/gtkcochqix.html

Path(__file__).resolve().parent
来源：http://dali.hysaishi.cn/Article/details/gtnkfnpagi.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtkyytxmrq.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtbylobobr.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gthsbndjfs.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtigpizyxh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtmttxmoyl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gthvohebba.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtifyuiesn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhixingplan.top/Article/details/gtjelfgpjw.html

[U43] PHP：声明命名空间
来源：http://dali.bjfxy.top/Article/details/gtnptmlefo.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gtglwqmuld.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtlvfuoxnd.html

declare(strict_types=1);
来源：http://dali.chenzaomai.com/Article/details/gtoqnuwcrq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtykdvstks.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtfjbvtsdz.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gtyimvsnys.html

?string $name = null
来源：http://dali.yanxiufei.cn/Article/details/gthrovvymm.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtmrpofyia.html

int|string $id
来源：http://dali.sweek.top/Article/details/gtathnqdbu.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfephiawg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhengqikj.top/Article/details/gtkixmvxlh.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gtglqbfuxv.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gttdttcavi.html

[U50] PHP：构造器属性提升
来源：http://dali.iojbl.cn/Article/details/gtngmxphps.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gtypmqoeoi.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlbtrshq.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gtpkzcxfln.html

[U52] PHP：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtlnzemnvv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhongyouzk.top/Article/details/gtsnmwsgiq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gtrxlrxvcm.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtsezstnbb.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gtltqqbkqb.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gtuhgsghzm.html

[U55] PHP：match 表达式
来源：http://dali.xinyue.icu/Article/details/gtyspgnpwe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtlfusapno.html

[U56] PHP：命名参数
来源：http://dali.redwolf501.top/Article/details/gtbtuicmvt.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtkhdycski.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtfmwynopp.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gtjsdqgeel.html

[U58] PHP：数组三件套
来源：http://dali.wangdashe.top/Article/details/gtdwmcphdm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtkjdjsmdr.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gtrvagygca.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtbikldfor.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gtrykvktlf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.havefunace.top/Article/details/gtwhujeioc.html

[U61] PHP：正则
来源：http://dali.havefunace.top/Article/details/gtpoaxxgwt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtsljtjkeo.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gtztwcsfax.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.c1oappe.top/Article/details/gtzyagmuqj.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtfaainlgy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gtoafiqedm.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtzdcmguii.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gtzbrytxaq.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtntndcdso.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtbzyaexqt.html

[U66] PHP：设置 Cookie
来源：http://dali.andypj.xyz/Article/details/gtzckiitxb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gtzvivnlkl.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gtwqzxjwva.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfzxvyed.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtzhyytvsh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gtghanjwbs.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gthduicmjm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.feifeiyinyue.top/Article/details/gtbukruzpb.html

[U70] PHP：PDO 事务
来源：http://dali.feifeiyinyue.top/Article/details/gtazqrqgep.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sufxvd.cn/Article/details/gtfticbvdt.html

[U71] PHP：抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtydeoiwsx.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtjgrhcrmc.html

[U72] PHP：写错误日志
来源：http://dali.fengsongda.top/Article/details/gtkjivvgyr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gtzpwcnkev.html

[U73] PHP：读取 ini 配置
来源：http://dali.havefunace.top/Article/details/gtzkmxjhxr.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gtnzssqhul.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtjswmtnre.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtysuvukkb.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gtmurezbcs.html

composer require psr/container
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqpvfvhh.html

[U76] PHP：简单路由
来源：http://dali.smart0.xyz/Article/details/gtvkyedrif.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwiyobwy.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gtkodzycjy.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gtsacmazcj.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtwruxtfun.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gtrpcymdbc.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gtnkkjdlea.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gtizctqdnd.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gtsvmnxrak.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cheryme.top/Article/details/gtgfrniykr.html

[U81] JS：初始化项目
来源：http://dali.yangfankeji.com/Article/details/gtjfxvbcpf.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gtwvdcyyzl.html

[U82] JS：package.json 脚本
来源：http://dali.hywenlv.cn/Article/details/gtrotfpgjd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttujoaqph.html

[U83] JS：ES Module 导入导出
来源：http://dali.cashguo.top/Article/details/gtlqxrxnkv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtlhfoxgxn.html

[U84] JS：CommonJS 写法
来源：http://dali.hongshengwenyu.top/Article/details/gtzcuwusiv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwdsooip.html

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gtkjlwkpuz.html

a?.b?.c
来源：http://dali.jinghuilouyu.cn/Article/details/gtnosppahk.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtstqjqbpy.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gtqbfrsoqr.html

[U87] JS：解构默认值
来源：http://dali.9152youxi.cn/Article/details/gtfrvgggwt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tian-w.cn/Article/details/gtfcvtmenw.html

[U88] JS：对象展开合并
来源：http://dali.gotoacloud.top/Article/details/gtleufdrtg.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gtpztaaaet.html

[U89] JS：数组去重
来源：http://dali.guowangkeji.top/Article/details/gtlfdjqdyp.html

[...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcpgfmzg.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gtgojhlprt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtnpumtopa.html

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gthgeugblv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gtkwddltmn.html

[U92] JS：深拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtdzqkpbih.html

structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtwavwjmoi.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gtiupmntjg.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gtxvxcntbr.html

[U94] JS：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gthphpdjbx.html

const double = x => x * 2;
来源：http://dali.316326.xyz/Article/details/gtsardfwby.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gtvizsrxzv.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gtfubkryar.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gtsuuwgnqu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtmgladvic.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtofopgmjc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gthmshvlpl.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gtyvtcwbmx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tanke756.top/Article/details/gtueeffjoo.html

[U99] JS：事件监听
来源：http://dali.zhiwuduotai.top/Article/details/gtsozislyb.html

el.addEventListener("click", e => {})
来源：http://dali.svipenyu.cn/Article/details/gtnyjozfvm.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjskicji.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gtlhyaqfjn.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gtmxxnecyl.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gtjnzniiqn.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gtqnjmcgxj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gtezrvewnn.html

[U103] JS：定时器
来源：http://dali.shanyushiyangtech.top/Article/details/gtlldfzctm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.quarkkingdee.top/Article/details/gtvuzujswc.html

[U104] JS：防抖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiefhezda.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtpmphqzlu.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtjgobepbm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtdsihshob.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtbfdibjoy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtzceydwyy.html

[U107] JS：数字千分位
来源：http://dali.nwbrower.top/Article/details/gtaxxxdlea.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gtjyfcsmml.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtyjapniws.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtzdtxxmbs.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gtstnsgboq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtalstthrd.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtgrxzietg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtndvkjwek.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtxpceetgh.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtvytcaket.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gtfseriwhm.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtafxlbpoq.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gtvuswsqxd.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtresnodgg.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtrsenafer.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtwzprlpdk.html

[U115] JS：生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywhrwtno.html

crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtnrjfdhok.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtheifdyug.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtosaxkfbz.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gthbrwlkqm.html

npm i -D vitest;  npx vitest
来源：http://dali.yangfankeji.com/Article/details/gtcauqejgr.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gtedyxxcdz.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gtmburoltx.html

[U119] JS：生产构建
来源：http://dali.fengsongda.top/Article/details/gttomuvuhy.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtvzjpqkpn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gtumpcjizz.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gtnnkkteid.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzaritvei.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtscddaiag.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthribkjeq.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gtxwwyvmcp.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtbblnstej.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gtrcmxmnyy.html

JavaScript ..... 252
来源：http://dali.sxryk.cn/Article/details/gtszhscyml.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gthfwijnmv.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gtrygxnepc.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtvhzolxdj.html

Ruby ........... 212
来源：http://dali.cashguo.top/Article/details/gtmxiomaru.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtjyxnsyur.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gtkvejoayn.html

C++ ............ 30
来源：http://dali.shangyingyoupin.top/Article/details/gtrrqlcyrv.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtdaulwpoe.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gtzglaruek.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtmfptlbxb.html

Swift .......... 15
来源：http://dali.yuxming.cn/Article/details/gtdeamqhep.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtuaydylbd.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gtysyuqyfa.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtosrkuvkl.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtcyokenav.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gtsoceavnp.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtzoqgfnzq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dianchejie.cn/Article/details/gtkljamgxu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gthfkplnve.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtmdjfghti.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtixbhjgcj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gtjdyfmyns.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gthybqiwzl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtxuwozzdt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtjscrgqow.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtzvwunszp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtsrqjafut.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtudmvitzh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtxzpyikoj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtqwfvtldt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtnppdjqml.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gtsmgzbigf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtynltcejf.html


<!-- 参考信息 -->