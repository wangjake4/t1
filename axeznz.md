代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2pnplprvy.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2hsygzijh.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2gorvixpo.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gt2zjcronlf.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2qibggvwr.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gt2tbmyvuom.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofygpldi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vwvqmcuk.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gt2thuabnvs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gt2modjpear.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gt2iqvtwmqi.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gt2rkojqaqh.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gt2eakpmxsl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2xcpxuczn.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2zhpizitk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gt2rakoawci.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gt2abhivxtd.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2fqjauzjm.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2eiorhqgv.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gt2dyxeevfm.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gt2worlkcrm.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2dajyroks.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2beuzhjgz.html

[T54] Scala：集合映射
来源：http://dali.cashguo.top/Article/details/gt2gpwsxpwf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gt2wrzgxbky.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2ezcdcnxu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gt2svaucoew.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gt2yctxvzea.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2altnncpm.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2iqfenqnf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2ftdkqhei.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2kkbldppf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2ingzkezs.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlotvayw.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2mbqluhep.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gt2rxozddwc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omarytjs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kmqfqufn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2anhaaifj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2yediumna.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gt2veestphy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gt2bqviykao.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gt2scidhwvk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gt2rzvctjwo.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2sngufcbq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2uypsvtrw.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2fdvcpfkg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drmcztfm.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gt2zboovapk.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2tzzsujzm.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjuowjmr.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gt2idfuxsqs.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gt2vetgdtwe.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gt2rmytbvgz.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gt2prfcotbz.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gt2ehpltonl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpgtzjwk.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gt2anqfxjyz.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gt2znlglvke.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcxnkmpq.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gt2bjrzxgpg.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2zymjyzwz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gt2pquxxxhu.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gt2hcvfeuig.html

[U13] Py：固定长度队列
来源：http://dali.mhx1999.top/Article/details/gt2rqxnymnk.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gt2pcstfdjw.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gt2vwnuzzyx.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gt2rsmgbark.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gt2pkfvfscy.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gt2ehxbxwdg.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2grogpaqc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gt2guggzdrv.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gt2uetaecxg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gt2ofjzgpwt.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gt2cvlyjfco.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2yxtqznwg.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gt2cvygoili.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjtspdw.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gt2oeskvyyw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gt2azpuihse.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhhfdrnp.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gt2dpyfzusu.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmcbzomg.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2lpkwrrzm.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gt2mzpeesdo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnqzz.top/Article/details/gt2blyenqvl.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gt2sqxnxjfz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2ywznwyrl.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gt2lvjnwytm.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gt2arxdcnei.html

[U26] Py：并发下载
来源：http://dali.fengsongda.top/Article/details/gt2fpdkcfno.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gt2oqdzqayc.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gt2ywlhuhad.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gt2bvnfkoob.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gt2nzoxwuzv.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gt2qsmagztz.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gt2gohmaggc.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gt2tezfimlf.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmcrivdw.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gt2xlishljj.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gt2qkjbyony.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2crddvqbq.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gt2remotxtu.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gt2eoqhqtbd.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gt2hnpcrzlo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.iojbl.cn/Article/details/gt2ckcnrjgy.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gt2mainfkzs.html

chardet.detect(raw)
来源：http://dali.hongshengwenyu.top/Article/details/gt2amapkztg.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gt2ppirfaot.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmrkphnw.html

[U36] Py：定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2hzpqwact.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2qupdbhyv.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gt2hjhqtuvf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iepayhsd.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwvnzvjm.html

Path(__file__).resolve().parent
来源：http://dali.cashguo.top/Article/details/gt2stqjogbj.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigufen.top/Article/details/gt2ewhrxqdr.html

sys.stdout.isatty()
来源：http://dali.mhx1999.top/Article/details/gt2gskvzdxy.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gt2owwtplwl.html

print("err", file=sys.stderr)
来源：http://dali.yuxming.cn/Article/details/gt2ktspkxcx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.smart0.xyz/Article/details/gt2irqvgrvu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gt2xzldyxlj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gt2rctqtejl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gt2mikcjgxu.html

[U43] PHP：声明命名空间
来源：http://dali.hammf.cn/Article/details/gt2xzdyqvqk.html

namespace App\Http;
来源：http://dali.vqdsnc.cn/Article/details/gt2pxpgzcks.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gt2xrouqqyx.html

declare(strict_types=1);
来源：http://dali.gzhubu.top/Article/details/gt2kpeebjvy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ivvv.top/Article/details/gt2oninulon.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2twvgxtnm.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gt2pcxclrjm.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gt2hopyyzov.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gt2wsxlaevg.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gt2iqiossmo.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gt2kwzccgzi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtzsioqe.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gt2gtmebmwl.html

public readonly string $name
来源：http://dali.yj20258888.top/Article/details/gt2slaxrekc.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emdgvqdp.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqodxbko.html

[U51] PHP：数组解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdlmappi.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gt2avbpwfrc.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gt2gsvdqtas.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jibycqlx.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gt2eybqapry.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gt2yspfitcd.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gt2cdqbwhgn.html

$obj?->method()
来源：http://dali.ybcxt.top/Article/details/gt2tlhdrnno.html

[U55] PHP：match 表达式
来源：http://dali.redwolf501.top/Article/details/gt2pcmdghxo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2awvvprek.html

[U56] PHP：命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzyljali.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2fsjmyesn.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2hdfdbcej.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geioowvy.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gt2xtfultmp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gt2cionshuc.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gt2kftougto.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2qnhtqbom.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gt2aykorwxv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqksmeel.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gt2kilafmvk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gt2jivaxwup.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gt2uavtvwft.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gt2eslwfcwp.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2rscklcfr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gt2tcybfrsk.html

[U64] PHP：目录遍历
来源：http://dali.fzhhl.top/Article/details/gt2ykryaxho.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guowangkeji.top/Article/details/gt2aoinuidu.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gt2hwfrzvni.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2gpgyzyup.html

[U66] PHP：设置 Cookie
来源：http://dali.yj202588.top/Article/details/gt2kiwsbvsx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swyqtqba.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gt2omhhezbv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gt2birsqrdx.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uoivqlfo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.andypj.xyz/Article/details/gt2dozzdlfj.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gt2xjpkltlx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cucudq.cn/Article/details/gt2vhqenzcz.html

[U70] PHP：PDO 事务
来源：http://dali.yueranfly.top/Article/details/gt2rjgdiepd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gt2djwghbui.html

[U71] PHP：抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2awmgjgpy.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2hvjkzwww.html

[U72] PHP：写错误日志
来源：http://dali.ivvv.top/Article/details/gt2yoscetau.html

error_log("失败: " . $e->getMessage());
来源：http://dali.fzhhl.top/Article/details/gt2ymrwnsol.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gt2afnjhwfh.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gt2xsiscqvu.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2ehcozphu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gt2aaorcctt.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gt2wzrjcxiv.html

composer require psr/container
来源：http://dali.yueranfly.top/Article/details/gt2kljswded.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gt2melubdvf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gt2odigdyyb.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gt2wyfvgxfr.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gt2ccokmurf.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gt2ccmvxuba.html

composer require --dev phpunit/phpunit
来源：http://dali.fengsongda.top/Article/details/gt2gkhrkhfx.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwedefue.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxxghqmh.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gt2iwiqbouk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnqzz.top/Article/details/gt2gwagfmhv.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzdtaqrp.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gt2hhaiotbx.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gt2jjjglqqr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxzknbba.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gt2vskledpo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldnbtlct.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gt2qpbzgtpd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gt2wtyurunf.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gt2rhmvmypz.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baaqwywk.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gt2mvhahyzd.html

a ?? b
来源：http://dali.nanxuanxn.top/Article/details/gt2edijgznv.html

[U87] JS：解构默认值
来源：http://dali.svipenyu.cn/Article/details/gt2dgalfkgl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pycfn.com/Article/details/gt2xyjpwnzi.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gt2hlmjjgao.html

{ ...a, ...b }
来源：http://dali.fengsongda.top/Article/details/gt2paahkjfo.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gt2fuvzgjgx.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2lzhfjxom.html

[U90] JS：数字数组排序
来源：http://dali.xuanzx.com/Article/details/gt2ltaxzzay.html

[...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2cysqbpqj.html

[U91] JS：对象键值遍历
来源：http://dali.tanke756.top/Article/details/gt2pskchwjr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gt2vtdstmvq.html

[U92] JS：深拷贝
来源：http://dali.zycfv.cn/Article/details/gt2dqdpphox.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2pomlefuj.html

[U93] JS：模板字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqhrmrhz.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgymotum.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gt2yripqgyz.html

const double = x => x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gt2syrhctnn.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gt2dwjyollc.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2dpuaglta.html

[U96] JS：async/await 与异常
来源：http://dali.svipenyu.cn/Article/details/gt2ckvvydou.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2acnygfxb.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gt2nwsgctts.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2phzghzlr.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2jlscsvii.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gt2pomtmvfz.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gt2csoxanmq.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovqtfquw.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gt2pkxtqczl.html

document.querySelector(".item")
来源：http://dali.zycfv.cn/Article/details/gt2bbqnbcyr.html

[U101] JS：classList 操作
来源：http://dali.yvedp.cn/Article/details/gt2arjsylpn.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gt2oweysunz.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2adnuzphj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gt2hydbcdkq.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gt2tjduuxjp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gt2kunwvhbo.html

[U104] JS：防抖
来源：http://dali.pycfn.com/Article/details/gt2kwaimegg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2ducqhfak.html

[U105] JS：节流
来源：http://dali.jianghu66.top/Article/details/gt2chitvgit.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gt2ztwrdwnz.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgauayay.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.svipenyu.cn/Article/details/gt2bfbmgwaa.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gt2rxnugzih.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gt2nuumiopq.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gt2yxwiwayb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gt2luvlmhow.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gt2abphqlzi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2pvyoeggn.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2gqjmgykh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gt2kjfhxkek.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwpzrqsg.html

new Map(Object.entries(obj))
来源：http://dali.ydzc1.top/Article/details/gt2nafmkfau.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gt2gabahwkg.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2dljogvbv.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gt2eugkaavq.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zklcnimq.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggusmitf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2qgtytjmh.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2nheaiyrc.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2vjlknwsl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gt2mcwhmdps.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hammf.cn/Article/details/gt2ythevbaf.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gt2vrebqcmk.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gt2xedatlda.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gt2xtrvbctt.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gt2gbckgztt.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gt2reisxtth.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gt2fuatqeve.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2tsayezmw.html

import.meta.env.VITE_API_URL
来源：http://dali.tian-w.cn/Article/details/gt2pkxtlmjw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqfvfaes.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gt2mbupyubj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qidepvto.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gt2sujrvclk.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gt2nkkdryvc.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gt2liadngnn.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gt2jreloimo.html

TypeScript ..... 212
来源：http://dali.meibo888.top/Article/details/gt2liaewubv.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gt2xridybzc.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2pwxfrfab.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gt2wjffepla.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gt2eezbuzmo.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gt2ackeqgxi.html

C++ ............ 30
来源：http://dali.gotoacloud.top/Article/details/gt2ltiwhqhc.html

SQL ............ 90
来源：http://dali.gotoacloud.top/Article/details/gt2djfpucuo.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntigfhhx.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylpokmjf.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gt2rhvjqyyd.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gt2gooxzxhm.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gt2ybwzqnjg.html


<!-- 参考信息 -->