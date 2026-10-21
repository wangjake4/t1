代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtrrunzcej.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtgsgtqqoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtogmxgbje.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtglghycfd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtxwdvfbiw.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtwqpxwhgc.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtajhfswgm.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtvtpnjguz.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtydgwchuk.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtaedinhta.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtzifvdmdx.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gthokqnhuu.html

static int counter = 0;
来源：http://dali.cdnleiting.top/Article/details/gtquhtmtch.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtkbgaqrbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtttyxqkwo.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtmutywwvi.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gteujnmwwh.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtckxprief.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjofiefqu.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtdtcxdfij.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtrxijpmxx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtrwaambqz.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtisjrzezz.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtsmvtzuci.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtsvyofjmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmhuppgb.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gttuckbsbp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtbztevxer.html

[S35] C++：map
来源：http://dali.yj202588.top/Article/details/gtxtsbdfji.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtrvxmxbsx.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtqiopepij.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtevardlbc.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtgqoketvm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtktwjfikv.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtzzompxyu.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtytlvzlqq.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtcvppsvsl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtsuxrhgid.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtabyegwzf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gttfoedklr.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gtvyorrtaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtdnwlgdnk.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtlxsanyok.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtvnldxpkl.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtyqiuiulr.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtccxbuupa.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtfzgsscph.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtbwvbmmts.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtqyokimtg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtiutonwdu.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtmenpfkco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtczslkbzs.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtkvxtgrtq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtvhezoudr.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtvqdrnazm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtkeqrxhmh.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtheaqxaqn.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtyfywyruc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtkmnjdkmj.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtdzldxqsl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtcurzabhs.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gttjonqjma.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtxbpovejw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtngluxtwv.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtrgmllhyi.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtwmhxxsaq.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtbeygkqjc.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtroufpvwj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtfgiwcxva.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtngwvnarw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtaaqpuinp.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtccnrquuw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtfxouubur.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtucsmgjit.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtwlpdjwnh.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtdczcqdkj.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtkfuvhahc.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gtghsojzok.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtohkbjips.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtiioeyrqc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gthavmxder.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjgmmhhpb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtivpzkrqg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtylgymfyx.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtcntqqpbw.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtouzrgvdh.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtpoaxrpit.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtebhiplxb.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtjdmiluks.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gteqxfhhjp.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtehtnakrz.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtkcunvwwv.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtrhbpzbrd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtbmevazcc.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtpzarqsfn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gticzhmrjq.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtoutxaiqz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtyihocubj.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtwdkagtop.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtvydgzgot.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtgwjcumpe.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtksnvtbop.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtumxvkpta.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtsxpiqqlh.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtcqyrektc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtszhfhkbj.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtigkrbcto.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtblxruoxy.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtzrkrqqnb.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtpslpzflb.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gtrjnlnhek.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gticdytxmt.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gttpgkzxhc.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gttgeaheuq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtttbzhdrs.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtjbfjmkyo.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtxradetdp.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtmsawyumy.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtsxrciqjv.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gtakunifcx.html

[T19] Swift：可选绑定
来源：http://dali.haohaochexian.top/Article/details/gtvprprkrp.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtpsgjhxmb.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtoaskeeve.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtxwwwqmgd.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtomxoydyp.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtyhumdxyw.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gthsocfpfa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtnungeern.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtxoayrcsi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtewpkseaz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gtwmbpzqda.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtcbgualcf.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gtrrgbtwtj.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtlvsvknms.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gttlwvqgtj.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtgfhglvyc.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejghflzl.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfcolaby.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtuhijztft.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gttbkqixrb.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gthtlwzvzs.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtkxpyzael.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtqsgrndrj.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgtxohwp.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtahdvkwvv.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtwizpxqzk.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtkmzmjucg.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtbhmmkrfb.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtmtsytlqq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtiucpqcdu.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtvxzggaei.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.kuanghao11.cn/Article/details/gtkcsmyytr.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gtnlckmptk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtrcxkwxpc.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtsjxtohdj.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtqgyzynoi.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtijwxsecn.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gthcgibhmy.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtqzzglqbf.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtrxazboxq.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtqtpquede.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gthzppatfw.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gtqydcipih.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gtktumsnta.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtuagxvnhb.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtlmrvatvl.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtrtvavebd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtgtsxgatc.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtralrzkdr.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtphiwyxrk.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gtpctyzvcg.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gtpxwebmik.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtfwwfeqst.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtyvzlatbe.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtlpbanxel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtwkwreynq.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtxbdpvnsl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtqfpmzwzv.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtbrpsuefk.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtgnyvamhn.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfyregfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtrdbsoway.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtsivjmxgh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtfhezubwb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtawjvniqp.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtaqgvujhi.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlacdogd.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtyfxyzpwe.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtzcaftsvy.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtjppebpmj.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtxiwvjuxw.html

[T54] Scala：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtytboiayn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwvvrusfx.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtyyifqxlj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtlomqgafg.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtgpexupln.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gthrjmnznw.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gthnyvcims.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtvqvssuim.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gthdxcyygh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtdolfbmay.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtxybjblxp.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtgzfiwlkt.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtoslegzgs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtzabclcas.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwvpzflhh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtubkdjbuy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtipjareco.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtjfkikexq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmiamymp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gtizvmttoe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gtpbrzmyxr.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtmdutascr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtgkkoqgap.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gtyiuyaiir.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtjkujjpym.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gtwktgqvid.html

list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtkierqeew.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtokfipzxt.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtdvrwfrcn.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtfwivyywe.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtijuzbphb.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtgbjajhsj.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtmaatuxfn.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gtrawyzbfi.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtiaeydxwn.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gtmnvtxwev.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtzpvzvpyp.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gticwuoefh.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfshzdmpd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtmurzprtf.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gthiwihghk.html

[U13] Py：固定长度队列
来源：http://dali.yj20258.top/Article/details/gtwlfuxscp.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtkjnnnatr.html

[U14] Py：分组收集到列表
来源：http://dali.sufxvd.cn/Article/details/gtepudugsz.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtadkdektj.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtrxlxxecw.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtecsuzbuh.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtsvxpuman.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gticicjlvd.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtljgyoosb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtzmoqphbh.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gtxldzuvns.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtprhioblg.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gtptwsuskh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtslrjbemp.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gtxssvheqi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtkkcjrpqi.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtewkjkoyb.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gttzioywva.html

[U22] Py：矩阵转置
来源：http://dali.haohaochexian.top/Article/details/gtjoclhxqh.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gteluzdbaj.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtnzzerunz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gttwbihybn.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gthffizykr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtdhjldtzx.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gtberkhwow.html

csv.DictReader(f)
来源：http://dali.sweek.top/Article/details/gtwaavrsmt.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gtixifzpwn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdsecajo.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gtmrhvgoiv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtbbtcirwh.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtdefpmnix.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gtraawvmmr.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtnxxufvmi.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtypymlckb.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gtgefnoiof.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtyilmkngn.html

[U31] Py：单测
来源：http://dali.pycfn.com/Article/details/gtioudruvp.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gtjlhukdsq.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gtycmvieyk.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gtyfjxbcpc.html

[U33] Py：打包发布
来源：http://dali.hongshengwenyu.top/Article/details/gtbfeuticd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtxzjatorr.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gtnugchsvb.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwgdjywf.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtalzrbsli.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gtrtxqdxjr.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtpaylekny.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtonbjfnjh.html

[U37] Py：读写 Excel
来源：http://dali.zycfv.cn/Article/details/gtapjddyrc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtyzaxapps.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gtmgnimyyt.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gtrurhzond.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gtvxnycffb.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gtvxixjyyg.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gtwoimzrmg.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatpdmnwm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yongpay.top/Article/details/gtcttxctyg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gtbmsqnixr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gtbedsoydf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtbobwgpbi.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtcznriwel.html

namespace App\Http;
来源：http://dali.xuanzx.com/Article/details/gtuzbknxur.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gttzicfmge.html

declare(strict_types=1);
来源：http://dali.zhiwuduotai.top/Article/details/gtvtudanha.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhengqikj.top/Article/details/gtmwonaaqe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtuwjxhcfi.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtjpllnsxs.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gtgrsegyxy.html


<!-- 参考信息 -->