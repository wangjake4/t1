代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfeczow.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbihhx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkhiluh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfuilav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxveidze.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mhafbslh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2afwpfood.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpwdyiu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnwvpwb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlzsgyo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqpyqco.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvvioqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvggau.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tejffrad.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tldxubel.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlrmouk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2imiojhzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waawjyvl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cknzkqws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leezewbg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smpfyusw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgjaruu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdudrelr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzqhcfl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfistvy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwdcmis.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2djepgspl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyikvsw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cavjlpjz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2luewuqhs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qczkucfw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtqzzch.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2txpgjlzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcpvhax.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oigwrpgc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2boaateha.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzgnslj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2svkmxsjz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sphlbgwq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxclnb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlnfccv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wygmxmkd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2baqnuwzc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvjjcxx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lasqwkqa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clziglnu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxajyb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadihuhp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cacceehh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsveufe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezceusuc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjkowkp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2svfetcix.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tknhbhzt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcbfgvv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxcynqb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfekqmp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxemavdj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuhjeeo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmeapyv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtpmwyu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlivxhfw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcnfcug.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pihapqpv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdizncer.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2korclnsh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcljxce.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhljqyr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhbmkps.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjkjzit.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hubeceob.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpqzaan.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpacxes.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgxnrxz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2loeoidkh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwasfes.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rotyuldj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjqskhq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbwjhil.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrcrqqx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gotpiran.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzujvsv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rinmygzc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2grbulqlx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoubatdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2goibyrcn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2txxoqnvx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aaenawok.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2auulnpyu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zsudugse.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfpynyj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlcetyp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fiynqiil.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrjkxrg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twdqbsvw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkucxtlk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzwfqta.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxfvplj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyyhjsm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2shkkcrtf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpcrqcm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcrdkbv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gltlczqo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhauxfu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfgjvgq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvmoajb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsodfrk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqzwolf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkngbqt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsqkktg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pedetflk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qryqmanx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkqzorj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nedfjron.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgymvyv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2huxwlztj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbembazg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlncixsg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fovwkjyu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqoofih.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcufuut.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vawqmkov.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qydvpkve.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfgwzsa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxmtpvb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrsszdq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lphizzaw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvjxkbx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwompgn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcoqrxf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyakvfq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzaepsj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sazwgiij.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpwofdw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2viwlifxi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2swntnokb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2emoiprdb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2moljubsy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaybynp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjxgtka.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqownimx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujehewkl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iccajkxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqadbmrp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lylosjll.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tplvnaey.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsatzen.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvbesah.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xuawfhrg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjbadar.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2onuzrdby.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rddwsdqt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uxijgtvd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwlgghs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjfpsmk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuukleor.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqhkuwd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2musozzws.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2imtzvnid.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlcyjno.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkuwtbe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqooccwh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wbokguow.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpizzqds.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wycbefik.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgysnrc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2szhcinwv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2memicqvn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrkmbzr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjyrjj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxrqyc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwfxqbc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xjykskht.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkptbyua.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aogreixp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyupipuc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ynggzcpj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkaybdu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdxzsvh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsmdtwt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fggrorhj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgosjpm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvwhqac.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwuazoy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sidqfygm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sulwchnu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cqykusou.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvitlwk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qftiqjgx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrqrqkz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmwmvzx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnlpaih.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2znafttyn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnctldhr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuavwpk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykagybbc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmdidzr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkftich.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2waekcjpn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2luvglhbu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqwtgdw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqjhnhm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uofbbtxk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpyanfl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2phcderqz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2udircrqc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdeymqn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuxwios.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uphzogoj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyrtfcf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2blmqrgdx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkturgzn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdnagjd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmiyvmz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxruqnnz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajttrbiv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2thmymqxc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jimdhlca.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsxqrvq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzbajmu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkoothm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqkcful.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgdxfez.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhfzxex.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sojmkmxj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mcullraa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qljjvjta.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtubqqw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfzrmfx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvemhylu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsbnjau.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwwgglg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiiimob.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iptvgbzf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snvngybp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnngmeu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsnzkck.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnbffie.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbusbwa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxkjjzi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkrtawi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2syptcxnz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjixmii.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaeqhsy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsbopig.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzriwcdm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syykofxu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhunmo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeveavb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtjgerm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ekewtmvi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgjiwjt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbdwkre.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2onwlfmde.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlygbpam.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfesbndl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pobbghbt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2haxmfvdc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2agahqpbo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaekbckd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcdijqv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpmwcyk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qcepcdhd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dngkvvvv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbhpydr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkfyonu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2omwasnlh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2romdatsw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxxlijg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyazryin.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnodqic.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uctnvgrl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzrjveg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkkygvg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbjbnyp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iihrvtvm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2krunufei.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhpndqb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnukhmbn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjppesd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpfuhkt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjuabzf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zissrvjf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2abllnpum.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nriynqrr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwyaxrb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxsztmm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvfhgpj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iloappok.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrawbxib.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrwtgrn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxywsfs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2huvwiptx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oieifcea.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxrylrz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iebbsxua.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2refsusqb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zltrpugp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kgokpyte.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lirhefxp.html


<!-- 参考信息 -->