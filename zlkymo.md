代发 wailian999

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtgpysebkx.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtjchmdyqx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtlbrbwxpo.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtqwimbvtg.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtngijkujm.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtlaxxouha.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtczeuqlhn.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtjmoihkhs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtxxgijesj.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gtxisintep.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtxmaqbcmo.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtdsqmxtsl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtvbgumuzx.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtqfjqfmsk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtastyzmdj.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtsyuhtqzg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtdopkiirw.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtnuolzbbs.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtvsndxqxq.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtzqexetdt.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfjyxhhu.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtnfrevicv.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtsasbxlpe.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtwianemro.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtzabeypxq.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtdassfsfr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtegypmnzu.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtxsvftzit.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtotcovjrw.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtigdzxobb.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtzxqqsbyn.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtszdjkcyy.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gthenciisx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtjrlfxqfo.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtiwlvdnqf.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtcdjvgqxa.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtmryqivdf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtysaxevvn.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtvnjmakmx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtwfscnuhz.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtzysvxabm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtlmeuukgj.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtuglccltn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gttfilqfrd.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtoqdojbed.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtvlngbtbs.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gterihthhy.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtnaeapwkh.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtsidqmxuz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtiwbrqwqh.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gtslcjyqaa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtaabxomhu.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtsedxjnyp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtsvhzhakm.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtpyehzhcn.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtciwdjpyr.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gthfqmcbdc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtukustyuw.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtnmlrbfix.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gttycfhdbg.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzmlulkv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtgdwpiopq.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtorfbnbxv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaaernbx.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtkjjfmrzl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtnasdhcux.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtrzqdktay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtcshbftoj.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtqvbypkox.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtzzgaaewo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtxhpxvchz.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gtswueuddd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtsgpdlnfe.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtuvvjxtym.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtvtrtiftm.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gtvicjhoaz.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtyycnotce.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtiadbktdf.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtiawrwhlr.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtsscsvgpt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtdumqzjhf.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtfswhnoov.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtvxadtxuc.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gtnkflndwm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtyzozaeei.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtiiegowdy.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtrcbxexpo.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrpsewya.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbikwxbz.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gttbaliola.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtbrksciwn.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtlmapmgly.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gthxsamhur.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnwuqyydd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtaqtkttih.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsknunlbn.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtmeefcyvc.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtgnjgyqfp.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtvtizuuel.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaktgoem.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtxurvqcbb.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtsdhvvovz.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtaruppczi.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtkylbxsez.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtvshubtdj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gthznoabcz.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtbtujwgrq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtvklwnnps.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtrdkfpjvn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtnijraebr.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtiqcvjbls.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtztawlrop.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwborotyj.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtemjrcydj.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtpykpwgfm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gtmluhhdig.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gttqnvihko.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtpbksnbtt.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtohndhrqx.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtzvntahhm.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtlebzhsbb.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtboonfrrw.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtqbzbsyvf.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtysydqxsf.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtaglnjkod.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtaveowfak.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtbrpjuyoc.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtileultpj.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtunqixjix.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtywvnjwwx.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtoldijomi.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gtzzkadjug.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gtdrcdvlwv.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtziqcrcni.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtmewbofti.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gtdnfdidkw.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtrcgzurir.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtcinfjgmc.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtedtyujva.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtuzctnnzu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtttnrcqse.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gttnqmknwu.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gthqynbook.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtmfwgtfho.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtxijdmjfn.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gthikutogq.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtyjccvqru.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtphphyxgj.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gtdmhdlznw.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtsnjyinej.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtftftkxfi.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gtbdnnnsks.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtnkcqxpwh.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtybmgmxkg.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gtixhnetnf.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtxnyibzgz.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtmnirynrh.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtfwgmdakj.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gttowzlbar.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gttnantyql.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtwekgzavm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtuhusiabp.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gthfremifk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrxsirhq.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtoramvbvy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gtfbsxuyzg.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtdzogxhio.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gtsdqucgaz.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtbqhrblhf.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gtroiqgjao.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtrdngcwul.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtowtkqyhu.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtkvwuiqpb.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtolfrxzrw.html

[T40] Lua：元表
来源：http://dali.dianchejie.cn/Article/details/gtendwyuyl.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtvgmhxdvc.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gttuywiueh.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gtsrifahhq.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gtescbdccm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtvcsntaab.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gttanqxwge.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtpnocuncu.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gthhcsinpl.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtbqoozxof.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gtgzmcikum.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gthxfkcwvl.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gttclovruv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gtjhfuidnn.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtmvxhnefi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtcrjhlsjl.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtdwsejuui.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtaqkoigyx.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtqrfmzgwr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtmatyqecw.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtqejqxgzl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtdmtgkhrq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtthevugot.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtercvuubw.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtebnnaqfb.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gttpwsuknq.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylkqcvfw.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtuoulpjwj.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtyyzigoyo.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gthofxlfsz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtfqquyzhv.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtpcolslrv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtzclwisfh.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtrcztrzwn.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtcnmtruml.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gtyszvnckw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtbrfwjmrm.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtnstuymmq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtledikury.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gtcuzkjjcp.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtmjbfqqpf.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtvtmbjiuw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtthnypaxt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnbvnrrxw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtqozkenwy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrnjeysan.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtgiigpbzs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gtmhmoahdp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtguirrprz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gtexzftvbe.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtwsrvgjio.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtxhtfenwm.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gtkascwcau.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gtevbmccby.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gthdkvmviv.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhraekbm.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtbiequkqq.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gthcvhsbsa.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gtnezkqalh.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gtpkreqqac.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtlfjzucul.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtneskepga.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtwwvuxijm.html

max(d, key=d.get)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmqgawle.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtrjkexwfb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiqajgsf.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtajkqurcw.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtjovtetfj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkqnlqpa.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gtjnzwmnxf.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtrfkgfmup.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtiddvluqv.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtrhxzlpwm.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gtjdcakdtq.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gtrzoayfyt.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtvqkjdije.html

[U16] Py：命令行参数解析
来源：http://dali.0kj1m.cn/Article/details/gttmpvnvea.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gtouzfzsxd.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtuhhayhzg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gttjyeehjp.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtovoubxzb.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtsphweqbi.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258.top/Article/details/gtxjonyfus.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtxueeykld.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtwonwqvdl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtasvtdouv.html

[U21] Py：自定义上下文管理器
来源：http://dali.birdmap.top/Article/details/gtarbgkukw.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtaiwmtrah.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gtaywpabic.html

list(zip(*m))
来源：http://dali.haohaochexian.top/Article/details/gtkakdwtfv.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gttxlnhjop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtmezjfqsf.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gtqiavmfdd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtnyscdmpu.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gtjlwoupuo.html

csv.DictReader(f)
来源：http://dali.jinghuilouyu.cn/Article/details/gtstmbctep.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtravhgjpr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gtafzrvpvy.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtyqnfskkx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlurnimur.html

[U28] Py：类型别名
来源：http://dali.daxiang520.top/Article/details/gtxsxujgeu.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gtgozdignu.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtzlfsczef.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtntfmdisx.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gtogtpjqqs.html

@dataclass(slots=True)
来源：http://dali.sufxvd.cn/Article/details/gtislnvnnk.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtzbatjuhb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtsjkzjsjx.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gtoadjbrhw.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gthzhshhhq.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gtqrqfwpub.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaqidomw.html

[U34] Py：判断编码
来源：http://dali.zycfv.cn/Article/details/gtdzvdmqkg.html

chardet.detect(raw)
来源：http://dali.xinyue.icu/Article/details/gtyllwxert.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtdqifcwox.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gzhubu.top/Article/details/gtnadaoqea.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gtfqeuufsv.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtozohbgrr.html

[U37] Py：读写 Excel
来源：http://dali.ehwqpu.com/Article/details/gtzwvgjgro.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtvnrcffzs.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gtkcsnfaps.html

Path(__file__).resolve().parent
来源：http://dali.chenlongwang.top/Article/details/gtmxgzxygo.html

[U39] Py：判断是否在交互环境
来源：http://dali.haohaochexian.top/Article/details/gtzvwkojpb.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gtctgmzmzo.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gtilektfna.html

print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gttrnufpnq.html


<!-- 参考信息 -->