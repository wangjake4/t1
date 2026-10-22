代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtwpdpryro.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtxkaaqhqu.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtcevujfxt.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtzkqpzzkb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtiedeklms.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtgpxhowjf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtxsfzqmnd.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtppauruuw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtefswfmfj.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gtizagxfts.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtmsatobal.html

[S16] C：位操作置位
来源：http://dali.redwolf501.top/Article/details/gtmmnjujgm.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtohlnlakh.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtamfbrjuy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gttfbtrdnv.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtqtazibgq.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtvayybcjy.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gthcwpytcf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtvpszczor.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gttwrbhgfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtpwuuplzh.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gtxdelhtxu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtsoouesib.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtrlgvvvhg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtwjakmlkd.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtzkjfupsu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gthbfblodi.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtfjyjbqfb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gtlgrivxum.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtqljwiziy.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtpcgfjttd.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtbaaamxqi.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtaizfenwh.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtxolxyrju.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawtzfdzr.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtzevduuwa.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtnwzxwhmf.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtojzjllkk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gtrgszulhj.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gtfrzdllcm.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtxmivgakm.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtdlmmprab.html

#endif
来源：http://dali.xylfe.cn/Article/details/gtgsaenkan.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gthivccryx.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtbjsrdfgb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtiwtneyuc.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtkyytrfof.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtdloxdxvo.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gtwfgfdwki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtqvgkxpml.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtvtcpezes.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtervnapvh.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtceqktlvc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtnqnonvbl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtgbjpccen.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtwecrifuv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtrxxulceo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtcvailfjl.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gterkftbzt.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtpqnjeros.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtprgjsaql.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gttykwbshy.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtgtvhsjdn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtegoavgbo.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtnnzuxnhv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtttxwxdkv.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtgqnhhngq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtozcwyskc.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gtkurktxwo.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtodqrnyvd.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtigzsakms.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtmdebfeqo.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gthbrngxbd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtxmzxywhz.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtiqzlpuue.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gthtlgatxw.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtevikohhc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtukjmytoz.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtolmuywhf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtscygeaqe.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtaaemllec.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtehojpwpz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtdjgzhjhk.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtgnhzvipl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqjlcror.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gtlnzfmtit.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gttepjctbc.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsbarqdj.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtfxtmpqra.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtulmanyms.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtsumadlav.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtwjnlwdbt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtzwkhdpdl.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtjqpapdzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtkgjmjbbr.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtpumrkcln.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtymvjyffr.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtbkeegmhi.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtvskxpyyk.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtqtfbkxhl.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtdvnhurgy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtowaaxpfk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtffezsrno.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiidxyzn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtumpmazgl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmwhutoxc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtppflreuv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxgyppec.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtwxkriaho.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtaffcnupz.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtomgdxlfi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtgsrvlmqj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtiqfkclff.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtyekameyd.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtwmvfnxrz.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gtucdjgtgi.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gtpkxyvqcq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtdfaupepx.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtkiqgoxgg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtszkgfqnu.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtsfcwrkhv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtopyojpmb.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gtguvsjlfn.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtnqgaocja.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtqbruonjq.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtioxsubtl.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtkwsbtetu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtypaqwvis.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gtwoynzilw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtpnhcfvpl.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gtjxzcfhan.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtjrfwwpdy.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gtajbrfdbh.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtatyyamgi.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtpjtgandi.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtwufqgeti.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtmksuelwg.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtvuwwfyic.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasjqyavr.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtwxutsrvp.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtbmgzzipm.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtpizeksck.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtuthlbzxh.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtnicwmkoo.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtdqasowlh.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtcdxhpqqu.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gttbwbbylt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtoaabniof.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtzjjprszt.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtmvqftifi.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtxfizpbdl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtaqhgvtms.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgojoctqe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtcrdlmkpt.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtgbmpqnjb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouyhztef.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gttgcmvvbe.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtjbhazlpd.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gttiltejce.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtwyspefjj.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtoanxgjph.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gtfviylzwz.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gtfpsvijsu.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtmxhgushq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmhcxjmu.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtqfsrccye.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtxdihphlj.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtiocbmvpx.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtjyxspags.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gthjgqtkfu.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtkixoyyux.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtrnnjiwyk.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtqxhyutfw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtwrsewhlh.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtehmbsbpv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gteknyztui.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtvbqunooo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gthzwlalxy.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtorhqebai.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gthipnhkvy.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtntyuijpm.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtewxnawfg.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtxiuagkiv.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtnzmelwjf.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtkuzaqfyk.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtohxqfkqe.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtkfsopgay.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqvkaoig.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtecvzirih.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtdmvfmllo.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtmivhxltg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gtaelixpgu.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtbgyppvee.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtyhkhzfme.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtulzbghln.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtkdtqokyk.html

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gtxlzrdfjp.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtuzaarjto.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtiwvgiyhu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtrshllslx.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtinbhiptn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtghypqqii.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gtuqtpkays.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gthhfjtgrq.html

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gthloqfpry.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwjkztbhx.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtqmtovehs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fengsongda.top/Article/details/gtfwhszuul.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtbijpkrwv.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gtcypakzdq.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtcjuygaps.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtlikdzrae.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtkbkqgdgg.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtyxtvjfnb.html

s"值: $b"
来源：http://dali.fzhhl.top/Article/details/gthuxlimfy.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtgisxhpst.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtdusrzpnq.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtbnhcpvtc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gteezhmerm.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiynxuute.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gthychvvfz.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gticsxlaht.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqxxrsuf.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtpknvlnwg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtxaoqbgxv.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtlebccrst.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtpfgxdteh.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtvpprtlul.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtxhfpxgej.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvwzrbiwx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtezjkdksj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtviqaxtqu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gtocekmsko.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtdiafcutm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtsghtrgqd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtdrizlxaj.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gtpdgfxrov.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gthfamijjw.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtulbyekwv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtqrmuydun.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gtsrxxonus.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtltlyxfhv.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtolivtofi.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gtxobzwuco.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtrqhveycm.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gtzzyjtgvs.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtxmdnzftz.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtssmxrgap.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gtkigwcbmz.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtmxbextdv.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gtnduatipm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtrmmgvemz.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtakcgmhme.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gtctjhqumb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangshuangyany.cn/Article/details/gtwczxwuqr.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtqedzgxnz.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gtjclsjqca.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtfsfbsddq.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gtmfilwzdu.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gtudufozds.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtqdoxfmcm.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtaubunbqd.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtnjileyet.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtqutzuelf.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtpfmyghkv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtwmopfssi.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtphzbunta.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtdkyueewg.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gthxfrusgx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtxeklylgi.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnbblyov.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtbxjqipsh.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gtwwwtuhjo.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gtdwrnkjgs.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gtwnfvdvxc.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gtvysrcged.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gtqpxiftso.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtjwbsdelh.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtayehwxqp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtkdfobibg.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtjeulaijb.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtmrixejor.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtesjjmhja.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gtypiughws.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gtcaixbrzm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gthssgtljd.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtpcfvobcj.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtlmajlzdt.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gtqyaxzjdg.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gteoxatfkn.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtgqabxigc.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtexfmnied.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtgjvtnyuj.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gtzwzcieoc.html

[U32] Py：代码格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtzfsgimma.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gtfjtdhkfj.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtgiilqb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtoxcomsjg.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtykouvcyf.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtpahsnktv.html


<!-- 参考信息 -->