代发 wailian999

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gt2wbnipsgz.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gt2ltmivbwt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2ktvxklnf.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gt2rvhkvaxm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2gllobrrd.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gt2frqekqyh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2oorkyhrp.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gt2vuvbbeau.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gt2sbigntkn.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfztdlro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2lwvejbtr.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpnxokwa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gt2ecaikcnq.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2dawsoglk.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gt2dfnvzrml.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gt2urlddljr.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gt2vesqceng.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2jattrgza.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2yxialdbg.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gt2ymygpswo.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gt2gehklsbx.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gt2hophduxv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyxjdtqv.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvseyvtl.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2buipnmps.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2wnoxufpy.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gt2wdnwyddd.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2shoelvvo.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gt2kgkeyogj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sunjbzws.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ibuepheh.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2fpcgnmnz.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pivqkdyi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gt2qpjlhspa.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2exxqlpet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2drabyiez.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gt2ljcfrhbe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2wbgrqnbq.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gt2oopyeaye.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2blfhasuo.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2xokqyasn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2vrwinnwd.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2tczhbnvk.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2ejhqeskh.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gt2inknyfsc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2mqynsyzk.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gt2ljpgimzr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gt2okxvcarw.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2phdclsqr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2smlprhay.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2gezubbrn.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpmtfdpm.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2rfukmwre.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvyelvcz.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gt2upsgrvtp.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzpwddbn.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gt2mkjdxbhw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gt2ewbfkukd.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nawgvdss.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2iwecttse.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gt2xqlocdol.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2rmppbxgf.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2zuyjfrhi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gt2jcxmevjg.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2eycmldud.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2uswjumkj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gt2sclrgrdl.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gt2pyfgwwhn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2tmmwcbqp.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2ttdpunkf.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gt2yqyvgpco.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2cvllwwiz.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gt2hsgysltb.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2elshckat.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2acbwptzg.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2qylmujqb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gt2ysmxrhnb.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gt2toywchgk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlfzmcti.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gocbfiqk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2vzhgtuhu.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gt2exrswuto.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2jhlvwhpp.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2einlvzrm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2dsswhkdw.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxykobny.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2cpuxttpz.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgsquyjd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2awmgxuyu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2tcyjuocw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqgcufkg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2cmepdpvq.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2zwqorahs.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2twjgbeeu.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gt2sbghmyqh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gt2rhgpwcqu.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gt2lcbtihza.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjcifdc.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gt2qvkeoiar.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gt2pvdxeazm.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gt2awgszcmp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gt2bjqammdt.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gt2qxbguric.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2okwldtof.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2gcvcqvym.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gt2ccqgqdhr.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gt2zrhsnkzr.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2cehtyapn.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajdtauoi.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnezjeda.html

[T10] Kotlin：默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2kniuzwhx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gt2qdtssubd.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gt2qeoogwve.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2getpvqmh.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2ircficcp.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2jsiquahs.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2mtoozzst.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gt2wndxvfwd.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gt2zzzfaaqz.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2bdqrrxzs.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqfirupq.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2rokxqqcr.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2kkdhvpat.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2mlaoafju.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gt2hudskxqi.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gt2unxxfxsn.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxnvxszx.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2vnqyvblq.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gt2bajikypu.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2valgpllk.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gt2ywxjrdig.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2firhrlta.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gt2qgpgxvbf.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2kseuicte.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gt2krluhdvd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2vdtxmxbd.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gt2cdhhxsjo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2ycblgtjp.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gt2vodlkddt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2zedokayq.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2atxvhyjy.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2jswrmvay.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gt2khcjwllu.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gt2tnbosddn.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gt2gtmkavhr.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2imofyynf.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2avmntmrb.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gt2ohrotiuj.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gt2zrqrfuca.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gt2xznwbrbo.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gt2gjtwkrry.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jphjjetw.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwegklcj.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2tmbaltql.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcyrwvss.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2aenjhrie.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gt2ohsxdjlk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gt2sruutpaf.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmnkqmwk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2vhdemotb.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2wwyfeblv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2nhjrcmwr.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2seyosdrr.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gt2hcxilkqd.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gt2zavildkk.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gt2ukeebkwt.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gt2nsouodbq.html

if x > 0 then print("正") end
来源：http://dali.nwbrower.top/Article/details/gt2glvtycnp.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gt2plmcynfn.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gt2xsfatdag.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfpkqtpm.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gt2ebucsnyu.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmbrlpik.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gt2wsdsdfuj.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gt2mijyetat.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gt2iadezqwx.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2jookrdup.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gt2azgsuvax.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gt2qcqhnvis.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gt2ebrdkukv.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gt2pdnulqxf.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2jwnbdvzz.html

[T46] Perl：哈希操作
来源：http://dali.c1oappe.top/Article/details/gt2ogavndmm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gt2ozonsrju.html

[T47] Perl：正则捕获
来源：http://dali.shzxlz.cn/Article/details/gt2iuvuhxdo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gt2plrxwdnc.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2zksenoke.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2fwfmshws.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gt2izqsjrcp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nitnfswc.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2reefjgsp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjxlzzze.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gt2ubzmjgsm.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gt2mmmjgywz.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2uikpfhjh.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2xrkbzkjh.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ylgzlbbo.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gt2ilivrohb.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gt2xokbjtwd.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gt2wlpqvzro.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gt2hujssfbj.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2elnabwaf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gt2bbynqtsm.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gt2dvkiyahj.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2gmcsygqh.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2vhoacwvk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulszmvtc.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2lepyeabg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gt2aczsxlzp.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gt2okvosogx.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2crszawxq.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2buwlpyip.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gt2efnrmjfj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nagwujtg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2qndbrcuq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2josaxfpx.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gt2uocphawh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gt2tfmuxwpa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2bjtigmoc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2mofstfcj.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gt2ojrsuefz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gt2hrcdkbgu.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gt2uvxtuwbm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcwcqmkh.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gt2idgnymkh.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2biludllj.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gt2tewjsqfl.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gt2mllwbwul.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2dqwcuzql.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gt2czkjusbb.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2znutfhaq.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gt2imkvmgfq.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gt2goceyfpe.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gt2cwmkttmg.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gt2ehwtwkpd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gt2lkxkwyba.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gt2muctvqel.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gt2myifpgqc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nwbrower.top/Article/details/gt2zpkhurmk.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2actnhupd.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjfmqvex.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gt2kzanzpck.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwmpiaxv.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gt2abdrtqjk.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gt2pwvenmre.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gt2alcapmov.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2hqjzoyit.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gt2hlwrwysw.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gt2xwokotsj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2ofzvhkne.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvowikrb.html

pat = re.compile(r"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2ondftypu.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gt2frmkiulc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gt2hrtftslr.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gt2eynnongy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gt2rglvosxp.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gt2czskqrkp.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdbxyaon.html

[U22] Py：矩阵转置
来源：http://dali.zhongyouzk.top/Article/details/gt2lhrojcra.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gt2dyfgbawq.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258.top/Article/details/gt2fccjucpn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgpknfqc.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gt2blupqgwi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zztguzmx.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2itzrktsy.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gt2tescswux.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gt2yegflykw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yongpay.top/Article/details/gt2zokfcqtn.html

[U27] Py：异步 HTTP
来源：http://dali.jqgfzy.top/Article/details/gt2lgtzkozi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gt2czukiaji.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gt2znpwpzmo.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gt2fmjqiaet.html

[U29] Py：属性校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfrlsstf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsnabeg.html

[U30] Py：数据类
来源：http://dali.tian-w.cn/Article/details/gt2towuxpyf.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gt2jgkaldpw.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gt2dyosyppa.html

python -m pytest -q
来源：http://dali.hnxiangtu.top/Article/details/gt2ohajocma.html

[U32] Py：代码格式化
来源：http://dali.nwbrower.top/Article/details/gt2lyrppkxd.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gt2kuzioxdu.html

[U33] Py：打包发布
来源：http://dali.c1oappe.top/Article/details/gt2hwhpeeau.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gt2jytpsnup.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gt2hsmtyeqe.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gt2agoxkpww.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gt2cygzkyxl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gt2cgudqiqx.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gt2kgqwajqt.html

schedule.every(10).minutes.do(job)
来源：http://dali.ivvv.top/Article/details/gt2dljvdvsz.html

[U37] Py：读写 Excel
来源：http://dali.dianchejie.cn/Article/details/gt2ffcfiyzf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2ronnjukx.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gt2utmoedqq.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gt2mgjafkft.html

[U39] Py：判断是否在交互环境
来源：http://dali.zycfv.cn/Article/details/gt2zgjasufv.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gt2cwbljmer.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gt2cuglryoi.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gt2tmadbrzk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gt2ibsorfdk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2acwmioku.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqhrovgb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gt2tssucbkh.html


<!-- 参考信息 -->