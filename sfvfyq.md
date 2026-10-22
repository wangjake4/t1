代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnfvzct.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qufxbbwf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbssslt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqobzsb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eexchtai.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyopszsv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2noaugtus.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpqhquy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lkilqlth.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yifkoxrb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2taznetfp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruroepjn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xocetzti.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzeqycs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yyartcjm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nywlnkbr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjqmeea.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exounhjt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvsantj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgszkcj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rjudainu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2odnwyivg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxefnso.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2obdygbxo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoujdql.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jecmkfnq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdxtwnl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qiulwmzp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cowcdvbd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyimhcr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2afpieyxp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sidettkr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wfavqtjp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtefjm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnhbogd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pammipfb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2esnlrivo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvnxqda.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeamvtw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiwswwq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwtwqey.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlqxecp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgaopte.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqccrai.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlolsbnx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxchgxw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwplkze.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjdoaal.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2szpldopw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dvonfxrr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuenoqld.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2agrploch.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqojmnn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ayasfirp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmqatxi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfitbnmw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwanoptd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjaabvm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azoshxbu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdafhafa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzzhai.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kckuhzsy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfesrxkj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oygnjbiz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbwxatq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uazmcjwt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhcbrmf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdypvhof.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqvlunt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvnzrix.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxidngb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxrwqoy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egufggjt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhljrhg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwyhnqd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmyacno.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjeikdj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzxvfnh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbafbnnw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pugtgknk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpdlzwi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztccnlau.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbkomlx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfqcqqo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvztjscd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czyvfnfe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2htykcgkw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eklefxed.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhhtqib.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeztjhe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zancuzqe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlkbaqz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgizpwgl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zvixexgf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khulnovt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqoridq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaotlgkm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkjjzld.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxjivch.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwextkm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pezshqfp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rvurjbql.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pacgpcdh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzxsqfk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xisfvhju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xocodjuq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iddvmjfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpbjxki.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nmthngom.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzerhol.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcnlakk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujynfqro.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdfuhcz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rugrheqm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdsilgq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhomyvt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgvulhf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsjhdds.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xzercdac.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fleuvhpp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvdupba.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoompfmr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aafuegza.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdurioje.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wexidxpe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrouksx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxckhue.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiovbanw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2queskfec.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twnfooqy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmecepy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalbvqxs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2opeczafk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aapirpvq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgybklwk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxltejd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmacalb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2raszaqsa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlcgipe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2apwhojzw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwwrnmo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqrmqjj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pljuylqq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2urlqoufq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgcveyb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isudqvid.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cafpljjm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlijpweu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjevktk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2txajzycd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcbsrcc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqvfpfv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdcfwtf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2srwhiliv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2egmxnkdi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwbuyyl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ungyvqhb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjfoqbw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cmadflua.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpgwgou.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnhqexx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwxsuyj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qebulacg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nlknyqsq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrdevhi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2okdrwzpc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxksmsx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoendoe.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2edivohvv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvtvwqg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vttbvydz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dkslkmdu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfmmhab.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjftarbw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzqkvrb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzqufqz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsduwrm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqqqiix.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdtqdzw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cizcfjbr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2naksxcjg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mnalaeew.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tuavnncl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzrqkls.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdypwsh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbnbvli.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdvkknq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsslotu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yxheagmw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkscdcl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nraynior.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eezyshgh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmukjvnu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpagrxcu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfnjuyf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sybvzlcf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqxudwd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvapzfzw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swyqdfjl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsewoqm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pytudamf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnprrnx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ohckabzq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nriisazw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbdylfh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnzixvm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gufnnzef.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubysmtxg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ceslnrwm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhjflff.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoxtlyi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbkswwt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2semejojc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzunhej.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dntpvurx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnwquzw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgwyxjv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlangfza.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxbqvgu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggouvyxo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtaxvbf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdbsoxc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbjpfkt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xthhceta.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvcnsfp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgigrbs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tqryinio.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2epclfunu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bysqztvr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuzmhxa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpmpbmp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpdugfs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2shselidi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcwbelx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2luhpmeqe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjcpesu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzumhit.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axbqyjhg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2suxrkyzq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzoohxf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmloakx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2reznwxww.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odenygmx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxwwkzt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehltsagi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrusgjbs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdedpgzv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpwmuqs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtymcxw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiizlhia.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jzamxtsc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mgchdikh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rvehlvny.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhuhehp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toolgiwy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkjzfoe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgikmzi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvutvdj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2durgsuuq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbsotpg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqqaouo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lveytdpl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zaovvhrs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwxahcv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gmarljlh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcvqzbw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjbahms.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsssnjl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wolkdhzw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsxedhk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxtuwpa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sonbydrq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2awoefzcd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rshlrsty.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gghhnykx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezekgdxq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qzboyxyh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcurihv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tojnvpwd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nojljfsn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2afozsxpq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2eachlmbq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xzntiujn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctcxuom.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyhpofg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbacznqq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2trbbhlfd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqsdpcr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okdmiyau.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmvymki.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrjfoje.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdsrffa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcjknje.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwvjewd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cduirdku.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bstyrhsw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qymbfnqc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kaawduwd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hecrduvh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iunbtxeq.html


<!-- 参考信息 -->