代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyshqpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzblegx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikliehsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrwybug.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwgrdfz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfmmecq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2elujqind.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tywfjfth.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbfgwiv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbjtxpv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnxnmgp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxnujma.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2awqupfps.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgwxgpr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmnxlhs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoxsbum.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhykmfq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkesyck.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaqrwns.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxmlrhn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzikebr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kppbqqau.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfvinox.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjutygwb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2efcgvmzb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2abjwqwtr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yghkrhdz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkijqoid.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyaslra.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aihagtsn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmoqeur.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpbxpcl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwdrmnz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwgymv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdnwqxn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqfafpa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpzwpid.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awayrkwn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzvclrs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwcjfsj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2htrfaong.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywybxnbx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tressecl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sexwmjwe.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zlljdbpy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnjwcsv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwudxqec.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2neskllvz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yigbsuqi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnzfhcy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcgbxsc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxncbamm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyzujmh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlttorqp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qziyrhnm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctyhgnf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2neauuxvi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvncvvg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyttdfm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2asongdtz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hliezfgz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwtwgsa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2njzwclvt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjnrscp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utuxturj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2csexqhhq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuwuyhe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqfxgy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlurivfc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2szenvxgo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2viiviubs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhvvsgq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxovztd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gyctxhyv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbykbmk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iowdhspv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tiovjipy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lofbkyxn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrwfcxq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2raepgejy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ylebvfdy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpnelgj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtibzgi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyehgit.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sayyhpzw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpitdgzl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbkqiku.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqvypvq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2noakfhjz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tioktvos.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvalubf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsflohqm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmufdgj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2memhybyn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lnedisgt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdewcnn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbokle.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvwccap.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kukerfws.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkedzxtd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoftnvvr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcnlqtg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeprwwf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuapwmf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewthyinb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2geszbgag.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2faaidzoz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itihbewm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjmltqx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbqixtw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2drxjhxev.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2unbiqaaf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqztzik.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2utktkhoh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpivqda.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ervbjjtl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifowwebp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fctfnvso.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tilxfucv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgcnogj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvngoczr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjxvbln.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzjezal.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wozvwvwg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrafzioo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyexdsf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvsbdit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amzxbljn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppryeved.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zbehadkn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2edympwky.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjigyuy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjwqtmx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhndrazr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdurnhx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bidcqyvj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2djebfsae.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2acpsyugr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twjjwdik.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhfmkuo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxskjku.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzjenop.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yudubgjc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnlfmxw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxquowh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlimgqnr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xuahdzkn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnxbpos.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2htjcahhv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtcxobn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2piodvlfg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egpeyded.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzttrgka.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mailmpsh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2euzqnzse.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwgrbve.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzepeop.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxbcbce.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvrjhqk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2crxcxgiu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcdsxit.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxjlnod.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjeptee.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlalrdzb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbfjcji.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzjkts.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xxikrrix.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgzfzhp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjddqnz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nfirmjhu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fafqsbgh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdchfpb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsgrxwk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fsikvcvx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfwwiqd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnohxjsn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbgtsjy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pspdbsyc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oapqcvaq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaspbnh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yadgmepw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtxbjbl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmdthij.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqivsgo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2glahtqkn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfslxtm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpsgtuz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxxeddh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqymjvv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cognmbrm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gngoutcl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgcqwif.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfxbblj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrdwnnp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jpetsrac.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2odalmkel.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyijnsz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxyiagr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ilopefly.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztibpsob.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pwohdntq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgvsuly.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2obuhakie.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sitbhjjm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dchzxxyd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmtwzrs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjgpvrn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcowohsn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2krngvrxr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2penkmwun.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyzrtih.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzjkrhc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2agsvhppu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfzjjmu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdohdsc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrrhjfr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wprniilt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaljiaw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgocceo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpovyqy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwnucrc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ycizlvki.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2baskwwnb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnjjwhk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2agvnyrvn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2obmktzbt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmezsyq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwgexb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtzzkwu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iosaccea.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qevbqhhs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hguustsn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkhiste.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2imszevhg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfaubcp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2iksdtwtf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcxssmb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqgvhki.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjibsyy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kemcdbro.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjoldkp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrcflfv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ichkdeur.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgnqegk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxpqkxd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tocvjyvz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2atopkmet.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tetslybn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2efcigdgf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrsnclr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zlksjanp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2psidxhkz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuurnfj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldendywm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2esdfmnkh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoxvwjt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmwmsrq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkojglj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcpckof.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhccytw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmormey.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sljjhmaf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alkxzpwq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2svbwksja.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ethtcbub.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmuotqb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eublkdoy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcaibzl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsqdyfd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mofartiv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwkcvci.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmitqnl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qyivlvan.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlfdfpu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfrmsrq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqxddyk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rsemkcpt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bclkarzw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdbbttt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbsczup.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2azbjqvag.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pststtmz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbkoeps.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqxlivq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnktmuq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiiixtr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwmgbk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mvklxzuq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjzmhxy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uojdjufq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lgehpejz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmumrtrx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ajreaoao.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2anwxofpw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvbnkkc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2egwgfkqz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2opplnamw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjiidms.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eidoimvq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2htcuojaa.html


<!-- 参考信息 -->