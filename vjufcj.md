代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtrligkels.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtklmaaoze.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtggumflhh.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gtzuwzumav.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtobnnfnlv.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtcimbcrud.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtfcyrvcpc.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtqvvilofj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtnepdsxkz.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtawkddnia.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtoewqciwm.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtcwhxovar.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtqqmsqjsm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlqjzbtsb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtxbzzxags.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttzbeocxr.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtotcnayma.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtpikathyn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtgfqbxbcf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtkpbtltgn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejieehmk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gtqfxpnoxi.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gtktrdntyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtmmiarykv.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gtvmezpdqx.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtrulkpmiy.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gtoxqxfrap.html

{**a, **b}
来源：http://dali.fengsongda.top/Article/details/gtvzywjguk.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtypnfoofc.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtbfgmbpzm.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtdfzefvbu.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtdtzoajbw.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gtbghqznbz.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtczghlbbu.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtnzvhqqlt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxqswdgi.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtntqytbmu.html

(x * 2 for x in arr)
来源：http://dali.haohaochexian.top/Article/details/gtonuysyuh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gtwbdssisu.html

Counter(arr).most_common(3)
来源：http://dali.yanxiufei.cn/Article/details/gtrmprfrtz.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gtpxmctauk.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gtsnrbhflc.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gtqexilcnl.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtamudttte.html

[U15] Py：高精度计时
来源：http://dali.zycfv.cn/Article/details/gtndyhqdly.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gtmudyesjr.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtokvjdkuw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gttiqwmyye.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gthilksyfg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gtsyxdgnnu.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtuxnvelmp.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtlgwtsqex.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gtxwmcqpdo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtytfhtbaa.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtyzpeyyju.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtoincliaz.html

[U21] Py：自定义上下文管理器
来源：http://dali.gaohongyu789.top/Article/details/gtyqvzcnrh.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gticspoifk.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gtyvhqejrk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gtqscvsakn.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gtonpixyrf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cashguo.top/Article/details/gtaivsfesn.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gtaiizlkzv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtynmgdsmk.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtwssxqdhk.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gtxytvxdou.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtrlfjdcvd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtfsudvpqo.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtzsnsmpbw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cheryme.top/Article/details/gtdqgbhhps.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gtdturzcui.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gtqfnnefwe.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtkrqromos.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gtkfteiwri.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gtnehqlzvd.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gtfhyzfxek.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gtbunmhesk.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gttveykbqg.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gtijpgvfcz.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtyqvmyvyb.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtzzibsnuf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gtgvqxxeuv.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtksrojvdx.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtkaeiklhk.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gtmcdargws.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtnhcqlxat.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtauirrwwn.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gtdfejrtin.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayhdjvkr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtoompfuko.html

[U38] Py：获取脚本所在目录
来源：http://dali.andypj.xyz/Article/details/gtxqbvxrmt.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtbhvcbejx.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gttwblxvao.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtrpqguawq.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gtkxyjsaym.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtiltlcoly.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gtztjygzap.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gtkbqydukf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gtscycdyap.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtznucdiaj.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gtkjsmxtzb.html

namespace App\Http;
来源：http://dali.ppjwa.cn/Article/details/gtizwlczrh.html

[U44] PHP：开启严格类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnhzoadjk.html

declare(strict_types=1);
来源：http://dali.hfpthk.cn/Article/details/gtwjarvbuf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gtfzdfvmhn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtojsbywpb.html

[U46] PHP：可空类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwmmhkrio.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtmtdemirj.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtffhzvbzb.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gtygngjhyw.html

[U48] PHP：纯枚举
来源：http://dali.jinqigufen.top/Article/details/gtxedfqtfp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvmrckroo.html

[U49] PHP：只读属性
来源：http://dali.ehwqpu.com/Article/details/gtjocufdho.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gtulriiimr.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gtixoktchs.html

public function __construct(private int $id) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmgwnhski.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gtaxllcyot.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gtqxyfseqo.html

[U52] PHP：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtwayxnviy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtzpplgicw.html

[U53] PHP：空合并运算符
来源：http://dali.sufxvd.cn/Article/details/gtezmucusw.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gtnmcfgkvz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gtxandabml.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gtanoensur.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gtgqryalsr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtqjyvhzlh.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtdtusavha.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtijokbunt.html

[U57] PHP：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtofvqkxyy.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtsjvdkbst.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gtobbatxxy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmibzpftg.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gtxesbtfjx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtdbusnmzi.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gtdutsbbqv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gttrbjaqnl.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gtbbvsowhs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtcqdyvjba.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gtczwczpjd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenjidiqi.icu/Article/details/gtsxlvrdgd.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtjsxbqhxq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtnrqvrsam.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gtayntnwup.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.andypj.xyz/Article/details/gtnodhgxde.html

[U65] PHP：会话
来源：http://dali.cheryme.top/Article/details/gtiutepqrt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtfbbvuphr.html

[U66] PHP：设置 Cookie
来源：http://dali.c1oappe.top/Article/details/gtegpnthnd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gttrsnokjp.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gtdtvqmjbp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gtqaiqkzjh.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtojqrpdbf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ivvv.top/Article/details/gtmmvudazi.html

[U69] PHP：PDO 预处理
来源：http://dali.shzxlz.cn/Article/details/gtqjucaxkb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscvjqgoa.html

[U70] PHP：PDO 事务
来源：http://dali.yongpay.top/Article/details/gtspwaqawz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.svipenyu.cn/Article/details/gterxlujmy.html

[U71] PHP：抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtrskrrgkb.html

throw new RuntimeException("失败", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtxzskusmi.html

[U72] PHP：写错误日志
来源：http://dali.316326.xyz/Article/details/gtckhsoxcx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gtmjqsjhrb.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtibnyivwa.html

parse_ini_file("config.ini", true)
来源：http://dali.316326.xyz/Article/details/gtwityffnw.html

[U74] PHP：读取环境变量
来源：http://dali.316326.xyz/Article/details/gtienxlbnr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gtioathelh.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gtkwgbcpbr.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gtddwsjemd.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gtrwxdxbjo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtpkvszsyx.html

[U77] PHP：模板渲染
来源：http://dali.sysykeji.top/Article/details/gtqithniff.html

composer require twig/twig
来源：http://dali.smart0.xyz/Article/details/gtxozdjlgc.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfehjgnyu.html

composer require --dev phpunit/phpunit
来源：http://dali.mhx1999.top/Article/details/gtonhjcyvy.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gtkqktghnv.html

composer require --dev phpstan/phpstan
来源：http://dali.yanxiufei.cn/Article/details/gtjjxrmbfl.html

[U80] PHP：代码规范修复
来源：http://dali.smart0.xyz/Article/details/gtgbavruba.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnqzz.top/Article/details/gtaunhvlof.html

[U81] JS：初始化项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtueadqzkq.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gtwrieimur.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtprbvpkvm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinqigfzy.top/Article/details/gtxetazyzg.html

[U83] JS：ES Module 导入导出
来源：http://dali.tian-w.cn/Article/details/gtyqvfnnyr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtfegmbmna.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gtjuivdkvo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gtjstpedjk.html

[U85] JS：可选链
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfwqmepr.html

a?.b?.c
来源：http://dali.hnqzz.top/Article/details/gtbtbepqym.html

[U86] JS：空值合并
来源：http://dali.nwbrower.top/Article/details/gtuzvaahgf.html

a ?? b
来源：http://dali.gogol.net.cn/Article/details/gtsborrfom.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gttnokbmpv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dianchejie.cn/Article/details/gtwapaeknu.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gtaqvqljac.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gtxlgrmcfc.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtigjyfjnv.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gturulhoqg.html

[U90] JS：数字数组排序
来源：http://dali.zhongyouzk.top/Article/details/gtdzlecomk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtbxbkaitn.html

[U91] JS：对象键值遍历
来源：http://dali.jianghu66.top/Article/details/gtrnopintb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtcftjeklz.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gtkcrnnicy.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtisojtmir.html

[U93] JS：模板字符串
来源：http://dali.chenlongwang.top/Article/details/gtdnrbmaoy.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtakvvmgbj.html

[U94] JS：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtfsuqsxsb.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtspbzpryd.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gtjdclggac.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtdaexhqxh.html

[U96] JS：async/await 与异常
来源：http://dali.cdnleiting.top/Article/details/gtpfaqaasc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtxbysxmpl.html

[U97] JS：并发请求
来源：http://dali.yuxming.cn/Article/details/gtiteltavr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtkqmcfdac.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrvcahwb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtnnsralsb.html

[U99] JS：事件监听
来源：http://dali.gaohongyu789.top/Article/details/gtcjrwhkhw.html

el.addEventListener("click", e => {})
来源：http://dali.9152youxi.cn/Article/details/gtmdlzchen.html

[U100] JS：DOM 查询
来源：http://dali.hysaishi.cn/Article/details/gtknlsarug.html

document.querySelector(".item")
来源：http://dali.hfpthk.cn/Article/details/gtaoeylpip.html

[U101] JS：classList 操作
来源：http://dali.hysaishi.cn/Article/details/gtnpflxhab.html

el.classList.toggle("active")
来源：http://dali.hywenlv.cn/Article/details/gtifotkpqb.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtmvnlavyl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqlggzvr.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtrbjexdfj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigufen.top/Article/details/gtxoeckwfn.html

[U104] JS：防抖
来源：http://dali.zycfv.cn/Article/details/gtjemefwgf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtdzxxjvnz.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtcjtxruku.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gtiqqmxwvj.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gtdiwckwbq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gthgwjaxkl.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gthqhgnbfd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pycfn.com/Article/details/gtarmagpjc.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gtqrshtlte.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gttrdazcph.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gtwcprgkls.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtritylyii.html

[U110] JS：数组分块
来源：http://dali.xziqi.cn/Article/details/gtivhnwetp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtqwynjftr.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtbnaihqka.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtlpxnmvqk.html

[U112] JS：字符串补位
来源：http://dali.chenjidiqi.icu/Article/details/gtnahaaexc.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gttcttbxvl.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gtqkvtygwt.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gttkbmoyaq.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtaakvfgzj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtfedonlnq.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtkzvhkopu.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtpmcwgbco.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqnuprnm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gtcutlymwy.html

[U117] JS：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtgwpsjlru.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtktonqshx.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gtrzcehfro.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gtnkggfmtg.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gtgzsjugjn.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtfwyystms.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gtydnthwag.html

import.meta.env.VITE_API_URL
来源：http://dali.guannengcc.top/Article/details/gtsrhyqkuw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbtxpcbtf.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gtvtoftqgn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdwsfgtia.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtlusbeuhu.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gtxykzplrw.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtshydwpqy.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gttbbeosnu.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtogddaqem.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtstfubxic.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtnqjpxgnz.html

Ruby ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gttfklijhj.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gtpvttldtt.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtyrtymxnj.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtdpxfnjgl.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtylmzthgm.html

Bash ........... 80
来源：http://dali.haohaochexian.top/Article/details/gtsvmytanq.html

Kotlin ......... 15
来源：http://dali.cucudq.cn/Article/details/gtipcmkupl.html

Swift .......... 15
来源：http://dali.aibaodan.cn/Article/details/gtjjtpbaap.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtqegsynmb.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtoaiwbgsm.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtvolkeugv.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtdyaxwzqo.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gtqozatfyi.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylnngpbl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtcyrvhcwo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtedlqffpq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtydfzplru.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gtvjafdytk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gterabogic.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gtprreoino.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtofwnbdbc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtsbkcnyyw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtzpeqrjou.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gtsbggdypc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtjvswwrrp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtscbuvemc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtcnwzsybp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtwgyfksro.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtlqiopzmn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtetswmfko.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gtojxgtadu.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gtmmwqitis.html

S C / C++ 专题                          60
来源：http://dali.meibo888.top/Article/details/gtydwzyxxe.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gtnfirzeqg.html


<!-- 参考信息 -->