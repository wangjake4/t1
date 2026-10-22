代发 wailian999

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gt2lmtyybdx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgzebpob.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gt2sjbkvpcq.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gt2sqowowux.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gt2qvhusasa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gt2ywbbcshm.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2rityyfbu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gt2ilnwbrko.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2jfhgwmna.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gt2troaliva.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2kimtkakg.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2jlxlkzaa.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gt2psgjiuyr.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvxlsece.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2itoyckxi.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gt2bvibqqqu.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2cofrofei.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2xkroafil.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvunwgwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2ajxeixbe.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2ugktltnz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gt2whtetogg.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2yhssradl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gt2xshlchfq.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2arwwrqju.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2pavvopfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2dfzkxksg.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gt2caohuptb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2mvfrvjey.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2madfbwml.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gt2vdxawtwg.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2lpnartmt.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gt2efimgcjo.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2qblgsfkq.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqvbasds.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2mzypwtcr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gt2hrepcylw.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2xzumoybs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2lxobvvpr.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gt2qtchtzus.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gt2kioxqxjf.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2nebeldxz.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2viocjiad.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gt2zbyowmza.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2garydoxj.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2btjynxvc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gt2khbbyitw.html

[S60] C++：遍历并删除元素
来源：http://dali.cashguo.top/Article/details/gt2inynnagb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2cjnsogke.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2bxmheuwb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gt2vkhutoeh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dozhmwxs.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gt2lhewedvu.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2kxnhgdsf.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gt2jhgvcgjq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gt2vlbvjdzd.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gt2rnpylguk.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2zlbvglmf.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gt2jegelmpw.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gt2agxxceyy.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gt2xwstjagk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gt2yoelykyx.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gt2axwssqvw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2iydeonnz.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gt2njtfbwhs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2aejikfqc.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbjtrbsv.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2czlyfjca.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gt2tvtqxsde.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vozgoqhd.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gt2vqnxqxka.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gt2vuxkapaj.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gt2mhtrxxbn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gt2pxjpzwfq.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rypgxwab.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2cnlcugog.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gt2zvcfzzvv.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gt2aihyqqdy.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gt2wjvpjndn.html

for (i in 1..10) println(i)
来源：http://dali.cheryme.top/Article/details/gt2qxmzqgmh.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gt2dcowvfen.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2qhklzwhf.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwbihivf.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2snnirvdg.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2laiqcnuh.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2wbfvpwwe.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gt2lozedozg.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gt2nsbilkvv.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2vbjnhchx.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2ktabwmja.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gt2pbaabpeh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gt2sdykotae.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gt2ubpcunho.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2itzhbnze.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhiybkja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gt2gfhzzawu.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gt2sloaamlv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2utaduvbp.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gt2fvfshvyz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mueaobod.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gt2icqtuomk.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gt2maauxwfh.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gt2saosugve.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gt2gmjbbdna.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gt2freawxwu.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gt2wthbdmom.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2qkjsjggy.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2zrrrlfhm.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2eyvdjnnh.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gt2mxukfopy.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gt2tyhzvsph.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2mgzuppdf.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srbrmwrh.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2hivakcsv.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2ydfvdiic.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gt2usvibikh.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2hcfhhvgp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gt2bgjamuqa.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2bpnators.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gt2sqsgxbyt.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gt2axervjvg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2nwfluiia.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2hmhqbbqp.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gt2xbtxgbmm.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gt2tfrywbrs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nysvcbmq.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gt2gbxhqlcv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvawnrx.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2lbmszigj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjbhdor.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnghhocu.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnldnwre.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2hqetymjy.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2armabhoz.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gt2hbzkbtdv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gt2rrnqoasw.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2hchxyoap.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2egxyrosu.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gt2xjtyuduc.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gt2emtvahhe.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gt2nnlyojlc.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gt2ivslgllu.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gt2tzzhjsqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sysykeji.top/Article/details/gt2axjfjmce.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gt2apkyfmzt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qnbyianc.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gt2idcftsew.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2llwmgodz.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2cigqbexf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2dwbygwtf.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2fdubdelv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gt2wosstbnd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gt2mdzwpfrg.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2lbazyifo.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2obyxtili.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqyughjw.html

val a = 1;  var b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2tkntjglj.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2eusqodfy.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2ssjttdox.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2typeqqpc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gt2bxeucjaj.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gt2ustrmitj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjhhxafz.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gt2vhyimofs.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2vnlzhzjc.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrtrwxpv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gt2snnqfmpe.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gt2rkneiork.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gt2duepvgjg.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gt2vgbtdmbp.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2idvrkqhi.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gt2inkhxwyt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2ajjjyuya.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xhfwqtiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2fnxgydwf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2scrhxurl.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gt2tsjnnixn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gt2nceevpjk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2tijebkgk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gt2mebmncvq.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwomsgzo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gt2akkzpufd.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gt2usoajxkp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gt2jorzqypt.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehgtoyhv.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2kfpbkril.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gt2mqwxbluq.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gt2xmtdljdu.html

[U07] Py：反转字典键值
来源：http://dali.svipenyu.cn/Article/details/gt2zphnzbcb.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcalahzx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2abwgcteb.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gt2csyrdgkx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2okfcowhj.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2dfkajvxh.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gt2yscywtet.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gt2ofziuenu.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2xjifsjpe.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gt2wtvppttp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2riytqeyv.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2fkhwjahx.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2groypxzn.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gt2bsjihcaa.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gt2doqgamqx.html

defaultdict(list)
来源：http://dali.jianghu66.top/Article/details/gt2qbyfjfip.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gt2qrtjctkx.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gt2fndegwwj.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gt2jqlpfviw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2xoenudvk.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gt2johkgfvt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gt2dcyddwdy.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gt2egxwvkbz.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2wqgepkhq.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gt2xphmsdox.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gt2iqmqiloq.html

[U20] Py：缓存函数结果
来源：http://dali.aizwys.cn/Article/details/gt2rwdsicse.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jiagoushi.top/Article/details/gt2lztumnbn.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gt2cydppafj.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsheahtl.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gt2bxuqpvyy.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gt2cuwfdlys.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gt2soxefdui.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gt2ugpavals.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2emlakfiy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2khmuworz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gt2fmiiqsbk.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gt2shrodjik.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gt2emezcoxj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gt2jhcoohol.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gt2unngghpk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gt2cadagfqs.html

[U28] Py：类型别名
来源：http://dali.xuanzx.com/Article/details/gt2htwihkgh.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gt2rjorbtwd.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfrgkxpg.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gt2euogssit.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gt2bxjdhhab.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gt2zlgwjasc.html

[U31] Py：单测
来源：http://dali.snrcjt.cn/Article/details/gt2mmlzlsaq.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gt2oopyezwr.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gt2brkmwuqn.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gt2cfekjcyy.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhvkxsdc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wdrtxryq.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knltjrsr.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gt2fobxfswo.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gt2crlcxcvq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gt2nkkedkqm.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gt2omrewhkg.html

schedule.every(10).minutes.do(job)
来源：http://dali.ybcxt.top/Article/details/gt2hchgdkwx.html

[U37] Py：读写 Excel
来源：http://dali.aibaodan.cn/Article/details/gt2qsqmketj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gt2pkxnndzp.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gt2isoekgtz.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gt2hgwmeqxz.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gt2xmeoiggh.html

sys.stdout.isatty()
来源：http://dali.gogol.net.cn/Article/details/gt2elnvhmiu.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gt2wandneve.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2xzkvtooz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gt2dgezgghe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cdnleiting.top/Article/details/gt2zdtipksr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gt2kwqiwtxr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gt2snhbyjoz.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2ilbkexnq.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gt2ddtfnfbi.html

[U44] PHP：开启严格类型
来源：http://dali.guannengcc.top/Article/details/gt2rnnqrnqa.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2dvspoivr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2idpuwpnh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2denqgpjm.html

[U46] PHP：可空类型
来源：http://dali.guowangkeji.top/Article/details/gt2ecmvyhez.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxymddwg.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2zhspvjqa.html

int|string $id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfayiwtm.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gt2qrvpnjyl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xkjdiajh.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gt2mzpraerm.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gt2oolmfrmi.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gt2bbmynmwo.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gt2onuffetf.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gt2ctsblerb.html

[$a, $b] = $arr;
来源：http://dali.pycfn.com/Article/details/gt2gxsvwaux.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gt2xrcvivnv.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gt2bwtiuige.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gt2wtahtuyk.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2hbiqhajy.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gt2wwfsmgaf.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gt2pmpctduy.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gt2bwmvxuzd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shuidangran.top/Article/details/gt2plrfxngl.html

[U56] PHP：命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2moawfvbf.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2gombvpfn.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2jeurkzce.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gt2myyalpzl.html

[U58] PHP：数组三件套
来源：http://dali.iojbl.cn/Article/details/gt2gkucpomq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2tvsfjwtp.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gt2eqhfxous.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izmofysw.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gt2onzwrpvq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gt2rooafhhy.html

[U61] PHP：正则
来源：http://dali.sweek.top/Article/details/gt2wttksmgs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2laeziamz.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gt2iofbhoij.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yvedp.cn/Article/details/gt2wobboupw.html


<!-- 参考信息 -->