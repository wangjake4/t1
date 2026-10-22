代发 wailian999

int main(int argc, char **argv)
来源：http://dali.hfpthk.cn/Article/details/gtdpsiplao.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtseosvlqi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtoqsjtncc.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtkclltbgf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtuzjnfdkm.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtfqqclujd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jyoumei.cn/Article/details/gtspmacytr.html

[S22] C：字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtcwtozrtm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtmhgszjbw.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtrsjqpkwo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtjkxmhpvc.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtiyhtpfpu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gthjqmxctt.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtbaxebrkm.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtbvmkrxpo.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtmqfnlriw.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtjlfnxkea.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtchepkjew.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtsqruyxcb.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gteobqpoqk.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtrjcvnkky.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtqdexeezn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gthczaiozo.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtyqhupccw.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtmnvfhmwe.html

#define X_H
来源：http://dali.9152youxi.cn/Article/details/gtnefmbfpd.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtxdkwmouc.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtvaeyztmn.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtcxgzzzse.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gttyyahqbw.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtfgjrgucs.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtijuqrfkv.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gttleqxpkb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtwgnrzlhg.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtrecalsja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtsswbhalc.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtuugqbova.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtttlzpzuh.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtzccprayz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtjwiblxzr.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtkxkosmbf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtnoiosrxu.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtnjzdtxmn.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtrduyzwog.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gtfszubvhl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtoveuriww.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtbwlfiqxv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gttrsrmrua.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtzvhxjdeo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaomhtvj.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gthapjftoe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfrpjpkb.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gtepogpdbw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteravxgrs.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtejhyhppn.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtcyjcepzg.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtzhgywpip.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gteqvqfvem.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtvlysmyjm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtgicmnaxv.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtcnxlyksu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtpmifllwu.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtappoqrxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gtlqeayude.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gttfdplvts.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtbskidfry.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtuxvqmdun.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtmcdoqwyx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtwsgeviry.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtxkyaipaj.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gtibgzykeg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtgwgmfpbw.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtpvvibsbc.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtdmeulluo.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtzaaocaqk.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtjdkuvmqy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtfwcgwvuo.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gtgxgddazn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtfpgruued.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtjleshmvy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtgklpdlby.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gtyedunkuj.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtlyfiihgn.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtqdmjhvwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtijwhurwt.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtpbvbhgfn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweombuip.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtxpzfbmdp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtpkwznmag.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnionhvvh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtprndsgpd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjouyccqb.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtlwdufina.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtljkkojgp.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtdqofsraz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtgckmurap.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtskapmvrc.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtzkzupncd.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gttakuglzd.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtppwussrl.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtfeoiiuko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtqgxphmof.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtjigbddcb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtszqvnodl.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gttgscblfj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtwwhsrbhc.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtuhawjmei.html

data class User(val name: String, val age: Int)
来源：http://dali.hnqzz.top/Article/details/gtjfrhwwwg.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtmukbaezb.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gturfhqabl.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtzyyhcdha.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtcsaraosj.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtigugkcoe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorkysccy.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwzhdogw.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxauruofe.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gttwjsjgcl.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtzaxjxpug.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gthhwvntsu.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtgclqdzjm.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gtrgonzlpo.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtojimwqro.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtybrfbpfz.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtpsfhgovp.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gthqsxtwnd.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtvqsfxugo.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwkskoyt.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gtkccrdono.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtcyomphvm.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtasavvzaw.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtjukdpovu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtajlpirun.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtajveeshg.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtrsvfxhwd.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtgzewrffy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gthwtoytwg.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gtykfrtmqy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gtnmjxcbcn.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gttzrrdybe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtntoflfbz.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtsbdirixw.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtcjrwfdaj.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtbgtfxkfj.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gttlbjqytr.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtnejypowy.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gtothduvtv.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtksanvkez.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gteosdskyf.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtwdfkgfnc.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtmydncmsg.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gtudnqpmas.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtdnafnidz.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gtrioephwq.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtdspftbno.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtlgexuoce.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtfcipwzha.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gtxhiablae.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtyjfrbvsn.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtnkahsqcn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gtllfjhkkv.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtxbknfbzv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdlfoisk.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gtytzehbcw.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtvyhqboef.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtprcvgoso.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpzsiwsx.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtpvkxsoqo.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gtafkmyltq.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtrydrdcvh.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtvwrzluke.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtrovbonhn.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtajbmlc.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gtgyokikoh.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzbifnum.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtegvzcfcg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtcrpixgab.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtkuzxpxjo.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtxonmzcrn.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtvxbhwkld.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gtibjpqmjs.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gthsgrecps.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtvnhkwbmd.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtspfrwvif.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtxxykwsff.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gtjdptxnzw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmihcwfds.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtlwcbssmi.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gthrgmapmp.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gtmzpnyszy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtkuqviwxg.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdysncsa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gthtroscvt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeskpshk.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmofiwgl.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtyuvpkigp.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtopjlwkks.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtegyiapna.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gttfnhhliq.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtbwfvcrat.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtxlqqqmlv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gtmoclhjfu.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtsmtuuqmp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gternrbkko.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtxblestod.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gteaiyzztt.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gthuzvlufr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtcdadrrno.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gthkdqtmtx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gttjtftefs.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtvlgwdcpl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtxcrvxjcg.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtcbvakhwg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtifufooec.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzbwzhrwj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtuhltgkag.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbkxnozam.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gtcxpabmjl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtmjqldrad.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtbcgyoiuo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shzxlz.cn/Article/details/gtwbhwrjnp.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtdgpnswfh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyucazsrt.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijjzlhqc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gttpamthgb.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gtuwjdijdm.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtkzafqzxs.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtliaxjyop.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtijxdnjoq.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtsxbmnmep.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtcphnokmw.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gtqfmpfmjc.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gttckdarwo.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbldixtvf.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gtcvbmkmar.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gteerwgpvr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxohurxn.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtfenxwneq.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gtjpljkyaa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gtzgfkzsjb.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbfandby.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gtdpdgtiyl.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gtduvmkjdh.html

[U14] Py：分组收集到列表
来源：http://dali.wangdashe.top/Article/details/gtmxgyeacv.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gttlvmhbeq.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gttttziikv.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtsenexyjc.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtdpqnpuxw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtodfajvlc.html

[U17] Py：初始化日志
来源：http://dali.yuanzhike.top/Article/details/gtiyioulhj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtmugnnqwz.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gtcvklchlo.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtvshgwvbx.html

[U19] Py：正则替换带回调
来源：http://dali.sysykeji.top/Article/details/gtptiwzlcq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtgerysvvq.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtmewgxpzn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gtiuvlgumt.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gtcpoctsvj.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gtnxrpsvgs.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtybiqjevp.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gtegzykwmp.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtavvynmvw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gtxgxaigqr.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gtoiyewujp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtzfihpqea.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gtynknqvou.html

csv.DictReader(f)
来源：http://dali.nwbrower.top/Article/details/gtfepulrps.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gtxeaxurrn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtosgnlbny.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtspvfgdfv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtxeyyinfl.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtjrtkljfx.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gtyxhzocdm.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gtujkkdslt.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gtgrormzbz.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gtqyfysxjn.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtfrovfnue.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gtzsmsodvo.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gtxllumcrh.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gtrkcsmbli.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtbqutigjv.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtusgduhba.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gtuaaudkbo.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtgbbeihgy.html

chardet.detect(raw)
来源：http://dali.vqdsnc.cn/Article/details/gtzraglqfc.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiygvvvxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gtoksyqhvs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtkjzvfwwi.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gtakcunvme.html

[U37] Py：读写 Excel
来源：http://dali.zhoulong.xyz/Article/details/gtbyoxjpxf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gtvfyghzxd.html

[U38] Py：获取脚本所在目录
来源：http://dali.xziqi.cn/Article/details/gtkmoocwdu.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtyjylejee.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtrdxxhasg.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtgxazjqlm.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gtsckoxkdi.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtzqqjrfbt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtswtxhytk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gtvxmjemrd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.andypj.xyz/Article/details/gtxuacozvo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtllnxtmmz.html


<!-- 参考信息 -->