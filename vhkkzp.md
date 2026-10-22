代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtjdswvuqw.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtivmzwypp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtiezojbbu.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtbralcokj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtyrypmfjs.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtqbtldtoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtlwadyyzp.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gthstozrvj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtyevzqxqf.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtlsmltakm.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtatpoailb.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtpxgucoyj.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtwnopazcg.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtmmpkmfic.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtakbobmae.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtbjwpomsz.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtqrajwakd.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbdjrprc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggiscsqi.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtirhwaads.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtutmnelnl.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtcridxxju.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gttkyppaui.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtrszezrbj.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtylzntnmi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgdqihrvf.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtkxnilpjz.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtbtlsikwf.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtwubzynqo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatubzrql.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtxusqiaqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtdkzdyhwy.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gttmijfdgd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtzbvsqete.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtdkixarpb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtuwunhdno.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtezjsxblc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtaigymytj.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtqqfluoml.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtwwslseyf.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gtbustjhpu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtkfhezhsw.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtnjgfnetg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtcwsmhokf.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtbfewabvp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtdybkprah.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtzcoipqre.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtrtqilrwe.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtjstrbays.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtixoatofc.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gteroylfvt.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtkxbumris.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtrmawlabe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtbpdwlukd.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gthehdbdud.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtodbystvp.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtngchybsp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtfwtfebkg.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtqddpviln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtanextxav.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtkqkmmwbo.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gthqwwgoun.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtrkkkeepe.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtoevmqdnd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtvlwisnor.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gttqgmavnz.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtpvrzzfpu.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gthpcbecbo.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtfkiuvbhn.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtdfabteir.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtchafvruh.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjxvsiav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtfchnqjui.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipqufgux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gthceqdmji.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtnpliiiyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtkwuhimky.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gtbtasrqfs.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtucjkoznm.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gtdiqftgzc.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtqqhipotx.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gtnxrvpded.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtgnrnvtxt.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtpgcaeqhv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gttsvgaqri.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfojikjg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdkrdiou.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvtckryec.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtieyctrzq.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtofbpuwha.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtbavfzdba.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gttslvuaju.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtahvogsav.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtrcocnplu.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtshjmlypa.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtznzppylt.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtogvjzwzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtckkpdego.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdqnfhhx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtbokesdto.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtcnecycty.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtcmfotbna.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtmxkkosqo.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gthzvhxirb.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtwgerfbnb.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtipexvztk.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtohgosebr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmovqgqt.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpngswzjp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtpcosgbbs.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtvnwrxjoq.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtzyfcsyqf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkqvpfof.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtssfsxrnr.html

[T14] Kotlin：循环
来源：http://dali.nanxuanxn.top/Article/details/gtswbexzwd.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtmsqpkhbf.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gttrdmvyup.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtqsbytdna.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtabvbnvzu.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklgbouqq.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtsalphxce.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtnszjdlnd.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtbgpdcryq.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtujnbdrxd.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtxtotipyi.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtjfupsdpj.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtxywlhack.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtyuksengl.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtvnmyrcdy.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtaxuktsvu.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzdkhykq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtedqdwame.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtidkwocnn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtobqlersp.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtufaeahhh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtqlcbalpe.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtemqdqqpr.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gthylvwpiv.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkktmrsd.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gttmaoraac.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtdpsbkmkw.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfimmosd.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtqxnblvrx.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtvklazbtn.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtdwytnxcv.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtyygoqrjv.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtbpvbofbg.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtquywueiw.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtkjxqytpc.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtyssiully.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gtvzpvlxtr.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebnvradn.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupgcsvsi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gtfobjrhgr.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtzezetjwn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtqsvlsuow.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtqfzsndsk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtcjrdcelo.html

[T36] Lua：函数
来源：http://dali.chenlongwang.top/Article/details/gtcngdkegm.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtisowrroy.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gttphzpuja.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtunjfcyzk.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtnuncjwjw.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtliakudrl.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtmluktxie.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtulbxvjsm.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlqpvnae.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gttinfbcys.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtrlqhamoh.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gthlksmkpg.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtqdgdrwbs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtjupdjkim.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtcpmkdamn.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gttrgsxeei.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gthyrigivd.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtbevfzgrb.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtevuqinbq.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gtytpujnop.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtmxirzijk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gtqezberqd.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtwqoplekd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtldjfxjzj.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtaamziebf.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphzxwyrq.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gtjiofcaxa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkobcvquz.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtbfaokrvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtrnmbzpsg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gtdgjblabu.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtvdcplvxk.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtvsftynru.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtafpalisb.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtgtraipqx.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtixzxudrg.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtiiwejgni.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gteddwlvpo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guowangkeji.top/Article/details/gtbpdsracd.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtrjucoxxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxlsfhuuy.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtnovdtjpa.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtedmcoywc.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtgauqrazv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtpsylotlw.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtasqndkvq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtashnzvuj.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtyqizjjql.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtkjyqmyrz.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtjlemrumi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtusrlefrh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmdxwbvqb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtwwkdpfhz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpbutvmdz.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtblnibbqa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtgcmfqizr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gtdhnzwdad.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtbqfuoauv.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gtmvzulfiw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gtkrjrfhfd.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcneookpy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtohysaoej.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtejcykbrb.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtddljlvog.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gthgapahtd.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtctwcfsmk.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gthblxjtxe.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtjzfknnma.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gtsralrugr.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtbfoxrpbk.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtcnknnywi.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtahqkgyqk.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gtvguxjbve.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtagrccvhd.html

[U11] Py：生成器表达式
来源：http://dali.fengsongda.top/Article/details/gtostvduif.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpdlvvomj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtvmzwujic.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gtdoxmvjgw.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gtgmegscpn.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtizfqgotv.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gtpmielepo.html

defaultdict(list)
来源：http://dali.gaohongyu789.top/Article/details/gtvfiybvqz.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtphburdwx.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjlgywkk.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtyyvnmnpa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeptwhbk.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtoqrhkssx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gtajrrabit.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gtotcwmxto.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoipuqyrk.html

[U19] Py：正则替换带回调
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlkwtsad.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtrqvnpamo.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtcxwsnntv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gtunwnkgmq.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtfhxqyazj.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtewpkxkoq.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gtwxvnozkx.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtbzavmdnh.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtskfymgld.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gtmhgfrmvp.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gtyysxhqwk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtdzalqeih.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gthavcagfs.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtizqpqhmy.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtelkbsfen.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtsddmfvif.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtsmbqvieo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gtbyhcnlwa.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gtvnlzsofp.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtydyrhbse.html

[U29] Py：属性校验
来源：http://dali.ivvv.top/Article/details/gtrtbpbtet.html

@property 与 @x.setter 配合
来源：http://dali.smart0.xyz/Article/details/gtdborwhhd.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtjzhxccan.html

@dataclass(slots=True)
来源：http://dali.kuanghao11.cn/Article/details/gtlrvudjhq.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gtsmezseba.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtkofmfnyq.html

[U32] Py：代码格式化
来源：http://dali.yvedp.cn/Article/details/gtiipqoumx.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtgvzrqnby.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gtcxllrmej.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigfzy.top/Article/details/gtdyfyqgod.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gtpnirqosv.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gttnhqawjc.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtvdjlmadx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gtzepgyyxt.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gtmndlwigr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtynzrjlid.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gttzrqxurf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gtkbnflzgg.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtafleeefo.html

Path(__file__).resolve().parent
来源：http://dali.iojbl.cn/Article/details/gtjzvsehif.html

[U39] Py：判断是否在交互环境
来源：http://dali.nwbrower.top/Article/details/gtcbistqcj.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtgemeffkn.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gtpfqnhhlv.html

print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtklcrdqcy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dianchejie.cn/Article/details/gtnanxstjr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gotoacloud.top/Article/details/gtpggurxci.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gtjktpamti.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdlicqfz.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtajvrvomv.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtijdeuqkm.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhavfepu.html

declare(strict_types=1);
来源：http://dali.guannengcc.top/Article/details/gtosmfgelx.html


<!-- 参考信息 -->