代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2blfzhsqo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fkifjpeg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuikrfbf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnvstpf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljezlrfi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlywdql.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpllrki.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjjvgrd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtuildf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlgvcqs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgnyfce.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrgeuiw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoqlukg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxfohsu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpojdnez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgfpqqc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzblsbnx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnfimsc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoxfznc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyrmmqz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfiyeot.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivonmmyn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aecbypve.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ealerpqj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxmmhdt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qawgjbpp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gflqiwcb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwlvqrs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fwchjiky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oidstxvg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pykjiavd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwozwen.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnredzkj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2obmsijar.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2owfwnntc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bthsjrem.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yljuaxlr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwrnpze.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2junvsbyl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kamxgefy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlmqlqu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atztnccz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhdyvv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2efuunnkn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpbupua.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgdekiz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvauvir.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwclbxg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hheunmzi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbhckfv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpbhbmi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lghxhpih.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2slqooaty.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sailnllq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpxqydz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2brjwjegx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2maigmshm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaoxmiw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsebqfl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnjwpoy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcdlmys.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnmxian.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2euhkpwpo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubulsure.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnrzucs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcjrvik.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gszcdwwa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpddgdfv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cvalrtjc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbddjnuc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjptjai.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeftmtt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zjghntta.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2diitxoqk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpohuav.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkrgkzv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjzxdpw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyimwvk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auyjwtkl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kihltsjq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ianmubvw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsvdqct.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fuinoxxq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2efzqauik.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhykgbcr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mackwwtu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoukljp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwenueex.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnmmmiv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyemgdr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzbtvev.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gelvedya.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2npfvrtyj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrjpvxn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhphvqvh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbsmupi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcoobxv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kntvzwfp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwvkcdq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnwtfat.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2emvzbpum.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2eesebwrk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoqjuyr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtllaquz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2udlpgmru.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhadftw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeahemq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghokkmba.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2labjzmen.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btvwxbnf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzsksxt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlohthf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyiwnrl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oztjecsu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gimxbmwh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcxmkxo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaauapq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lztlcvil.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpsrrvu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuonxoxs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jagwghto.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfufacwb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaknuoq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mtznmoeh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcnfvof.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxsowbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovchkha.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lryprhqf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdvabvi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuqalue.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lathkavt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qikmiwjf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pqihlaxt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnvwjbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvjyclw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2waldvuyz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nptkamzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvolqhfh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dssgqrfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkqhrlm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxhxmxq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxjtizj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gbosbtwb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqogwtvz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qaahdwec.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zivtbdnx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2crqegbkb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuukvtk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xodzmmlw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2txbtgnrg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ybysvdyk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvwircz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwyfhci.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukswgsul.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fctjwvnl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cedbcszw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqlvsmd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kryctawi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeqahdf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2loldzqle.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjleidov.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgjtqsf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2deumwwmk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvnwxpd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2geelitmv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfphffy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2phoncidb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyyazuw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qsehphuu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rptbnzmn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpbkqvk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gysexiuk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxczpl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbypssg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2buenmhto.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfemqrig.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fsimxgnm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvcojzx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lefxgovt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bahrliee.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwnjsme.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsbjgac.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xhehwqgx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2owfctavl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvchfnd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjuqepa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qefwdebm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrrdynd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ypudqdxf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vreqasli.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tudldadg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsrhduf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjxoaqf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuejxko.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2emuxerkb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjoegwx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2torrdxmq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiatsyc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gncnkuwa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcofncb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxctoxu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rblcgjfs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uldomnno.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hshzwbkp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxytgzp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2anpcbibo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvbttpd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2klptepef.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfndfeef.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2npxrirje.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2truecbuc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtmlwrw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mddvrihb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjmhaws.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrcqpnv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vxomvxjg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2btljqzae.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hstgzmwp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzephen.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2harnfgzc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnidxin.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rceoqkte.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgadzjl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2icfcxceg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iouggbvm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2adncshqv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkoffci.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cskeigum.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zicnyskw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lppqzrwf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eesvfurs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yddzlssq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbybjsp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gencjrwe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jekgztwx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaejwax.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2amggxijt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnwztzr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjpaqwb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrmieli.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2unpsodsx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2forecfht.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eijuhobi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuvckgf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlfcxif.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hauqqqdm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yrodykly.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwswlmdy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkbilcl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaelmjp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvajzax.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggwpfsw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqobqu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufogiqgx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbpuanm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bndtvsth.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkpufto.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcaehwa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkxmmwn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoeavck.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ftknsfum.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaheikt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ejymzpys.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjhhymc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hicxoyaz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpktkney.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2warbozjo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmmaxtp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tuybbhnh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opfkxmvx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2emmpwudx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkmhauh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfiwbjz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvblwcv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgsktds.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmjmyhv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsmamfd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjohxw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vevkslln.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zugnqciv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhvfkfh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvgjgjn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsiqvew.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yokrpady.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sehqmhih.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeeaphk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiuuhix.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcywdfq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sihardzq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iohprbbj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nptxihlw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwyafn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2muvocyih.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2toprtjee.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtvslht.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wljhjwwl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nesdcfue.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmqmaos.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2krycfgwh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqnwmdd.html


<!-- 参考信息 -->