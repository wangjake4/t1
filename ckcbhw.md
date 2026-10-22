代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gt2okrxoaus.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gt2lsnawbml.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gt2hiwauwbo.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2dfwwqhjy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gt2pmpwivcr.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gt2fapazhwz.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkcnicpp.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gt2ntbrgqww.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gt2lgcothqw.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2zhkyzkuc.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2xtrqbvzz.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gt2tutjjrih.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2evnbguen.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gt2vcdagffd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gt2npvqxnph.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2uooawixy.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2utctfkln.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gt2hqoczsit.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2plejxcxj.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2bfdqlgsi.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2ptklyzqn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ffwkvnvj.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fstxnghl.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gt2funrmsvi.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2nqcifnqq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gt2iwmyisvu.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gt2ttkcscsl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gt2kvjunnbo.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gt2yqxhmnra.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2tusgnugu.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gt2punotnyw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2tcevqlvc.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gt2hcvzczay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2wasbzdlg.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gt2acmkrxvg.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gt2wtxhgcru.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gt2iwvnlglk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gt2yguprqvc.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gt2wekcrrfc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gt2rdtcmnag.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gt2psqgdlft.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gt2yjogisja.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gt2glbjmkvm.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpzwolwn.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2jukatuop.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2oiwtlrty.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzyqiwwq.html

void inc(int &x) { ++x; }
来源：http://dali.jyoumei.cn/Article/details/gt2sqaardsf.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gt2crfmpqrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gt2coikkzxk.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gt2qedhwsbe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2whprmmqp.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2zwqeexwk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gt2gxyqzbwn.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2vjebwnqd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gt2anwzodgv.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2zrjvntpt.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gt2chdxeyhe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gt2pnkwmavu.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2ufhwlxli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2bynkdued.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gt2yighmvpw.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtngftxu.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gt2wrmdsrlf.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2lsmxnrte.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiiecvks.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gt2amnmeffe.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2tcwrgyge.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niexrecp.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2jdypdpkq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2pddyhwkm.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gt2wiomomee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gt2gmfxveci.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gt2xphfcqkv.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2qtulrkzm.html

[S58] C++：命名空间
来源：http://dali.tanke756.top/Article/details/gt2cqeesngk.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gt2xfkjkinv.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gt2dhtehpsg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2nyweivrf.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2pwqpbhrz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyhbktuv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vtqqqxhf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gt2qwzvwycp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ycalkdgo.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ejjsvjii.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gt2yeyssacg.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2djsmiqsu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gt2vvlmvezs.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2iqvtabdh.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gt2dskfzoeo.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gt2spbklhpn.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gt2nzpqhggq.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gt2fzlhsibn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gt2uruxdvyu.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdtwvuqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gt2grxfqllg.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gt2rknydkze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2febnkjnz.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2poiuaaou.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2xdeoncok.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gt2rqqwkefb.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gt2xxakybzw.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2kmkwfuda.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gt2qjxbcjqn.html

[T11] Kotlin：协程
来源：http://dali.cashguo.top/Article/details/gt2zmjzpmrh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gt2vcvbpark.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gt2ofxqajbq.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2wzyrxpss.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gt2uknbpkab.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2abtbdiko.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2kxaecqft.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2tsutjxka.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gt2bzlgmpal.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gt2tqgyestd.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2wnxljong.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2nztabjit.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gt2lljabdss.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2uzhdpwuy.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2btoicbrw.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gt2jqynjryh.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2ucalhdyv.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2gyestinh.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gt2micbdefl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gt2oazqfguw.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gt2olmuawbq.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gt2vjahhupv.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gt2gwynpsmf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2aqmjrlvv.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2tipccywy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gt2tchbdmjo.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gt2sgnvfrrr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2ijfurcxq.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gt2mkzclyfc.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gt2rvncuimu.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gt2ptbuzwrq.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gt2vlzyajsf.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouhkytyj.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gt2zvphtzlk.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2zeevddpr.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2huojyuqp.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gt2ccbjlkyq.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2exzdkdnf.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gt2nmuadbat.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gt2mqatuyco.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2rsrxeyoo.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2vkhvbbpl.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gt2wgnuuqpx.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gt2ehqmujdp.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gt2yipvdiud.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gt2ijtmurqu.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2vuhwobbe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2paczhlfx.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2ijrpsjgh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2dedurdje.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2jwslfrnf.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gt2oqlaadls.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2qacyaipz.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gt2tpocoazl.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gt2hvnxqnvw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2phefjvpt.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gt2drgshboz.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ogqzttxr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzcjigl.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gt2lqltevtj.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gt2rxzikdhb.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2puhugaoh.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gt2dhaszify.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2zjljmrek.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2asswajmz.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2jcbgwkue.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmdxwosa.html

if ($a > 0) { print "正"; }
来源：http://dali.pycfn.com/Article/details/gt2aadarchx.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2ochuoueq.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gt2yrgbsees.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gt2vvqylpwz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gt2vyvnwqxm.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gt2jiyelsmb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hnbekvpn.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gt2kffilucs.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gt2ywwhceug.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iylmbtkh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2qwnsopsi.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgksewei.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gt2vntgkisb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2whjhnqhn.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2nznanrdd.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2uumcjsxs.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2ajnpwkpx.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gt2kdtohnnb.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2jhjttrjy.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbiwyhpr.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2htnvydwa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2grmvfppb.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2abixvdab.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gt2etkdvixc.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gt2abcpgxms.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2ymdwenyn.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2ufgdslnu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gt2aisvfwmb.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2xaczvmtb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcikshsk.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gt2cnnqnzfg.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gt2ztcahqpv.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gt2wiwsomzr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2kfgdsyvi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbylgtkj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gt2icchenkc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hghxhbgw.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gt2qtfpjavw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.bjfxy.top/Article/details/gt2tnilhgri.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gt2yeerggzn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gt2ajcitcdr.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gt2mgnhciwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gt2wwhjximq.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gt2zncgxbza.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gt2demypknt.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gt2rfemurdl.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2oudkozjh.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gt2afpwlfte.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqtartml.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2wtotarrn.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gt2wrqkiwpl.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gt2ssxqepdd.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gt2nnrnlfel.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gt2pkhkrmex.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gt2sqmefhoc.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2tzxatjva.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gt2gdaodhnh.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gt2afclngir.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2tydjhcqh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigfzy.top/Article/details/gt2omzxonnh.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gt2rdvasekj.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gt2znebubjg.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gt2binbendi.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gt2wpphiisy.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gt2gswpqjmf.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gt2ffuqayvv.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gt2ngtgtlnn.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gt2nakntofm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gt2gdxyuctx.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gt2bfkcbpvt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gt2isgafcvd.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gt2ejpkcoxy.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2xuakyfsb.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gt2gjjffptq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.iojbl.cn/Article/details/gt2rlbrnaof.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2zylrpovn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sufxvd.cn/Article/details/gt2cbntaatn.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gt2bfcdzzjz.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gt2suzdzcwz.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2woogxqwg.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2gckgmqwi.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gt2xburyksw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gotoacloud.top/Article/details/gt2hdxczfrn.html

[U24] Py：路径操作
来源：http://dali.316326.xyz/Article/details/gt2jrmrkura.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gt2qhqgqxpg.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gt2rdcmucjd.html

csv.DictReader(f)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obhnvgke.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gt2dnzuirnh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gt2ftoyotke.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gt2ocnzakwm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gt2kjwgbnye.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gt2djjspzxb.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gt2nznushjc.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gt2zubkzncm.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gt2xvllwcrt.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2ujbqspth.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gt2brzusvua.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2qxisizbk.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gt2ofzvwqrb.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gt2vyjomkph.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsxlbyc.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gt2eytuzzjw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2hjalathf.html

[U34] Py：判断编码
来源：http://dali.ybcxt.top/Article/details/gt2waygnant.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gt2bmovycss.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhnsruho.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gt2qrgcgiqv.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gt2jmfukfed.html

schedule.every(10).minutes.do(job)
来源：http://dali.smart0.xyz/Article/details/gt2evfbkyqf.html

[U37] Py：读写 Excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvmcvrde.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sufxvd.cn/Article/details/gt2hshcxsrv.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gt2vvgijwwa.html

Path(__file__).resolve().parent
来源：http://dali.yangfankeji.com/Article/details/gt2lhmcylvy.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gt2eftswkmp.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gt2jyldviro.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gt2wynrbogp.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2miaukari.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gt2ghqkdzlp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkzmaqcu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gt2dxpgoufi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gt2lscrzurg.html

[U43] PHP：声明命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2snajqaeq.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gt2dnzufwxz.html

[U44] PHP：开启严格类型
来源：http://dali.yonumen.top/Article/details/gt2jlxlbogd.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gt2ujzbasbt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gt2wohejacn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2sefehzkm.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gt2mqctcqbc.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gt2povmhtrh.html


<!-- 参考信息 -->