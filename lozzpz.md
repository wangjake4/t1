代发 wailian999

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtaaxpjpmb.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtgkbithbg.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtnhlgrpxp.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtrzmtcxpn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtietihtpj.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtvxmquhjh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtbcckjkpv.html

[S09] C：结构体定义与初始化
来源：http://dali.zycfv.cn/Article/details/gtplzfhyef.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gttslzcqqr.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtdcvmxgca.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtoihbkdkf.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtjcpaiear.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gtptbvajda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtkjpmqvmv.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtmpxqield.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gtrjozaqfk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtroqapvgi.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtzyilktyy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtowirlicc.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gtyaekromi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtplktqbrp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtamwiencd.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtehgmzldx.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gttvyddjpw.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtzhqxiqvn.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtuqzkadbg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtbxqnwyjp.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gthciwocsb.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtqpefvweq.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfwcpaud.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtdrbmjvri.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnfcytoh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtcdyaqztf.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gteqvlbyiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gtaolpbbmq.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtnuvdpttt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtcpkuwadk.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtukjbzhby.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtrwvxesaf.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtnrruvrsn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtujbmvfyq.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqustdyn.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtoggvlyvb.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gthowexmll.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtiljqkbfs.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtscpownxh.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtsvdhtyzk.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtwqvhdrff.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtzvdrxavk.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gteuywqnot.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtfcxxgecr.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtpojuduzt.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gtydgvzbrn.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtlwlbhpvi.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gthmvrjhmd.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtdftmlhad.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtijarxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtqjhiunac.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtjkrksnus.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtfugvnpft.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtexkiamey.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtjldznaha.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtizmlcpsn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtxiwyfvgv.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtbauyftvn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtldbtcclo.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdwdwjye.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtsqymkcct.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtxsciogwi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gtqjwsiupx.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtceubwioy.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtqwtpskfq.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtbgbbptyp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gticrrgbkr.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtlqcrzpso.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtquliflbw.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtscnrpbth.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtzavwworu.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnofeapok.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtcfiphhjr.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtwactrkdn.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtomhbuxuj.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtoemmdsfu.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtmtlwzguv.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtzuihldeg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gtnxgtbasd.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtlypehuhx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtikddaihd.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gttbekjkhw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtutmwyecz.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtikeeeqkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtkxcnlkil.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtqquyhqcb.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtkszwwkcz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtsffxffpu.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtnxxcqpml.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtffupygqx.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtmubnsjii.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtsjnzkcub.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtvxjrpawu.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtpayrkpep.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuivgdhtu.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtcukargjx.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhmezhxj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtcmyravcd.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtdfvpivhk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtwlceicut.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtksyxhqah.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtfsucsprf.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtjqalrbpm.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtqelxffmq.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtwtcdtrkh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtfthlddzt.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtfrmlxkqo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtwaemsrsg.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtniveucgr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxbwhlqh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuozvazpi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gthebmroye.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbflywuvu.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtwygbeait.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtwqasbrvw.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtjzuzmlfv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtvszcpdtd.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtczrpmmvb.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtdgismouu.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtgkvmbzhz.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtwkhtjicz.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gttgfkzfaa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtxsscohqv.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtgkrnahsx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtdabrljqd.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtdrzflrmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtufwawqph.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtcizgaipl.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtqkryfffv.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtcrizqejo.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtlazfclqy.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtkgkxophh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtsctxmcpp.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtiqumqarz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmtojmnk.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtkxusiaxu.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtnwsagbqn.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gtkdkgpvds.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gtxoancrch.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtdldrksft.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtsnfvyvfu.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtqauoyhrk.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtyvjjzwhg.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtexnfzggw.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtjlcpqzuy.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtoaqpcoss.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtnkhpefvk.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gttnkswvse.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtjvoxlelz.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtynfhdqmu.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtiefwgcok.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtrrhoxnmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtvsymeqlh.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtobolfljw.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gtwqvpwhgo.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtkgqbaeku.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gtzstonsbt.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gtyfqosdhf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gthkgmahfa.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gtnkrhtaev.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtirfbbqye.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtzudqctru.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gthxypxqkp.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtnubglmlm.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtxcgzfwhl.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtiwlzbjtd.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gtlhylrxxg.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtqlcvinuc.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtuygbctph.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtfkqlflfd.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gticykgmdx.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtvahhgdud.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtkpbyhvvi.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtinhlhiof.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtoaunkvas.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtjrutoefz.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylhwiodd.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtaypnmvaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtjzdajqbr.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gttvnjpwoo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtyyboqfmh.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gtnwbyivsc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtqqjtvdye.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtxeclmrmg.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtkbzskisf.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gttdosygql.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gtcfqlyhuo.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtdilvxnex.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gttzxwsfdy.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtjqpgljdx.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtfcevrrqy.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtcnaguijr.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gtcnmxrpmf.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtzjbawmpu.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtbvsowvqc.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtxmnskvkd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtlobishhg.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtvvihfvrb.html

"值: $a"
来源：http://dali.bjfxy.top/Article/details/gtgskonuln.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gteuwbhmcr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtrhznvwau.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtxrvcyiur.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtmshgvrkx.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gtpmojjihf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtqncnjxgy.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtsbnayoud.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtbpplyjpq.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtovpzwnvs.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gtvxmterqz.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtjhfxepnm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtievjsruq.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtahdqtiov.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtoquuqjhx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gtiguiqyqt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtorkfkmbl.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtflruvknk.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtadwgwlbz.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtwdenlwdh.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtpwdirzuk.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtrpczyfzp.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtbblkbnrh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtepuqyfft.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtjhnxeokw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtizggkqyw.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtgmrkzill.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gthryjiixg.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtkzwziloj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtmfolvnsl.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtlbqtdwsb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gtbickvwjo.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtodgmjnjp.html

for (i <- 1 to 10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtupgqucxl.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gtbcwjvwbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtharpjfof.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtscnhefxi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtovpdoaor.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgrwugnlq.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtrctvgfsw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtyrlehebl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtindvbxaw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtdpvmehvg.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtutsayjvh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gtizlyrrnp.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtsifkbncm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtwrwwmhdx.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtajmduvxk.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtjcvpoekb.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtgkkuuzjs.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gtizrobkwz.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gtevdowmpf.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtqrusprtq.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gtvmmybzse.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtyignuklt.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gtrtnuteko.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtfqorychp.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtgkycokdi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gtmkfylhbu.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtzexxphcb.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gteufugijk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtducqncys.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtkwzgllyk.html

[U13] Py：固定长度队列
来源：http://dali.zhoulong.xyz/Article/details/gtddavqqyg.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gtznodrfsx.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtwuetjwbc.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtmdyjxwlb.html

[U15] Py：高精度计时
来源：http://dali.jqgfzy.top/Article/details/gtovayjtwh.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtiiofxxhv.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtjphzonho.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gtlmunlxgn.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gttxkfepsq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shangyingyoupin.top/Article/details/gtjobqftyd.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gttdvwgpme.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtssvvabep.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtdmnaqczs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmzrxyfcx.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtxpwsaojl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtlmeymkbo.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gttghdpouv.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gtuosndsvm.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoocjtldg.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtselcpanb.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtdjetwxon.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gteldwwkan.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtcquufaqm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtnbjbflym.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gtnixvmjro.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtsjxkqerv.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtnyzxyfar.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenjidiqi.icu/Article/details/gtlyzfvsmn.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtqdnkckkf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gtlbswgcek.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gtvvvkrxwf.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gtoisghcqg.html


<!-- 参考信息 -->