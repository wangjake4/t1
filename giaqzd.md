代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmlneeo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdeszwp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwatizw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2poapokmk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcfpkbh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkuxeet.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqycdi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2djdooqaj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usraqlne.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnfpzh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdwngzf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mwydiorl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2epbtcxag.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwzidlo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxbyyrk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bicrndds.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woadwpkv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaikdtw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2abmgiqcq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eecwftuh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevckkbk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hghqbzam.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gliplirc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2flykwnxi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrysitu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuteekc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjqgrey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmutnnff.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psymdnsw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyznkvy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yljokltg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pntxsvwj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2khyxwuyq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdodslm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2puhouypd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmgstnp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjzyahz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiaevrm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmyyisf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2isfwfzuk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pojvncxx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mysjvlkf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sybtcmvc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2btsjlsrl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxzntai.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoebjsy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxcwhqj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2exdfhhiw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdnjvwb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhjhfka.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2alwqcnwe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vckhywhf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mebkbkml.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbizomeh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qivjkftt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxskabb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2auvflgid.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiazduj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2peluiewy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblqxcn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2admqqzoz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hemwxhtg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vblglbjr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2igfzydle.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pinhitzg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrzdtym.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qkssxxcl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjxkpgd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaadnwx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwoupul.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhasnez.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xknoitgr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhghhfq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgoknnm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gblwltcw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjlhajp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wnijoyqh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2isocmywz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aepetghm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlxcera.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzazcgp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzejosid.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ldghgzrh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2avuasxtv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uflgrtli.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqyxhbn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrpupxr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmafrvly.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzinqmio.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kphroaez.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2umrhfakb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtuyjyu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcznsgc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcrvkxw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2txzspygo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hodrvybh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzwscng.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imktefxc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrorzou.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxmzjop.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtdtnnj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdylhphk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwsehev.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvphpayb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjixxpn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqmpoeo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqqhcox.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfulptmw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsbyhzb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyptewi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bahppxqx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyexzeey.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrfwkek.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoiltdc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuenmqj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxtbxix.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhfnfpb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkxfzmv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpmlnfd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoneznv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2boqpjgbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwnsaym.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqeokmw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdlfmvv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2saphuqxu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwtdkip.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhovuyuf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyrjeoc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjbnapu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrrwdme.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kelakwix.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnldmsf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2caoyzbtg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2epufekdn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxancbrq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2owzmnzlo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zioxkgfn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvdtnae.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxawfzu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xpytamfm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2opcfwwum.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjcyelx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kritfrdu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvrrnku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2axxcctgb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vuumlkpz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeizflkj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qezrnybg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtupzbtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhlunjm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfyldar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buuiuaqz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmlxhvp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhomrup.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eitttdzj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnfefco.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lhapwxyt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoxnzjy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xksjsfke.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwsllrv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyatzaep.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrkevfs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwdzbyg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2suoibptc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iitwqbyh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2syuanigb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhddloo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdcxurx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ksofywwz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzrebik.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmremmy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbldlgm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgromhag.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fudrkpgt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2poduvfri.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuyaxcl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2omocxzfz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoormdn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aaodngek.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwpwmdt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqpcwnv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtqkeru.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmoiefn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aonagkno.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwiood.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2neyycalh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgtzqrr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2drtoarez.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pohzczua.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwzwktz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yymqbbsu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhbmcpu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tumbjnjn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2srkjkazs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrgpprc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsagqnws.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxufqpat.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhmafvh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mworwkmb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuxhlpq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ootqyyly.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2osukpcau.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2abpochni.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yukkjmbp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2niuyvtqh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2phweoyvv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnktqno.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2psbbezmh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgovdbe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2niymorct.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsrfkut.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpyzxww.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpmucfn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rxchvftb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkngcaeu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsmvtim.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yovpcrxk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2czbeloom.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbvazvg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxexnnfm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwrfccb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzzhmun.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rslcnpon.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyurfyy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqazvve.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfyckfi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpwrzpx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2umkamehi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2syazmbfg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgrzpmv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2frplpsvc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebafyubf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdcdlul.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2actayjfy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzpebgx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgabywg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2spafsckr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxylyddk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqtrpdc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaxzkzs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umvzcwlu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyuvvpo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjwnwlb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bnndwhho.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gisuplmb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsmpshl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsfjwyw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdojobuz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwmaktn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yeamagot.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qqahbotd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgprphi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnxzsqg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtpkjx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2heyakdct.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2svuezdbp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2seviqzzr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfawzyjj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdshhdk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsjpxeg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zaegszxj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkuzyqx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tohbdtlu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygplvsgl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdroxhz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxsgthn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uwctoecj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2byabvbof.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcofmglj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgokivk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgmgypm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpdjhqb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rafdmvfj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgqybqn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2viebdgsu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gadqlvpz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyzesuk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxinmde.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrgbfgq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkxreqg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbgasvb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubihktch.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvuyxtq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fadypnwt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoqxqmm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2orltebqg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2plaaksck.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiulmqq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxjsbjn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xunjqgcq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaxfmwk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfojkrg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jerrcuyq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuyhgbj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cutmzovy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2guflmcrl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2renxdolm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpaionz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzcnzsj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2loxffdak.html


<!-- 参考信息 -->