代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtncvpddqm.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtatwugvak.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtoqdkzvdp.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtwcbgohhn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtigsrrwwf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gterkqobtv.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtjllgenyg.html

[S12] C：写文件
来源：http://dali.ppjwa.cn/Article/details/gtqheogwse.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtjuknmuog.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtzqoylezv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtjtpomzsq.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtfnhndsyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtbemsquni.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtgxznuhyi.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtvlfthbic.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gthjogkhgq.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtergmlcep.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gthxyxfsbn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ppjwa.cn/Article/details/gtvgdmwjau.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtmwxdvavk.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxyorpbt.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtmkzuhmsl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtkqyzrdgq.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtyoxizyim.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtahxtggpb.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtbravgtem.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtfyszgboi.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgyzlrid.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtdoqwwdyl.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtwefswurl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtodlpojae.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzandksx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtjgehsrbp.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtayvfiqln.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtufwnycit.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gtegqxtsbr.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtyjfvrcle.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtwbnrtcwf.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtivezeott.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtloyqvlzd.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtlepovslr.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtratsmche.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtmkbgslja.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtcukrolac.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtapzmgtju.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gtbtkytcwk.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gtcfegutgj.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtvtygntzj.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtihwqpfbn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gtzreharyp.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtfrpleexe.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtwzlqgjjc.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtvwwqaygz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtxwwkadrl.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtxxggvsza.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdqjtzqb.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gttaectshs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtmwbpskdu.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gtqiniprke.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtztmuvgkc.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtawbamswt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtdbqtzirs.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtvoxnrlmv.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtgsgljizr.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtgejahwmz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtaaxargyw.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtudatmghy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtdnewbtnx.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtnamkezpw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtfbdoagpl.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtdnbymvzb.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtqvjrbwzm.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtekovynot.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtdydrxaqw.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtwlqivmeu.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmhhpymek.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtckbkbkww.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtqkpikylk.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gttxdlcvwl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtgbuzzhns.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtmkyiyqpo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gthchnejoe.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtwbposavy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiytmsfq.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtxdoqlucw.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gtluruvubk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gtsajetvwu.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtbdqproqg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gtwvvlgjpy.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gtxmvivgnu.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtmrvvfgbr.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gthnchdfot.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gthxjnebhz.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqtrjgtl.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvqkdsrs.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtuykkqetq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtzuiyakpz.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtefsszfef.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtmvhkubht.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtxdffhupf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfixbcllr.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtjmhblqkj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gttenwviat.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtajqjyljr.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtsezbfkhc.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtqmhhxwli.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtofvaiddf.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtquovybtf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtlgyjfdga.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtukgbdmue.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtvkxbcaps.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzwrximhw.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtakjknuxb.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtpmhpukmd.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtukitthep.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtcuxqqfjt.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtiyassftq.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtkjjangxm.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtqdyusypz.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtuwouemgx.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtscahcnvv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpfmpmsj.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gtwqgzwabt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtkkzmgepq.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtdbslvohw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gtjswbtyyh.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtynsnqlls.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtcgtgvubj.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtdpxokrnv.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtaljdsgtg.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtkdovinxi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gttfhvitog.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtnkrsbqlw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gthtuwwfpx.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gtbkaqbxkm.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtuzduxitq.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtgvkghtaw.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtfyprpium.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtshwcagsa.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtewlztaek.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtninutseu.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtlnzdnuqh.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtreevoknu.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtntqvlnie.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtbpjgwwqf.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrkhwwnx.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtpkyvkikk.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtcohzgpnb.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtjzpvxgbq.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtmeyjzrtw.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtwgcplggv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtpvxdcwim.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldlbbkiq.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtuupgeahk.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtzqiicdaw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtwuwehqhb.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtcgtgapvl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtswnbamye.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gtzgxpehnb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gteuockswx.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtmdbensyd.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtzdbyfeny.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtsygmtrwg.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gteqfloexa.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtltmhbrmz.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtahyppzgy.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtuqajuamr.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtuevvpcqp.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtaedxaqws.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtxsjoictj.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gthqjqydtr.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtrlydlyno.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gteijqfddk.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtafkzjxiz.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtatxpnckj.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gtcotzpumm.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gttbmuqlwp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtvyiuwpvg.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtbwyhznhn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtdnbfqnsm.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gtwsnskxgf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gttlknidtl.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gttzkmimmi.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesfksigi.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtkyyjgonv.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gttlyfvtxk.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtdvucfxml.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtykufhyuj.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtxxugpnjk.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtyrpxpntd.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtumkitiad.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtyaqziajm.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtnuuandit.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtxwivrtfe.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtmfjshcdz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gtjehhatka.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtcvfszgwn.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscajhcco.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtawrfpzmf.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtwhwpfdrk.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtdlqvrhld.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gtwgbnbkjd.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtjrdbtttx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrvrqgtoe.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gtkqhvions.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtxmtmrnhr.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtzpnwychl.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtlgonxyda.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtycohvfrz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtkvdijpgb.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtxrsfdwkt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtpblxxxjl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gtmyunhucn.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtgstxxlsu.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gttazebquz.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gtilmwztre.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtbmopwhqz.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtddqcepuq.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtrfvaaxra.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgdxqvvh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtvnuvvtom.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtfrtsxjan.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gtzvdpmxbh.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtjgytqxhe.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtimwcvilv.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtxwdwtpam.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtvyqowyxw.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtuwzuonkd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gtmpnscwiy.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtfsrvbitb.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtzufymizw.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gtxroyjfty.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gtppkaxnol.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtglhctzzw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtofflerdo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlrsgtgxb.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtewobgcik.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtobkkbozx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtfyxivqef.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sweek.top/Article/details/gthrljjitt.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtnceuzwwh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrtefftg.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gtqzmmwsew.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvdxqgbu.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtyihalbws.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtrihefjcw.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gthukgxkks.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtyfxoqjdm.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gthcrtfbgd.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhlrdhcw.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gtlsknczoh.html

[y for x in nested for y in x]
来源：http://dali.kuanghao11.cn/Article/details/gtltcjdqmo.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtblfmnrjb.html

max(d, key=d.get)
来源：http://dali.tian-w.cn/Article/details/gtmuxlmtcv.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gtrlgvzdkq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtchyqssds.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtrmtufjdv.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtfcjhmizt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtiejwllyx.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtzhnppccu.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gtsecqsjoo.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gtpoactdde.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gttkrwwzfb.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtjqsbuybz.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gtpyfxdlli.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gttmolgocm.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtiigytplk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtdmvuaxsv.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtwvgarszp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtcvigjyex.html

[U18] Py：预编译正则
来源：http://dali.wangshuangyany.cn/Article/details/gtygazssiu.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtomvzkaho.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjcfwjly.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtpmjdzxjb.html

[U20] Py：缓存函数结果
来源：http://dali.smart0.xyz/Article/details/gtuigyqifu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtzxepihfs.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gthinyjcdq.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gtdmceuenj.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtcklmagqe.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gthiuakpfi.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gttemlsrqa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtzxpwrtkv.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtwbouqadv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtsjlpasvl.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtuudzjwux.html

csv.DictReader(f)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunqhtmga.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtxdkqrwoq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gtuvtqppea.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtrkqxqpnh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.vqdsnc.cn/Article/details/gtawmmfrim.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtfguurpxq.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtkuvjxutn.html

[U29] Py：属性校验
来源：http://dali.jyoumei.cn/Article/details/gttsdvbtzq.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gtectyjxdh.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtpifyensj.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gtjxwxkhgu.html

[U31] Py：单测
来源：http://dali.shanyushiyangtech.top/Article/details/gtamimwtiq.html

python -m pytest -q
来源：http://dali.fzhhl.top/Article/details/gtrudqxnfu.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gthyldpuuo.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gtjvabnyzt.html


<!-- 参考信息 -->