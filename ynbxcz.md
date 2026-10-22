代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gt2gylfrqca.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2kdgrbfif.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gt2cztowecq.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgsqrktn.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gt2ndefotmd.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2qtwlchgx.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2dapxoenx.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gt2omtwctmv.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gt2rttovxaw.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gt2wznnxeyh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gt2kerguytg.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2usmjrxrl.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gt2aztumfko.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2wehpaarn.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2tukpgxeq.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2rripczgw.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2jlumjdur.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwjuvvzf.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gt2gnozhnho.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2zjoossld.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2cbsfotdr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2ujvxvedf.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gt2yhqctswv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2daktakiv.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2knmtlcgp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2juussktq.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gt2zskrzmhe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2rrflwzrg.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2qlmgvuzy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gt2ntotjzse.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gt2okpuxuwm.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2gzutnctz.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gt2kueupemq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwpornuw.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2zsfpzcga.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gt2mgceaudl.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2asrirycx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gt2hrkzfpkn.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gt2zztdbutw.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mucxiytb.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gt2xxaawgor.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2hpytpeij.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gt2nusbncfd.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gt2etmmlhit.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gt2zqevwgio.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2olxpycgz.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gt2upmkikcm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dykgffqe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhvzfqkm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2vlcboqdc.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2pjeqkhim.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gt2bskauftu.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxrxzzbb.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2zcwnbmnj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2sgitzqco.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gt2oqipsfen.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2luimuqaj.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gt2evurexto.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gt2cqxpnhmc.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gt2hwuudkpk.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2wmpwghgc.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gt2slobdvym.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2rymoybdd.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gt2mwlmvapw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2huucpkrc.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2sachanpf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkeicyxx.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gt2dczfjjbw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gt2vigptnqk.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gt2bonvcbcp.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gt2myqthnwm.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwlomkvn.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2fdpuejgl.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gt2oqtkmmvk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gt2uokhxwxg.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gt2zjmgknqe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2ywmmboff.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2jcasloqk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2afqiymcm.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cbdhudwa.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2keupqdaw.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2aoryosch.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2selrsejd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2kivjqofk.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gt2priiprmv.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2astmwjkk.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gt2xzlhxcjm.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gt2cmjfphau.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gt2bbizwnoj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gt2wtzxnqhk.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gt2hmbfrtud.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2jwnslxyj.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2ktsdelfz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2xwfqmwds.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gt2dwsfiusq.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gt2fepqjboi.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gt2gafcewgl.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gt2ezjzegin.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2cufjddna.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gt2eckfixdn.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gt2mgdmucbs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gt2rlwkbayl.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gt2ndlrdyvc.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2fktpigkj.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2ohxdiodu.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xywqhlos.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2wayuhadi.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2cvqtbhwf.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddebjknw.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gt2bsfsrkwy.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2dzpwbbtb.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2zkvylbvf.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gt2knohekeq.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2xghbklzq.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2wxqabzwi.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2wqjkkzjn.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2nafvifse.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gt2lyjxcxug.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhljlwik.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2djhqehoc.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gt2ckegcoxe.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gt2bcibinpn.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gt2xworuehp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gt2angckofa.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gt2ziateuwl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2vtuavqjt.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gt2oethqdxz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2azgxpzbt.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahelhcqc.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovozayhe.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gt2iabgrewg.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2plevnjri.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gt2houmvmwr.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gt2qkahflrg.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gt2rbvqnffg.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gt2txrpjjho.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2odllcafm.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gt2skdkhmik.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gt2dyzpxysk.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqausspk.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gt2otbjanux.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2hukfvrit.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gt2ntivuefh.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gt2hwippmdz.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gt2cxdkyqdv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gt2utsgybok.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gt2oeqfrahp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gt2vsieafee.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gt2kkggqxvg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2wgfbueax.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypwxeapu.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2rnvnlsji.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2rhqatmfn.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gt2zeqevebo.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gt2ztezwdbu.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2kglarfcx.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2pofeayrh.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbiqiknt.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gt2utlbeydj.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nghnrkae.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2rzuuwoul.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2sfxfyfkl.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gt2hkzuifbd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqthepwv.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycroygxh.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gt2auchojkf.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gt2frppmmkn.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gt2wmfbgtrt.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2pmntzcfe.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gt2txhtvtqi.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gt2ubedkisn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gt2oxiexdol.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gt2uafpgqtu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yupnhgkc.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gt2yuosuwkz.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gt2wekvpvzc.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exoqwhhx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2bemuishi.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2iunujhlb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gt2gjqyucbb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gt2ebpajyeu.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2opvhwjnb.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2bxjuicbj.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gt2oiknvnqh.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gt2temcwcwg.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2ibsicwph.html

s"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2lfppxlir.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gt2nglkheng.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2jsibqmph.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2dbvbarbb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2dhlntcme.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gt2gcycijzv.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gt2avwzuhta.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2mzgimuvd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gt2daukfrqa.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gt2gfvsdjim.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258.top/Article/details/gt2ohkbfysu.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gt2dowowprj.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2urmlidtf.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gt2tpisohzd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gt2gftsamax.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2vxcrmwmk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gt2zsiqixfw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fykujoma.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gt2nhslsjqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ivvv.top/Article/details/gt2acioexjv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2dhhwhqlg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ysjmtgnn.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2ofxpgwvc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gt2guatitjl.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gt2kegyvvyg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgufenzy.top/Article/details/gt2kiuuypvv.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gt2kwfbgqcj.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2txryynpj.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2hzkxvzyp.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gt2pyysluds.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gt2cmsjbmqr.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gt2sjrifvlf.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyneiyxc.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gt2fjcgecve.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gt2gifdsrnv.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gt2rrtbpbta.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gt2urhxebgu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gt2rkkwkixi.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gt2zjclbyea.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gt2rxejfpsj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2hexjrohb.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxshoeaa.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gt2twjrirmq.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gt2gemmzgow.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gt2tpznimsm.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gt2qvwvcsnj.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gt2zwbxyjuq.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2ydigyfnj.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gt2nopwtrtr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gt2elfxzrbs.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gt2tpudwcgz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nwbrower.top/Article/details/gt2ughcxzcm.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxngoktz.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2gzhhtrxc.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfqbmfgj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gt2tugvuwjs.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gt2whncayzz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gt2udrsaayo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2topojcnm.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gt2tpahklvv.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gt2xrlqflcn.html

list(zip(*m))
来源：http://dali.yonumen.top/Article/details/gt2smesijfu.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gt2hpsdmxcr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gt2rhnljywk.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gt2whnlninv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2mmdgmxqm.html

[U25] Py：CSV 按字典读
来源：http://dali.guowangkeji.top/Article/details/gt2dkkrtvtq.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gt2hnhywhwl.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gt2rkspelue.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gt2vgozwcwo.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gt2iazsvnbs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gt2tdtxmrxf.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2tjiogeef.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psdyppgg.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gt2ippqgkzy.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gt2vdosphqe.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2psglijhk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmcqiob.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2cwjlqfgm.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gt2jcjdrhfs.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gt2uygncbkc.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuugylpf.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gt2ufcbtsmt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2aynpulmb.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gt2qzqvdfxx.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2dhpojjxv.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gt2isuhxcgd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxuanxn.top/Article/details/gt2ayqxyxpe.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gt2tusftcav.html

schedule.every(10).minutes.do(job)
来源：http://dali.iojbl.cn/Article/details/gt2vigvvkwy.html

[U37] Py：读写 Excel
来源：http://dali.zhongyouzk.top/Article/details/gt2cesdzpad.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkggdlqz.html

[U38] Py：获取脚本所在目录
来源：http://dali.sysykeji.top/Article/details/gt2oqcznscw.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gt2usdycmqv.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djqcrzfr.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2phqoynio.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rizlpzyw.html

print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2hklnslue.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gt2jdxphpyy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2beunjzrs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.kuanghao11.cn/Article/details/gt2hikfoajh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.haohaochexian.top/Article/details/gt2zbnfrpvl.html

[U43] PHP：声明命名空间
来源：http://dali.chenlongwang.top/Article/details/gt2eutreetf.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gt2pbzeagfa.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gt2dzdhzxzm.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gt2cwwtwlue.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sysykeji.top/Article/details/gt2fyuvqvwl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2esxgwzef.html

[U46] PHP：可空类型
来源：http://dali.nwbrower.top/Article/details/gt2gzcuamyo.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gt2hkvdwcpv.html

[U47] PHP：联合类型
来源：http://dali.cucudq.cn/Article/details/gt2ajoylngk.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvtzaxsv.html

[U48] PHP：纯枚举
来源：http://dali.daria6918.cn/Article/details/gt2milqymsy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gt2jueprntr.html


<!-- 参考信息 -->