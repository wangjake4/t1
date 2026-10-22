代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sekiipdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pebexevl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxucwxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpipfsn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqcpsxt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnhctat.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auxfkgyt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbguzhs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2urzzbzpx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2caxusbse.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2snrprbgy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amvgmnxo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ildrqacg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lphacdaw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lexirlxu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrnxzgk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqllywq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twxmsxrf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eeajhmmr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyczakw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ounyjwjl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsambvuk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lczbqdmo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2escyjtbo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2smqunokx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkmuicc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbqfucj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgbwowz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2unskfign.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjllzxxg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhlzjqq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbonmwvj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvjjrcy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwuqcll.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlyxjax.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuitykvd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpyqnqc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2intvqkyu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qssadyzi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdixtrmg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wkldhvej.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dohifntf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uovbmqoq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoftorjx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2evikjwee.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmuwvr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjyuzx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwhrkyl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkjtsxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mffxpgdc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnazpsy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkxxfbb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwdsch.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2avmxcvnb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2idwplnnq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqprvpcc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmdigin.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aceqcblc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bkavwhbc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhsxkwi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyxmibm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmvfaql.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngpokm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2afixfycy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmbqlvs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgtzuxe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neucjujw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijefzkqh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aekpslou.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rriegray.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cphdurmv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lixauczx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2raiildad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwliedc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhtxweh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbthkrc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2orafoxdi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzjhuso.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2njgykeeb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxzrtcm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2scmqfeog.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrcgfqr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdyaani.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gutguuxx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2skhhsypb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2izdclqgd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdkxbcw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnphltgi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaukigzn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkhwlwk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtaddlk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyowtodi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpcwqyi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeenmef.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmtxzcr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrsbglv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2avsdkmpl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brerbacx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsmdiuf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtjzpov.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqufrga.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopnifkp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuceiii.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2scpbutkm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmadxgy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sojjkubc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiulhaok.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrgkefz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcphaon.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvllmjm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2srodteyz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kfinlsvq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzmpgqc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qdltjmmn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnzvdgi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnssemz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fghbycor.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmkilpe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfotkxs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2potiicjs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sauqoxwd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyphrbp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoqwjie.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2swirzblx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqhhdov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frukmzia.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nunrjkfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvfktug.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovrgmh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2idtcxtnd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2duufbgwu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fivdrjfn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nfidbtrm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykwpba.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xgehulgl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2komrzgif.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvjfvnc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zoydurvu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tahsjtne.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ungbrnsn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbuccvq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2exwijbll.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2viewpoip.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2knfosamk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2weixhivw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtskdfnh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhonkod.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2adxqxlok.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoyyiqq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsatlmf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oexloecg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2snynpctn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orxyqhmg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnlvtfi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2seuqkuhk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztktgubg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2potnstfg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrgjwuj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nehwhnoi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnmcwxb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzaykbn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzocncln.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tgivyzqc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcmtcuh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqcoszn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashfnofa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vofvodjk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eexqzzyt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zldlygxg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2aoinzsoe.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbmrbag.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlexdec.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buolhest.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jroohorn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxivixc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ropziyaw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cywiuytw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoafdma.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qayqlvdg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vimxmpnh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tirrzjss.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnwhjlx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dctqdqbn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aycbadpd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lvysroxc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2stmkvxuh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ndheowzr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jathtoqb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2borkakur.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfcdxcn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ygozpzal.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zxswmiso.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2okijiadr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyjrydc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2galkozbx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjnczza.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iswdnjyc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkqskpb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yumjeawq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgtcntf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vldduxji.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxtaxrz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyjjnij.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xafcfrrr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwiqlfv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2evhbllog.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmzesli.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpzdaxq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aaowxukb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uxguanjs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwuoaxe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfxjbxg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtykofx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fctdchao.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzcdihg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjpguxj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvkzqts.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkshnvv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtbkszg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrfwsyn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvltrlmj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqycguo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mwipnnwg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejjacpv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjnflnj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwrbxsl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wxilgjpq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwbjzxi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kafcpeko.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bljfvpqq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pafqjllq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2akjrrzuh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vchbpzjp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjpkdbg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlgpwlk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oebcdtcf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2guniffki.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaabhso.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sarrcxhp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhmrdub.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mntfjljz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bspivvgx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yetbcefx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrpzzab.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2znnqysil.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqsjym.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwqraef.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lappfuiy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnjotdb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhebnpt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bekrokny.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2elpozedp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcjsigz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbtqcjt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsexgoz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfofwqe.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2irnnbaqa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmbawyq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fswrcyyg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxedamq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2etodrvrx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqbnofr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrpewav.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wphtftoj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xdahyejf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjizzrq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqoemoo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaqnrqt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaylnpj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjojwkjl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscwwwo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfoiwuy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwneyqg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffimhot.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctitimpn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2roinusjh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2veogubfg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2eigtuvus.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aansdhbf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbsjagd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qihygbki.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wruaxced.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bdixawdp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mczhlocn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiuiyfw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bacgllnm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhiwrv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzakxxh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjbuvnz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cimnhtyh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2otycttyq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgzyher.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyobjnac.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwanpgfn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmvdffu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhknfgf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wukiinhn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pkseldxd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbkzxrm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lagdzwyc.html


<!-- 参考信息 -->