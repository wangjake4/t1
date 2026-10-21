代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtvrynxsnm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtubbgtufv.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtekzsavak.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmmsziku.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtpvvqyqwr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtddnvfvfx.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gthnaevdhw.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtpnlscwgz.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtbroxbigj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtrqrcjkwd.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtjsugfkre.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtfrhvturo.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtmgkikbae.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtsdasqyks.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtlnshxqan.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtknnmukio.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtytcgnfno.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtfzshtelz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtlwftshim.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtesrllgck.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtimubsrur.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtfqsnmdqy.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewfkfhgf.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtcjsaajks.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gttjmhzfuv.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtfmbgspyq.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtunjrmjjq.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtwfobcrxd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtymwaadxz.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtencxcoyp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtyhbnwdbc.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtbjhkadsr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtjfqskdfb.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtwmdecwgo.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtvcjyeczi.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczdlyvle.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gtlatouwal.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gttijlcgxm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziwsmygz.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtdcfzwemh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtohcrssyb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzovbmydp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtzrgshmkf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtssfnozsq.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtwwxhegnz.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtsbeberzz.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtgjwnqznz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gttjjparyq.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gttolslzms.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtrnjhuduh.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gtowdmanbr.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtmkajeeit.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtdryqxtli.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtyzmnqphw.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtdfklbvlq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gtpuivoewh.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtdlvposof.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpskdkwrt.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlppumpw.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtfvdwmnaa.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtidycties.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtiyxxtwgh.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtxfdlrzyc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtsxxdmjtc.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtkdtogwfc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdfmjqto.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gtaphenfej.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtigszqbjv.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtgxyptwxq.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcrccwvbb.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtlldkhmwa.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtnoqzhxve.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gthnebxhcw.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtfftfiugw.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxeaminey.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtulgpbuqz.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtmdvmnwid.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtmwjclceh.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gteucmgkav.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtewdfpkqd.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtdbowmixl.html

if let n = opt { print(n) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmrssuol.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtosjkuekp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtaeowfeyb.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtvpxqbznh.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gtqbuapoah.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtjlndtzat.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtiimisnzh.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtgjorwhnx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtwvyuxwum.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahjdiumr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtroykekng.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtkqsrkzhq.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtmzwmgubb.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtljpgxtkb.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtzhqvwsoi.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtfxvbyrwo.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtjhmhezdg.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gttzebunez.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gtkeqesink.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gthohzycog.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gtkiytqmuf.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gtwcsoqcjz.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtwdddptdp.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtbtvhgypa.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gttmtscerm.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtuznwozil.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gtzorsnnth.html

[T33] Lua：表（数组）
来源：http://dali.yanxiufei.cn/Article/details/gtnmkgdozg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtpvwnokoe.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtkgdghvux.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtswokfpwg.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gthcubgfzz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtyesigwip.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtpolkowqh.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gtjfiwbqsn.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gthndrtvbh.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gtfpkipcns.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtmycssvcj.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtxaayonxv.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtircpztci.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtzyjcovdn.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gtulalbqih.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gthrllittj.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtzktckycn.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gttezkuogg.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtvvsuratn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtbsovxupa.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtsflwdfhs.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gttelpfrrv.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtalyjpuyp.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtyvysiiil.html

[T45] Perl：数组遍历
来源：http://dali.gaohongyu789.top/Article/details/gtjnywzdbg.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtwupcrctr.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gtygcbnuzk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtjcnxltze.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtowbdkwyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtqlqbudew.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtxucwpgsh.html

$s =~ s/old/new/g;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfvijxny.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gthgnobtvp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtbookgezg.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtxhywrqrs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtjtssagcw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtcnzxfgfk.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtrbakhysb.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtoxwjgoig.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtgunznugk.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gteaqefuco.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtupowrtae.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtfowvodxg.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtodzlmpsz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtuorhbghr.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtxdrpnsre.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gttvgcxmsk.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtfwqsbgxl.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtbczukhaf.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtvbdsrdgb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gttljfrexd.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtgyymvmno.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtbgbtwodk.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtidewdcah.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtwyabsgwu.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtowqvspvu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtjmordngk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttdcqnwyc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtjyxnjfde.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqnbcdzxo.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtpjfatpqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gthumxzynw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtokpstqct.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gtbppbfdfg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gtqqpxtisv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gtxfsfnbfm.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtiqxkokgc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gtprbuxshr.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gtojpipxov.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtbxcprbap.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtypnyopku.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gttqjcfond.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtuapudqwc.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtbwfhxaqd.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtgojvrpnd.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gtvdxtdhvd.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtjotruqev.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtlqtqgprg.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gtwtlvdzye.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gtvgqamdhm.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthseruzsd.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtkgkzwstj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gtwuqotqbo.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gtduxwolhf.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtemgfxqrf.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtcfojqqbw.html

[U14] Py：分组收集到列表
来源：http://dali.hywenlv.cn/Article/details/gtoptzcirw.html

defaultdict(list)
来源：http://dali.yueranfly.top/Article/details/gtikxhhpav.html

[U15] Py：高精度计时
来源：http://dali.nwbrower.top/Article/details/gtdftvojzi.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtwfwajile.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gtynmwwwxj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gtbvqkdhbn.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtvfcyedzq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtprfdxwda.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjqecntn.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtxulrbpty.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gtzcqysoiw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gtidjqcvnk.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gtjzinrbkg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gtweleeexx.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gttjzdrsza.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtshsbflkt.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gttortvxnv.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gtkyrifzld.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtkxnnhzhe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gtsihrqfqf.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gthmjxtxso.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtzkkokkqg.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gtqiqrwsvi.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgayfivet.html

[U26] Py：并发下载
来源：http://dali.yuanzhike.top/Article/details/gtyqvuoect.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj202588.top/Article/details/gtmpyvxvfz.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gtbenxenwd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtsudxtxhz.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtrbtsohaw.html

UserId = int
来源：http://dali.birdmap.top/Article/details/gtkxqbkmru.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gtwrwmdigh.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gthvyvmbtp.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtqzzwcuae.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gtgjhzbdum.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gtlvpvuitj.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtuldyacpt.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gtjmwbhegk.html

ruff format . && ruff check --fix .
来源：http://dali.havefunace.top/Article/details/gtoyfclgjh.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtbkmxjtbl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zdqjudy.top/Article/details/gtgjiuucfr.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gtkzfecyrj.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gtgfnharen.html

[U35] Py：发送邮件
来源：http://dali.pengpengdd.cyou/Article/details/gtvfqoqwrd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gtincuzpli.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtwxiqnfeo.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gtzjeurzjx.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gtqtyqnhwi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtcmixlkyo.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gturhuysxa.html

Path(__file__).resolve().parent
来源：http://dali.jinqigufen.top/Article/details/gtqgexjeqc.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gtfgstmtwk.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gtnzyldvgt.html

[U40] Py：打印到标准错误
来源：http://dali.quarkkingdee.top/Article/details/gttkoogkwb.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcixihcch.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtojzitvbb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gtbcnujvgp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtyihderye.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gtstpuxxti.html

[U43] PHP：声明命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtopfutrft.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gtavlzpdwg.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtovacvasr.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtuypwstbz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtqlkalloa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlmhhjtke.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gttzighddv.html

?string $name = null
来源：http://dali.fzhhl.top/Article/details/gtsxlgjngf.html

[U47] PHP：联合类型
来源：http://dali.hnqzz.top/Article/details/gtfdurkohe.html

int|string $id
来源：http://dali.nwbrower.top/Article/details/gtlomtrlxg.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtwtvpfddp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtrtiennpb.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtsofamsuw.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gtbszgbede.html

[U50] PHP：构造器属性提升
来源：http://dali.wangdashe.top/Article/details/gtegmfufnd.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtjkeblnyi.html

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gtftjgvpyf.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gtxbctuubz.html

[U52] PHP：箭头函数
来源：http://dali.ybcxt.top/Article/details/gtjtczefec.html

$double = fn($x) => $x * 2;
来源：http://dali.hywenlv.cn/Article/details/gtmkipantj.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtciefdgmh.html

$v = $a ?? $b ?? "default";
来源：http://dali.svipenyu.cn/Article/details/gtgppgbgax.html

[U54] PHP：空安全调用
来源：http://dali.guannengcc.top/Article/details/gtriqmkrdp.html

$obj?->method()
来源：http://dali.0kj1m.cn/Article/details/gtkzwcwhco.html

[U55] PHP：match 表达式
来源：http://dali.daxiang520.top/Article/details/gtvuholhaw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtxatddvyg.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtkxzncrmb.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gthpwahpid.html

[U57] PHP：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gthucbhurn.html

"值: {$a}"
来源：http://dali.ehwqpu.com/Article/details/gtbblzfidf.html

[U58] PHP：数组三件套
来源：http://dali.ivvv.top/Article/details/gtnbobsycp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gtypvqgyxy.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gttvyaxuhd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtgtnkfmya.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtdjngliuc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xziqi.cn/Article/details/gtkcvnhavs.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gtbrgogsvh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtfpjgoucz.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtsaciujfr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258.top/Article/details/gtsllspctw.html

[U63] PHP：文件读写
来源：http://dali.316326.xyz/Article/details/gtyvskiyvo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gtsafnamuz.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtfgckmldc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzunpdudb.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gtktkupsop.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtwwpgvvgr.html

[U66] PHP：设置 Cookie
来源：http://dali.zdqjudy.top/Article/details/gtcilxgjev.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fengsongda.top/Article/details/gtqzzyoich.html


<!-- 参考信息 -->