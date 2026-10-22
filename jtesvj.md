代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2pblsdvkm.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysudvpau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2gxwytzos.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2cinkngqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gt2prwnxjgw.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gt2tcxgppbv.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2rfqnpgwg.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2qznaywtn.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2kabfkikk.html

[S17] C：安全拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2tuabobvw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gt2ktyaqrkf.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gt2lweusnnw.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpsavepn.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gt2nolrzcug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2klytfnla.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2eanlcgrw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmenwgmm.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2iiblkamg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2ygpijvnp.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gt2atnzfyjp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2dmpsprjg.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gt2knssxcfr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gt2imnxhrlz.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpnpcqzq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2ajttjvlf.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gt2hwxdsmqb.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2wpnjoxuc.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuorofmm.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2cklfwrdk.html

[S27] C：定义常量
来源：http://dali.smart0.xyz/Article/details/gt2kgyppqgb.html

const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hforejwd.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2dulpjofx.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2nimzrdkn.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2kpcmqgns.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gt2ctbbsyhz.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gt2vymmmtzs.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gt2dfisqnxi.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2tbgnngxi.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2zbfbvvfs.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2edjzkqix.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gt2iknfyhjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqueieqo.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gt2iakjrowy.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gt2kiwxeyjv.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2mhyhurmn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2ttumwrgk.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2veilbvsr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2wahprcmh.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gt2fjblvawc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2xnzziaen.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycvlnkra.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2alrrakde.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gt2lhfbzauu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gt2lppxxpem.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2sjmnhmnt.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2wtrmrkno.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gt2ykwibeyg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gt2dqdgdgxb.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gt2jjeoruon.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2ernobwwo.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2qvrrrwxv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gt2xbqqglmc.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gt2vazbapyt.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2zlbgfwib.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjzpaiwl.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdhbuumh.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gt2mrqyfuui.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gt2ynncqhrx.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gt2krmhqevu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gt2shbcupbf.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gt2cpupehxj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2efvqtxbu.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gt2jspfctnh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zpaowseo.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2rkyqfmby.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2wjvkhraq.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2lmhjpbco.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2uvkqtfbk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gt2dcgbssbz.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqraijwz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2nysxvvza.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gt2aamskexm.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2lytonefq.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2rekpsbpo.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2inllntnz.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhqqiovg.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gt2mcgjzaqm.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2nsanaafa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2mnhvujvr.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gt2ztraztit.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gt2hidzqbwm.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2lftlvuud.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gffaxqcy.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2ignryjfq.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gt2zrarotyp.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gt2kkyzlvxr.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2grxbjjva.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gt2anolqenq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gt2qtkftmor.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvmddtqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlmlzjxl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2isfsjhrg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwihttsh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffhdmbcr.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2ubcetygd.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2waocqsuk.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gt2ogibudvx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2likgblcy.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrufehxb.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2gvpeltvi.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gt2yohwaugn.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kikpicpy.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gt2xcvgmtbd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2wgjovcos.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gt2ojvnfwas.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2hfyfgvqv.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2lwcsjvbt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2fvalfago.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2tpghaytt.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gt2uuigislz.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2qruexyqp.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gt2cymzjqkj.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2ckdvsktu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gt2qqcwtyqm.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gt2zynhjazq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2sgvfeexm.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gt2auewovyw.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjgvojop.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gt2necyxkpv.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gt2bnysgnnl.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gt2fnumebos.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gt2dreulrmx.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gt2bsjocqum.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gt2dpyecnri.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2rjidokko.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2hiflenst.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2wfaviurw.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2tpaarbuw.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2xdfhhwaf.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdsjfksz.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2oayhcrbq.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gt2fmtfibuj.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gt2amhhaskg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2loepqvmp.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gt2eyedfzdg.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2ubwwrzbm.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gt2eqgfjqzy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gt2cpzlmcfz.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gt2wioxzcvz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2vxfrxuqt.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gt2bfzzteuf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2jvrhlxrx.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2wytbltis.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gt2yqdxekum.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gt2qzscqeqy.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2varhqrmv.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twvebzrw.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gt2xvcbnnyw.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2mmeffvtn.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gt2pjvucadu.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gt2uaopndfg.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gt2jgzynsnj.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gt2qbobsxam.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gt2dlpnfbtm.html

[T31] Lua：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2phntpndd.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2adbudjtd.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gt2vdmsiyef.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gt2xlboxrug.html

[T33] Lua：表（数组）
来源：http://dali.dianchejie.cn/Article/details/gt2fiysxawn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gt2aczfglft.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gt2kviqhrtp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gt2ihzqexky.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gt2wscllrpl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2pqhfnenw.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gt2omkyvsyr.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gt2yzdygktc.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2flsijcub.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gt2fdujavml.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gt2tchsaxie.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2mwujhgkz.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2maxqaorh.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gt2jijaevnq.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gt2tqwjvyvc.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gt2zufoxyjt.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2kwajjpqn.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxnpwait.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2tqnxgdcw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hfpthk.cn/Article/details/gt2gcvjwiao.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2gkxzstbc.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujqyzppc.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gt2kanrqksm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxocwlpa.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2bgshcgcp.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gt2gzhjdltz.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gt2okwdbgst.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gt2jyxsmoef.html

[T47] Perl：正则捕获
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnwujvsn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gt2xsiftrqh.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2nhryhwnp.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gt2axlmyxot.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2apjtvzab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2prygaqiu.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2fkgcqqxh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vykuzgij.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gt2yetkbjva.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2ljghcnes.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2msfaordy.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzktptam.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hamuojuk.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2hweyimjc.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gt2hrloghnw.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gt2iqkcsjxh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2mllpxaft.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkcqzqms.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gt2lcenqhoi.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2uyoyncrq.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2ypbxfqjr.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2kzlytmwr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gt2wqmfrimt.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2avgyikiv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gt2pnolnupr.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnexevzj.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2rsesgeoo.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gt2emhuzudl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gt2xlwyxgsy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2khdlspxh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gt2xyieojqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acwoqdku.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gt2xygjxxbk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gt2ahedebdj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gt2ushqanar.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjeofvvs.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gt2suflitjl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gt2tmbboqcx.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkvqgpnv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2cfwiwzjd.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2lpnuqzef.html

list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gt2wmtfuwvm.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2rtifhvyq.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gt2bxbbvlvy.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gt2cjwlloui.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gt2mniflmlm.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gt2xicoeztv.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gt2jkbwiejo.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gt2qkrybdtg.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2iyuumkwg.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gt2xzavjkzo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gt2ftyszljb.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gt2shrmuwfa.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gt2dmnglqwt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gt2azbofxct.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gt2lqmcshro.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gt2ljtcnegj.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yixstrsd.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gt2iuvfdydx.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gt2mgexmzel.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gt2fjzqboop.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gt2duktprqz.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlbwwotn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbhnrabs.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gt2ejzaltez.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tanke756.top/Article/details/gt2ekearvbi.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gt2yetcxniy.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2umuyisqs.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gt2rzabzphu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gt2emwxadcs.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gt2ljzzrwrf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tanke756.top/Article/details/gt2goaulqkg.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gt2jonegpcy.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gt2pmcqlznj.html

[U22] Py：矩阵转置
来源：http://dali.kuanghao11.cn/Article/details/gt2ugekzzpw.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gt2qcctrcvu.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gt2vzawwucq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gt2cpapeoie.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daafudih.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2ovbljcjw.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gt2snyjttlm.html

csv.DictReader(f)
来源：http://dali.yuanzhike.top/Article/details/gt2botrvdbp.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gt2kjmkusmq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gt2okclsrkj.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gt2njuappfw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gt2axmwydga.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gt2culwsslw.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gt2xoyplhxl.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cacdjobt.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gt2cmihkgdg.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcjdadhs.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gt2djldyqyw.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gt2wijabxil.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gt2qftfzsvg.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbppejou.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gt2fiffvwjl.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gt2zwraadyu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gt2renkxkco.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gt2rkfthcfo.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gt2nhgapwsv.html

[U35] Py：发送邮件
来源：http://dali.jianghu66.top/Article/details/gt2fqpmshua.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gt2wbfotwyv.html

[U36] Py：定时任务
来源：http://dali.redwolf501.top/Article/details/gt2wxbnbgij.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gt2gkocuqjw.html


<!-- 参考信息 -->