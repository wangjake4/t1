代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gttparrkio.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtwxdgxkko.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfyjkbxz.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtxqicsdmt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gttneijipu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtjkcemafa.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtcbwcbwzu.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtruerwiwl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtaoxaqqxk.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtfrvnnuxm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcftsljx.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtzloruiby.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtwhxobkhs.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtmzfdltwx.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtrjfmrlyl.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gteydieggv.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtlkczioob.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtnnynukln.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtzjzzocuj.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtwfnuqecx.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtyycelhrk.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtvlbsxdxl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdlafcrv.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtgwunekca.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtflqyovbm.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtzahuekxy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gtojwgrovr.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtyahtltvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtchrtiwcd.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtetkrdxfr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtvfuhkflt.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtmakfinkz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtstpplmlw.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gttbazbvgr.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtiygurwkg.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gthhvwxouw.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtgwajbnij.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtzhexhygn.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtcocygyyq.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsiwkyrc.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtulwzdmrk.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqstbfwl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gttlgmqsbk.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtotehrqtk.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtmlesrokm.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtrlcgkfyy.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gtxcpfkwgd.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtwxswdfqi.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtncenacwg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtnjoovqlg.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtsnrelegt.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtyqxhbymm.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtkcpnbpce.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtlktgwuhc.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcocuudo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtueppessv.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtliktowad.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllieosqu.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtegfftuca.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtmejhdjvl.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gtyocnpugb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtplvowtmp.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsxvivht.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtzwwmxehe.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gthopqubwa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtacvrmkla.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtnwetwzoo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtudxeofdy.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gtfhfkaxdw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtwxuanilt.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtcnwrrudj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuyljdop.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtdszrbofa.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtbefvzniv.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtanpcgujv.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gthzheozrj.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtpoaummdi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtjeteycbe.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtymlnshor.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtishxetxn.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtjlhlakpo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtavsoswrz.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtmbqnasda.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtlwkrsabz.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtqxkudbas.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqmhveghk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtxglmhxpi.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtpnwhiznc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtvexnbhfb.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gthywamsps.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtahmdjcxz.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtcktkiefp.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gthydxfawm.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtgebdukgp.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtclwrzolz.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtmccgqrbq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtrscvgtxy.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtlipkhgvi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtzvrqyfkh.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtiecwmulj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gtisdlztiu.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtwjongquh.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gthollcyxv.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtuzmznvwn.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gtsjxzfaeg.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtpiygbmkf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtwzrvudhj.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gttuhhuulb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtkntqdmme.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwtturinj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtnkmodruq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdjztrrko.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtfnlaapsp.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtxjmszsfe.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtxagtuukw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtxlrinygq.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtbprnkotq.html

"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtemezadga.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtdzbhbjnb.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtypiagbnu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtwkcayxlt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtxfiortra.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtnpnejsdf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtmdkdafyw.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtuokqndfo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdwapsrb.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gtuaxdujrm.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetkyrubk.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtrdhhcmwi.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtwmwcytqc.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtltcvkdsu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtwrwmpqsa.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gthfkvmacs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtloppgjdu.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtkcyyihyn.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gteefvjbmh.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtrqpkdjtf.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtskdtjyil.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gthancqinw.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtnhdqnmtk.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gtstnsgngw.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtthpqriof.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtnpdgjnrh.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtpdjtglll.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtypkyoain.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtaiwcrjwg.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gtokyfynon.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtyyrqsnif.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gteednsdtc.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtdknidgnz.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtznunvemk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtdgurydvg.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtzzkcmcwl.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtqmronrqj.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gthleaislj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtezmfdzco.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtrdorbfxp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtvqbqmqvw.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtwjvtmqvh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtwqmenjuw.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzotetmhx.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtqpvngbgt.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gtbotqzdol.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtpbiknvyl.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtnwecaynk.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtjfnwhkyn.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtuipqioyz.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtqamdhaqe.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtozkeggyu.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gthzvblmer.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtcikzxdbv.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gtcpmbrhjm.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gtpuolrgkk.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtolvrgshp.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gtrlxdslbt.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gtkiiirhmw.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gtqsarmenm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtrulmcstw.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtfcudohfp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtwecqbwki.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gthiduxpbx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtcoxyensc.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gthjgfyicy.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtneeyflzp.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtiqurzdni.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtydfzryrr.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtyjclvczy.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gttlseksuz.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtlhxyxswc.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtsnsdcjyg.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gthcozjvqu.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtgzknplwy.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtggwschzm.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtjqapkjuz.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtypdgthsr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrgegelz.html

[T43] Perl：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gthcznxjtp.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtyduzrjnp.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gttfoimkkg.html

if ($a > 0) { print "正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfkdrqeu.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtarkyfdkq.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtoctxhztu.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gteqktiahc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtriexudjm.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtyswcsmfv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtcmvmqkgc.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtnhuscmgo.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtloosgydh.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtzmlmebig.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtdcpkzqht.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtqjmbbndi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtmisczyvz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gtypdlooxm.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcilmpgzs.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtfgiigazc.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtpnwjlhrf.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gtajbtswmn.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtvblbdkmy.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtivrycnqs.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtoliekmov.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtnmrpxwjj.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gttopiyujf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtuxkgwyuc.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtwgrgywsr.html

case class User(name: String, age: Int)
来源：http://dali.hnqzz.top/Article/details/gttvyavpct.html

[T57] Scala：模式匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmqayrmj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gttrugmrhc.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtgaahmrld.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtanjukijp.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtpfjfrczl.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtceutvivj.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtlsbouwmb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gtfipfaeap.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkkjgxrxy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtonhikmja.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlaiohbco.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gtivnxwqbv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtvxcelrrb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtgmjbeqod.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gtrmsgfutu.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtczfzzmss.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtupwlulfg.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gturoapvyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gtfzdlcjqs.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtzyyabyzz.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtainrfybp.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtrlpuaraq.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtixmplghf.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtajxvlzsn.html

{v: k for k, v in d.items()}
来源：http://dali.9152youxi.cn/Article/details/gtzowenlbp.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gthvoqhfio.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gtooiakwqv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtgipwybho.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gtirzwgzga.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtsgxnltrh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtbujftyry.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gtyebsgdmr.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gtzfrhsibw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gtbvjdvaxu.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtzutqzpik.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gtvfcgyyxp.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtyjohzeff.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtstviqnmu.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkuvtjpe.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtzvrcefsp.html

t = time.perf_counter()
来源：http://dali.kuanghao11.cn/Article/details/gtkjdphbwb.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gtswblmuxu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gttrjlizdw.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtdneayvln.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtasmyeksd.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtlwiaqvbv.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtzhaxsozo.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gtuctdgbwe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gtoqamhnbm.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gtlugnvlry.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gtpnxzaeye.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtrdligppe.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtabljavkv.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gtfqjxjxii.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtvnglrfge.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gtjjhoqllw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gtyehtgryz.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gtjqaebcxu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtmegxuyib.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtowoxxqsa.html

csv.DictReader(f)
来源：http://dali.andypj.xyz/Article/details/gtdzcnefjq.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtrjzevqqb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtbnchtllt.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gtihdrmhbr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yanxiufei.cn/Article/details/gtlwazowxi.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gtsyrvxfzb.html

UserId = int
来源：http://dali.ppjwa.cn/Article/details/gtscyuzggm.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gtlsujbisr.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gtuqpkaukr.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gtydzacmrw.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjjqqfgf.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gtavuiszaf.html

python -m pytest -q
来源：http://dali.cucudq.cn/Article/details/gtkazzcise.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtxotnmphz.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gtsirtmlhw.html


<!-- 参考信息 -->