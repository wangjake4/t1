代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtveqttbel.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtbfrzexdz.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtlezviict.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtluupabtd.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtpqvwhdny.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gthmiaafcf.html

[T46] Perl：哈希操作
来源：http://dali.hnqzz.top/Article/details/gtdoqcajph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtxaqkgfyx.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtdteootzy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtvtyjvquc.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfygrnqo.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtpelyublj.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtrkhhledi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtjoznoisq.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtawgsnkbs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtcffatezh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtezqghkuw.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtsvslconw.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtajxwwyam.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gthoqbnegs.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtoyoovbgz.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtiegdiwsm.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtgwlecjsj.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtkwhpodrp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gtjsgdgwia.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtyvbtfuyn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtwuajnqhc.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gtcblneuva.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtctjutvqw.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtchvtlkrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtohknpyqd.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gttltlosgr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gtipzpzlux.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeijohpd.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtrtoffaug.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtnljwjxak.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtfzfpmqzb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpcugzijm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtafypvbrj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjuqgovrr.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtvegtcxnd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwrtgyey.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuwrfvnz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtxmnggzan.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtdemnzs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtpjcrilbw.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtqtpcwdcj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gtpqjzndrw.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtydygiexe.html

list(dict.fromkeys(arr))
来源：http://dali.xziqi.cn/Article/details/gtxbybzsoa.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gtjjnbvaou.html

{**a, **b}
来源：http://dali.yanxiufei.cn/Article/details/gtiudcgrkt.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtnaafslcw.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gtfbogvqqt.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtmcsyvcio.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqadbnci.html

[U09] Py：字典取最大值的键
来源：http://dali.yangfankeji.com/Article/details/gtliqkdjvj.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtuqnxokjf.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gtdnzjyloh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gtmmasztbi.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtutzuuexa.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvcvirldc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtgigozyha.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtpezaeymb.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtryffslwd.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gtfsosevgk.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gtgfazsyav.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtuxxbsuxy.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gtjrdwukky.html

t = time.perf_counter()
来源：http://dali.mhx1999.top/Article/details/gtxihtoleu.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gtxixhxxre.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gthuhwqnhy.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gtelidjyqk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gtnainzrxt.html

[U18] Py：预编译正则
来源：http://dali.sufxvd.cn/Article/details/gtvgqboosu.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtryrvvbqy.html

[U19] Py：正则替换带回调
来源：http://dali.smart0.xyz/Article/details/gtsbegwrfy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteblfyrkr.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtrvlligtw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gttzydhumi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gtjkrehmum.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtkknzrpho.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gtxhprtith.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzomtglrn.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gtlqemxdvy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtwtiukzub.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtzfthxrou.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtxkbnxaoc.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdvdzigs.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtchqlqmdv.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gtdjmhiktq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gtjhgzzmft.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtibomiqbv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtwyjnkdwr.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gtyiypzikt.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gtvibvcqda.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvyaqgzi.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gtnmplwixs.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gtnxaxegua.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gtrpqxtkmy.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtquyctixo.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtbjygdtrp.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gtzlnehskb.html

ruff format . && ruff check --fix .
来源：http://dali.hysaishi.cn/Article/details/gtsjcakeqz.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtyyromvbr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtkpiiimos.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gtnxgdnrns.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtukdfqivw.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gtvtuxzfpd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtlbksofhj.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtwarymfok.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gtbbqjxuud.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtpbeawypu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtcxtxcsat.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhixingplan.top/Article/details/gtsokqdwgp.html

Path(__file__).resolve().parent
来源：http://dali.guowangkeji.top/Article/details/gtfqhfqujr.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbemalndc.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gtsqvfeslv.html

[U40] Py：打印到标准错误
来源：http://dali.hammf.cn/Article/details/gtsaacccwd.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqiwaikjs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gtqchelihb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nwbrower.top/Article/details/gtpqpovhja.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsctdofbr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtxfetuort.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtsvrgatrv.html

namespace App\Http;
来源：http://dali.shzxlz.cn/Article/details/gtpbusrszc.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gtprtbqjge.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gtlacfstiz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtvpandqbn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtdxomqljl.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gtymxqhfol.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtowesiewx.html

[U47] PHP：联合类型
来源：http://dali.pycfn.com/Article/details/gtctipsxtx.html

int|string $id
来源：http://dali.yuxming.cn/Article/details/gtwurqpcha.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gtbwdfyijj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jiagoushi.top/Article/details/gtsexpbcba.html

[U49] PHP：只读属性
来源：http://dali.vqdsnc.cn/Article/details/gttrbrkpps.html

public readonly string $name
来源：http://dali.hysaishi.cn/Article/details/gtbpsuhfuq.html

[U50] PHP：构造器属性提升
来源：http://dali.vqdsnc.cn/Article/details/gtmqkgowue.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gtasugnoon.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtwcieelxc.html

[$a, $b] = $arr;
来源：http://dali.wangshuangyany.cn/Article/details/gtwqfdnwsb.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gteryusure.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjcqbrsv.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigfzy.top/Article/details/gtrcedyxqg.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfuydstx.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gtmrvxgjwc.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gtfxywlzce.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtiijarzau.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gtxmanyyvy.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtjuglglit.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtbtwngvrg.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxshqlvx.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtpruzpspn.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtpyfsnbbr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gtckmnlziq.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtqricuveb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuwxvzzj.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtapzvclyu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.bjfxy.top/Article/details/gttvpxoyeb.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gtxuygnwuu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtjuzwpgvk.html

[U62] PHP：日期对象
来源：http://dali.cashguo.top/Article/details/gthjsvbwit.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtgbznwvpj.html

[U63] PHP：文件读写
来源：http://dali.yongpay.top/Article/details/gtqlapaond.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtdtayedms.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gtsiwvdxkb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtexbztbvj.html

[U65] PHP：会话
来源：http://dali.guowangkeji.top/Article/details/gtfcraxdkw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtpwmsnort.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gthekjcuwy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258.top/Article/details/gtfgmjnglq.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gttihdwkzn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtszqkxxxt.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtcvrkrpug.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nwbrower.top/Article/details/gtaydbbsro.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gtjtbsvxtd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gtkonvuvez.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigfzy.top/Article/details/gtdxmauzbd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gttaehomyc.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gtssmqyqsn.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gtqggajmri.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gtcjznyzvg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtmfnfmcaz.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gtycwnjvix.html

parse_ini_file("config.ini", true)
来源：http://dali.sufxvd.cn/Article/details/gtxacswlep.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtjnkkcber.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenlongwang.top/Article/details/gtpafftgyx.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gtwzpsvcjj.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtrylhasqj.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgdcksnh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dianchejie.cn/Article/details/gtzqfkiptx.html

[U77] PHP：模板渲染
来源：http://dali.gotoacloud.top/Article/details/gtrythyqmc.html

composer require twig/twig
来源：http://dali.hammf.cn/Article/details/gtnaxdpkew.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtrdxrmmwu.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gtgqqjpcik.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gtssynvrxr.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gtegllkopu.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gtbxjpgrmy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pengpengdd.cyou/Article/details/gtwwdjmdvi.html

[U81] JS：初始化项目
来源：http://dali.zhongyouzk.top/Article/details/gtvzdefryw.html

npm init -y;  npm i express
来源：http://dali.andypj.xyz/Article/details/gtqjnefjhq.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gtdfpgitph.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenzaomai.com/Article/details/gtherttuef.html

[U83] JS：ES Module 导入导出
来源：http://dali.bjfxy.top/Article/details/gtmyorrvfy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtkkcsgsbx.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gtxsznralw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqydpmglp.html

[U85] JS：可选链
来源：http://dali.yueranfly.top/Article/details/gteujvjqop.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gthpkdmmaj.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbkjupdl.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtrczbjxgd.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gtuearrcgm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.bjfxy.top/Article/details/gtffsbmqhn.html

[U88] JS：对象展开合并
来源：http://dali.shuidangran.top/Article/details/gtyfftdwfg.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtsejjxdsh.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gtgjjljnxl.html

[...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtbfiygobk.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtqlgltkdm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdsoglnp.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gtvhkyovns.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtovadfnyt.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumgaubkz.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gttiknivrb.html

[U93] JS：模板字符串
来源：http://dali.tian-w.cn/Article/details/gtenzlkshz.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gtcsmbnmby.html

[U94] JS：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtcsooozlf.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtjnfsljac.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtvmiymxik.html

new Promise((resolve, reject) => {})
来源：http://dali.shangyingyoupin.top/Article/details/gtsyivwxon.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gtrtcjnqlx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtjuzzbc.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqfkwyco.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtneyayfca.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtwxzuytia.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cheryme.top/Article/details/gttspgtjvx.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtjikqhgbw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gtzsecaerk.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtjmxciaod.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gtleilgwnu.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtcawjcxtx.html

el.classList.toggle("active")
来源：http://dali.daxiang520.top/Article/details/gtkibjmeet.html

[U102] JS：本地存储
来源：http://dali.jianghu66.top/Article/details/gtsxbcafff.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sweek.top/Article/details/gtpwsajrpy.html

[U103] JS：定时器
来源：http://dali.xziqi.cn/Article/details/gtimfuniah.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hywenlv.cn/Article/details/gtnmwpbgtx.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtoojaaczw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwkmkqci.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtolmbebff.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gtlogmcxps.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtmpfdbjiv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gtqvkmtmhb.html

[U107] JS：数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtxyylhncf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdbsnthw.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gtiqvxusti.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtppeckdls.html

[U109] JS：数组分组
来源：http://dali.hysaishi.cn/Article/details/gtccoddqca.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gttkwammxd.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gttomthphu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtnamxulcp.html

[U111] JS：对象转 Map
来源：http://dali.yj20258888.top/Article/details/gtowkkvoik.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gteswqvnnp.html

[U112] JS：字符串补位
来源：http://dali.aibaodan.cn/Article/details/gtmdtnlfil.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtmzqsbzkh.html

[U113] JS：正则替换全部
来源：http://dali.havefunace.top/Article/details/gtmregdzjp.html

s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtgtqwvvdx.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gtbtuqqwbu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtssrdeelp.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtaiqfwpfq.html

crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtnajbfobp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gttnxrxqlw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtsvtncpoj.html

[U117] JS：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gteutbldbr.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gttiyrvzll.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtxnerwsuo.html

npm i -D vite;  npx vite
来源：http://dali.fzhhl.top/Article/details/gtwabkqyto.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gtpdforpwf.html

npx vite build
来源：http://dali.smart0.xyz/Article/details/gththukvzg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtzjjtwjmg.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtbpbynjqp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjklnwdwm.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gtktjjhbua.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtakjpacsx.html

按语言统计（条）：
来源：http://dali.mhx1999.top/Article/details/gtngedltab.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gtblomouxs.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gtpibfdnxk.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gtzmigvwlk.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gtrozeqvol.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gtpnxwnkmd.html

Go ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtwgkvsexb.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtlvhupyxj.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtggzllutx.html

C .............. 30
来源：http://dali.hnxiangtu.top/Article/details/gtofqzktku.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtegynh.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gtipfprarr.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtfvcrjxww.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtnjzrspek.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkaywomd.html

Lua ............ 10
来源：http://dali.redwolf501.top/Article/details/gtexwlerfn.html

Perl ........... 10
来源：http://dali.zhongyouzk.top/Article/details/gtwfdtatrs.html


<!-- 参考信息 -->