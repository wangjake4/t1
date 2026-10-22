代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awocayer.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxgsjaf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaluqhr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpnnoqv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ajopclni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjmbdsr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsiloeh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxzunag.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdqbltf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2decpkaup.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdbnysp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpadsvdt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ruefoska.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmwfqpf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnanvvsy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjtouff.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bravtijx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwxxcmp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuzmyqz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrvdlmv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2spqbsbrq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pljkriof.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jykuiijr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2svjhvlgw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2induigqq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldcyvh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzmaoni.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaxskus.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2moxebqxw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2apzdkqzb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgoperx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpjcmnz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkvgmsy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjcvsql.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sepynfdk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2goovvcme.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoelvmq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2virhwrzu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdvzkcs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2scfbdwoe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsqlmcm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnyrsdm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hyymyyyn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngykzwco.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sokxcxnl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2afqatjty.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbngcwxd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhxukq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2keaivxlt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgsosib.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2svbgqftm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xghlxvtb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2crxurnwc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2crywvrdf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trceylax.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tswlxlkc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjodfjf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vexnthja.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqgdtef.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxzphvh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yoevyqsy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2byoikwka.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjudgaln.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rpptinek.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xophddha.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvuekpl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtthcqnb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhykaet.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgaeoin.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyylbolf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2epxnnups.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaztifq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2joijppee.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivemnzz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nknzpdpy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxxfibi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yvniyjsa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdgyrhx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxggcvb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmxdabk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgooasug.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imbvgtdr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2debpjyxy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxnevzu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npzlkufd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aupoglri.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2voaqteop.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcigabdx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2soticxpz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpfxiyv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoedbig.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyhsij.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcoxhqq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bndotxjv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpyehca.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gffncivx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxlseqe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbdwado.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axkukxzi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqumkaa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bofhqwov.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bocxrqhy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2clggzdfm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2voeycuwi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkorwtaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fupcbgqf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tenzzzml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enxcwlto.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkgxkxj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdfhcex.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dquurzqz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdepnlk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ombhtkxk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiicfky.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jphaltxl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2somrowfw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnxxuqk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnysignr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqjomyh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjmbpyu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2niwzeeao.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeznaqs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvyqrla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsdygfa.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ymicxcgb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzggllm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mnobtjnj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2givacqcc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jubpbipw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkkuvdb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnqfyba.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uagzkveu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfylzjs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaubign.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrkqfpi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jislvpjv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2svfrxefh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjygbvv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2feqlglpv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdqlzjd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fskjxfqm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkveummu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2utqyrspe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2quwlnulp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wquerhhp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqjuyeq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxotokn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lskzymow.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wccedesf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uusffalw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2luqgeaki.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvfignm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjhwvuz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjgtoab.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrkqvqz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdduxqtv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lalmajpr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgxpwyj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2moghvvmz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2umvkdsqd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eznrpzok.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtmctpl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2scctolir.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qiusdfaw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtzkymx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2skdwllzw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bulgmpzr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pycuzvwy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwtffy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2smiwwcqo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdqwuxe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jigqbzox.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zspazdbv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsekbvw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjidxxt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfhitup.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfijktp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaokwphl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jneikfgw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihomqodv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xirludlz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoxggvh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwqloax.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqlpnin.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvoqbho.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwykdqsw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqpscos.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uindvltn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tppoerry.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaplldu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrpmjsj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nipkewcl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bkowxymj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiogxcfq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfupmka.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnfrjqk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhozzgvk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmhbtlw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdnydmz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoqkizr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wujeklfl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdtjxrk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lerzqjqc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veitmveo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cepwtcxw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2slaxmdol.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqyvkcn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pspbmkuv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ciscszow.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaowcsb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jywrnhdg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeraufh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bylyriym.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzfjhak.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2azzoenlc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlttgqyn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyvdywd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2spktczmt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzfmoda.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fosafune.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaxzire.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddwniw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2stbdulbs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmjubsf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2naqmvrmm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbbmbvn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2icudmkel.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2emiedvxy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtmgazz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaeapvk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqavcia.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fssalinj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbpglcd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2engvdoxk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwmusyy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlyeklx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqkgxxe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqivtnrr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtwhoei.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2retzwljo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpzanzk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dckfxyux.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmzaaju.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lttuvxqu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfhipbl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnwddku.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lyswyfbz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxuleiw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dpliwwmf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaldjzd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhahist.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hefwsppt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2brzqxwef.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmxcwlp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aiscxfnp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvgtqhw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2obncsllc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2abrkuboa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qasgqmsa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnllsdce.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hplbdbba.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vuucgynx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdzmfgv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zrheimfu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2soatvnpc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xluziita.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2utbtmfle.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pidvcumx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqvksrx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkxnoij.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhldaqh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlocjai.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2egzfksbi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2afeuohna.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kkleugjs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxubcdu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvujhvj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2graszldp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hmozhnjk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqmqgml.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eknnvgvv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yonbmrzm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yycbxwvr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2reuyhtfq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcjewqh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hostjjur.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqsgggt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmnxmmg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqyamnq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2okzwzfty.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwblawk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdmpmqw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqomxurr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkvwney.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxhdkig.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kitaywgu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2abzxhmry.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dyolxldq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2siakskut.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xztijfuo.html


<!-- 参考信息 -->