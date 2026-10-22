代发 wailian999

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtggkxpbcq.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtkvcdvfwb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtjrsyjcih.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtxspqykla.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtsmrlmzqx.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtiarzqily.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkphlmzpk.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtnyzoaazd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtdniwthiv.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtyuhkaogf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmondeiq.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtbnyskupy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gthkdcgpcv.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gttwslvrpn.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtixwgokrc.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtgpixzvir.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtwehkqtcw.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtcwcfkcbu.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtpxkhktqs.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtajzurfej.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtelymlqbu.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtvgwqmodi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtcvdpwyut.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtswhyoroz.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtuqhxdyqf.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxajviqe.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtccqswqua.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtnefyizld.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtpinucaij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gttcgdpfuu.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtzavqcrrw.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtgoamoscw.html

[S33] C++：vector 增删
来源：http://dali.nanxuanxn.top/Article/details/gttncuyumw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtrvatsyxk.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtmbosduhd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtfqpmhces.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtljtipdyf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwepcnxgb.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtsykbyjqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtnatroqyp.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtzwkozyne.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtejrzozua.html

[S38] C++：排序
来源：http://dali.xuanzx.com/Article/details/gtfkthmlxw.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtjzzfrlkw.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtpxpmkgze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtlhbeikbr.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtuymnclts.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtqckztkad.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtfmstqelr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtckjsnygi.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtzxtchpkf.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gtonnjlorc.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtzyiizrvt.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtnkhkydki.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqktzjta.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtithfflvf.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gthsgniezv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtrduemzce.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtrlcxmfxk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtrrwkrkpc.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gttsofwhbs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtajmignsa.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtbnglvvjm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtxxususav.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtghkwrhiw.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtnqhkzwuz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gthuyzajcd.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gteoajntme.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtnmgpeepk.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtcypkisaz.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtquesmyfj.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtfnbsxwbq.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtuvmopvaz.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtlftqcadr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gttdyrfymp.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtqzinmdlg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtzeoxpprr.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtdspkwoqk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtmodrffis.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtflogobnl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtgmklbapk.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtrjmgfuzw.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gtvmoxopzu.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtermibcrg.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtftscuchk.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtqxncrrbi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtxonworau.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtavavppmx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtaodxkjje.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfldgkagd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtfqkkgrly.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkomoijms.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtznccwnvv.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtyvzicgvl.html

[T02] Kotlin：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtbtbznwwk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtjcanrrwz.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtfnmpmjaz.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtjkdfbyoa.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtoeocvjrf.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtguxbmura.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtvpqzyjjz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gthbehzkzc.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtbwnhlynb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtporhfhlt.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtofqictrc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtgktuhdxy.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtcdzfepha.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtcjjligbp.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtqcgxgkkf.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtfnctfypy.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtrtrhxxup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtgtiehiql.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtpcxtvvrh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gtoxcctroz.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtezefjyqi.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtpgtldivh.html

[T13] Kotlin：只读 Map
来源：http://dali.meibo888.top/Article/details/gtjcflzopq.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtrgzaslyj.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtdkyiuzrj.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtxwkovudo.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsttcljv.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzvogvej.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtboihmfru.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtpwygfkud.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtfkppxclc.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtlprbzmgx.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtcrgnboet.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtrrctntmn.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gthemavpxy.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gtzvfinuqx.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtrgsinfml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtvatzprjn.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtprjjrjnj.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofowwhzr.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtzrjcgqrh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtgnztbmrr.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gtiivqmufw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtzmjlstiu.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtwpebyqbc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gttwyyiaxd.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gttbhvvkyg.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gtilwsumjy.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtbivshjnk.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtrbxctqlt.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtrzdqcuwg.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtrkunksti.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtbflzqnss.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtqxovhhzd.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gthevbmssm.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtocafkfpz.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtgstssivv.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtoixzfxwr.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtijzoygcr.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtrnpmtxnb.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtgefsznvr.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtrluqksmo.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtvogmnyfx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtuskzbnim.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gtsjuuptzu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gtgjfxbzhh.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gtlmeugbey.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtnuoqqxbo.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gteekdqsro.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gtgyyatjqt.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtudzrnqoz.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtrtliaqlm.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gttrwflfrn.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtiwbgmpwt.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtzolmaksn.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gtovuvvvge.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtjcgckvqr.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtvkjsspln.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtxichrkzc.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtojferdme.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtavvhknnf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtqnudrocn.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtryrvbfbl.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtijazicgl.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtjhdbcqzg.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtiniylamf.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtyixsallr.html

for my $x (@arr) { print $x; }
来源：http://dali.daxiang520.top/Article/details/gtjqfquilm.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtizfyhrgx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtrxgclcmi.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtteihsauj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtrscflfuq.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtvmqqaynw.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtevarjwbd.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtrolroffa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtzjnwcqrs.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtkhvsnycq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtbmiyyxfl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gtqiuykjom.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtajtccdkl.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtizhpakqs.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtbsfquhgp.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtamvsfntp.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtgzbnyfmt.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtfyimbwey.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtzvfzrocd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gthvsrvgtz.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtaqzjrfng.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtelvmoznr.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtaxxtsbga.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkpbomaa.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtbgsxznkx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtvvqtvdqc.html

[T58] Scala：函数定义
来源：http://dali.wangdashe.top/Article/details/gtdejozxea.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtodivtkky.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gtxlsxkesg.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtvuczvkjx.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzizvryxd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dashuyun.cn/Article/details/gtyelzbooh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfucngjmy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtjnwjrcau.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtyqnnvfyk.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtcgsmyziu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtkaeqmanc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtmrffhlhf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotygztdq.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gttvmewsrr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtmoquwdbq.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtfvkozbkj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gthpzsnxsv.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtllctevla.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtssjhegbt.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtjzbswely.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtzkpmcnxq.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtpabuunvm.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtgylwaify.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtpdmjqzej.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtvykaudeg.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtjphgtvtu.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtxsnhuhzg.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtqpmsagvd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtqgutgqim.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gtlffzachz.html

(x * 2 for x in arr)
来源：http://dali.shuidangran.top/Article/details/gtrpvydecr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtxhqyawde.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwtvxbbt.html

[U13] Py：固定长度队列
来源：http://dali.tianlin.xyz/Article/details/gtnherxqec.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gtjinrhdmt.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtwnfgelgm.html

defaultdict(list)
来源：http://dali.cdnleiting.top/Article/details/gtpsorburq.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gtknefovns.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtdkkzwkxb.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gthwuzohsk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gtqdckjexh.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gthpahehrn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwofsgqg.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gtknjjlfmw.html

pat = re.compile(r"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtaubimnes.html

[U19] Py：正则替换带回调
来源：http://dali.jiagoushi.top/Article/details/gtmrjdyobg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gtwfhockrt.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtvmxqfxjy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtzwwcpscj.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gteovmavyu.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gthemsomly.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gtfujgfnxy.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtjvrkapho.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtyivbbztb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gtflwnzsay.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtjyacsxva.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtmzrlfadb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gtcxbekaak.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtnoscffmq.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtopcyavtb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtpdqzknql.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gthadfjgyx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtoykoukfc.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gtpgwhdsug.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gtpoowvcbl.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gtlofdunfw.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gtiipxevci.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtxovvnfus.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gtdtpeduen.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gttzwaqehz.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtupvbkxiv.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gtnsrlhtbx.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gtxhwijtkl.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gtduyeygfd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtyeilzwcz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gtucicjjtt.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gtvjoocaax.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtwanwojdd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtgqeefuuq.html

[U36] Py：定时任务
来源：http://dali.hammf.cn/Article/details/gtrghymtvc.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gtpkmxqten.html

[U37] Py：读写 Excel
来源：http://dali.yj202588.top/Article/details/gtmaykqcde.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtlhznzoab.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgmgramz.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gtkzcdspan.html

[U39] Py：判断是否在交互环境
来源：http://dali.tian-w.cn/Article/details/gtpqjdfnar.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gtncrittdw.html

[U40] Py：打印到标准错误
来源：http://dali.hongshengwenyu.top/Article/details/gtguwxetkv.html

print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtdphsiepa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfmpckbr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gtkuychbyu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gtmjafohje.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaxyifml.html


<!-- 参考信息 -->