代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtrshilqzk.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtomytrdix.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtjlkxcmdt.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtlcyzytci.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtsxgbgbez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtilxyqnyg.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtnfnyjpew.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gttotmujxu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtabemjskj.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtullvgwgb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtramzuzge.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtllopsujg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtliaqspkz.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtlygdsljf.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtbsqankag.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtauvzbozv.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtehmdtuha.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtvegbonil.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gtjudauqsi.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtyfqzmhxk.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gthsxuckov.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtzqnbztyv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtyggjjgud.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtnsxzxzig.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtqljogljm.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtwnohostv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gtmkiocrcg.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtxgcagtrg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtbmhdfzjk.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvnpzkbh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gtrpdunxst.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtitclzjkm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtqxzqngxi.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtnlgimpjo.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gttdtgkbnc.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtrpdcoorl.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtkalwrmlc.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtwrnujihx.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtsqknebjl.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gthwbdxkrp.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtcjdcsjub.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtaczyyufm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtqmpwnmdn.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtyxyxdlry.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtzymaxswh.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtgqsiliyc.html

#endif
来源：http://dali.birdmap.top/Article/details/gtzhctbycw.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtpqhqgx.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtrvbypkru.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtndzfkprd.html

[S32] C++：字符串
来源：http://dali.9152youxi.cn/Article/details/gtchtrfuvr.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmywpkcc.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtusxinzmw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtrarakrzz.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtzswvlpup.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtdtqtimbf.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtadsaoheb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtwzjkcdoq.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtjkirdkyh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtvsufycqs.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyrqwjsi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtrmkugokx.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtfmkooped.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtmyqvooip.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtlyzofiyx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtolxknbcj.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gtvkbdzbvi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtameczios.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtkpusnzjt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtglaihlnu.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtavphdqdk.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtvgdxkvff.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtwlfjkhir.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gtwnfixoag.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtcwaraqwc.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtjnxhkakm.html

[S45] C++：lambda
来源：http://dali.snrcjt.cn/Article/details/gtglfwggds.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtkewrwfds.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gtruktpfdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gterwzfzxh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtqnhviwcn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtboyalrte.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtutfjkvyv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtdlfwzyuz.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtfzjhizkj.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtchreomcd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtylidigdw.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gtevtulndd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtzyfyrkic.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtuxyiapgi.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtpnqebptj.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gtblaeahdq.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtysvexplf.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtwnwoijpl.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtyvmwyery.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtznfwwcsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtfhgivzjl.html

[S55] C++：结构化绑定
来源：http://dali.shzxlz.cn/Article/details/gtyzamlvdv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtjtihrxhu.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gtjcoffljh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtztqnpplc.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtgrbjlaoo.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtobuszzyn.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtwhddpowx.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtkuqiggxi.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtprixtotx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtbzmfhzvd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtftrxfcam.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtnqcrrgqv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdgcvevjj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtpdplmfxq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcoydmyje.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtemmbticx.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtqndgyopc.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtltryifnf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtmrwzcird.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtuzyhbjtb.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtbiynujku.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtkxascbjh.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtwfezgfkn.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtpncahzhr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtmpouqxvf.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtksywxtzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtqysdlmup.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtjphcaycw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtkcnmvpom.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtajdmvrbi.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtddalslzc.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtyvxdgbfh.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtwcsnuyop.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtiwnzhfmd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtslrsflzr.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gtcclmvtxl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtwugiitnl.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtmlndxqex.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtvzqwollk.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtmsdydmeh.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtxdvrlbou.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtugwbhouu.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtgyqiifzy.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtnxzxuvkg.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfyxwbfr.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtnvdgudsk.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtyuhvwswb.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtlxefoyph.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtuubmpqvc.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtdrgqwtis.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtejsirdqb.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtmidbcbpp.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtmeexaesw.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtattkvhgg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtqvgghzzl.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtjgcydcun.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gtojwwgkpw.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtwdalfrpy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtdkakrprd.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvqibrds.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtrlyjtomf.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gtanevalah.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtkhlwbwdx.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtkujepjwu.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gthsxqtaue.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtizrpnmwo.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtdauzeltj.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gtewprlkdh.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtthvloljb.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtfnpujikc.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxptnlfqy.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtibwiruef.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtliqzzhhl.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtgkanajhn.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtsbvjaheh.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsczmzkxc.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtopmhygoo.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gtpoyebtpb.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gtwgrcnjjj.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtymrlcqxx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtzpotiynq.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gtdomnajcv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gtdyhpjfmm.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gtxsttvcxj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmxqqpho.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtflljcdou.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtilohstby.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtbdhgqskm.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtpnkiubrd.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtmpvhlleg.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gtguhzovjv.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtmzxataqs.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtmiavuznd.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtsjhhnfzx.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtajcmpysd.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtwbhpuaip.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtnuccfqpb.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtmhcwvsyi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gtqwlbkhbl.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtbzzryllz.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gttremholu.html

[T44] Perl：条件
来源：http://dali.zhengqikj.top/Article/details/gtjzcrrmvv.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gtpudijwau.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gtdlzwnxef.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtlnxzvejt.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtarroorbi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfighpjar.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gthktiuxii.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtfovnhlsk.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtuhvnqpzi.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtjpswrgpy.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtylzjxfvk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtrqnxislo.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtawcqutid.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaujiijqk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtzoikzaqs.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtyzwtpoqm.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtnjgsjhvk.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtximozaoc.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtffukpoyl.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtyzxvotbv.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtwmboncbv.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtrjesxyio.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gtxzxyygoo.html

[T55] Scala：集合过滤
来源：http://dali.xziqi.cn/Article/details/gtvlagjltd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwciyfvd.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyieiowyj.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcksffvle.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtpasoclqs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtkssyyldk.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtqsddlmsr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gthmakwziy.html

[T59] Scala：循环
来源：http://dali.yj20258.top/Article/details/gtfznczgib.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtxzgyfntx.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtxksryjxl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gtdbgdsczm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbnwnmprv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtltctglhl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwobkehwg.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gtmmvqdvbd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtjqhzdccf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gtzrmlhyuh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtarhicmvj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gtalcerfeh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gtkynibtcl.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gtbcggqege.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtbnmzewww.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtrpdrsaqv.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gtuodwmbxz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gtxssiebkx.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtxxcmamcu.html

[U07] Py：反转字典键值
来源：http://dali.mhx1999.top/Article/details/gtgykidxkq.html

{v: k for k, v in d.items()}
来源：http://dali.9152youxi.cn/Article/details/gtowjmlrle.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtbzukgroj.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtyzjbetyn.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtjelmjmfy.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtxszxwyaz.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtwwhbjdke.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gttavtxblm.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtbynkpoqe.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtufszdova.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtdzdlnbey.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gtomzsiwzi.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtjsnvlyjr.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtgtqcnwry.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gteobuitis.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gtsnihrlwg.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtkxcroxxt.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gtbathybtv.html

[U16] Py：命令行参数解析
来源：http://dali.hysaishi.cn/Article/details/gtlhqftaus.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtimhnqkbk.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtigekacqh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gotoacloud.top/Article/details/gtbuqmhzkt.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gtlvlngkfz.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtztbpepit.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjstojlv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gtsecspanu.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gtzmpwydfe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtjwrdarwd.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gtbjrzmfel.html

@contextlib.contextmanager
来源：http://dali.aizwys.cn/Article/details/gtjoixcdej.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gtvdklnxkd.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gtwffpajew.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtxjlumsrq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gtrsbenyzn.html

[U24] Py：路径操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaebalcm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtawhiapnk.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gtkthfceed.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtfjqlpfbz.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtgqboftnm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigfzy.top/Article/details/gtgqcuhlwz.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtwczhvmqc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtggykcrcs.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtzixmdewd.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gtkdiukjhx.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtpzalmqhk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gtvlrzwokz.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkxesxdp.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gtwzxnzzse.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtghmjdnfd.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gtpvwuokmb.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtizaxoxnt.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gtzizhdgil.html


<!-- 参考信息 -->