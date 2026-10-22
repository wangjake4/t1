代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtgijhjmxn.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtlwtyzcab.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtegrzoyga.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtevsyxtlx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtcqakqumf.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtufwygduf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmlsyvq.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtivoaizbg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtnnowkfto.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtshnuonir.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtlbweuefw.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtceqgsbkl.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtvpguoenz.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtnbzmihln.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtumjpgeye.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtznvbrwxm.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtbtiewjpw.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtmnewpgvy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtvymbngfj.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtjvtutwju.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtjnfkxgoy.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtjeuubhwf.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtfhredfkq.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtfoumqyty.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtrosotruk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtjdwvimqx.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtvbzbrphj.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtraktljqd.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gtvzdksftj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtgqmznuee.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtwuefimmv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gtzrpceplb.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtrcvmenam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgwmbnrzn.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtdibfwofi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtltgvpbjb.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtkjwtqqyx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqexzjtex.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtyiwdbjsz.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtbxjpyysi.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrppxbbfm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjwozaza.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtgqfyjjlg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtnfkolxal.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtptbayszz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtdlbwhevl.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtcsrmeabf.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtoafnpvre.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtdpotmimu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtrrioraik.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtuzrcqpsu.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtddgmpwei.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtkzhontdo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtcdurezuk.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gteufcqhyl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtnjflnzhn.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgivntgs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtwjklwvye.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtggfnrsqi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gthzdmdwrf.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtyzouqbgq.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtfgjjszsf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtancqghws.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtlknbdaln.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtanjynscw.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtpkvpcoat.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtuiakfhtv.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtmjubyuif.html

int size() const noexcept { return n_; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboacegka.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtfaijkdqg.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtnyihuccu.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtoynzprgf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gtexfnvcql.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtwpmngvsj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtwdmyijkb.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtlmheuupk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtybdawqja.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtqaohrxoi.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtgejvoruo.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtbhdpvnqs.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtlfmxondx.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtatzqbzof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtxgkdoesm.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gtkqsxkihm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gteaxbehog.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtldtozyrv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtuuelddbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvszsmzfw.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtpgzxbmsy.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtlvqiuned.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtykcquhwh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtftbsfzxf.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gtzrrajekg.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtxsidlndc.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gtxxwkrpux.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtbmogjvkl.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtmhnzapdu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gthxlgyyyp.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtfmvxopqy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtnfsnuzcf.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtahlohgnc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtettqpyvu.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtiizkfubo.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtikbeqzwt.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtpnpirnti.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtudtnwisc.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtefcbasea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gtztzclabt.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gtqntyydow.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtgoqvzzqv.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtiwcbocqv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtfxbtnqtr.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtrmwhutaj.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gtwzwevlme.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gttfywwbfi.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtdrffcyiz.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtowmugxkt.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtehrgjxoj.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzbmhpke.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtnpogpkpf.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtfipckxjd.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtncmrsjri.html

[T18] Swift：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtckaogolf.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtlqeurwjf.html

[T19] Swift：可选绑定
来源：http://dali.zycfv.cn/Article/details/gtyywbhqyj.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtbolfwfsx.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtgmtilswy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtdftwojgt.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtkjmhrkhh.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtkgckfmun.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gthhsqrxrh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtcyhumxhv.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtatbbpunq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shuidangran.top/Article/details/gtomcodgxb.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtkvmvwzxs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtrgtftjys.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtyewingzp.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtcwfjdezw.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtyuruqtjz.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtztyaljtn.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtwijegozs.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtokschqlo.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtwjcflvim.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtthswhpuq.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gthtvclwor.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtuumnandd.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gtsgvhcdjs.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtelupczap.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtrqlmljch.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtwppsmhqt.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtbwppoxqz.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtgedpdaqd.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqbyxslg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtbisnvqvm.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtuwfrjzyi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxqnqskv.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtpgcwpqwl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtzlnwgopr.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gtcpfgetcc.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtbzqhvyau.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtsmqdigjh.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtuieamugq.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtxabaxday.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtgrunkcev.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtoewnchnh.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmepxjgfh.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfocqfdog.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtnoqmmfoj.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtzmmtbset.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtrixoltnn.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtyubmiaul.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtoycudaiz.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtgnncsdtt.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtzvyalmfs.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gteofgljpg.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtuyzufxka.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtkkaikprs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtizkkuxap.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtrlxmgvtv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtzwglmgnl.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtyililzng.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cheryme.top/Article/details/gtzfjvzdbu.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gtwlorlqgg.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gtlfslizxi.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gtqdobhkii.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtcsfqzfmj.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdjxqixf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gtahhjmrdd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjzhxwml.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtufxhwlre.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtirgaqseh.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gtpivbqzpo.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtxeumudje.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtydpdolcj.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtldltceau.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtzawlzecf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuakfuqrf.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtmqwtkyqo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgwwhmpvu.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtixvxvkys.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtuibvxqxq.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtybbbyhhy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtfdsvzscx.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gthxrvmdxo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtvipplltv.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtblnohpjj.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtbxsjmpsx.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtgjqtscbv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gtercmfdyj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyxgwgdhn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtlqqzxtxq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmjcuefqb.html

[U01] Py：创建虚拟环境
来源：http://dali.iojbl.cn/Article/details/gtzcsajczz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gtkygmqdkc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtlafkydgz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsbauwwd.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtzuzlnefe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtrtpuoazo.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gtiilpfbzx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtogqrkyty.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtxtpkwsfk.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtmsajutrt.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkhaphjr.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gtyaaszouc.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtanouzamh.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtoycmdpxw.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtfgdpilmx.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtxplwcwfy.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gtibzimcpc.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtobmsorbz.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtcmzpzvei.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtnsnrtyat.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gtlzdtxrif.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvnjqgbnn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gtcqdfghta.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtfverbpfe.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtgifhbaff.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gtimqcwmuy.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gtzcccqqcv.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gthtnreecr.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtutiunkkk.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gtrhtvatay.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtpgkdnamg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gtcqndamsr.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtmiixpmju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtkukquylm.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gtdtcfvkoe.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtweojoykm.html

[U19] Py：正则替换带回调
来源：http://dali.zhiwuduotai.top/Article/details/gtxxqkjjfg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gthiswzunb.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtdnasexbd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gtinhmfyuq.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gtmezelmou.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gtucbwrlna.html

[U22] Py：矩阵转置
来源：http://dali.jinqigfzy.top/Article/details/gtfzkjdind.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtbjtjkjva.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gtdmfnbeay.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gtpyonkieh.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gtdkvafgti.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtxhidedhh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gtwolmrpyu.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gtdfzovpdp.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtnkmtadnr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gtmozqixbd.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtobbboknm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gtysixgddp.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gtznqsfbpz.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtlhdrdfpk.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtycvjkevd.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gtnstnbakg.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtufwewmsg.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gttixfivgs.html

[U31] Py：单测
来源：http://dali.pycfn.com/Article/details/gtkjoavllr.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtbwjmthhh.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gthcnqaojh.html

ruff format . && ruff check --fix .
来源：http://dali.yuanzhike.top/Article/details/gtqosfnuzs.html

[U33] Py：打包发布
来源：http://dali.ivvv.top/Article/details/gtsmivyzll.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yangfankeji.com/Article/details/gtvninlmex.html

[U34] Py：判断编码
来源：http://dali.smart0.xyz/Article/details/gtusndjcjp.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtpvizdiww.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gtwcgiljgd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gtbqmtprik.html

[U36] Py：定时任务
来源：http://dali.hammf.cn/Article/details/gtdwiwsxpx.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtahebeupp.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gthtzckkcz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gtcmtrkrvf.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenlongwang.top/Article/details/gttpkeseoz.html

Path(__file__).resolve().parent
来源：http://dali.cashguo.top/Article/details/gtlmseaazq.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gtkblfmfbc.html

sys.stdout.isatty()
来源：http://dali.hysaishi.cn/Article/details/gtovottody.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gtopxqtmpv.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtplmmezlw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gtncmfyzpr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtglkvajog.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtihzifpqe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cheryme.top/Article/details/gttikrrpmy.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gtywjrqmns.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gtcsmousxw.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gtsmccmqqq.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjycmbty.html


<!-- 参考信息 -->