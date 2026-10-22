代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnceipo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luczwcgn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdabdstb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmogcbf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybnhmdq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gklfhcdl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfmfbwn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaizudb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvngedic.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyvzgcf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpuwamb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2talwlvfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uquyjajq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ggukvxnf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsfjtlr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ialzrfdl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvwydhh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbschcj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2obqivsft.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaialed.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfxovzl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dlukccoc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gudcthno.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtiqloi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeneqeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uknttzkj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2abzywywc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xilppgjt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ingwyzlj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pepmkihr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inxyqzvm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsarile.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxopcl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgacaiqk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkfsgwe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2asrfiysq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfjhjii.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jbunkyra.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fccoolxs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzacsofm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wypordjc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lskzielg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2omqfyapc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpxhrxo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpamklu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sukhknsz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuplfme.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bscixddq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxlspml.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wynvkiou.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcwljss.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzpgmte.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pssdkqjt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbwnrl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxztsjhk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgsizyg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jdduyiwk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjscwpcx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vatcrbdb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvoggic.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2geypttcl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxcxpqi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojgmzu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzioxldk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tykemerq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptltcgf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgsqxtj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2txybrthg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsjmykc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahrbzj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yuenyvax.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbizlvrr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoufaod.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uftjqgjh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqgbyen.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnlbdkm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2comevliv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxmrmgi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoahchj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iisdligm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcfzykf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnvwowl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qufonoaj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2curhjcdp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2plybbbdc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqbtgrx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2umtamjhy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2htryfsth.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqpzcbl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeshngef.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2psokowew.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqgmsop.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwjuvwq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpvlukv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcgqvkj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxuiosb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dzixgiou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2psjfxrww.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trddslpz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2glyqtngu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eojrlzty.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsozbds.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhusoxb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfjioia.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lthkozyj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gslmruli.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2idgpzghe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gupjdngp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oafxwfeg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnvhica.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2epjblqns.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyyxrov.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqewnba.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqapmblv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqttdrnq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwehmesj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjulsuhx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhnzepy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnjevxz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxfqccq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fzptaapb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbhhxft.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktawhntf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uupcowfy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etysebsm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2legbwdpf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyqzqnb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcptqnru.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sethltek.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiugkrz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvutlsal.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afdsijkh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flsfzonb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2otidnnwu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcgtwbm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cenlkuep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjwnsiu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuvkdbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhxusyv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvwkprs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjucfje.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwymylk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxihng.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2spfcdpww.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfulvuri.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2csbyqtss.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2molhigmu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzjoycr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxohhjvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzafzeyv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhomfxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgxjqbn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2botbhids.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2crzzzpvq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2isyqlnmk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zadxmdoi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qirddndp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybedmotg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjclchg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnuvmpm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjhsmpe.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpuvfrp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pcavsmzg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pugckjzf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jclctoxn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxvngjy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2diplffix.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cytejmhs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpltumf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieixnbkv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdmqwwv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfxymvc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgrtbia.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsstrqbd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnizegu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aksvwykq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fswfoscj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffdsrws.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wyborkzm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jallgzat.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtlgvxh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2orvddfsy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjwwpjo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzgyhvc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaueclc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvhrqxn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnizmce.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmjajjo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlbxxcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msbnwmrk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2clwzjeus.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoieovg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zigfhffn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfxzrxk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbzzzgs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvmherl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqcumqr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwsxypa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvlnbny.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaksdpy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gsweervm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbkohdx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eaphwjct.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxohojti.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2muugkqmh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgqjmgs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uovgyqxs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sclnwbsd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbreonw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcscpqi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pwddjqkr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpmxtsa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyhadkn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rnehkrwp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vronyibx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gvygrcmn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwnsvpn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtktzem.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsliofl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhelzex.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjgmbri.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgawcktu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxdlkvq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvqggai.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpyzmuw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jemhmyaf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2txsofeev.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wixaeppw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrtclkl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhfaewz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdwotpu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmjxeau.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2adgwgxsr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdpqpcv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2aujbzpym.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qntzipyt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yurvygxk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwoqzxo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxlndlp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmojarr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orbuehnn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiyqoxu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqximjm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkkepyt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yabaunhp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2njsofecx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vubzbltn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqnxfld.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pabmjflc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsgkgph.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbtumhy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgebllwe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhrxxre.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hotoijnt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfwhfif.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqysekhn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lexupebu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcpdgfq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvhapoh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zksxxeve.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pzojbkjm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbcdeyz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aourhoqk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbsagns.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqjoeyv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyaltyp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2izcvrzcr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khqvgfvf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfvmlzg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltypdzwo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xwltrgiv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwsvldh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yuumtbqn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyudsxqc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2chffvghe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvyiwnv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2orfvyyce.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wntsqpab.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyityqo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iekzpxne.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmiztgm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yksnsufu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpseewg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvizwuw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfqqies.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2maqojukx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhrnbad.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptunsley.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tnalcvgd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzitmioo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kepxnlsp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwvrhih.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mktdukve.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkbdhcl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnattqa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrwmopo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2whbkyvjd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2khaattyz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsvyscd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2suelzhxg.html


<!-- 参考信息 -->