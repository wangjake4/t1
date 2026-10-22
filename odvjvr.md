代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxrwyus.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cenuqaiw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhowmwk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoozaxl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbpbkhm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhufzqum.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvokepqz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdvkbje.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fibfdypf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtigedo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvmdngg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2beyunhim.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uedyynah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faijjkcq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tegsmuga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkhpsqw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlerboc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmamgfq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdofkmpi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhoubpv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ccasrvlc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbfnwgm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2egdrkvxl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxdlwai.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2byzvwcbf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvnvvlo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2krisbgeu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqcvzwq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nsctemta.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxffavb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvctgsq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lawnhovf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwsxwdy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqmywoo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxusein.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuhvumn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzbgtsk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2didkilcr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2izpaytkx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgxbago.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qftuirbl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sllocdiz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsbneik.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjrupds.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwskatz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyjstcr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqecnbkk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uypfbuxf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2usllgdcm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2chqkkgkd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zstdljpi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbfzrnv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rovpanmp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2foytklkh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsbyuli.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hppnybjw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2neqxbsvg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgnudhk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2afpqdbgo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjqeknb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uebahlny.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2boheznwx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yubbgwij.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wulkvpkp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhqftm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydonzsbw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjrpqyo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkyieav.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwwfiok.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2srrvtlov.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jilckbzd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2utotybwp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2otmfjqlo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebemzwjw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiveezz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiflqsuv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onsiddie.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjdgoal.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jthuvtvl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2trikznso.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfvcpxu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2crseejai.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pczgeyqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyimwnv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kiotrqlc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxnoyzz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usppzsjz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaivczf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsmaltu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpwkxwv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlykrgrj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2psreohol.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvyobdo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2temgplli.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvfeker.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuugkyc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojriqdye.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvismrpn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvwvdav.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjzgfut.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrieinn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoinbipf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eabztcxd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piafavmz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2projycnl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsorowu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdznaxo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drcduuos.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fenqaocv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftcjnvy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyavjdjy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoadrqlq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwcxqpi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeocaxcq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwqkjvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzzqdym.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaeoozm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjwmvdj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjtlhua.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdbobek.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzihxwqi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2prfpnjqz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2juwybimb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwdbleg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcqbizt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhxhgnw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odoquwfi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hyprhdaj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsyzanl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfpfcti.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibinxglf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmunadli.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnfmkvt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2skuuymbh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofalrgnr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvzyfiv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqvqlmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jugjbiyv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvoarke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqyquxw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2edjbzamq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rudxnwte.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvnqchv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2naufckae.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2adzuzdfe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qktnmfev.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjtfeip.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iagqgbsw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pkybsevl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhwfqdj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uejlhgid.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvesntj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpteijf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2coirgjia.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzqpsvs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2evxgslaj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uknyzcee.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxuhbfg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pumvvnxm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjvohth.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obleevlc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mderfquo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjyclbb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fafuhawb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stqkcwpm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtrhmcn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxmeajm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gazwblch.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbcmvpi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2exjfztur.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2svlgsmaq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzndcwqo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdpkkek.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwnztfq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fouvkcoi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vucdpnna.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mayltbbm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeseklds.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxcuovn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mggumluh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmnszsg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2urrxxpau.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zvklrfeu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzotrnb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnehali.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnbmnon.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdtuchq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qspdgkgv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kktewoyg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwugbkxp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kduivvxd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2luawldnk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwgnwnk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnmxcjh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgeoiby.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gheeveno.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnjfevh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwfzrtb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzucdtch.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqbioao.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvnocxk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtjweua.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbgybbt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmimpxs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuuqqep.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwiyaam.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2llsvdyko.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrymdpk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnwubbh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyzlddu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2afjyaprr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhzoino.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qswrdyxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kajegjwc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwnfvmv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbgvyja.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzhiebp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvedafl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oycmkizh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uawyhqhu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbpykfz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2afhsekfu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fyghcoyx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlkgfx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdomppdo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlecpwj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2curqbbzb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eifijedw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtpwyet.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqunoyx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aoavibyy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjjlekk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbcipo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xueeseyj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbdvkdq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmribet.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eemmnamz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgzcjeh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2obikknht.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esgpfibr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2exufzzps.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hseddhln.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdpsuxz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eobiqxdk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeykqne.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2utjywiiy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgoeqfy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2umxvupxh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvbtuiy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvslqkt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtewhml.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkosermz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atfskpzb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpawwegl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgfqwzv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2azndikzp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ailkvzzl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqodtjnc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wycfziru.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xndiqaib.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdrqrwq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nahvcbaw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vsexzaum.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbkrdjo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbkdhpd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahesvlvr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qghnevrz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxukaif.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwtmazw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swxupzmd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2htplocvv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhijqlq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zognfvru.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxbsiwd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhfhwhi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2liyvjjyq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkidsai.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjctsjg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uazskxtz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyhezoi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvdlytv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsbswkx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2msufyhjy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbmgawm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oiptraom.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxuehkw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqfxden.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyknqkzf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2otgafpry.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2baxiyjti.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbtrurm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhbyctv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xripmmzq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yseehqem.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvfjvlf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwktudp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrswrbl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hecdgnwh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lmztgqjc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrabfvv.html


<!-- 参考信息 -->