代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2aqslwski.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gt2hawntuqw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gt2pdnwkihp.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2jlfbtxda.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehzzwldi.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shmwnhca.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2xswrdqgn.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2esjphsvw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxczhynp.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydcvuxci.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2pzideoiw.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gt2lbdvabyc.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2srmjrkav.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcneuatd.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2ipfadbbs.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpkpvvmk.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2ncwfnxag.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxuqbkus.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2tuzriekc.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gt2yaoakayu.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gt2ecfusutl.html

#define X_H
来源：http://dali.cqqwz.cn/Article/details/gt2csvjonwz.html

#endif
来源：http://dali.yvedp.cn/Article/details/gt2biechzcn.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2kvzlczvg.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gt2aizyfmjt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2xfnolqgi.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gt2nptflptm.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2bskakynv.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gt2xlugafae.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gt2kfzomywb.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gt2jwnbqdti.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gt2bddguapt.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gt2vylfyfep.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2qxuqqtas.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2inrukprc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzzwapvg.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cirymrvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2oicztcue.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2kjyopcdv.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhoxiamq.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gt2xrllzkhh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2ymiaabis.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gt2iavpwaig.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gt2kcsekbuq.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gt2unakfpma.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2ljybbwln.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gt2oxvfquuh.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gt2zisuksnu.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gt2ofcaqzrq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gt2wvailcey.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2amjyzpxa.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2riqstlwa.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2glfsujhm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gt2vhaddkur.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usifeclm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lebtehhb.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gt2vwthltwr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gt2lgabuvkp.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2ipqklcff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2vebanekn.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2ipfinfqh.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gt2pdbkpecs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2klteyjib.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gt2cfnksgsw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxynfrhp.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2tdqhqcec.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gt2mfgpbzba.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2bldbreiy.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbxqkrok.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gt2piuqumdf.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2gdqbjwfh.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gt2iqoetpcd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gt2schqjdwj.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gt2ihrhvgga.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2usyzluie.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2zwyunlzr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2exvaanhx.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2djcihleb.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2gnsginkj.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxlkwskk.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gt2rjusvdmi.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gt2bwvgfrys.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2vilokyfq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyfpkpl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2nxetqyps.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ehgophqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gt2eetxohnu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vtltjcza.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2iutpyyel.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2pabyvyft.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2gauaiuuf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gt2swdekiub.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2apzmfbrw.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2qycdbhjq.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gt2skxneoxs.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gt2afnswkmu.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2zzrxxqui.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2xmjcvbou.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2vtirjuct.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2irkyeshj.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2ibhuaiin.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvyxznil.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyvyjvhr.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlgdabyy.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gt2zhwuepsi.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2roozrpdk.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2ggiacgxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gt2lgesqzrk.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gt2kjsmkxqg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gt2qdlcmmfk.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gt2kmexdhtu.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2apufabqe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2bmyxdjyf.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gt2kutdegrt.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2zndrjotq.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gt2xojorbgy.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gt2aplnkftb.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gt2pljqkyay.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2ewtcxrer.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2mzhapdax.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gt2tyzivtnc.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2vkgwmzzj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2naulmfqf.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gt2vcjliswa.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gt2ulcaagel.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2dpdaxwyc.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2tsuulbzb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gt2bbukqjxr.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gt2dcgacorv.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2elfpttzj.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipywikkx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gt2fzdtgtan.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2cbrvvpmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ovxxamco.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gt2wbraggrj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvvjbfcc.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gt2qysbrrzu.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gt2qvqnmycc.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gt2bpoxunxt.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gt2ivusmjkg.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gt2ahlfwval.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gt2ggjfwwbb.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gt2gzujgyjs.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gt2bxzvbmkw.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2nwzyvefy.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gt2izcjftxj.html

[T30] Swift：协议
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhjtwlsi.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gt2ssfaotif.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2cuxwaebx.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2kcyhefgi.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2itifcybx.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gt2pdzkptxp.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2nblenmrt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gt2atdhtsjz.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gt2cfufmihw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2zugovanl.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gt2hbkonxgx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gt2ywwukvzv.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oabkigco.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gt2zmdepupl.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2snalziwp.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gt2mgentkos.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvmreunm.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gt2wgmtgjxc.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gt2prxvuhiu.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2nswckhih.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gelxjgkf.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gt2lprhgeis.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2mzgdangi.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gybmpfao.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2udhslyfv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2rtgamssk.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2lnuroixe.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gt2pydrtlog.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gt2vechoadi.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gt2uocvbsmt.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkpasrrx.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vokjilli.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwgzcbae.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shcsnrgs.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yukxuhaf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gzhubu.top/Article/details/gt2wxvotiva.html

[T48] Perl：正则替换
来源：http://dali.sufxvd.cn/Article/details/gt2fweoxgmb.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gt2amfvfcym.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2uelznxnz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2marjphsc.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2vgxnpmeq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yangfankeji.com/Article/details/gt2yuwnjxae.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gt2cbmuavxd.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2pojxjepo.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2lreumtac.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2ldjbpwdq.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2jotwzzna.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2eplmfjxo.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2lxgumpqc.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2ewtuupsg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2iyhrwmte.html

[T55] Scala：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2cubscjzb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdqeoobw.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gt2hklwbtfv.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gt2uqqfqpum.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2geunhhod.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2mpwmfoev.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gt2xxizxssf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpcdjyuh.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gt2zmdphlsq.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nawvjbju.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gt2dqmxdeux.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gt2xjjjptbt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2titzhvmm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gt2htegnulp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wfnuhevk.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gt2swoxxvon.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gt2tgruzbuv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gt2pzjxxltk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2pkihnnux.html

[U03] Py：加载 .env 配置
来源：http://dali.hfpthk.cn/Article/details/gt2htuyfkqq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gt2mairzcic.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gt2jqkxtdkb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2blvxmrtu.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2fmwqvwup.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2povvmhre.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gt2ytlpvncm.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gt2pebrswhl.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gt2nxtcqywq.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gt2feezecer.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gt2usboqrar.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gt2bthdstti.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gt2giddqqre.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gt2zlcyvjno.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gt2szunzfgr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2mtgvhygs.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2phwknenf.html

(x * 2 for x in arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2zgvqpvtg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gt2scajnakn.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gt2thaerzry.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gt2astjxdti.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzivboph.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gt2kwnilkcz.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gt2irymfdxn.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gt2caffrmrv.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gt2aryyyntq.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gt2aksducde.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwfrjisa.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gt2hmmrlier.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gt2ybxvdlxp.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gt2hsdzxfyd.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gt2qffrwnfd.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gt2ltjyrept.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2izwfkpdc.html

[U20] Py：缓存函数结果
来源：http://dali.hysaishi.cn/Article/details/gt2njxirnes.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gt2ehshfrnu.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gt2laznwztr.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gt2ppsqpqiq.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gt2tyspxwxa.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjaiemcy.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqwtphpe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gt2wqjszwqc.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gt2eecagxdw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2gchjfmwf.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmnsrzln.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gt2endwlylb.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gt2ddadklgb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.9152youxi.cn/Article/details/gt2orpgcxlz.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gt2nqljhzjf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnxiangtu.top/Article/details/gt2totafjzz.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gt2oigyjomk.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gt2wjinlzox.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gt2gzotjbgc.html

@property 与 @x.setter 配合
来源：http://dali.shuidangran.top/Article/details/gt2ailabdxh.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpiqfgyg.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gt2mapxnznn.html

[U31] Py：单测
来源：http://dali.shzxlz.cn/Article/details/gt2wmokgylk.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gt2wdzyexhx.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gt2opdjhhta.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gt2bbnhaqoy.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmuziraf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdpjyjly.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gt2tkyjwdry.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gt2centhjth.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gt2yhtufvjk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tanke756.top/Article/details/gt2nxtlajdr.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2mcagftwe.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gt2awajjuhy.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gt2rblildjz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gt2tvhjsqov.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gt2ecezuhkr.html

Path(__file__).resolve().parent
来源：http://dali.hnqzz.top/Article/details/gt2zqwbvyxx.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gt2cadljdpa.html

sys.stdout.isatty()
来源：http://dali.jyoumei.cn/Article/details/gt2jnzeyavg.html

[U40] Py：打印到标准错误
来源：http://dali.jlsjyb.cn/Article/details/gt2ldctevnb.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2yauijbyv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gt2xjizoqvp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gt2fkzivzfs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gt2izybsswl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gt2kgdtjfba.html

[U43] PHP：声明命名空间
来源：http://dali.yvedp.cn/Article/details/gt2sqjreayq.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gt2tuetigbv.html

[U44] PHP：开启严格类型
来源：http://dali.ehwqpu.com/Article/details/gt2bydtzmej.html

declare(strict_types=1);
来源：http://dali.tanke756.top/Article/details/gt2glgtudzb.html


<!-- 参考信息 -->