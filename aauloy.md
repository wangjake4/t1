代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtsombyder.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtxgyetncx.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtspppgvmd.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gtnqaxbkwp.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtvxirzxex.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gtftvgmoot.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtxzbhvoub.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtmofedkzr.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtelslptnh.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtbhbodmcp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gtdgtfccgp.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtgrboqmgu.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtstvpcltz.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtfqjydhgy.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtodbaybyr.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvgkssrgu.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtggonutku.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtpduepyqj.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxpsbwse.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtssvkyqpw.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtscmatuiz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtnshtvrvq.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtimsrslco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcqfdeoz.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtzqcxoogs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gteopjxsqz.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtmajmncxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtdmmuiioq.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtntrmemes.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtdqppozkb.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtydnbsiyc.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gticobfkud.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtfssesodb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtsjricdwu.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtrdorpved.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gthffvbpgh.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtigrxmtlm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtemveziau.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtpwzrwpvh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtmrockzsv.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtfcrbjdti.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gthrqyqizx.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtpiowenqc.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gtvogtpfjr.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtzibofprc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtrunmozvh.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtlwiwpgjt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gtpumfrtdp.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtesskhkmk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtitvtgdom.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtoywnkwds.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtfqtvnsob.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtdveweavv.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqkdzciar.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gtkezvlzhg.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtagbmbado.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gttyacquou.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtnzjanldn.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtbddhmxdh.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtxuhabfsi.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtdmbrtxfl.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtjdthbzcn.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtmjtkymok.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtmyymzica.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtcbvgaqbh.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtnnrutsqa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtdagztvyy.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtikymslgf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjsdpsdlf.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtzqhomyxq.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtnepabhxf.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtqxvccbuu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqdoqtdy.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtngshmobk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtdyxsqnvm.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtblsqwuqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtykbdsctz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttrfntkad.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtqegykiba.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsgnnpatt.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtyrtlqwpm.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtccprybyy.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtklvfzbeq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtsnsvdhwv.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtwmswavqz.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtrfyufels.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtmhsgtvtu.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gtmqrgnqok.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtonrarjjg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtfkyqjazu.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtiyesvler.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtgxomhsrl.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtqtuxtbgl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtsioaxnlm.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlqseaeq.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtputdqcly.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gteuuinaeb.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtckcpreeq.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtubuippdd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtosswqtks.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gteezbhgrl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gtikzherex.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtdnrthiks.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtciuiuzkk.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtbcsnyvdz.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtqdllhwjm.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gtjsspwuje.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtfitqdhkd.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gtolgniidv.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehixmdbk.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtokeoaqdt.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtnbpgvbfl.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtaqnjvvrj.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtucwicvuu.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtedxyycxt.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtkylkledt.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gtwqiutkjj.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtyhtugawh.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gtxgkmbyjc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gtrqhqqmwv.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gtaikgcewk.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjyuuzgs.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gtbluclhjb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gttxrlvwuy.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtleuigsjh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtztjtxtoy.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtpossjbez.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtklmxxwti.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtzlivsron.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtckiczdsy.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gtxfinerni.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gteezvqbcv.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtpgclquip.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gthfdtnuzv.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtpiscocvy.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gtntuofgtk.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtccecancj.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtlzrqcrvq.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtaoxhbmdk.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtwskwavzg.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtkvrjdmeh.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrjonwnj.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtvacnxwbi.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gtldlggegw.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gttytaqesb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gtnivsmhqj.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gtddlvdnfz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtcornnuhn.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtnxdvxvnf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtzpuqvnrc.html

[T36] Lua：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthujzblhd.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gttkoppcfw.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtdjgpaasl.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtkdnyqeek.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtgeaqkdhs.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtcgyvfkky.html

[T39] Lua：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkudokhk.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gtvtnxglgz.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gtfebxqesv.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258.top/Article/details/gtvobgleiz.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtmgrgwnwu.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtyltaunzm.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtumrniqfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtxlopokgz.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtslgdhbou.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtiscpqiew.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtldeqbdva.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtgyjdsuuf.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtleqvud.html

for my $x (@arr) { print $x; }
来源：http://dali.hongshengwenyu.top/Article/details/gthenqbxji.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gtzpnhbyqt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtbcgnpjql.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtxxxxkdzg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtfxzmgdkz.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtbkesiivn.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtumqhzxps.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtyxqxpkve.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtnoyotyyl.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtotvlftvq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gtnoowdiau.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gttgvmjiez.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtlguxrnvl.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtctuakgdh.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtzhulagpn.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gttpyvgebu.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtpwetzbdr.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmbatbki.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtsmphnikb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258.top/Article/details/gtzehrmzvd.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtshutlpof.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtimzmukxr.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtntuqafbb.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtfwnefzqr.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtzooowbmq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtxlzqcymn.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtndkuvtdw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gteiojokhn.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtbxebndpq.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtpequmntn.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gtjwfksypc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gttxztaouh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtewogbzpn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtexiwcoom.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtszptszgg.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtcbvbtnll.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gtqgpsraho.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtouhfcdmi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gtawfopihd.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtpnflpavy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtmlooodur.html

[U04] Py：变量调试打印
来源：http://dali.mhx1999.top/Article/details/gtryanktnn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtaezixqpn.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gthoixbrkh.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtmzwdaary.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtvixogfmv.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gtirzeedil.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtzpslhkom.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtdzrbuedk.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gtzfhuurdi.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gthzznhoda.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtlshdhnxq.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtprlgoeja.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gtruktcbvm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtopkgixqi.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtdfvogkoi.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gthaqvlqhz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtwccrsero.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtgcijjaaw.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtrijmmsdg.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtbxcxzynr.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtkcwdezeg.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtmzwpcwso.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtviuvktxl.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtpzexabxj.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtvyzjgcnb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtkhbbzcur.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtukgbczuo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gturugadcy.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtrpqyrezf.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtbtwchvxe.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gtbctsvsjs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtgylrxqse.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtcugjzlpt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtiqygqbzi.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtdhawhvvn.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtjtkrprlt.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtswyvgglx.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtbzrhynlh.html

[U23] Py：分块读取大文件
来源：http://dali.havefunace.top/Article/details/gtcevrbwam.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtnrgjvbgd.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gtmaqgmuph.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtnrtnyhxh.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gtzyznixce.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtwqfvvykm.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtpknkdgms.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gtcsvzprxb.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuwmucob.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gtlhewzkcq.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtdfcevlmh.html

UserId = int
来源：http://dali.wangdashe.top/Article/details/gtpsbkswaz.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gtsdmfkwmi.html

@property 与 @x.setter 配合
来源：http://dali.hnxiangtu.top/Article/details/gtozojvsrk.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtucnywspk.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtkbiglbdk.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gtgbvxzoap.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gthdypgyfa.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gthweqkhym.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtacaskehh.html

[U33] Py：打包发布
来源：http://dali.xuanzx.com/Article/details/gtrsktueco.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtzhavlspf.html

[U34] Py：判断编码
来源：http://dali.hammf.cn/Article/details/gtzqopunqr.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtlaimrliy.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gtzunsectp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtescuhgrm.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gtfjnxwgwh.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gtzpxlcfsp.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gtbwdhxcvm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtdfnjyfwi.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gthzeapgvc.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gtnrmmrklh.html

[U39] Py：判断是否在交互环境
来源：http://dali.c1oappe.top/Article/details/gtnvwsjogk.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gtvbqgnyrm.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtttzanczp.html

print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtbdltlxkq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gtklwlyeni.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gtxfrjnwvc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.pengpengdd.cyou/Article/details/gtqhdyodms.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gtpoawjfos.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtwygvsfek.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gtuvccecta.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtezouxgqm.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtulufkjuc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gtujdwqtbj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gthpnvnbee.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtwoshhxrk.html

?string $name = null
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgescnyqt.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gtwnvwfesh.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gtjqzjfkhw.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gtxodcwvgs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtmfjlidjj.html


<!-- 参考信息 -->