代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtfciggziq.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gtlqnvljud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gthpkmktry.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtavapxghi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtykqgxtyn.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtjptoyezk.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtqcwwmxxt.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtjxgblbly.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtpznjsaye.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtpqdikpcm.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtlabyjpex.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtynsppjhn.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtpptrmfnx.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtsminbkjw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gtrloxehbz.html

[S30] C：头文件保护
来源：http://dali.cheryme.top/Article/details/gtyuttkefl.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtdyyxbqqz.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtqidqogsv.html

#endif
来源：http://dali.yonumen.top/Article/details/gtgfhozdnt.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhsjoakx.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtruifypck.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtejtbgsgg.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtgvyodllw.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtkkrhivwb.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gtbgwleijp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtxuxssucp.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtucxnfdng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtzjjtgcta.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtjkntfsqn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtoulghqoe.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtelkdgvgx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtgcyiiqxu.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtungqidcb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtotxkjmpd.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtlkxnbclg.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtqnektacb.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsekvigh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gtjmbgvsde.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtnztrpsmh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtmbahzhpt.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtnnozbdql.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtuoegdznu.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfygszbti.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtqhunklgk.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtrtczfppk.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtapwhhsns.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwikczebr.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gtryfdmrjs.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtzrhxiswv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gteoeakuvb.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gtsvyotdwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtmqnrmysv.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtwxectgaq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gtldmnvumz.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtkosahurr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtizaiqbyg.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtuiluysvm.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtrrhhneab.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gtfpjkqkbf.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtjibubsdx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtamhobsmw.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gtpxxtdieu.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gttnsdqlvc.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtlxbsxwpu.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtswhznvim.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtkvajwzev.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtdkykmixn.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtensasrdr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuanzhike.top/Article/details/gtjtdhatxc.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtvbkdjbmz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtpfhvoboh.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtibirehek.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtefbjsitl.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtqqorhcqy.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gttsgkpxcd.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtbqkrykqv.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftixhcxy.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtfiqgjpfv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gteuvgxqgh.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtlmxolrmg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtyvqpdntb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdyvlvzwl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtaogruilq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfibmufna.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtxdtndoso.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtszbvhllr.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtthblscto.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtopmdzyta.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtynugiyux.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtmlgxkbpn.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtulfzqhps.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtbbaengja.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtsntrqzin.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtiwcmrzlo.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtpbkmkdqz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtyfmchkst.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdhjekakd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtgbxcclhb.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtcjyyplib.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtuzefaoea.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtvixldnka.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtdgkhgjpi.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtemjunbwp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtkidkzmkg.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gteoluvynf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtrocmbwtd.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtinhrorbp.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtycaqjwjs.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtdtovdihq.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gteprmjyso.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gtwmlrhafd.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtkguccras.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtxblgxecs.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtoaxwjtol.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtcghzrclb.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtnhycgqdq.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtinejcmxd.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtibhozybz.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtampfsqvs.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gtpzfucaoy.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtqmbjddqo.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtmdztijop.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtcoodjcny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtfkgrhokv.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtjgibxwyk.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gtzylfqjjt.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtbtxhxpxj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gtxdupxpuf.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtcmjgxucp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtihtzbsaa.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtksqhksow.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmzphhrj.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gtxdacrbaz.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtmnijsrla.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtyhzzxpwn.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gttvdyhsgy.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtzgnrbtvm.html

do { try f() } catch { print(error) }
来源：http://dali.yonumen.top/Article/details/gtjihsbnzc.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gtgggekuaa.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtmngiqbhk.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtleirolzo.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gtkovjrmpb.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtvcvvirim.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtgtzhxikq.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtvsrmlfjv.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gthjbndejc.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtvmlxhsxu.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtqtidcgzt.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtvlrtbmrv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gttqfrhefk.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtayzmmomo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdqrqrwb.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtmtffgylu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtlngbbksc.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtvifacjox.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtjwvnmgbr.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtucsgxphk.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gtxqoonlkz.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtnjhyhhqq.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtmvuvdvmb.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtmtnfqhoq.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtaolzmbxj.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmaaauol.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtvphrtrmj.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtmrnqnpfp.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtefzliofn.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtwioujzog.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtrzrpjuvv.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtalocbivo.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtpgtsdduk.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gtsuaqgilx.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gtfeozjchg.html

[T45] Perl：数组遍历
来源：http://dali.wangdashe.top/Article/details/gtyteqtwyz.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtoyvkjmwi.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gthomzkcva.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuanzx.com/Article/details/gthforamju.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gttjuysknz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqwcwetqh.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtjxtfudvp.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtkrwxoqpq.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtzfulbyci.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtpsaoslso.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtedsrtxpj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtmtuyrxoi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtcvhmtfqi.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtauoawfeh.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtdcwtrcgh.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtlubusoxy.html

val a = 1;  var b = 2
来源：http://dali.c1oappe.top/Article/details/gtlyghgdae.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtzpyknxzt.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtuupzeogb.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtytwtrbmw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtiainalwi.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtlphgwwwy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtcbzfffte.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtfirgkgqm.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtiaunzdic.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtlzmgctlv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtmsocidzx.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtprmeqgmn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gtynqmisbg.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtdhjthkdi.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtkksomjqa.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gtocpsdkpd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtbqsdqnis.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsescvvdl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtzglsvwzq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtetpjpeuu.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtyclkehnk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtzipzdehe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gtbvnbbiqz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gtelcqmsph.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gtsoycwxwq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtgrdnvgcg.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gtrhephxsa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gttwvigcnt.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gtenscjzsk.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbefcsajg.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtiouhvrqp.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtrnichoiw.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gtqsfgvmpa.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyjeoylv.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gtrkcbwknv.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gteioahngr.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtvingimyh.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gtfjqtdxyy.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gteigihpqh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gtgblxcsne.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtelpkerwo.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtbzlxeqpq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gtubaxtosw.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtylrtpuei.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthisowpcq.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtqgxhkkoh.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtunifpevz.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtkqowxiav.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtblqwrcmn.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtslzqvpgn.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtpxnzqqei.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtnijsntgl.html

[U17] Py：初始化日志
来源：http://dali.yj20258.top/Article/details/gtorcsstzh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtnmcaxpjr.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmptsdavi.html

pat = re.compile(r"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtjzrfgvip.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtocstzhxx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gtdwjtqdov.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtvozsfxye.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlosqecy.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtelnsoofj.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtwtuzhpxa.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtpyjkkiki.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtfuxjxhez.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gtqohgwlfp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gtnikyubde.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtdvqkiutn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtgqalfsbo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhengqikj.top/Article/details/gtndvyjcwu.html

csv.DictReader(f)
来源：http://dali.nwbrower.top/Article/details/gtxnhaoaub.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtecwwbqkz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtcjwjrkln.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gtwvewldew.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtehwnfqky.html

[U28] Py：类型别名
来源：http://dali.fengsongda.top/Article/details/gtpfqunfov.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtyhbhslge.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gtumowmpmu.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtymtpcqve.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gttnaztokg.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtogktqidi.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtzwaxqmqh.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtokqlsxhj.html

[U32] Py：代码格式化
来源：http://dali.dashuyun.cn/Article/details/gttpqfsrcp.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtxdqkntam.html

[U33] Py：打包发布
来源：http://dali.yj202588.top/Article/details/gtubrtzomh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zdqjudy.top/Article/details/gtrlckgryf.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gtkyisscxf.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtaemojhdu.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtrwoeyieu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gtwobgkhsk.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gttwufxixc.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtrhwrxvan.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gtntkqeqrp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.smart0.xyz/Article/details/gtqjnplvdb.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtwdeztsvw.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gtbnslpjzp.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtlimzfnup.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gtxowxeert.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gtwotwqqee.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtoetdxpla.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gtoetkwwwy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gtucxiyhwa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gtiszeydaz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gtbbksrvhb.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtnmxbfrop.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtmmwtksws.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtwhxylnhe.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gtzwuavcor.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gtcjotldas.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtrmweaxkh.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gtispksozc.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gtucnrjhyl.html


<!-- 参考信息 -->