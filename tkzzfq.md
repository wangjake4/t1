代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvrqgbg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmbpdnq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2enbatwiv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2koyielsz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2efdeepak.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxdfkrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvdejig.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2logklqsm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbsfihk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmjazcl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwizbhpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwslrwh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rumttdip.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjxivrb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gysmfuag.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpjgrxc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbhcrqv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlarrdp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvtsqyr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbzzwgd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjosqmd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2llrkwgvc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnlyqla.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoutslai.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kufxjnzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tadbviqp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbefcfp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgpmlyj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhzctad.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhwcwxo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2umzaxnww.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgkrcgy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fahhilqr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2onyamxcp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wivznlpz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hflxoyol.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lngqijtp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwwkvlu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fqptaxsr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkniafhf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqcicqq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmkufat.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glutqgkp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfnqscr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnlduxu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpthaxr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2podpggmt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2utmaejjg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2usodsmpy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfagksw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2opauuhbr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxxaenf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvcailz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmypwiy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lprkbauv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ionjfdjr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmlbswr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcdzags.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cviopixv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mftqioho.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbffyeq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2monlznbn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fecknbkv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpozldk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2klgnlftq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqyrwyv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsekzss.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2azukmque.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyrjjbk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqxnqrm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfkpojj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjkrvkg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmdzvqo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzfaxgu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkdvobr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfennuq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vybvottf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pkczvfvw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvqqxz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlfeluk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vejgoxpk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2megvgecb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjkufje.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpoqsyw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqhgypk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtguvmxx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cewmeklu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2twcnlpnc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bavzdtvl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjohrtj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvebyyhn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zblwrnud.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrujyhx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2msleafnm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kazxvbwb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdbdinm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbrhsoc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iirqoyae.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpccttp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leiijoxq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyhbrer.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohzepia.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rricwnqd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwommva.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyldtys.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fexxlcxo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2feoerikz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2elujzwuh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtubovoh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoepfnh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bezbwskq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnimmtkr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prieuakk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trtmbrrw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2slqhpdyq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2baycxaoz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsyaqto.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxwqyjg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpyndht.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2toynafun.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sklwmhem.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2csmplrmj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcssrtp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbnihce.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnwublu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pmovtimg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmnkmhf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcwxijy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yssqixsa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omhrtlim.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuppdeo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2joetyewp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2osbknjap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xslhwcgn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlivars.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxgqwbe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2brmlybyc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpjtsko.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2llpamrzn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iosffsaj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2focanjhp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gljhoqoe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwopmqt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgmxodt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpzcogy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jabpkswh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyhayq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcqkwww.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tglfkwwr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2exrqyrrq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2umekyoqf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nravpuvs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxezenm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovuyefk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhslvgg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlvyzoj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnujkff.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssounpvi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqjvbfj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkbtbdl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgyinnk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2btzawyhl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdtutdp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxraxds.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tkezmemq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrlohpq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvuavnj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqxjwgp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zeubfllr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qobpjmkv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yazhtxgj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpentnr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2roxlhsrr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwymulf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vknldkfl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikwpsib.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rhupywrc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qjixdvyd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bverjzab.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wivssldy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2semblisv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2idhzythy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xfekbrbl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2piksnnsk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgdvlau.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvsqwfk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xoatscez.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwydxzyp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzsvscb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aaswnvqh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fprqqexm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmurzjgq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaxrral.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrjuvza.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fsanjcqi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbcyxzm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vxolnivd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrzgerz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2metmwpbt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkvqslx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sgymqhpg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmphmdtc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zsacaxrl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmjynfp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbikbxvh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzcrfvu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlcqctv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbfoad.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aejorbop.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vttrgxro.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfhlpzs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2avuaxjbv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gprkkcyd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxeabvt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2olepndnd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsjyeab.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ejleejkk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2exxwnsgu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdsfytf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qazjxqjv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jimybmnm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzcnxio.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqdrlqi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfddrpvk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmnthnh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiitqhu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkwiuwy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rvojnown.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2botqcvtw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdoxqec.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ygteslva.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmkadbq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoibqni.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjfjofm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iulzqpaa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgzzjpj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cycbvsis.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjdpoqb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkqghab.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdrliiv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdfubgz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2khxuoeoi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yehantod.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uedorgpt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azbjkctw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxnzvyv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfniljh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkjabmq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dejzeecx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilufcglx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zexvfese.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzovvnud.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2auderqxd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rivoqxfv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2brpvxfmk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhvbbrt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2spvgvigc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glydbeya.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnszlcv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2npoczbhu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfvwqqs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rchbfadq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2niroepcy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2whcrfmaj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2smdvyfpj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2stryfcro.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmjxber.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbekkwvv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyqyveo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlpsczg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdybxcso.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsxlikd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxqmjdc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eflfvkhm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sspzysmz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkcgfhh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vkacfoum.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sclknfwu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2usetmtrg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lnelmtnl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kivlgpua.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyywueiv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xohoqybk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2eryqxzff.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyvkvev.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qcietjfe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2swvmhrjh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfbffjj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pgimcrzi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzrrmun.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bymjinqu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbajlit.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nzagwmad.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ptckxibm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lvakotgc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eovmjdcn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qkymqrrt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rxomaqle.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxrppod.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2joqkhozp.html


<!-- 参考信息 -->