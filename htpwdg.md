代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlojuty.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhnpjbj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2niwwuumf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2whjkcjjg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dulhutvs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrixbel.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdnipdo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgjbjmd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yludzzzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2twkvgwpq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vapgnjuy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjclhxti.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdojhuk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuvodzy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzionizl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mldvskff.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eogrmqom.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoeadfi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivguufnl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjelcmyy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tppwwugv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqyommq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqfjvgy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbencbk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoztcoq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyxukjk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrmkmuo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzzoxny.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2apmdzstm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2brdfzgzr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbttymp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2znhcbskg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrglngi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfectnw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddabbpen.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvimbcrk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhjrmcg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnqeevo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaldxse.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwcoymn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmktcpmm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdimnkzg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vadbadmw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqubtce.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sykertjc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrwevxh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgflmca.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmznxwz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqfhcuy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvlrjpe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2djdvjwkt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zygvucby.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2apvxdzdr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxjkpfj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiynuom.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2apagaagk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxwfzu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxnguue.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnfnwib.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhtofpu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ralrtsov.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcitgev.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbnynvn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eayruhep.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2muisicvt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ddplsszb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvohalax.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrpuskr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2itikbjvw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsgovdi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urpyqydw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnfgkgj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uszjctro.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuszifpd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezagmfrx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfbtcck.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzlybsq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqnjshn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uswmrbpc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnezcan.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvsvdey.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ublpimty.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptefhtlv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqatphc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhweldao.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvnhufa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqmgiin.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hujbcxuq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaerkju.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpyabsg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uopxpuhg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dctrqxsi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2joqqrhcj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whhzinba.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjxuqgd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijgffv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftekhrrh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zemkrxfw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otlqbrlw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbtqkli.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgrpbj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whcedzgu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmvwhmd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ancbompm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qzskwzqc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2foaumhwt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2voebvonw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmmectw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hemmyuzg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2enrsiubr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2opmgwaym.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2axmwvxre.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsuweec.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvjqnln.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2javfagox.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdrbdrp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcojxjg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2anrqpfya.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzloyfy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yciknsuz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomxnjme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvqrmph.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdylrgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvadbcq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2etnunovl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxsyusf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfatrpo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nklgtzse.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ztppfwnd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfzrsma.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvjlbjq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jewmflsf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nkohvyhs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnjyqje.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojplhdto.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuahjrhr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsakpgsx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aztkpdhp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ppktbdbs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpexvom.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bftkhisv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvixnkx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oncifgun.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2udrkycqt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2meuqbhhm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrllhkht.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqgvzxe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdihcup.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcubhuo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqmmths.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fskmdbfo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsigenbj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmczexw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzzqjqx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwcnzvh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxxcvzo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkyfvel.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aynxplsl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cguzrziw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2atigryji.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gykwjzzq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgccdin.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdxrekg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajtxriv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaememf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lupmeeaq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnixtqw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkxbzmt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afzqcvzh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmpbuka.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eooaoawi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2udsgujca.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqbylpy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtcfvri.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2psgekqke.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2miznbnyp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeptzoi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuepqiv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvnpzfq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bugosbgh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hrukzkmv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uppeanpw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdocirzt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbodiyh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yiegvicr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzxyxkd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfydxxzn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyonecf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtqsgzd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2islwvtsp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eutxyuvk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigxjlej.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqfzjwq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijooxxym.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiwzzsb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvufhneu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrhnqpi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zkblvzad.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2brihngbu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bugxneje.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iourivrs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oixqfrhi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjfixyr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnybqewa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rctktepi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bjslggaf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2analhccc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmivxeo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmxjwcv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2iumwlyws.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfclruu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2idlzidmt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jazndcsi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsvsylv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ukocsdaq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2snhgevog.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tglqcqvp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2slqnqdwy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dwluckfh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aargfyuz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zalsfaiq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ojamwxry.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwwygmj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swbuxztq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wflfasac.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zelezlhn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flacsnza.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwwcxth.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvhvzpx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiaronz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qyolxdkl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gufjazfc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yansjtsq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnooxa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgxwizw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wogyjftr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uelrzxkq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzhshis.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxxseud.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhomjrm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrtrkbo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuundye.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlwmhtc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdnkele.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqtlqsu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wunmhidw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcxfeeg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2itxblupa.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cirwckca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nucqmlxy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmneqonx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvoamfi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsjrljl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gegrbnvz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iejpuxun.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdfjmgq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxucgmr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2urihrijb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2paofldxa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qobbvrkh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qaibhdok.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqclvxgf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2etqablro.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaonsdr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tilaadxq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzxfsbc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llvxtqhs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2aiupqtwg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dobacfeq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrqiahp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptodvaik.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtaizei.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfqjfvs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cldzsrez.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uzazztmy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtehvyw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2poijpwqj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiyeykp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kogvctvg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmdqdfc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhsbgsm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxehoah.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgzocze.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dlisxpzy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ussnxfxf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iizzjmul.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmtyldp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dafimlgt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpsvnev.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2firmrsma.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kykmvwap.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yojriwyo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlaihtz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qstlpsap.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fxohhsul.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jmodtayl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oohnjrgd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvxylzi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiwgnqo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2trnkadrm.html


<!-- 参考信息 -->