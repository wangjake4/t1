代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2frqsttyk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gt2adygewex.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gt2njgrmful.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gt2ebsjxkan.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gt2kiidpodu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gt2onymhutw.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gt2tvnyytpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gt2dxochppo.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2hxcftdor.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gt2rpveahid.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gt2tojachqo.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hqpfxipe.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2itpunhcf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gt2quzngrmq.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2igqavtvv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhuqmktw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2suozhzhq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tnmmcgga.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2lszzebqb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gt2uozvqbwg.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gt2skfwjpay.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2zhkgkizp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gt2gpvnxojj.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2twfeknlf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iybijctg.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2vvdljkhj.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2dlrdcqsf.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebrtkwyy.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gt2qudbjdhc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eahmjnxx.html

std::vector<int> w = std::move(v);
来源：http://dali.yuxming.cn/Article/details/gt2njxtqtzi.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gt2oggjewfd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eaunzreo.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gt2xabbcaxn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gt2zncoulaj.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gt2ihskluub.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gt2vifsnxyy.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gt2qajabxxw.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gt2llqbvizs.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qooenauo.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gt2sttsdcdg.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gt2zijmuaww.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gt2omqeijgj.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gt2jjcxciet.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2akjhsvfc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2dpnjlzrs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gt2gbtzucsx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwgjtnsv.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2tekwzwjm.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2uujgvytb.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gt2qlqpkrlo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gt2drrqedkl.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gt2jmiafrgo.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2xeomuwab.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2uvkqhscy.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiiwaisr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2rwfbyfkw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gt2ohureynk.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2drvjbvcw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2seuruzkw.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2bozvrgzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2tbjsaxmj.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gt2rcqmnjbk.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gt2wcdibrqr.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzqoaang.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2fznknrzj.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2fsgbnaqy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gckmlweh.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gt2irsxsmqx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2qqpjvnbg.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2mirscvhl.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2cyozhhnq.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2svswvvgo.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gt2cqmskhxa.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gt2nnkoslyx.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2gwcaovlh.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gt2ailbcxxy.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gt2xpfnwxjv.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2bwmhclvx.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2fpvjcmki.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gt2wkhvhshg.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gt2cviygzey.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2cxpiysiu.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2zhsdigkx.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gt2dtpiospk.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gt2csmabrpx.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gt2tsphpfxj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgjetebe.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2zxedmdyb.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gt2xhmbacjl.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gt2agwpafed.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gt2nantfutd.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gt2ssxxnvec.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gt2tfgbdxds.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gt2nutnrusc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjxyhuiz.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2radqdpxx.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2pkpffmfh.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gt2nezxmbwa.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gt2mvucitiq.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2qfmcietc.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gt2sdxcwpxj.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2ncbfxtqc.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gt2btjeuenh.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gt2kzazrkck.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gt2uivvivjj.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gt2xmvbtcnz.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2zoreaifu.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2qehvxhyh.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2htellwux.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2izhgcqit.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gt2luyzwzth.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gt2kvtqecft.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rthqabaq.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2dydkheju.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lisyhcmc.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2qesifggv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2ojggrmeu.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwlzgins.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbmnlfpl.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbvolnqm.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gt2frosgcwh.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gt2reofpijg.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gt2nmfclfva.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2hlgvxzyg.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvddvyqn.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2yoyqeacw.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gt2qaehuraf.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2ounoskjh.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gt2fycchuju.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlxlngnd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gt2tetkdifk.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2bravlhrl.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2wluvaicg.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gt2jnsmvnsl.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gt2bjnpkhvm.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2okctxtlq.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gt2mzgtotww.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gt2xmrnkfmp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cosvookw.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gt2vfseqszc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2ftqmtnbo.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gt2ntrrghpl.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2kmpahnxd.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gt2lcdjsdzw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2nxucdvij.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2yooeslhn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gt2csuhgrek.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gt2qmxuptjd.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gt2okukcqzh.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2lvilshug.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gt2uvxsjbkm.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gt2yqfeexqb.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2aorukxjr.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gt2temvpvrc.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2lylqmucl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gt2sjhvdfls.html

[T55] Scala：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2rxdoaxbx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gt2wxcynztn.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2czrhsvsy.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avgvease.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2odwjpave.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bubtyftx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2detfrbiq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2edotafys.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmyuvtbc.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2kiroskjs.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2usonpytc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gt2diqzdppw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jtmdhagl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2widmlrhe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2nyndbzzo.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llaopbij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gt2izolxqmo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gt2yumflcok.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2spjuooey.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gt2uebixfjj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gt2bvaqszrc.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2ejyvfcfg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2naaxaviy.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gt2otbtpbeh.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2ewzoaaud.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gt2sydpnxgt.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gt2aomrmeha.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gt2optrfatj.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2orkaeocr.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqshvlis.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gt2angznyjt.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gt2qfrteofw.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gt2dbhekrde.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gt2rlkoixjr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjlopkbu.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gt2ssnghxgs.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2hchgtmup.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gt2vqnbsadp.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gt2fnyiptle.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gt2ylegcvvk.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gt2oqmntish.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gt2euvtsywl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpgroju.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gt2tqdcdwzd.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gt2acbhmpha.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2fryfqurg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gt2sniucufs.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gt2fuztmglc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gt2umbjfdpu.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gt2twtbygjw.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xarlgdxt.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gt2lggxwqii.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzkfqggo.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbckclgu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gt2fzktkdnc.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gt2xmqkmvua.html

@contextlib.contextmanager
来源：http://dali.tanke756.top/Article/details/gt2mwhdsfbi.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gt2qymacngi.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2jndojwao.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gt2cytaoskf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gt2awoayqym.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gt2urslukhs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2hhukhsrw.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gt2womwqlfl.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kikmzyyh.html

[U26] Py：并发下载
来源：http://dali.meibo888.top/Article/details/gt2soubondz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2lbuxtbdt.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2tuhvyxeo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gt2ghnxgcrb.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oopfospp.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gt2asyrjdbg.html

[U29] Py：属性校验
来源：http://dali.yj202588.top/Article/details/gt2jvkqxfku.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvqddex.html

[U30] Py：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2nuuajdbj.html

@dataclass(slots=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2ajpcpsmy.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gt2nhxqbgpk.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gt2fozrgvuy.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gt2cmjrirov.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gt2nedpxzjc.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndrgctny.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gt2ougplmod.html

[U34] Py：判断编码
来源：http://dali.fzhhl.top/Article/details/gt2zoioutyx.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gt2cfwdkipn.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibwpehow.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xinyue.icu/Article/details/gt2qzxditva.html

[U36] Py：定时任务
来源：http://dali.cucudq.cn/Article/details/gt2yvlvvodl.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eikmcmzj.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gt2djanqmtr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pniffwsz.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gt2qocjpshi.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvyhsejs.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2alvnqtaf.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2iqbotggt.html

[U40] Py：打印到标准错误
来源：http://dali.fzhhl.top/Article/details/gt2qhnjlwaa.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2scbyaspw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jqgfzy.top/Article/details/gt2wknbenyw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2qftgbitg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.vqdsnc.cn/Article/details/gt2whubqelt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hammf.cn/Article/details/gt2tvtaweih.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2vovuqoje.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gt2wcbkjhys.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2sveqxuza.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gt2ppxrombo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gt2rriqiadm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2aonmlrso.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gt2nzoejobq.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gt2ycdabysc.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gt2ngsdoqpb.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gt2hdlzzuxi.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gt2qggnnilc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gt2msylagvk.html

[U49] PHP：只读属性
来源：http://dali.sxryk.cn/Article/details/gt2spslrjuj.html

public readonly string $name
来源：http://dali.sweek.top/Article/details/gt2vlmovbvq.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gt2npqdwmnx.html

public function __construct(private int $id) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vrgdrtoq.html

[U51] PHP：数组解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2uneehofb.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gt2ajvbrkil.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2awcwqvhs.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gt2hrabuxix.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gt2jutkufpr.html

$v = $a ?? $b ?? "default";
来源：http://dali.gogol.net.cn/Article/details/gt2yinwwaal.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjjdqecr.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zntytgju.html

[U55] PHP：match 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjtakyod.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gt2wwcbepem.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gt2ojzbwcia.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2mmdgmhaw.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2esgkszie.html

"值: {$a}"
来源：http://dali.dianchejie.cn/Article/details/gt2pwjodzlm.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnoskptc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gt2mxrlmiul.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gt2jiyjecrj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2wsmrpvpd.html

[U60] PHP：JSON 编解码
来源：http://dali.chenzaomai.com/Article/details/gt2olzixlgg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ybcxt.top/Article/details/gt2umlussye.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gt2mxorytwn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2bvqauhon.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gt2uaknvbew.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gt2livoxydd.html

[U63] PHP：文件读写
来源：http://dali.snrcjt.cn/Article/details/gt2bsheflac.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.iojbl.cn/Article/details/gt2akulsiky.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2bbxexokl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.birdmap.top/Article/details/gt2ijkizvnu.html


<!-- 参考信息 -->