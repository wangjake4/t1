代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqbvrji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2celufurv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2quwjvmcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osfdkafx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxkkvee.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knidcuen.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2flebqjqi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hhazzmwu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ksasyyyv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhazcetr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgokeyf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2shqqktzm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjahaghx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoyptdx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kadvzngh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqxbrtx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdnywmx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkknzeof.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpwwcdc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsonktam.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdiqmfq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuiznej.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzagtjk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsakvdar.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvwpxln.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxwuftx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzdbljf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phrxbnit.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuxkabl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwegiiz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmsfcgt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoxzjmp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2outpzxkq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyynulpd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqxjesa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtwkrce.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsowbcvj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzejfgq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vccmejoe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvqhfan.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzwzalk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdaonvs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2akenmmvx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvzlthv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkdilow.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vurmmygd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aknqmwnl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkltpygl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhgbghs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjeejuc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jripagkk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umbbyqii.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfdlqym.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kazthlxy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyxslt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdpuvtq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcquzkq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlehewrm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtxumzp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwapvnih.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwxblnx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrnwise.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zsllywom.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjbvmk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ronyaqtv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmmxqnb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdxcxtn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhyymdy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkluwbhm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyltdoq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxipmvbp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxifnlz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvndjnir.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2atijhdqe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzwllua.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwzacha.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oqezfaqy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqinbfej.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsatlbgv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zedopbib.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2orepagft.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsksuen.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlysvnoo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2auznjswn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwmmpmw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkixzjh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwziksk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxerlvv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpoxrpb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxhinid.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkioerp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vimyluda.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvziioeq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgadrzz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfrmnqh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoobcqv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmvyzqj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvrcjrc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvlguua.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmaczfk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akqzuhmh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaeekss.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxutwshr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnawljs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwesqmxm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dggontkh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiutmkg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nclpcyhz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxshkes.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqzhmsp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2folujstw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyjfmod.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2natxpagz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmjftny.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoxgztd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpwpfyd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmnlyuc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpqsgcf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyqrjbw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kotaqmnu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2szyevntk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtvinnu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rveeoqcn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxfyuqx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdbqbjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohceeosq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkmuthb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrdfzcb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbzuqqo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwmtzlm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbegwso.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbbstdi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dykldqvm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnixkfao.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2etdrhplz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoucytt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2atmrgkdw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzingljx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmmuwvh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2olztfvpk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2krdqafad.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfihkoht.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwsagjv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcodxgl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjrxhtt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cipcrfsv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmjphiz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2truoeomk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlhnty.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyarqelk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mydnvlqw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfhziab.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnlltow.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbytdnv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkxmmnq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nojzpinm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnovaxc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2reqkspss.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pdubyetz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuqhywx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tayovkjm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pooyjyed.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfuvzgy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jffidhqp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cqakrhfz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtnvrmb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2siwhsxdp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vygyiops.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hsufvhcv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sgalemqr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyvlspd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yybbrgsy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvxllva.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcupxcn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxwuruq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfoilmy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ursidkae.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2umcnebmy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpybaif.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yabuqbrp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lancllmd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2shkooukw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmjmldx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nxktdlui.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2famemxwr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2weuqmzcn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqoyvyn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2odgeexcq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2arbqloge.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dusnewlj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkclqbg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pahwqpjz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfpltpw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwlgbth.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bvawortd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkphjxh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zltjhomz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2iejicekj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2doufzrue.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zetbxddf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxlmmwc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kiotlkqx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2htgialgn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtkqixp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sftquoqr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqnudbp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zgidtypk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2meppmwrn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfpzqux.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rwujkxug.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjedyoz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypruyahx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dksedjja.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2owfldctc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuupeuj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdqjnci.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzixhuny.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soztfhhs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crzwdlva.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2prtrvflm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cydgniks.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hppnorio.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdsoqbx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqdfazl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2axlzkqws.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaaipuf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xrykxvtd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usrbehqt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjjxfxp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2witpghvq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wipovkev.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2meugopjy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuoxeuu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrborazl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhketxm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbsbuvp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2amptvmox.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhijyixj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2loqrzwur.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aenxpqba.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkfxxrz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaukbfb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2titggyub.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2slytthre.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqzjgas.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjgjahh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bafhtzpt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2utogltzc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2swuiwgpe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2udomvppb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zalmeedn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjwncql.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkknotx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjxsgog.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwnjwhg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxtqwif.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvplzgy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeilgjp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhvfsyv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xymudpxv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfixehm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdigiitd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bivxqgqa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqwdwwu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrbpkdn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2segokkkg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uiawnbtk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhrdqck.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2atmwucno.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2puqyvdxd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwlvszn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxeeyah.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uujsqhht.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmgkeje.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qybbaliw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2afgvnlak.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhmiuwq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cejkcobr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tktvdqmh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2efwpjsch.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2quadvbdq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnkypzp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sasgomwf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqtjyar.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfylsbt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvxozji.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjmfgbr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fycjzsbr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvwicam.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvtumub.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rornbjmw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbecscn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2krkenbsj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ajksgmqz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzaeqcg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sthecshb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjrlhom.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrpamre.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlzsscy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpquiltd.html


<!-- 参考信息 -->