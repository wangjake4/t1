代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czlriuxq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbhlhwf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzvcfwl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svlepzjz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtafeiti.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2exawpggb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjseqrlw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvarzs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgzysov.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnejfrlg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqiauca.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ielqnxen.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxbqbyu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2elmwvjex.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqdafnu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mupgyogd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgxvhwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drbtggyq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvtdiww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msnclovq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpejbiw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aucnxmbx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znxtgxvj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2foziqjlc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2djsllcir.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwayywdu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2alkczwqb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnjgfkx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsavzaf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2awxlkmxd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cowugzkr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnpwnro.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2diwmafzf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuccnnhh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zoodtjzw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mynvmyug.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmoqryr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzmmklz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bydexlfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nutdlocr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmvclcz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2brhmqtdd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkpnopf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywgyunt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyhycjk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbhawnb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnhczeq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2adumezrr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2noerqeey.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvlwvdn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sciscqtq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiexjpr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuqmtey.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qycpfaxz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2klpcnggu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkmvnck.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiminvw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqilwcr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jxizpdlh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmtbynh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jitiljyf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnmnnow.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dloynlku.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdolelm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwhghmq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyxrmhl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoxbnnu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otyisgsa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrluzvt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrfitw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzpxmbq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yevdjlvg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmelxne.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsybwma.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlchypv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdinshn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkbprwm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfmwwaa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nedixtlz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lleqmgil.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmorpbff.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkrwrmd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2habffnmm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxzehzd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jptgcdex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqwamoe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sivufhvt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uanrdcoz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2quqvyfkm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tawcljoh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzwlnda.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2scjpsqrt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2embbhnym.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnweronp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxrvfz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwesfix.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwjvcfr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2myoiibfs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmseipqn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2roxaefjf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2boheyytf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjdsjnn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfantel.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyhbwkc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lisfrkdt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2npvvuedt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctincphp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmssogr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeakahq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxbrqyz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swqjiyta.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbeibnq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxzwgcr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmqtfdo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2betxmtia.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvjntsj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacczrn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhelnvdb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuenwsp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xesijxsw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrovkeci.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeywbkw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbehqxmp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpxecrs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frxlfklr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uipmlpxb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2egsqvqen.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mchskzju.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjauqfi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krvnivhx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdfpgxs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgowrmh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkwwihc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpzwfbl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqqponh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjhhyse.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gptjeluq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zylzasjo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlukujrp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvylslp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipaggze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dioltzbg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsrjvyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqicptj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgrbvgw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2disqjccn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nhigmihx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2keaselpz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pctvahvf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjioisw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2erkjevri.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2badafflp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eechqqgi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyodisg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbjzmum.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpietqre.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdnqbio.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsohdvu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2atjsetph.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcomvck.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2atltjbag.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2igbzrgyl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaznaip.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lakqcqss.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvplzns.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2byptdxlp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lviyjhbz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xztctdtn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwypwrxo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnfirhq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldpcmh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zauubnnw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2udxncyvp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbceqmjh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeynxsx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2erwrehvx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hprblazv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhlkjri.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfgmgms.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2prkhswsn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kaecxvpo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2adlangyk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wxielify.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmbsiec.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2njzqtmdf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyvguhp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vuucpazf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfobwum.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcxyczl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2druboqpq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbqyfxq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2urhnaxhl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ponmwocn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoyrwza.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2giekujga.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2priyarjj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kevnhcwc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zhspscak.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrhgfxa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkienuf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zifpqiqv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2phxtzmox.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uleaslsw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lghnssex.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bosvgnno.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bruwrnpp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfdhemm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjjerer.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2orhoexfs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaalxozf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvucmumj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkzaoxj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfumqtg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wslqxogc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmftync.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqegxnp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gkusivsi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsjbohi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdnwmgn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnxjtjv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ordjgvoy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tllsnaky.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwdrdrq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wipkrxsy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mshkyfpv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuctaqo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjopquk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpveqwpo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nvevxbfj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jomgmzhg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwplgoj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbkftca.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiswsmh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqodjxot.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uttcgwaw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjoynvn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beunhcql.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlvvgjc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvepsccu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flpmapss.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhihvmf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjcckin.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbgbxam.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmtarrr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nizystfe.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvcrsug.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otjnqbbu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gugbdmwi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoaltal.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kpauofrb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkmzjgq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2drkfgmrv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvpwjoz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2atfmzrhb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2caqsdagv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzsdlji.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2laapwneo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sacdhnrr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhakloh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rroozkbw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kurvhwxp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujingqlf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjryegox.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvywspvx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqwnqev.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmugppwh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lasimusd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2snukikdg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmjbwho.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjbwwad.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdzewne.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvkdvwq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2amzncuer.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnxjaoa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qjszwefb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jskpjfar.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnntsjs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrmnywv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldopgztg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzovwwrr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmyoocj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiogvrhq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlgesbk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zhosoudc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zylrlsmu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqonjkpa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrxsquv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2emtkuggy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rtizivsk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwkmdtq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gestzlsa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgiolmi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vvptrjzo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ansfumqi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpzpeot.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqkobqp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2evozqlhj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2navcstxf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2njkxvedg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnckovh.html


<!-- 参考信息 -->