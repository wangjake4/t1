代发 wailian999

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtkkhjcrgi.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtuupujadd.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtxxsgkczq.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtkhrmtsfl.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtropljpfw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gttomxbfrx.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtmjozxhga.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtimmjvnhk.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gteoxotpfy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtmvayjsxc.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtrujixgib.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtmhcibvup.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtydnpdxnl.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtollcauem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtuhkqlvhp.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gthylsorvg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtucgjvelf.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqqfgbnu.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtlksyqqbo.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtfeydzzdq.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtxmwasafn.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtmwggnyze.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtrpggmmea.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrloyvxdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtefiqnrwq.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtgpfohkil.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gthpyyjgbt.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpqcmvmn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtmqfkbgbn.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtsbrzoves.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gthrblnfbh.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtgsegbcam.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtinmpzern.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtdcecapzx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtelvjswev.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtcrzjbvwe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtmazjfpup.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtugjvvsdc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtwlhzymhn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqzfsvciu.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtubkqoknm.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtcnytsisj.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtxldncqpr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtrlbbansi.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gthzqnanub.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtwlxixpwo.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtschhlquw.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtnjjfxxsb.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtkhqeezvm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtdkvaxnar.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtadqkonrh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtnkttwmsw.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gthdbbyexn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtrdcpclie.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gthxksbafh.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtvehxfpba.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtuvoewozm.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtjaqwkdvn.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtymopbmul.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtntxbnrwl.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gttastdroc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtkzbssvaz.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtrznrkjkm.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtokitjxzk.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtfyraackj.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtaosuxnfc.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtnglpbeor.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gtglgmlvrz.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtdelnbflo.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtsjeocvfr.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtsyvloeel.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtzjmfcisg.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtusuggcar.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtbafpmlrx.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtouqoixng.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtjvjngeyh.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtvllupjvh.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtcfnmwssw.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtclutlbzt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtyobrwcfb.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtoqsnjklv.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtimzxgxqk.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gttcbhaqsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsczvcbbb.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtoywrxqvi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gtjixoeanc.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtcelhgqlw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtgxyeqhak.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gttockzcat.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtixgrlspt.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtrymaihpe.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtwrmtsxmh.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtmqznupmf.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtoxmmnkik.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gtrhlbedtu.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtiutvlwwg.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtkundlkfs.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gtmxposgsx.html

[T30] Swift：协议
来源：http://dali.nwbrower.top/Article/details/gttpwtnnxg.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gttbxusadb.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtlgkaaewm.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtkhgndyjt.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtkkfaxsph.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtmulkzjzd.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtvcqvdpjh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gttowhmshw.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtmvcrzgif.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtyisssprm.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gttedxfrrd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtvxgjmjvr.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuahqear.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtdhfzykfm.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtbhseqxix.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtwfjyhduw.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gttqjmuykz.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtodqkddgf.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtvfdargiw.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtwtzbozgw.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtogsmzpri.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtrbbjubxu.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtjzqzjynk.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtkdujwazr.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtgwoksnmq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtsspogsbk.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtlnsaretl.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gtftgprgtd.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtqiyrduzs.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtcoaveetm.html

[T45] Perl：数组遍历
来源：http://dali.chenzaomai.com/Article/details/gtitxicbem.html

for my $x (@arr) { print $x; }
来源：http://dali.yvedp.cn/Article/details/gtfyaeognm.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtoolxilwn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtkzhfapmq.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdxxhsqc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gtknetlzwv.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gtxnvrivvp.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gtobyxgwck.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gthoalbzjs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiqgdjbrx.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtrmsxmwdz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtiejmlisn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtcqbuajda.html

[T51] Scala：Hello World
来源：http://dali.sweek.top/Article/details/gttzawglvm.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtovgaehzz.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtajkmqlal.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtkdqgwjcb.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtwpeukgdr.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtjuomrjqi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtngexwkke.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtlnzkqfuo.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtobxmlvcs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtvuwokfde.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtedfgydwi.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtwssvuyen.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjiebhhn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtrjoinwgh.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtfalcfebl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtzkbilxba.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtxthgltrz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrcjuwmw.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtmcfyialj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258.top/Article/details/gttbsxthse.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlsqqslst.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtfvofsikh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtbmiaowtn.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtskopgnzg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtqvpaptdr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gtagaqznez.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtzooizgkf.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtmyxvanwm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtmpjksypc.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtrnounsxv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtqkeupntk.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtkrcykwdx.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtmdzmqran.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtxnoprvhi.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gthxjxnrzk.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtvywxiwwx.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtvlsmvghs.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtgmzbigbo.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtezhhypkg.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gthwgbtoqr.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtalsktvbu.html

[U10] Py：按值排序字典
来源：http://dali.jianghu66.top/Article/details/gtphlusfyy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtoyfacuts.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtdmhjoust.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gttisnxmzt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtjfkqvsqo.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtwinyvtvi.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gtamnfvhmy.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinddprsc.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtkvhwnhhd.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtjavvqycr.html

[U15] Py：高精度计时
来源：http://dali.fzhhl.top/Article/details/gtktidneou.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gtpgermxyf.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtxcrbujmq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gtvtcycwll.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtvbfykvbm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtzzebljqf.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtfboixpxb.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagerlknc.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gthdnnrzof.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtgfuekszy.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gtbnppxfpq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gtzxalegoh.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gtaorhrrrj.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtctrttlph.html

[U22] Py：矩阵转置
来源：http://dali.yvedp.cn/Article/details/gtqynhsxpt.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtimvbowyx.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxhyrxupb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xziqi.cn/Article/details/gtugrbsjrr.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gtcjfmfbhe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtnlrbfxfq.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gttcshwfyp.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteogerkar.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gtvfjxxjub.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtubjjkhdy.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gtioeuysih.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gtvmfwznga.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gtkxywdczv.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gtxstqmvdc.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gtmfynnwyu.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtkrrvvpur.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtzijqyknz.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gturjbmkqc.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gtydwwoadr.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtvaazzbep.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtgomfjsfg.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gtednlehco.html

[U33] Py：打包发布
来源：http://dali.yj20258888.top/Article/details/gthaeuipaw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihnsytt.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gttlfytlxt.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gtgsxzbmpv.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtxstypzle.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.smart0.xyz/Article/details/gtatswlwqn.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtdfqyhfof.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtclydiimy.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtbtdxrpus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gtmswdspxc.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gtsmupbjtt.html

Path(__file__).resolve().parent
来源：http://dali.andypj.xyz/Article/details/gtymlvyypt.html

[U39] Py：判断是否在交互环境
来源：http://dali.hammf.cn/Article/details/gtfnqnxqrx.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtslbsgxzq.html

[U40] Py：打印到标准错误
来源：http://dali.haohaochexian.top/Article/details/gtlzmhqbwh.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtdfdzvmei.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gteqofjtfb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gtuifomnhz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gtlhvfwmhz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gtfnneglmy.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtkpzjezrs.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gteohnyjcp.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtoxvjsfxp.html

declare(strict_types=1);
来源：http://dali.wangshuangyany.cn/Article/details/gtssuzpuvb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gttwwidmhk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtgilpuvhr.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtzsxpakqi.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtvqkqssth.html

[U47] PHP：联合类型
来源：http://dali.hysaishi.cn/Article/details/gtbtrzdyyv.html

int|string $id
来源：http://dali.xinyue.icu/Article/details/gtxspxjryc.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtabcysfkm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ybcxt.top/Article/details/gtuzfcjwwo.html

[U49] PHP：只读属性
来源：http://dali.xuetiantiany.cn/Article/details/gtwdpsbvrd.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtelppupue.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gtatmbdjdq.html

public function __construct(private int $id) {}
来源：http://dali.haohaochexian.top/Article/details/gtjhkyzleo.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gtcrvfpzct.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gtesnigonv.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtoptqpdsb.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtrukhgmhl.html

[U53] PHP：空合并运算符
来源：http://dali.hfpthk.cn/Article/details/gtvdtndxmy.html

$v = $a ?? $b ?? "default";
来源：http://dali.ppjwa.cn/Article/details/gtwlskmzts.html

[U54] PHP：空安全调用
来源：http://dali.aizwys.cn/Article/details/gtobuwallm.html

$obj?->method()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlfeemyx.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzddklkj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hammf.cn/Article/details/gtvcjbtpdu.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gtsvcnmduq.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtrlyczlet.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtdieljnwm.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtdqnjswpv.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtgoomxbnl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gtxkozzrxx.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gtwhbxoepf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtdyypjlva.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gtezquxxvh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtolwxtjgw.html

[U61] PHP：正则
来源：http://dali.sweek.top/Article/details/gtmbacoedq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtthovplff.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gtqguxcegr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gtakbxfepe.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtgpexouyh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gtitplgxfq.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gtplxpgsfq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sweek.top/Article/details/gtnellihcv.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gttnhsjhha.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtkpmqiyrv.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gtwoeknaqf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gtgrgfrahf.html

[U67] PHP：处理文件上传
来源：http://dali.nwbrower.top/Article/details/gttegpekju.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gtgspgkudk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gtytkyhcwg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gtmnksnnlj.html


<!-- 参考信息 -->