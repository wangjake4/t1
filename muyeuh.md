代发 wailian999

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrsehcy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfismca.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjuveii.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyizjrzy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfckxeeo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgobcfg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqylmob.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxlmlqr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2igxxlpkt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoaoync.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjsejur.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqfodxj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvxbrgc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2udwkvcyl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pllbxipe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvawili.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdrdrfm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtozzhyc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrkyngr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfcvocs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2egwoffys.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqclqchx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xocypqow.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgwmcrj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vggnzkja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbsvgia.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpeiyml.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzeywv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbebqsn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdizjqa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjrytsa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfvkgel.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2odkiroms.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckitdtsx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2svejkauf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxpunet.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ggubpjga.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2herrytxd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjestsdp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdskjngu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oowytdxh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhsoyme.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nvispdjm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhvhlie.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hchaodja.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjsmzhu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnactls.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfbeeot.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtnywnk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnozvqhr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjonsfp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uadoendp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqhllym.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsgzjsh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlfkypw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxkpzpy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpussxh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmpyoja.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tflbacym.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxitllvb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yozkrkag.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmenhyt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2euywgzyz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozldldsn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tivlwsrk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbelxges.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhkypgu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxqroej.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orkaqcoi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxmcgsh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuljjind.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiwsuyo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxlutso.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adinzcao.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjfqhgq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hitduxqs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2httpyqpl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fszwftgh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axcpxxdg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gylrlvog.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyjugzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxustph.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbpgukm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpzehip.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqmcpeh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zamrsvgh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhdwfou.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxtbzvv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgtrfam.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nencgdty.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjlnlam.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sknggxix.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpjshhu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmgttoj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pazfngec.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlwgmpo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2scctcegd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdigtnx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbcbfvb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2prrnbxqz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2urokbbqt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvnprwb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjxulgk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aknbsbxc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2judmmtfq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twpsbpnj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrhjdkz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvzqmzu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbzkhve.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfllkdk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvggoaw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwktdpeu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbdhodq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2znccqbni.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kevilfkk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfrncmj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiyfuli.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiwbbth.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2krkbtlhg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nshljdsb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxjuluk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oirjwamc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwgudrz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgimgjq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2etfdfrbw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxyfhxs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qpppqhjy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2khgtiyhe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbrepdp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuxbtmk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2shbriaou.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zombllye.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lbixrvmz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2btqnfkjo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwgucta.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoxyjyo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxrbfok.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oazmzfcd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlsgqgx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fveabhzg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qibvishq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjumdrx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqxfona.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bazdqdcd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdyjwcn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhjbkah.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tspydrps.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpthayw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lfflfvss.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwioku.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2djisewxm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2imawmhjj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiymsvj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxtunwc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbnnqgi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnndhwdx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqyrksm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkvsnzg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpysjhh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rcairkuz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eywzzxlc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuueezqc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgjoeus.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxprzqq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qranuadv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yphtyidx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvnyqvt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vggtzqlc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfvefjf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2agcoaoxe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvkluum.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwtsikd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wqesexlv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdohrxvu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eszlqrdd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ayujbadw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqquxlu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2amjfloct.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkbhmlv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voagaoml.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuwhesu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2anvrimcc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwpkbra.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgnoscs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nadspyxz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2grevgjpi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imrtppoj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtvpyrl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tchqqqkt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyorean.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2brmlgeda.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2elzzkbrd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaiessi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhqmtag.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiutqpbz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsvgphy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrxbcog.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ownchfty.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uxequxuo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2padresta.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2evuunhxa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsktrjdh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnelbox.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2epfoeigg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlkbfm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhrrsrt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfiouuu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoqdokf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdmjsut.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpljwvrv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyegpye.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewviahsm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2njzrgakk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyukvkt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkvkklo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hivzqwqq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdlswjh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cakaehhl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuwhmvb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnfutwo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2trcaqvlh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yamukugq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onxneyqr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2otkeedhn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuexmha.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sadslcnm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2janldadh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jthubnxn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cenbtngw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpvkkc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfhhxfp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2izzalfek.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2euygkmpu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpuxain.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rpphppnn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxhisib.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyjderx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfzbssb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kkifiijn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2etqzdqgm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlxrvuv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uawuqmns.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2clscjgkg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyrbzvo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2azbngaqq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2upqkqscq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjpwjhl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkcqlvx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mgttvwhc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bysiiupp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lutruovr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnibaxsf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nxksrqwz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cyazhlzw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpisklc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtuprjq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddknrhdi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmelzsrf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2temvjmih.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzwcrno.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrqajos.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfyrdse.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxbubzc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjtybqe.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdnhkja.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qsohhaqp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsakapu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqztmlr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpugsoym.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmizsvq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frjdwsly.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wedvtihk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jhceozjv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txgpkryj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcstpnt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnywzkbz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vawstnhp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdljsnis.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jayfvugt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyorgoi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrloaoq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzqdvwc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdihhrrw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrstxrtj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpwrksn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eglftopd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2udbdkich.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwkespt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeqhnlw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bblbdgdg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iekdwoed.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svsfiezr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrxmozs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkzaosi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipiilj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2styztyau.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyaldpk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkddbna.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rongfulc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqoonzv.html


<!-- 参考信息 -->