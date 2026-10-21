代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtegixpugq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexcawcn.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtuiwyjnlp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtgasgnobp.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqnouuguo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtzcqqxmra.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtfsjamhdy.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtfryyplie.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtdtnrkdst.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtcoaslbxz.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtmpunpxyz.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtwjayukim.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gttznzdnml.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtctsxnpwa.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtzhmjdcxx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gteomxhxkz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtbqdiwfsv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtskngpxtn.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtofdkcbjx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtlmjfrjtf.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtpjprojzj.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtxljdefmv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtxoeyocha.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtiiucoysx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtzjvafabu.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtspsezgaq.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gtzcwwryci.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtkhrzmzrq.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtajinthvb.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdolxbasa.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtnxkkznez.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtxwvxugpv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gtjxohfebx.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gttjvikhps.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtchqclqaw.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gthantfmpi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtgcjczadd.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtjmvrlhxm.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtpsnmmwyl.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtbwxtwcei.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtanhlskmx.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjysuimi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtpiqzwbth.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtjlnoiyjw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtdazsnwhr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmbtyzblg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtdcsddldg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmyorfsib.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtebuaevmr.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtxabgwdae.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtskvwrhki.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtadgpupeb.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtnbotshbr.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtrfdnhysx.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtrhxgzldc.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gthckqiuzy.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtpiwomttz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtejrmoutg.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtpqxofgyt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtuyutomml.html

[T07] Kotlin：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtrtmuqbnp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gthhzokdro.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtiimfduon.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtpxudyqzb.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtladirkni.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtedmdfwyv.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtfurnjilb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtubdjzvkr.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtsybvaomg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pycfn.com/Article/details/gtfaepscvs.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gthrjpklzt.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtqynpovnt.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtwdwnkubd.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gthoqmdkbz.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtzkhbypqi.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtiplvopfy.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gttrfdnwxb.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gtjvrlsljl.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtbkrriarf.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gttagbmbnw.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpzhdiqm.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtwemwumcm.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gthbvfoumx.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtzliimsna.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtpugqbqtt.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gturgwfsrl.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtoxteuobn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gtrrnaleiw.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtaehlxtsw.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gtelyrbkmk.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtzakyhzna.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtqzvxmvvv.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gttwlxalxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gtpdlemvjg.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gtpthnbcei.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtwregvhvg.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gtvtqjtkmu.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gthujmirqq.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtkojunxpf.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtqgwwwzgu.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gthnjozpir.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gtxewbpbfo.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtugjchohl.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtctsdedzn.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gthnacuglr.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtgldhgzrt.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtetsmebwt.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtbtbmdwri.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gttlnlhudn.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtpmymhywl.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtfdqbrapy.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtbabnqpkw.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gtvlaixlbn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gthzpqpqtr.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gttsogfvxo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gthsvgudfy.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gthrmzorkw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtezniqycn.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtbchnlxlq.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtqwaqrvms.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtzyksghra.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gteeocldde.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gttcrkfzhk.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtlnlqprtg.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtqulumbap.html

string.find(s, "%d+")
来源：http://dali.vqdsnc.cn/Article/details/gtewdjmfes.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtpiukrvtj.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gtqnqzstoc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtnlvqsgvx.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtklnuknsf.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtuivvlzgp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtvjuajagv.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtscvtjaye.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gtktkqlnze.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gtbcjyeibt.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjonwtuvf.html

[T45] Perl：数组遍历
来源：http://dali.kuanghao11.cn/Article/details/gtrqtceoul.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gteehcyydw.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gtzwxxuflg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtqawdyyww.html

[T47] Perl：正则捕获
来源：http://dali.vqdsnc.cn/Article/details/gtdqonipcf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtlnhjekqz.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtdpeyfnpi.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtzodafnth.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtuaqigyzr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtbyrleafj.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtlbfanuun.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gtzrtvopzp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhengqikj.top/Article/details/gtzypibhgs.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gtwbqkqmfb.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gthjxcwstc.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtxgrrbbym.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtmiqiowxt.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtbixcfzlt.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gteqzemcwo.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtlzysvakq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gtrpcwaeuq.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtyjnmgfys.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtmxylfxal.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtjzmrawbd.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtsgulnqaa.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtihunptsu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtcrvezfeo.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gttylqcovf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtccywcycg.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtrnuwercd.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtnapjwpyx.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtxwlglfzt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtkoinpykm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthtghtjrw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtwvxyqurh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqdljkkje.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtbokbmsjp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtgsvfuhrb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gtbsgudvgo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtlafijtln.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtdeuhnpms.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtflpwjlij.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtkerorzoi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtmykzpacw.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gtewetawdc.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtyseaatxv.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gtqimghpfo.html

{**a, **b}
来源：http://dali.yueranfly.top/Article/details/gtzxymvqxx.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtytbtesiy.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gtmivjqfzw.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtgmapcryj.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gtdjkvnmuk.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gtgyuariya.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtvebrozav.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtomubrtxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtwtucqjfo.html

[U11] Py：生成器表达式
来源：http://dali.cashguo.top/Article/details/gtsfhgyvvt.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtsqdobqoa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gtnfbddjhu.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtvmdeufah.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gtczldsuru.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtyrnicseo.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gttsjqrzyp.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtkdjwbulq.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtmzrjrgzn.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtycxmqlbt.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtifikjtkt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gtvqxmevtu.html

[U17] Py：初始化日志
来源：http://dali.yj20258888.top/Article/details/gtnqmzpfci.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcivmxaa.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtnnphhrfy.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtdayqqnnd.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtkccowxhx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gtoeyhyslc.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtjijsgzii.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtfhcqyilc.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gtbdmgukzt.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gtivfdjzrm.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewrdabjw.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtzucfsjns.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gtignpqkns.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtbvwgutdc.html

[U24] Py：路径操作
来源：http://dali.hnqzz.top/Article/details/gtozisjqpp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtxnwrvuyd.html

[U25] Py：CSV 按字典读
来源：http://dali.c1oappe.top/Article/details/gtexytiewf.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gtquhjsqvl.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexbekudl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gtikqnlikt.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtyzzgmyhm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gtdzrnvwwb.html

[U28] Py：类型别名
来源：http://dali.cheryme.top/Article/details/gtlyuvdqkm.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtwoxyejjc.html

[U29] Py：属性校验
来源：http://dali.daxiang520.top/Article/details/gtpwxgrbxa.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gtxhwimjca.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtwmgyuenn.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtsnoomxvz.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtzohvxzha.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtrfcrxxpm.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gtzycbyurn.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gtpgtwmcgi.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtliatefpc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gtbeuztdqm.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gthskwsorx.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gtpfywioep.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gtxcdqthmk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtasmjsgio.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gtnsgkaxtq.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gttboaxwme.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtrprxiahw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtruapwxbz.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtezlskvhp.html

Path(__file__).resolve().parent
来源：http://dali.havefunace.top/Article/details/gtqwzdmaal.html

[U39] Py：判断是否在交互环境
来源：http://dali.fengsongda.top/Article/details/gtwmkelaxv.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtxilidzxe.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gtcnzfrafr.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtxfmlrxcu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtkwxcphwl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gogol.net.cn/Article/details/gtpytvdjip.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dashuyun.cn/Article/details/gtqxkvvojt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shuidangran.top/Article/details/gtgnudfsaj.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gtuimrlyxr.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gtlcclecnk.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gtwssebbmb.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gtldthmkmw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtynaljzov.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtlbqbdnha.html

[U46] PHP：可空类型
来源：http://dali.fzhhl.top/Article/details/gtzywclqay.html

?string $name = null
来源：http://dali.tanke756.top/Article/details/gtjyfbhjgj.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtcpqtvfhz.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gtsitciovx.html

[U48] PHP：纯枚举
来源：http://dali.0kj1m.cn/Article/details/gtvhttxddl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.snrcjt.cn/Article/details/gthxfarcaz.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtxoswacia.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtxmsbxlyz.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgufenzy.top/Article/details/gtiwbswdjr.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gtwlohpknn.html

[U51] PHP：数组解构
来源：http://dali.havefunace.top/Article/details/gtnydbqsbf.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gtysqbawof.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gtlzcimdwo.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gteekiwfaa.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gtgdjofzen.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gtzzojdfom.html

[U54] PHP：空安全调用
来源：http://dali.fzhhl.top/Article/details/gtmktvdiuw.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gtqzyyyjce.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrzbahyh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtqpxvelcj.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gtrkhxvhmi.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gthmkslcil.html

[U57] PHP：字符串插值
来源：http://dali.smart0.xyz/Article/details/gteetolpqr.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtvnvmiyqo.html

[U58] PHP：数组三件套
来源：http://dali.chenlongwang.top/Article/details/gtntgndguy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtdcvpaupw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gtvrmufrdp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtzaffqxgm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhixingplan.top/Article/details/gtnobbbpqf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gtsyodsxmh.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gtegtpolfx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtnpozxnsx.html

[U62] PHP：日期对象
来源：http://dali.sufxvd.cn/Article/details/gtxnjrdgcp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gtntiufdye.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gtbvlnqyhg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gteiqxgpfe.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gtndajgenv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuetiantiany.cn/Article/details/gtplavrqwu.html


<!-- 参考信息 -->