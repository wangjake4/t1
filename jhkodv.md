代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkmlzzi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eefxroqs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwudtrla.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbqsurz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tiomxmfc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdagdxxo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jegbdybg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcutemx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaqroms.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnztfdx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tlumsmfv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajildtq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2czdqxvie.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jotzxmtl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcjiqns.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dogkiipo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvdybhc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlczlidj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxmghks.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nozcvstc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oymnsprw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uplhpfoq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2urfzqptg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlfxrms.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdbcyqs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlxrbjh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fapcccwu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyzqvyt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzzrsdl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoicsij.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stiqfvnz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wawqzids.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2liihguxs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzsxoaf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhdogoh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2biecorro.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aywctacn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrjtmop.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jplsxwby.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uszcxrxk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2muteelgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsvomdt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swwmsdmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdsimko.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2olapqmmi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qisxywfn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyvxkmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jejjkmox.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbkdbrp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vstwzapw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xspzgxck.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2schfrzjz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2idptxxif.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2crsgwwpp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nuveqlfn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlqvdnd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2arfyyoeh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpfqtjx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwmsteh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2agcaclvn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgvubad.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirdokmd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nvshcytz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfkewqf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxvxodp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbqikub.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2medtebue.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fulzhpgu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpysqjee.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdzxwhn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfilbxq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeykldl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kavseixa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcxnytx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2summkzzh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwpootf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tuztkgjx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klphztdr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sphdoehz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkezgzle.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcwevay.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbikqoi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqqltxy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhyjfxa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnogsfh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqwjmdv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnqcvuu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdwrafz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgecxvyt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxywjir.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqntbvym.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpxnmvr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgnkqjw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2egphdxot.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlfekju.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnnkfry.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpjjqaf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2woqspgvf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cyybimyz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpkdwre.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uivgazlf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2srtgfayl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fshffofs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhknqqby.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcxepgx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2emeoxfki.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwfmwu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgoovpp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmncblw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2btoymiwd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oeujxpba.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhacuflt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwnslqg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdruxtel.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qabohjte.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoksjfk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iikacoov.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2myjczhpz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvvrzjc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fltmjqix.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdvgyug.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzluqhzb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sisjkvso.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzahedc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wrucyckl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2obqzhmmx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgwipfn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnpuczv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoosemp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnrfrzb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaeabdy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wueguhuv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lozmluuv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqlgpib.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whlfeero.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2krfebefw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmokbec.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2diggvkir.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxnadfz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhslblt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2trwijujw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnsyzhp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdeclfd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whflyozw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rakomejr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcabiil.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tthclgbr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytitxatz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwxjtig.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcnrbio.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnuwykj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqagehop.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwldamoh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpjtrkn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pesfbfux.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftrxshy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkowikb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hizvknwh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwdqfxq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioskpoob.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2acvlqcte.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpvlfuf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2janlzpta.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtpefgi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2isjtzdxm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cavlsoiq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgpxrki.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsipljd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wiojifpn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mscpqxvi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoncqcp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrkeeld.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwmftgg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anjwffhx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rudjcdxr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hghefzsb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oesxtoha.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kscvrqbg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtjzpwh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrjlfk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2offhuesf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nevqpvur.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtuiexy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fobgwlhe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhipxxe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdljvcph.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gbedlevs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2buhvmtdr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sotqrbtr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkbgwnm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iixzzgcn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lymisfri.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pusnttdd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjfauev.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2plseqgng.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjbuofe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxaqrbz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gquiskiv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vytxwakq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtekvqs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2upekpiye.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2omfcfiga.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2odmccyeb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjseinp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ympoanmu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmozvxu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvkugeb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yakmvkrl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2amqsqzss.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2punynhep.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2spgzvwvk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpexdkp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxxxhxi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwyseie.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wikywati.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kilgpkem.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jluhnizj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2reihnaob.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwbjuqd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hugazwfq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzuqkbg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmomxvqp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhurjfyz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iriqlvkf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmuizzt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkbdtwz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxuxxyf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qttcytxi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apyyqeab.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrfuuyw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgpvlka.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2udookfgk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyytjdh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2acratven.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaaxdyb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvoubva.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaegzka.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2spordbwg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxwzodw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcbbxfv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gihydvza.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jggybaux.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdttqfbx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvckuxbd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrfynfp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2peuwbjfe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfujwqd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fltznjaz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fciojjfb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wemsfbvu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bytibcel.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuobnnb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iogggwfz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsgwhij.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qggwnkce.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzxjhat.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sadvvhfi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkwgbll.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqjxcip.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqlaihh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwehmlw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpzdbcd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyqqcwm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxpnvbi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkwugjz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xisuvjsm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zovqddat.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkcuicq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaqipwj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2albyocnf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwutgyav.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iweabgli.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jnumdwpo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sygvopel.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhxebay.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jprdqygu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjvetis.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjwbldl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rrophbtd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2byolfegf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tevenkkb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrtqrds.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogalqigy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dikqhruc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpxsnlj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjjrrny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvyfcvr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdlavxq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpizyig.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2azeodbey.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2chgarskh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lklkptlu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhcozor.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2trgapifg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gzewrcyu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2goeimeod.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lshkonph.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mynrwkad.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcysguk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjbjnog.html


<!-- 参考信息 -->