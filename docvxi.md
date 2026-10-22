代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfypilhr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaxvrqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2srinbvqb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uavffege.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdysnupa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rebdmemc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvppyphl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsihvnr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urtvmyuz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaziybr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brridweu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jogtiklc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbysozi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cncpnqog.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2twbxavbx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jltepehq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yplrngsv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaepbbf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvpsijz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdmdply.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqmuora.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qigiwfpp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxpkuic.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pndekpgq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hijrgkmc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmjmoae.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpfubnp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnymvfez.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bktafcxi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2whsuckxf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkttshd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwlbawe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhngtat.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cshbiqjs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhjztfd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfgvygd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjuauiv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjcwclo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfvskcq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaphrce.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qejlmaty.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqinkxah.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeudveo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2efztqvgr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hfptwjpe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfdhwjt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2emfebicj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikavbgjd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xlefnazd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dilabpbq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeofcvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2faayvipe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwniokr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2deellimf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2waugejnr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oifvkixq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcwoenb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2trchxslj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvgedym.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfnogla.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zencegsm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2scxzeepo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eskholxb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2byfdimqp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhhoudc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yraprxap.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pojtbbsv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bliprjwc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srimlnzv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2miatomys.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qseytwkm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ulngmynq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuvglyu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2slftrmmv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnshqwn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbwvqwt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjjuol.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqavtlqg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhpovfg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhvoekm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgbqhji.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umktwpvt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrrlfem.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbijpqju.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ffswlsbn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vchqober.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqbciji.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpcnxby.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txbrudpm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgptsnni.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhkziya.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2injrgtsn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtppqju.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqfeetp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyugsskw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuktdvi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaoyohx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsovurd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvppoubu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdworzu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfxhjzw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fatuutvx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlbwoxa.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kypftajk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhvzcqf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skudwjpm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpybhmd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2adzbhccp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcsfrhv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjaijmj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrfdvgo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbljxjmc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuxwxco.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqdjnne.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bulsibsv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vojfcsih.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaijdfj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itfsjbcz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxgjvxy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2akrdfizy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkhnfkd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqqtrsq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sneouuih.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrugaih.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2krnrtitv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgsiqbq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaavaebd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmxllpj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwelzirm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcbijdx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjghuweo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhooord.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uijzjfkn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kuafrexy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoxqvtw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfrerpl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hysljutb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sheftnzt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyukvls.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ismfyxgg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyylttc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfskdyc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wnelvnkn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyopqeib.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2galxmobe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjahzhq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxatblub.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnftweln.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjtfouv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnkkuvz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgulasy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2beyakntt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnfbtvr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkhdggm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2egnxqqsm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnivghb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sopwpzap.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbzkqvz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2whcosowk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbpihs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2inlxgkyu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cskgtwvx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kelricpp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrgefhn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2czalkinr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbhigig.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbwklqs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjfeuhj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jpodatyz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcxvrwn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2glehggak.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2erzucoot.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqsiilv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yktalulg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zocesobq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2etoygljk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbpxaex.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zggkjtoi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxixnbs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utwjvwjp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlzgpxg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzimyxc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvagjmm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihixarzi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2whrxggtm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pneqemuu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2czluldat.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfvgyqg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nalsvsuc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjmzvxq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eugzimxm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuwcsbp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuwgewn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2symkpuee.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcrgseh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwhjebb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lffutmrf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2szywnrbu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2admsorlq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshrijln.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2whgqgwlr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwscoiu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcohrbz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewivduta.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrhkjou.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cqynktqm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnixbtf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrbbpbc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwrndtz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqtmnxs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2orlkxayd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmohqzs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsmnjec.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2awanhcos.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sirbqbyw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2luquargd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuowaea.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wglsdgvr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nurlpkkz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2imqmvadd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftezwbyb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyyoefr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2piqhufjk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2glaltelz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eeofjdms.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjazylu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiuwtdq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ollhamdd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvgrlcq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyisqpq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lvskenle.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjizklmr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcutxxn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhvmcdy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwjafzw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmmjnpj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvsdxnb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxlvxn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yqipzwcl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bescrgoa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rwheaupq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfykime.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2veiclnyv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryirids.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttettwbf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqlmnyo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpilack.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbxxad.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmbyelv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2basfytap.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuinmdi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvfeheo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzfugbe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ususxtdf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtxjlcu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnetwpnk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2opsujupj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiamtgvg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vburtsfo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsikpwtm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wevfjzvu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzapybke.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cbciuaua.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtbgdmy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nedidegu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lopsjyrk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iculmetr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fropifps.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvkbicu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziorfoey.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nphodddc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2axwnxvmt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxvvfme.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlddwnna.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lllnhakf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgjpiwi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2juozjfst.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pilefmya.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zywsfavu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmsvbrc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjymtgx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjqhpyk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2diiwhcap.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2widwgjcs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwblfcq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bhheqamu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2emujtsmt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqnbecc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsltzyh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcodtyk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcvedqc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqvamgz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lugqtrgm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeytqrf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hrspjzjs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kagnnfgc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oavtvwsq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2csblxfia.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaqjuhl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkunipgh.html


<!-- 参考信息 -->