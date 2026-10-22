代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrlimrb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mfubmsau.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuyytqs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ooobtkbe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iuukxiqg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfnqna.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2haaoxtso.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoexlxt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzttdjd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2khsfdcgj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyolhyd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyykzmj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuxdpmw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmthcdgp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsngvgp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyskvbt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dokvcwhk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjolots.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqschiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvozidgc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gujjgypp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xabzmzvb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgflgrpd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdcrooq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmfpxtd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzwtuzc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rufqldmc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbijcex.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcsiezo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mankzydu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ooibfzoq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvbzzqf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeotkqap.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cghajttz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igrjqrnx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmkrjlr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alcxmgkt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqdvxwb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uikpklpz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sewggvey.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rksfdogk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcggjtxw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2belgcwow.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdpdqes.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeghvflb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoieaqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiidqolm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yazunkdz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2icurufwk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2udamnldr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnndqasz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaezlqb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oagfnvjw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iigzyopw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxygosu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhzuhwz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjjfznn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amuqhrpm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fregmzgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klskcccq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeqdxss.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bryddidy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gxildojd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dksdlxtn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pwghmvaj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2knlvmoye.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvyixfl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mlojjbkf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dinciiuw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeypnlnz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jbykmlfw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jofbzphw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjqjpka.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrcqdoy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyipexo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2udxlxytt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xedwdysp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqsmels.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aemtiicc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2srrqdrsj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eitozgix.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2accevwcc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzqdtiv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwlnhgu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzvoijt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnqrkfi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2habwrccg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2npprprlj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtjauzg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdxgezi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkjyyhh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqxwpkw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qnylqicp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikypuljs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwhpcoe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkardweb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbgqwfb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxndqqo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2awxcohjw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsdcpnz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qldhumdb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qalyglib.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2abroionl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbnbspf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfltprxh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nwofbqeq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrxekih.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjwafhj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rraqikba.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrridquq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2phjxkrhp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclvpwmk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqutgye.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpjgeas.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtchfme.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmswnio.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyuaint.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tousablp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2btcbttpu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkzgmvx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pplpgrur.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqwumvk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hpimvyxq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2isthgoaq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tkweqaxd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqinkgrc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlbaoml.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fstyrgpo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzomlvg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvedrdye.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fliqkqga.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnxkvuy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vxasipur.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kvioxndq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2awtkryuq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyvhltk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zndbgjqo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlerulr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kxycyvdo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2roylnjdw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhtkyrt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvkeaqh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xshhyysg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2inxkjzum.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sslbnihi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfybwolk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxvbnlx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzwctcw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vleevnlc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubroignk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfmuqgz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2otdxhbmo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeolcai.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sonmpcfg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uztoztxj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2educzrxu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2srvigsvt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ytakwcoc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvcvgky.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zglwecrz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2trtvgoss.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdwajcb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhbrocn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqvwcbe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nldlpyvf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlmetiz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2etdcreok.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtlydzw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtkykdp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcucedzq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eejffsxc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwogwcfu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2prmxahbq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htbggvcw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2itoqkvbb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jadtkuti.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xosasudj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyynaxo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2atsiyysm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pokorolf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzdqogh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkeboua.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2acnblage.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqenall.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaxajjw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzcjjwk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kylzabgh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2msmbjgef.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lalklfhm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hihnakze.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sfelmhca.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unscfqmj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgbeosw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hskxkxqg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaehozj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwnmlvd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iljychfw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuviopp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwtlrkm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qraydmog.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hpswibog.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vleojniq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tkupqpwp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgffhww.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2duzvvmdc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpvygry.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sewnynjm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpyrsva.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sazxtekv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2obmqelqh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnjlypq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzawhoc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2klieerow.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdvstkm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2emmksmcv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2aneinbys.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfrqcrq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoopgoa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpwclhd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iiretdce.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2imodpepc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yawzmtjv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bxveworq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrsiubj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2scgscgtt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbslvovz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oovhrgrl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptagmjha.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuarsog.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgfmuxr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tcewbskf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwnrbsr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqslbdzz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxuewuq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gokxjjlz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlxsink.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dtidcjcm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2badoeigv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmthapzc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otgzlajv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvukksua.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2onqzatku.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uilbsgro.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxmclvj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2knbaxcgl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyligvz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpyehox.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcwidau.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kngezhce.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2helntdoz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2efbkahex.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvikpyy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bimzfjpv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzrxrfr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ernrgnoh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2abjaalgo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eavscbgf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcuebdl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvbgvjd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dafsbuwd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hicydtud.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpiwdba.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nzokrnas.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrcgors.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2igxxjnzn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbrrkad.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjmeelc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkplceie.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzwuzrj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2avhvprls.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtcstew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgpjpjz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqeknvb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxjalax.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nquohegv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2exqcrwkw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2knfmtzas.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrkhrca.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iptmviwr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxvfqkq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvoemic.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcwkemv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2thmwexhe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnkyghd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uevcofdc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2npytcbic.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqydvnuy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfeqxys.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yoblaptz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecehsxlr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2arpotrwy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elcibhot.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2scxsxofl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkurmeh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ejasfvxt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnqluon.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhhsfhd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgszpru.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuareza.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtpdzzr.html


<!-- 参考信息 -->