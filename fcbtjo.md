代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gt2jtvraoty.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2hplbolvy.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gt2otdrpmbb.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gt2lbxlvofb.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocnywsev.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2cplkdbqs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhuylqn.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2erxdnxoo.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gt2drtasusp.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2ruaibmek.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2unhehclm.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2llumftri.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2thtiqwip.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gt2segpfcxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gt2urssrxfy.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2ppkstiee.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjcjzzfq.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnicmesp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gt2jmlpkkvc.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gt2smwjkkln.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2tmxpgyhm.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gt2wybxgyef.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2womunphq.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2gawmstzm.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gt2noimidgu.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gt2jztdavfx.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2yvscxggm.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gt2rqawkffc.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2ckaqrrqx.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2bydlnhda.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zthllvhe.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gt2oiejoeac.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wathjigh.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gt2wzpjcqzd.html

#endif
来源：http://dali.ivvv.top/Article/details/gt2pmlzcwmg.html

[S31] C++：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2rmhailzb.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gt2iuqxacmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2woyncnrr.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gt2sgfbfveg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gt2djzoiolb.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gt2epjogvfk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zottauxw.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gt2mheznjxw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gt2ezmudlbe.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gt2vceeoahn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2omextutg.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gt2eezvhffn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2nrofthpu.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2zzmzxfks.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jianghu66.top/Article/details/gt2yljsfnfd.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gt2evuegsdv.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2yktlwszm.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2fbazvqpu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2nnzdolsa.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gt2izyfwzso.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnmsxhbh.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2pligigqe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gt2llcmneax.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gt2hewmwyry.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2ogiyvtni.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gt2uhclqeyf.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gt2nentouui.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2fgwydiyl.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ughchixp.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gt2bexypkkc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gt2fflnlirj.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gt2jzdfgvyo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gt2vdmtewot.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gt2dhlgkqdz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogcrjbln.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rztiefqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gt2szwwadgs.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2onbctjnq.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gt2cixaipfx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gt2jcgepcfy.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gt2xfhvwjos.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhshmvul.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gt2xyqkrumb.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gt2jcrncgfq.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gt2ckjdbqiz.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2thfkvarw.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gt2ytvbbjvt.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gt2fanjisfe.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gt2yqnbjlfi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gt2sdfgazgt.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2ygddyvhh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gt2dxjhrzfh.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2desodfhx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gt2vmptwdxl.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gt2rlpgfuko.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gt2cfjafcii.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gt2pqxqzdmy.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gt2ydpinktv.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gt2rdxsrbmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gt2dihvcepo.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2sovltbtw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gt2uomzzwrc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2gspxfenc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gt2pgrthiys.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2odohxzwr.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2kqdujaue.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2rwkrmqfc.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gt2pkcxxhvu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gt2rjlwgfmx.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gt2egatgygh.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2nnqizdjl.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gt2fpyvlgux.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gt2canqmeun.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggdykjbb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gt2ewlmlkpv.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2omxaqsux.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2kjgzbwii.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlcwwnis.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2sbujvpkh.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2hzvtfckh.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2fudfjvvl.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gt2boqdxwsr.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gt2acrjxhzr.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2qmymaagz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2txhrvjeo.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gt2vknxmqrs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amzmrzim.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2qkgvefbd.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2gcwgodhg.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gt2eudyaprs.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gt2fiwppzrz.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gt2dlmlkjbh.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gt2snfwdieb.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gt2sphxfice.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gt2qmibyrvc.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2lieiyrcn.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2wbqoppxv.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gt2penvkike.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2tkmkuehc.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2lwjnsvqz.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfszkvkh.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhkqidhx.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gt2ryfmbfqt.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2itmunekt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2mgzytgmv.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2bnnbngfa.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfkjyyux.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2udlglolr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2wjkclqmi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wctcbkbg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2jsbcsdad.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2sqtycvdw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2wzuxworx.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2olobxsxf.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gt2fmwxodqq.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gt2ygttoyan.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gt2objmomht.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gt2zjsouzey.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gt2mkxdirqk.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqwwflwg.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gt2ingvopfu.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gt2jpvcjodh.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gt2laxjpkug.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2kkzouhrn.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gt2kxgknrvu.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2nwptjzec.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2cjmfwdyw.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rijrscht.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gt2dvsfzjsl.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gt2ffiruxwt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gt2sumlninx.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gt2wozfiwdj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gt2ouytkcaj.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2ovdnwpie.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2vnjgyfek.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2oztskbnb.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gt2wgvtxlwc.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gt2nnxbdxyv.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gt2hpqdyqni.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gt2bkichrjg.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2zawhepmk.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gt2thicjzxy.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntjtqgoy.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gt2hlhlunwi.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gt2aacktuyb.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2apfolbas.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gt2iawvnzjp.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2ypygolzx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gt2uspsgekw.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2kvwvnsmv.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkwwwjuq.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2kwnbsnkg.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ljjecfvv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbbscyp.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2skupnvvs.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gt2zfblsted.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gt2ljysrwyi.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odkzfodp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2barhenfd.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2jqapxcpp.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gt2lpcrnhvb.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gt2csvnrbvh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlqlhkin.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2rrgnznfv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhengqikj.top/Article/details/gt2lgwtsdho.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gt2hddidyhr.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2juridtca.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2clvslugs.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gt2cjzcuwej.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2zgqifeeu.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2jotlqmfb.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gt2cyoegwhl.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gt2axwtppxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2nmcmzbht.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2wkjjpdjm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gt2jvqbjpmd.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2foxfflhy.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2fdypuldf.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2wxgnuevk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gt2gtgyhpwl.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gt2ojqcdxje.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gt2ewhdipzw.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2agwjxxqd.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gt2jlisqtua.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2yaajtzyf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gt2yvgegsqx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvtxrhaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gt2lwgvfgyx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zobgvwwe.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gt2luxpnnqd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gt2czccdtfi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gt2pzbwbvvb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gt2gfzogsgz.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gt2lwbwvopp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gt2gkgladpf.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gt2lzpvatih.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbvairvf.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gt2dbhwwawq.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2dovhcuwg.html

[U06] Py：合并两个字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjptkpqr.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gt2enxtfgyo.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gt2skynatas.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gt2mdtvaohx.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gt2rlcaqaxs.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2plrwzkio.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gt2kugcrwtn.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gt2gnrmozth.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gt2sgpnjejx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gt2owfxfvll.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gt2isqzvjcs.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gt2ajjlotwl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gt2irlxcome.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gt2kblqkkpg.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gt2innhkisb.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gt2fxubombb.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gt2lypbgpeo.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gt2ggavgvog.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gt2tsuewrtl.html

t = time.perf_counter()
来源：http://dali.zhixingplan.top/Article/details/gt2dzahbbul.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gt2utcstmol.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zdqjudy.top/Article/details/gt2qcxitmxf.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gt2eefpgcns.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gt2mhwvtptr.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gt2dpfcvydt.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gt2weescolg.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2qetovgdi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gt2dqnswmhh.html

[U20] Py：缓存函数结果
来源：http://dali.bjfxy.top/Article/details/gt2sjcxmweh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gt2tvnaqycs.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzxexalc.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gt2uzpjdmva.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gt2gyeagubm.html

list(zip(*m))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnhozajt.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gt2wfqytnff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gt2oronoxhp.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2oamqsjin.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gt2oiilrxfp.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gt2bhoxytgm.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gt2zbvczmci.html

[U26] Py：并发下载
来源：http://dali.cdnleiting.top/Article/details/gt2cccczbkn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gt2odstyyrv.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigufen.top/Article/details/gt2lmegheyh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gt2rzpybvlv.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gt2imrcycms.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gt2xltkfehl.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gt2ortytlso.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gt2quflwich.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxfcrhd.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gt2wwzeqvqc.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gt2dnbzalzv.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gt2rvrzpqcb.html

[U32] Py：代码格式化
来源：http://dali.fzhhl.top/Article/details/gt2otrixaon.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gt2xbcupniw.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gt2yqjagsnk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gt2xvshcbne.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gt2rdkoodxc.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gt2cbdkjfyg.html

[U35] Py：发送邮件
来源：http://dali.shuidangran.top/Article/details/gt2veggyjmv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gt2bszinsfq.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2kvqokxcx.html

schedule.every(10).minutes.do(job)
来源：http://dali.316326.xyz/Article/details/gt2jmuyozjb.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gt2rjxcuslo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gt2seexruwu.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gt2ctrwiefl.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gt2okhcupej.html


<!-- 参考信息 -->