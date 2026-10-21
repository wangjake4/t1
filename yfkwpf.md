代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhrazspr.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gttupyfvnr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtpjvidxnw.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtcnhzqexr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtarxqtmum.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtnryvgeji.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtzgjzbabm.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gthtnnojyr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevtsmwaj.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtlsanytfz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtyvbmnxmg.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gtgncuyyhd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtuincltgk.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gtwczyspar.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtylksvflu.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtsxgwqekl.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtfvocozhx.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtjwvpckhs.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtgervhcih.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtipzcxmco.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtrczarcti.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtoezylprl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtpxrzwflu.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtnkenrrda.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtgnutmxlf.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtckjnidsl.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxirkezv.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtkgbxqiki.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gtbjamsgyy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtcdazttsb.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtzemytowv.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtudfwrhei.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtbkvhuxql.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtzsbzaxqq.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtkaobwstw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkkxqrlt.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtbbghnlqi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtpqqwknfa.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gthdttbbtt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtvzxcgske.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtrhcleiuo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtzhbnmsxh.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gttawhsbrc.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtfthmljdd.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtemqbouvt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtuohsikjj.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gtpqoimrlg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtznhxodkv.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtvvnlfriu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtyicnruro.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtbnogywmk.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtnqaicnmg.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtbrippdev.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtulsktqgc.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtxfykidfz.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdebcopuf.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtasnxbjkf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gturdnmlkn.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtvgpeabrt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtqiwsvwui.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtwlbvroqf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtskgfyfeb.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtrtiqntzl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gtemicljfh.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtzsrjyqjw.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtfxtyqeww.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtdzijwbjd.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtdttaycro.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtginutumr.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtogvhnzbn.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtuytgulta.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtcmfmjjnt.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtgfncpwfz.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtwtcsxsfg.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtuzwwjhrw.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtobyidufi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtcucqzjrm.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtaqgjevag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtfaqcpbxj.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtsfehqksm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtaupldvyv.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtdagphegl.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtmyjwcbha.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtcnvffxqr.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjvzhfqpf.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtmmcirgns.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtkzmvbozq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtvwwgozhg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtpzmqxlhy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtiqnlpbsu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtvkhkwdrk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpynsnouf.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuwbcsij.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtpisftsmi.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gthuurhvxo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtfqwlfnbj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaowdntl.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gthtzydrqh.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtkivlqduy.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtbdvpktsj.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtueivshrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjdvmdys.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslfrzzfo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtptctzual.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtkcvjorua.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtazeofiie.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtcceeglcx.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtppzwnfbz.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtrwpmaszk.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtybcyrgzl.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtmpvirtow.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtkcviaugx.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtoikcbpve.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtasrppepz.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtotaxikwt.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtyighpqkv.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtfjmowbfd.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtjhhondkq.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gtwcmznhyd.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtvfdzezje.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtdgbxtwhx.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtjlxjzthu.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktehjdqw.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtjaayadst.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtgzlzoosw.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gtfmushaeo.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gtwxcfyfjn.html

"值: \(b)"
来源：http://dali.ybcxt.top/Article/details/gtoodotbsl.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtzqwyveuy.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtenkwceik.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gtunyfqonk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtckuejzdb.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtnuekxloc.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcwtxsmy.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtbpsjylnh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtqbtsjybt.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtaaswpirj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtxrohhyri.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtpdrsochl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtplbsdqqy.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtgdkdtekm.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gtbmkgknnm.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtznptztic.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtvneguzyg.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtwrfgjxzc.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtzculpjgm.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtqngknhbz.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gtoabzeyhe.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtymakfdoi.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gtifgnhmbm.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtgdihprsq.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtaxcyttel.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtynyqlwor.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtsfcydtsl.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gteqmpwodl.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtrghjhwci.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtfemmmsis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtqpxhbnye.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtxxqxoeva.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgufenzy.top/Article/details/gtdtzkjpkj.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtuqbaulok.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtzduzpghd.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtqybewjbo.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtdcytbdeu.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtskaoycsd.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gtoawogpud.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarwgyddm.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtdhdvlpig.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtzxotwxrx.html

string.find(s, "%d+")
来源：http://dali.daxiang520.top/Article/details/gthygrnwed.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiluytgvt.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtabopidad.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gtmxuclbis.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtayvnemii.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gtlfkxsygv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtelqpslyk.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtkufugwmg.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gtrzmpebkk.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtrzuuzgst.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtvpqzdeml.html

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gtkbwilrje.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtinzsdfig.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtpzoejrxd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtfjisuufo.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtwxiohdpe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtdbgabykb.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gtasezddhk.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyjtzzek.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtsprgecdw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtbjpjndyz.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtxkrccmte.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gtbcxhzdki.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtrwrccpat.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtkvyrhoam.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtshidsnjx.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtapbaquvo.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtihtvamkn.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtynqtwyue.html

s"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtpkstyjzg.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtaqealiwy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtosabcvvl.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtrxiyqbue.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdkdkiup.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtldvyipks.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhkhdqkw.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtyrnfegxg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtlpasfkue.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkslcunma.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtjmintxio.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gttopzfawb.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtqqbhqsrd.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtsuahhgia.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gthpacgblo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjycpnhol.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpezkjnxw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpsbvgiqk.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtxvfwderu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtmpurcpbi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtvgzgyenl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.iojbl.cn/Article/details/gtaunhdvue.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtwgcvqjzs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtsijfhnvd.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtbhbnrzur.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtvyjhwfeb.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gttlutsckm.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtgtxmcvbr.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gthpasynsk.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtqoxinejw.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtwcvldzdu.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtlrireyzu.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gtvwvqzbqm.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtqbjalvho.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtquuqqrlr.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwrrkvvf.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtetawuryk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtcoavgqwy.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtgdwdbbpl.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gtrupevmda.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gtyucxusco.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gthpqhjvys.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtysixrlmh.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtummuwwjz.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtccbcushy.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtxbnmbfzt.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gtsfkqhwfi.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gteyqffeof.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gthfdrorut.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gtiqrvlrpd.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtntslaxrg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtupltnppu.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gtlcwjhqbc.html

pat = re.compile(r"\d+")
来源：http://dali.cucudq.cn/Article/details/gtowvuvogs.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gtejfbpptg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gtywtpdolh.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtfukfrhvh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gtpwzischu.html

[U21] Py：自定义上下文管理器
来源：http://dali.yonumen.top/Article/details/gtxalaaxna.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtdnhdacup.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gtvgkbkxrk.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gtgcgcyzhk.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gtpaoovwcz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gterusigdc.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtcxdafszs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtgecwfkpe.html

[U25] Py：CSV 按字典读
来源：http://dali.hysaishi.cn/Article/details/gtuvkzggig.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gthvfhopig.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtybbuhkcg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtruldwbqi.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtdfdgcnmj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gtwmqbnjtd.html

[U28] Py：类型别名
来源：http://dali.aibaodan.cn/Article/details/gtpqbfklzv.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtrdoinomz.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gtlfgppqvz.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtbqgjmvqy.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gtesomollx.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtqigivrik.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtwafausfq.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtppwtptxc.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtjzkftdgn.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gtcpcbupzf.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gtgnfhwzju.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gthezaquqi.html

[U34] Py：判断编码
来源：http://dali.zhixingplan.top/Article/details/gtbgibvfqs.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gtxdihusah.html

[U35] Py：发送邮件
来源：http://dali.smart0.xyz/Article/details/gtmoroamqc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtgbawtrrm.html

[U36] Py：定时任务
来源：http://dali.xuetiantiany.cn/Article/details/gtxdoryjej.html

schedule.every(10).minutes.do(job)
来源：http://dali.hammf.cn/Article/details/gtqexwjksz.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtzxgeykqs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtcoyglhay.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtcovaqbmv.html

Path(__file__).resolve().parent
来源：http://dali.hysaishi.cn/Article/details/gtvkobasrp.html

[U39] Py：判断是否在交互环境
来源：http://dali.svipenyu.cn/Article/details/gteoqcufvi.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtkqrujklx.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gtcvosnnyl.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtbrxxpnha.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gtqytpjdlq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtiiggwqsu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtgfyciezv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtnvzxlcwr.html


<!-- 参考信息 -->