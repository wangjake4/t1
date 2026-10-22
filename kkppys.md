代发 wailian999

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtwikqzhuo.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtfjkqjaas.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtbqyihonz.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtgjdipiam.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtkqqtucqg.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtjunefejp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gthwrsxuja.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtshmiilte.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gtuyvfczwl.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtozzxkbgg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtwxzugeow.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtuxsvmwje.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtymsflblj.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtpsfzhqgb.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtqtkibypj.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtvxlmrgne.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtwujeybhk.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtuonammqz.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtqxritcib.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtpditqyzy.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtqhwymxtu.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtcjzcghpt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtgcjcdckl.html

[S30] C：头文件保护
来源：http://dali.zycfv.cn/Article/details/gtbohrgjqq.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtflcgkdwx.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtwrwujiao.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtkyvchztq.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtplrqutlf.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtowdmqmau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gtmexowwad.html

[S32] C++：字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtmmcznmas.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtxfrywtur.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtkldwvmhp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtneafnsxo.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtyrquydxw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtksbsoras.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtomgkzybm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtlwadxecb.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtczskiuqg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtxadukpgh.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtqnzpnkrb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtqpfpfsyt.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtaeepcypv.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtbtllfbxf.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtyltacmlp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gtwzhujbwn.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtesyahtng.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtrfuifuem.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtfnoraojm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtmbzfloeu.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtrisolhcd.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gthvyfkacl.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtbiwlbgkp.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtmtomgwap.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtjevlqrpl.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtyamouayr.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtrprexnua.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtsbwkdohd.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdbsqimp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpgsjdefq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtpqpzwtxf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtlyiakkcx.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtkexplllu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtuarwgrko.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gtxtyxlofq.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvwtjgdc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtdlrrdbjo.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtixcahets.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtcxrgfevd.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtjznimwgy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtdclvojbm.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtfmexaryr.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtckxnzibi.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtrrwtokxw.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtsulgjdvc.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtobdkaqkc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtkefsafjk.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtmwaslqha.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gtcyhepstl.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxivsyvo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtfjvdxpgx.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtzwdqjobc.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtnvenjqhs.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtiisfgozn.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtxngcsthy.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtbtybctmo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtobnowhjb.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtlyplfbra.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtficrdqej.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvvvdkgmh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtxbfxwqct.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpqubbpbb.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtwwetrlxw.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gthpaesxyi.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtuhmymprj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtfawzfpzs.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtcecpticb.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtuwrwelvr.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gthkvhbidu.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtlkpkluab.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtluywizfo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtathyeosn.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtjhbrnqcz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtlabcyqza.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtmmykpytd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gtcwmlshds.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtemfirenb.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtsprbhwny.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtyoixmctk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyanswgo.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtfexssmnb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gtroqlqkbi.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gthlgugwmt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gtzvceikdp.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtyfatlrcr.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gthaxlcxvx.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqrpejzl.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gtxlcikkbw.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gttnehywco.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtrtknaamt.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtyqdihiuq.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtovpkbrlt.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtyjozzedl.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtutvkmlpk.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtdkaiqlbd.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtolcjkjym.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtjcfepqtn.html

"值: \(b)"
来源：http://dali.hnqzz.top/Article/details/gtnlesrlkf.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gtqsmeydtn.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxnnrnqp.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtlcyqbhng.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtuqkgxitu.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtbsyazoza.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gtsdudenvu.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtzhdkmkff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtglngpwrb.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmuehinyl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtpgzszzro.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtsmplthfj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtgunytppy.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtugiosznf.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtpsghcjmp.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gtjrjmnfav.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtrijquxma.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtfmhhrdto.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtiabkefqk.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtierzqkfv.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtdiojiqov.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtoztnopia.html

guard let x = opt else { return }
来源：http://dali.chenlongwang.top/Article/details/gtvjciqzja.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gttjfgaupi.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtierpcptk.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtubtwxslt.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtypayzqvw.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gthyqcfvcf.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtcunizlpf.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gttujpnipw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtamltwmsp.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtfwfcgirm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtqqpyhksb.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtfhwdvhpa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtfhembnnn.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtdxjqpwiw.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtsbrijrxd.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtdyzedihq.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gtyevervqf.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gtwbjdgxch.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtgksesfjb.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtshfhfuzn.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtdwsuubos.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtgvctiuyu.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtvjnvkedi.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtcfprrlyr.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtplnggeqq.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtkstppycc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtvgygzmgv.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtlmmtyxqm.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtqqtljuqs.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtmxxrxxci.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtubfgemjq.html

[T45] Perl：数组遍历
来源：http://dali.gotoacloud.top/Article/details/gtjcfmpjvq.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gtkbekqdoz.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtujhefizk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtivfhncvi.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtadoljkpc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gtfnbzlsbw.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtjtiwbepe.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtcvghfvoc.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtcmthwaps.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtvxwlynas.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtluhveqot.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gtzlfzzuyh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjpgacle.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhuogear.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtnczjxckk.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtrtxiraqy.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtthfnqqfz.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtxzofotyr.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtmwenzbqe.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gtjkqixdmk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtkecolvvv.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gttoguolqw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtkhmecnwb.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtnevfzhkl.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtrozkvhgd.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtrwkxhuvm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtgtrsznyu.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvhbpmmri.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gtjbdiluml.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtghocbvdh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzznylxhy.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gtqagdtucb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gttxvhseaq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwjrtghub.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtrgzhdilc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrowqbev.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gtwenubaiq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtfxxqcfhl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gtbmtzhbhu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtvmppyaaq.html

[U03] Py：加载 .env 配置
来源：http://dali.chenjidiqi.icu/Article/details/gtbpyfctzn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtcewvafcz.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtgkpejzor.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthglsgdib.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtdsxbbhqx.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtlzjxochq.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtzwmidbwh.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtudvmptbp.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtbbjjgrwm.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtpctcdgjo.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtxgxipwsg.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtqwhsdgah.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtpjvckxmu.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gtnseuqijv.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtadoseldd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtvqktslnc.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtlxwlsihe.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtmyeibhxf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gtxbrikcmo.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihnhrowq.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gtrcxauirn.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtekavtmxv.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtjvssqcdd.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtshnnavpq.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtduxxqrif.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtsevbgihr.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gtqculazbr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjobgscqr.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtxifntjgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtylnvvlxq.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzovnmmp.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtahsuuyip.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gtnnmcbsnz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtpogsmnze.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtklcsfeje.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtdvbvzyoo.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtqxoqbcns.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtjnwuidwy.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtzwqlbmup.html

list(zip(*m))
来源：http://dali.cheryme.top/Article/details/gtvymtbjpy.html

[U23] Py：分块读取大文件
来源：http://dali.jqgufenzy.top/Article/details/gtsjvonkxf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gtcqjkhypi.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gtqielufmh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtgjdhkoeu.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gtmmxrpxhk.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtnfjmyblb.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gtnvsocrdq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cucudq.cn/Article/details/gtdsyxjjdr.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gtarjejuwr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.feifeiyinyue.top/Article/details/gtkuewidah.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gtygnewjkn.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gtqagacqxk.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfqexsjk.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtpftyhdoe.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtzxsbhchb.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtlyhdozfd.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gthzsmammx.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gtpduzmtlv.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtjlneixhi.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtcekuecxr.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gtwrqyijxc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtrxkdnuto.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwicnhtx.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtduqphwln.html

[U35] Py：发送邮件
来源：http://dali.ivvv.top/Article/details/gtdfawwddx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ybcxt.top/Article/details/gtpauruejm.html

[U36] Py：定时任务
来源：http://dali.aizwys.cn/Article/details/gtbhehsfnj.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gtxbbjfeoh.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gtpznwyinp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhongyouzk.top/Article/details/gtpbffphjm.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gtvpdsdsch.html

Path(__file__).resolve().parent
来源：http://dali.guannengcc.top/Article/details/gtpkimmiqa.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gtnhpbrfrn.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gtpogjbxzr.html

[U40] Py：打印到标准错误
来源：http://dali.birdmap.top/Article/details/gtzcskzwbw.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxczlxti.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtzjtzfwvj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gthuzbdemp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fzhhl.top/Article/details/gtewruotee.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiekkkbct.html


<!-- 参考信息 -->