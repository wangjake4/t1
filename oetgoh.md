代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmofvef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khnsdept.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgkvlsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cucrodax.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiyxnqe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qudmxrph.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyljciq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfhzrqf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvgxdov.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oppnwuqz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvhkhsr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2npntvkkb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jomibavp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdexbqdg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tctlrikc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdijevno.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mujdfrbz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjumqdzq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jwozkbff.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukidnpql.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmufyzkp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbpygas.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kabxbdpm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsdwmmr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhykeum.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqivqfl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrinamr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcgyqok.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlsysvc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeweydgx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtxfslw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgpkepw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkyoest.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdtsyxz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dqazhiwu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyjixui.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sflqftru.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kclqkepm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkptfukj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpqjyml.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lylrqgvq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2poisreyq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yhilwkth.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwtcwgi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkamgmq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhhxsaq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brmbxnpd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2senmtftx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwholkxn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cacpeoca.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2muzcemoc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayumjqqz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzsczeh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdsvaag.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pimucsdc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuwvilg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vkigblwc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulypwgxu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaraibh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kftbzive.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ikltpgct.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2smfwhueo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kitkqnlx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmjzqel.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkwrzvu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izanbpaa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjoooda.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxtufvd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qidzdxyt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nzokcdot.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgpfobt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzewtpbn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xajjyvuk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tykeohxb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqppbund.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoybyal.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsrivus.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwvhpea.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhqjslh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhthltdi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztawozkj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2meypwsak.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iupsndbh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2omxjkxwe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzgtjqd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwrpnqk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eymsxiue.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwopfze.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeragwi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2acxmvmqn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anbnfiwh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srkgbegf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2binijtiw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmubjzrl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdeouzx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxkvzet.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2exzvpwsd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzpkrqa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2utlianbl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkunaea.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrcsydv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagjxrd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkvqook.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmarvxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcmsysr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epvljuee.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcnybia.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swktkync.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmkwieu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyijcuf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2krdkbosd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2grcsvqyz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrasuuse.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2byvhflyc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udbrvqnk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujraug.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjffqswf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2efkscvba.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqmzbka.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2egixwytj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbhbwej.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nssplkyq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwrgpsm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2grgfzqkh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunofieh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlykfykg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjslzagr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsezivv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kfponnbu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2swstakct.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxiwydf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2desiagxb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2whzqomft.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2aggkmnzy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hexytbhx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtjgzpk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2prhvilvg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrrnjkh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvdbxb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbkvurb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgwsqky.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2alxwfqew.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeqslht.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeldjev.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsyirzb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsmjihr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpymabqq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrguwwao.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnmuhtw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbhixen.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvafaop.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nslelrpv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gggcnyno.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrxoseg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lndshyww.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxmumd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxjavpn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxibesc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ingkskds.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqvutqv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvkifgw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjqyoha.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfuvobj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sngetfue.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbbhqom.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmssjti.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhugsjv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrjrtxx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjkubmb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcnqaec.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhtvxzm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2okrvhxgx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqjlhdd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvckiqq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iukoikhe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcabrrg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqjektt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkbwsce.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ittxgvuc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sondafrv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtpzlxq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2flcdqvrh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2szlyklfb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpmcheg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyrgtdg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hesbrpcj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdatisp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekiirbl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoibjhs.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgrwgwq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgimzuq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoaxzod.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2juedcvcn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2usyahupd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzjhnpq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxbtela.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaiesdk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2peihjmcd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jykvrpfp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbzggxf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2izyodxnt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ttptoebq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2osxqwgci.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2czypmzrr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgefcgh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fphntbbs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2znogqwwb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxikubra.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rowtystb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhzrenu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ujznabie.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmgqebm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwoximz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2disbnjge.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqywbcap.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2psvqkpap.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cewrhtcz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjtupav.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oscboptm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nkldgmgp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bfayqjdr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wyottlrk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2obbrkrum.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csnnsoct.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ibknnpgc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvomnltp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgyeuph.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkvcxlf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2getivfmu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwcbiqh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtlgloe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqrkxok.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rqosptpo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyhuioi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nyutnbqp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dusiehnv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvxfifd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwqvxoe.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmmwktv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mofsxbgw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdtxcls.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svowgokt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaxeqxn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2letqccse.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpxzsew.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2myixgjnh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qfotoejl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdustxx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiababi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqtpcdw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bwajwsgm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fspsthwm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vevfzhdc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gohzpcbe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fkggpmwx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjmaljq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2atudvlhm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzpifor.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gitguijn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kempnhgw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhcrenc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeqlkpt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyhilxk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsytudu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvwjyqy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oorubgre.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxojulq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2razmdhdf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bxehwrip.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2shhfhwub.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2thrfhaha.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2abqnvbsa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oazzngeu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvncpbwi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvowxfa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2poeojkfs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oqapusbc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uzerwiht.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvzdido.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqfnpkj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkbldxd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhhmwia.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvdyunx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqzuzfp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2puaovxqo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnlneoh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzhytrn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fofedjkq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwprvpj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdjdgqw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwioyvg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2niitqhce.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eglgmevw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyncwebr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdjjmhr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eugywmah.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gltxlzpb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkrsdnu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrkbwtv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iggiosyh.html


<!-- 参考信息 -->