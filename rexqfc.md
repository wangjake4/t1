代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtsrymvkyt.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtctthmjbd.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gtccwyepss.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtoydlwnto.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtaiuzsqxm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gtelturtww.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gtbdhtrqlz.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtdphtvejn.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gtavtbxmdq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtbdyxhdfg.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtzaozvgab.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtkcojwdri.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtjylcazpk.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtpxfkmyec.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtpiydntbq.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtzstfxyhd.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gtlgdgjten.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtienapfvj.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gterecqvmb.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxpnmota.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtscsvkdoh.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtnixusiaa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtyitdndhm.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtaxibjits.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtgwctedof.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtwwmzxgjy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtnwwgrumo.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gteljopnnr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtfoovbbmo.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtcgjngtos.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtpgdfkoro.html

[T60] Scala：折叠
来源：http://dali.nwbrower.top/Article/details/gtgpwhxjzs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtamxmurfh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdfilpzah.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gturfilvef.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmvkxtyzz.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaikmxhnq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtnnnmukia.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gtfarertuc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtvcxxgpgv.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtjxxeexuw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gtyvywrosu.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtojultjyn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gtmaosmdvs.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtxuzcqjmt.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtoylxycys.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtqrrzcjhp.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtgdyvjcna.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtjnuzkqqh.html

{v: k for k, v in d.items()}
来源：http://dali.jlsjyb.cn/Article/details/gtwjfluqgt.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtxbvmzkha.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtslpuwvbh.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtyrzyjvqw.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtyrpfzuby.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtpdgcdztu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtiehnjdtu.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gtdmzvovkl.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gtknztbcsi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtkoobkssx.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmtqhpbm.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gtzalptxqq.html

deque(maxlen=10)
来源：http://dali.hongshengwenyu.top/Article/details/gtxbrrvdju.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggrrvyzy.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtcrhiqqsb.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtyeapkqzz.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtsztgcgur.html

[U16] Py：命令行参数解析
来源：http://dali.yangfankeji.com/Article/details/gtbxzgpevx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gtrpwotxwn.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtprliihgo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtpuskzvgn.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gttsexxsse.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxjfagow.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtjxxfmkbf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gttvnckwwx.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtnisdgsno.html

@functools.lru_cache(maxsize=None)
来源：http://dali.redwolf501.top/Article/details/gtfczpzmiu.html

[U21] Py：自定义上下文管理器
来源：http://dali.hywenlv.cn/Article/details/gteonfbssl.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtkzhlfsus.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtqkhdznus.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtaltcdfie.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gtvmnzfsed.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gtyaphkpwc.html

[U24] Py：路径操作
来源：http://dali.quarkkingdee.top/Article/details/gtmhkabazh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtesccurvs.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtcwaepfsy.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtjjwyebxq.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtuxogdahp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtoerdyqpx.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtxsjuktsf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.andypj.xyz/Article/details/gtewnzslez.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gtywxorbxq.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtajvbxmwh.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtyqvgmxry.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglbhbhpq.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gteixxxxwa.html

@dataclass(slots=True)
来源：http://dali.birdmap.top/Article/details/gtbkuftngm.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gtalzktmeq.html

python -m pytest -q
来源：http://dali.yongpay.top/Article/details/gtlatwbtgh.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gthssygsug.html

ruff format . && ruff check --fix .
来源：http://dali.aizwys.cn/Article/details/gtiztdazrd.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gthhylftag.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gteqmkiakz.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gtznmzzbeg.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gtcqzklqbg.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gtcmvjqsam.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtcmafwrzr.html

[U36] Py：定时任务
来源：http://dali.hnqzz.top/Article/details/gtlaqhhsuv.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttqimyxq.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtwbfcnqcw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtguqxscyk.html

[U38] Py：获取脚本所在目录
来源：http://dali.yangfankeji.com/Article/details/gtsfyfyool.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtvbhirwut.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gtqoxzjfnn.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtpbexbjku.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gtkvraghvt.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtaxqnrhmr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ehwqpu.com/Article/details/gtxvycizdo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtpcgmkchl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sxryk.cn/Article/details/gtytxhsgvr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtrmaeahes.html

[U43] PHP：声明命名空间
来源：http://dali.cheryme.top/Article/details/gthbfyedkx.html

namespace App\Http;
来源：http://dali.zhoulong.xyz/Article/details/gtgdydoavg.html

[U44] PHP：开启严格类型
来源：http://dali.yuxming.cn/Article/details/gtgvknyagw.html

declare(strict_types=1);
来源：http://dali.havefunace.top/Article/details/gttxbxrmwp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtuceelecr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gttbistbbk.html

[U46] PHP：可空类型
来源：http://dali.tanke756.top/Article/details/gtaiqeztsw.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtyeoexkjf.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gtyqwbejja.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gtxksvrwpz.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtnqipeduu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ehwqpu.com/Article/details/gtpajnctrb.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gtrlzljatd.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gtzqmlvorn.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gtimszfcmz.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gtbjtcybwr.html

[U51] PHP：数组解构
来源：http://dali.ybcxt.top/Article/details/gtyzbxmzoy.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtmntqzcqc.html

[U52] PHP：箭头函数
来源：http://dali.ybcxt.top/Article/details/gtzzysjmdd.html

$double = fn($x) => $x * 2;
来源：http://dali.ybcxt.top/Article/details/gtkqdxieiu.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gtktzfiljg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gttnpgpcwz.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gtdjsucauz.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gtnxfdplza.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gtnnofnflc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtgcntjktn.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gtboaslsxt.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtbeanlnxp.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtpnvihzzr.html

"值: {$a}"
来源：http://dali.yuxming.cn/Article/details/gtuezufbvr.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gtmontskmw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtvcvgpjmn.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtwkfibvcp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtvlomdcfh.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gtnxqcuuin.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gtgnnkczqd.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtkoperbmp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtjrmwpmkf.html

[U62] PHP：日期对象
来源：http://dali.mhx1999.top/Article/details/gtilpqitoo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daria6918.cn/Article/details/gtefweogyx.html

[U63] PHP：文件读写
来源：http://dali.jinqigfzy.top/Article/details/gtuatbvvfi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gtpcfjccud.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtxvrextff.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pycfn.com/Article/details/gtlhmcsstm.html

[U65] PHP：会话
来源：http://dali.pycfn.com/Article/details/gtfomdgdmd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtopfuzetw.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtrpbhqdsy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dianchejie.cn/Article/details/gtzlxksqjq.html

[U67] PHP：处理文件上传
来源：http://dali.ivvv.top/Article/details/gtnrreerqu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gtdykwqgib.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gtzeugirgd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtvdchojaz.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gtodkvorwy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gtsxlyisam.html

[U70] PHP：PDO 事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuomvtpxt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gtgotiwpxm.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtbdpvfdwz.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gtmiqcbdxh.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtaxfjayzt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gtogjfcmsr.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gtuuvqwlfr.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gthjklbgxq.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gthjbfbhxh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cqqwz.cn/Article/details/gthdteyfid.html

[U75] PHP：依赖注入
来源：http://dali.birdmap.top/Article/details/gtwimagmyy.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gttxrgopza.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gtwzysnbpw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.0kj1m.cn/Article/details/gtldyfcowj.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfjtnrwy.html

composer require twig/twig
来源：http://dali.gaohongyu789.top/Article/details/gttrpzieeg.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtxyulblpp.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gtbuanrxqu.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gthscwtcdl.html

composer require --dev phpstan/phpstan
来源：http://dali.316326.xyz/Article/details/gtokknyflf.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gtaffjunvd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gtsiokvnlv.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gtnmtmbqxp.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gtavhvfdpb.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtpvhmhzwc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ybcxt.top/Article/details/gtjevclctj.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjzrfyma.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtyqqgbzpa.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtmukctdyq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gtjieuqkse.html

[U85] JS：可选链
来源：http://dali.hysaishi.cn/Article/details/gtvppnggmf.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gtvoaazzah.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gtvnucsklm.html

a ?? b
来源：http://dali.redwolf501.top/Article/details/gtnlqkasmj.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gtngzarvcz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yonumen.top/Article/details/gtegzlsgwo.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gtjfcxujxr.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gttduzbraf.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gturldmsyt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtisbrpdux.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gttrxowcll.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhjxcxep.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtqzlokfha.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gtazyfcpcd.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gtokmcvjbg.html

structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtsqvuuoed.html

[U93] JS：模板字符串
来源：http://dali.yj202588.top/Article/details/gtuvetayxb.html

`共 ${n} 条`
来源：http://dali.aibaodan.cn/Article/details/gtcjtaizwi.html

[U94] JS：箭头函数
来源：http://dali.mhx1999.top/Article/details/gttpvyqkey.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtppiaeznl.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gttgpysyoz.html

new Promise((resolve, reject) => {})
来源：http://dali.hammf.cn/Article/details/gtulogklsb.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtoafeupti.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtdmzxdanj.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndhpujmc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtcwozlckz.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gtauwpvhtf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gtxhkinyzm.html

[U99] JS：事件监听
来源：http://dali.yj202588.top/Article/details/gtdgadtycn.html

el.addEventListener("click", e => {})
来源：http://dali.hammf.cn/Article/details/gtvftgqeon.html

[U100] JS：DOM 查询
来源：http://dali.daria6918.cn/Article/details/gtgqekclop.html

document.querySelector(".item")
来源：http://dali.jyoumei.cn/Article/details/gtzfapnynw.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsphlddey.html

el.classList.toggle("active")
来源：http://dali.tianlin.xyz/Article/details/gtqkpmnfnb.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gtnmxilcqp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.c1oappe.top/Article/details/gtgiqufvyz.html

[U103] JS：定时器
来源：http://dali.zhiwuduotai.top/Article/details/gtqvfdqmtw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gttnjlaiwy.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtujwtzmue.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtelaghfsp.html

[U105] JS：节流
来源：http://dali.hywenlv.cn/Article/details/gtdiaeoxvw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gtpzytdcdn.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gtxzgxkqhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtrpludisc.html

[U107] JS：数字千分位
来源：http://dali.jianghu66.top/Article/details/gtvtjtenlv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtigedrhek.html

[U108] JS：随机整数
来源：http://dali.cheryme.top/Article/details/gtrrankzba.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtutjampcf.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gtpkgiwugl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtzeqeqjva.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gttennmsul.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gtxanxdkys.html

[U111] JS：对象转 Map
来源：http://dali.yanxiufei.cn/Article/details/gtpyoddhom.html

new Map(Object.entries(obj))
来源：http://dali.hysaishi.cn/Article/details/gtdmvelkdk.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtlnaofcbj.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtmkjvdljn.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gtgmjrdvtk.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtjaxujuax.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtppolielh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtiogyybhe.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gthsjfpybr.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gthvoxlhrq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxdzrgru.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gtqsvljhpn.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gtcqfqprub.html

npm i -D vitest;  npx vitest
来源：http://dali.xuetiantiany.cn/Article/details/gtsetxoxsi.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtzyegusus.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gthrlceqqc.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gtssmxuhjh.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtbnhyxcxw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gtbaefzane.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gtqfvojtmh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttowwnfcv.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gtixjhuoxy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtlqwjsrrk.html

按语言统计（条）：
来源：http://dali.hysaishi.cn/Article/details/gthxupikje.html

Python ......... 252
来源：http://dali.yangfankeji.com/Article/details/gteaagdtmr.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtujgzhiqf.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gtppjptjes.html

TypeScript ..... 212
来源：http://dali.shzxlz.cn/Article/details/gttdapizus.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtnbixenbu.html

Go ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtnxhqujie.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtyvgiylyb.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gthwlcanob.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gtkyszfyso.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gthubkpjgz.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtiotthecl.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtsvysisvd.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gttlhdjmww.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gteqesgeck.html

Lua ............ 10
来源：http://dali.shuidangran.top/Article/details/gtbksrforf.html

Perl ........... 10
来源：http://dali.guannengcc.top/Article/details/gtyvxfwtiu.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gtwedbqtxw.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtnaqhoyer.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtmatydnov.html

按章节统计：
来源：http://dali.cdnleiting.top/Article/details/gtbqtgqyfc.html


<!-- 参考信息 -->