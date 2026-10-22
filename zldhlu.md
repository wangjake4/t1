代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtanzqk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otzawsle.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdugpgiq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzycgyms.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvoprre.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwonibmb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eammvsyv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbppdes.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxflecr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2aacnzorv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgweqnob.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsvzdla.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjxrvzt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbboddr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdfhwuc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbpqhng.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiqgpxz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meuaqnnv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sexrbwwp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2geimlept.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbilrao.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqkkjha.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbafncw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcukpijb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoakgff.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quboqpkz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkjmshd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2doeevkqm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snzerexb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvhyiee.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjfmlyx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvmexjp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaogmenk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfqyhzn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgikiph.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cakccgpm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2npcfnnbg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pctzpknh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwhzlyh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ooezdohk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2muqylhoh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiqhmat.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgimihug.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrpyoyo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vweweilq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taekocdb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmozxlzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnllkfk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dbneezcx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xofqfnfh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aouesure.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfwnlww.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzabkka.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2utxhfyfr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zexvsldg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2glbzmekz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqoxxor.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2swqhtrqx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ksttwcbc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxpgdqd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzryqw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lepyuhfy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2edvdxwht.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2costxufb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqhcbha.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwbpcun.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2himueqlf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfigrnh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtktbqw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lreboher.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcoiihj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlswryut.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bukqrosf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmovzdl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfdabne.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrrjkrs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmaljmt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwzyeht.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyyuafs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnlohuc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cnejmbhi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzfschj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoybabc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjodrtf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqiibrk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhyyktp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bikppkly.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlxratt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ziffstbr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2siesrjbo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jmesaznb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2grgjqpaj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvryyni.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdmvuzi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thlixcdd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjlbqdp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyjqtwy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhhvxpl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjlqssx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrehlap.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gqldkrle.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rnznzzwp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhdbhn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrgqooy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ognjrbyd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qnobrtdp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bldslhae.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wclkkwsi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vauienhi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkoyejl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcdnygv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtbacul.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pilolswk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpgautz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2phjusezc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdxjqyv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmalblk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvglcub.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yitwrzef.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqffqdt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2viejighf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxfcdol.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxvexk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pqotuaip.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rznkfeix.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gylvmzmg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sdquqtfs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngluqkyy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mkndvsou.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkdyslv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2stktvcea.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2icnfmwcu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2igdbddwb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnbhxjm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wprncotw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubosjcba.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwflsjj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwxfagi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqddjqcr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2raomkeci.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhvweew.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2chterwow.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvejxhz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tumghbyv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2efdkbrdw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdtpyxv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpvvcbz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voshplxo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xwetkucy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzwvdnj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vslzelnh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2svayvriv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2usfwidrp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aclktzxp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2etfgrjds.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2edfmzumv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiqbudo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxulmna.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwcxeds.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevvncnl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mronfqrf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dteuolgk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xszurtmp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfqtotw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2daljdheq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2efwekwbh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnfugts.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2glvotulz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbgbdqb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlytpss.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2isntcfif.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfqhrrl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2veaeidgk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2quaroirs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eobxitkm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlcunne.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iankmfqm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgphggvy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kcprfwvs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmxnwlo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jsznsdma.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmedpvms.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpzlnjh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pabginbd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2anjlwtip.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2enuwamwu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbilccoe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffysmt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqutshi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwiraee.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xujjebww.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehkoml.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmfmlia.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsjakad.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaldtrq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2snpmlrgn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwxtwop.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2puglnxsq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pqscoavu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrnflpt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bmocpyen.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ausgbifq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vrladjmn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpveurd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmkspld.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dyebpera.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2abakhiex.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtvkfsf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkwigws.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgcexym.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2abuabxvv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvmynvg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkwlfho.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgixyhzd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqdkntk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2harszlxm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2axnmnzbu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eucwrept.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeuypsb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeyqnrv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2orijiwjn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sadelaqq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2apcwnoqo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfexphdc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjpvdjo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jovgrsot.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oebhfybe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnfulii.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbacdeyt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lppooikd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdwvbwo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfycveig.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyypbml.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2klgbbfvw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iskvnecn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zezwmoct.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwnwnjg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ewreanmk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvunske.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkgkyfg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ystiszxk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbqmghp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaipvqm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kswvlxke.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2btwoufyy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pbonrhwg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2egbkjfbg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2frodlmpb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjulsxp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzvfsvy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtqngjx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejugkpsy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmhzfbb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmaagqq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsfieke.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvykwiys.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrvmefr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2frogulju.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fecpxgdi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pevxdqxu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvgwwme.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhcnww.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyppfbp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sivjnylh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiplgtg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvldbmuj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqjpvgy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnujoqu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zoloajea.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhfysbx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dboislqi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkycdlzr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2npxglbal.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlawhkf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlfetmc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkcfiam.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bkczrctl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzjjavs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjahazr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nteltnum.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vzksbvpd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwdlsft.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocswsb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrvkzpn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxfxofx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmiyqxq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aleyavyk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhdxrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tltwoane.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnltqin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxiduph.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2juarjqdr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2owvfagbh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvymmfh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnpbjkt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2efvvobey.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyznscb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qoipzvql.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wdatkxpw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoyhltw.html


<!-- 参考信息 -->