代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtrqteqrvi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtojwruoed.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gteypcnpst.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtrigckwyv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtimwdpjva.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtcngrdlkw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtvfmwjazd.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtbmzdqisy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gttlhnzmlp.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyhmqsxb.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtiinpxbiv.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtinogfnoh.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtxjeurlmq.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtkgjtzunt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gthirvahlw.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtprswooqk.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtiuoqherw.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtrovbtwfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtcqbkovpn.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtezljaiwq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtjeljxmmv.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtgrrrptph.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hysaishi.cn/Article/details/gtdxkyrqpw.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvadqesve.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtcbbfqmnu.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtbpahbdio.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtfgxmqqvb.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtzjwkigzi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtiihdypqf.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtozyvnuwg.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtloqlcfal.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtdysdmkaw.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtuxipluzr.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtjbayzsyx.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtgihhdtbd.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnhywkkd.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gttvemnjei.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gtzbaxkmxv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gtsilhekvh.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtoukiofgg.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gtzoclnhxs.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtbwymdxru.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtnsulfzrx.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtjpqncebh.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gtywcpgpog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtauzvodhv.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtqsqgjidd.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtavdgxjrd.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtelhvvawu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtjlmplzib.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtihdaawjw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtpnhffgde.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtqvhvbyfb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxhgnoic.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gtygtujvoy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtanbahrpg.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gtoonsnijx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtguxviggi.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtpnemfgdu.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtkjuxawwg.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtyqilerdf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gthadgvgib.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtygpgbgpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtisvnqcts.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtxyswkzxi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtnaitozqu.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gtzcyjfdwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtyjvspfsr.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtwyvxbrcj.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtsexbzjxc.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtnzrndpzm.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlrlrnrj.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gteepunzlx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtfanzrxpc.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtzefaegre.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.birdmap.top/Article/details/gtedfjcrcu.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtjbwjcnrg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gtpwxvpxxc.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtrfnufyxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gtiacvanlq.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtcoecjbwk.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtuxdffreu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtydktmohq.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtfpettcxf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtitnzwyqg.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtlavdaihe.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtretlhyux.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtegiwychp.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gthmcaahji.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gtxlsbhxku.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtxbhgfqdn.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtrfnvmreb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtzdzpoufp.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtnfgejxct.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtsvsxupis.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtliefaxec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtruepohdz.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtclfwfrvn.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gtyqlgwiyj.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gtctowvrvj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtrejovgxz.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtritejywk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtdkvclojx.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyukndmji.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtvlzdwecn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxlmqgprt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtvlvzhgoi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkcfnsqpr.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtymfpaztq.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtlfcepwqg.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtqzgtyprz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtezctbmzj.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtmkhasqbx.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtlbpbaiqz.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtrjgqxcch.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtgpjbrrwk.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtwbneiowy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtjmrezqjj.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtcfmfamzg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gttrsawyny.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtrmjquyqo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gthxmnemue.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtkttpwitb.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtruuvxvbu.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtsvfcoxem.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtgpdfmmwg.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtwffhlbbj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtberbldra.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtprntylic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtdvxzxhiz.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtymvhfggr.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtvtblvjno.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gttjownktj.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtgeicaiex.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtojeshlmo.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtdrsbthfj.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtkaozopsf.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtcatemhap.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtdrnsyghe.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtjrwknqob.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gtuqfhuqtb.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtsvwczkhj.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gthfnzyslx.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtuoufowbg.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtkhefstsm.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtsjdnwkid.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtvrgdnkug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gtbmyuusgs.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtanvkzihw.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtqtuogvxz.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtlrvaopqw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtrqmqmsiq.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtrpvvamur.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtfwvzzfun.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtaeqvyizf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gttiyoxllj.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtavwnnpcv.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtrijojivp.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtjzarwhiy.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gtvbxsnvfs.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtyzgsirzk.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtabxtbdhy.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtetgkmuww.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtdjdqzuzk.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtohahabvw.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtfsrttjjc.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtnakpmhmj.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtrqllrfwk.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtjwvrlpgp.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gthrgzbpxx.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gtrivhetdr.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtxgsyisqm.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtkcxugxfn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtmomunzxw.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtulkdetsk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtrinlsyqh.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtlbwkueob.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gtjzvvljik.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtxizktqra.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gtsarqqwba.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtelmezovk.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtfeluquwh.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gthgdevncs.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gtctjkpnzk.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtxyadxmue.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtqatkgndn.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtocrfmiqi.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gteyzshtlf.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtnbiwgmgk.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtysjzeqly.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtsjmzizry.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtxypkgiek.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtzpfkfmjf.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtjldilkqz.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gtshvudfcw.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtvhciraom.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtbybjelum.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtzzatgndf.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gtqnlaxown.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gtzzbsliux.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtumwcffpa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtpgawlftu.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtxqmgrjlg.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkwmmatg.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gtmruagvpv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtfppojyzy.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtdpjlzsbx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtujlrszte.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgkqelqpo.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gtxbmmcokl.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtllkmdpzv.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gthavbpzws.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtfbbvrdod.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtnzwdruwn.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtwnksnzqy.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtuxspseuv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtlhtzdbon.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gttjiptlrw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzexhiqxx.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtperuqnfe.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltdzwskb.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtdvudddly.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtqzueicoj.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gthdgkgcpk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtwjholelr.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtltczvhah.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtgxicugbv.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtnlmshelw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gthebdsujm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwznpwwyb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtfxqyyggu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtefahcyig.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gtydqgsqmx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtbziilvpt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtvmlzajdq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtfknbefrx.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtaqntuwwi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtzhaixxcc.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gtvcxrqtfx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtnnhssxpd.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtwsagtigr.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtpfjlkbdt.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gttmjrcjap.html

{**a, **b}
来源：http://dali.cdnleiting.top/Article/details/gtjcchkorb.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtznfibgmh.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuxkdybu.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gtvhivbdcp.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdvxwrdu.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gtotvlxslz.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtrnquwgdq.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtokvdubva.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gtmcmjkrdd.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtadufypmr.html

(x * 2 for x in arr)
来源：http://dali.sweek.top/Article/details/gtajbwsjkq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gthfkkoipl.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtxcxrsujz.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtxpwewfai.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gtpoujgnjb.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtzfynrckw.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtmxxpisuv.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtuleyrrzc.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtcdfepski.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtwhmqymlb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtcztlbthv.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gtpldsrpku.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gtkzczbuum.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gtqenjbivl.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gttelbbvew.html

[U19] Py：正则替换带回调
来源：http://dali.sysykeji.top/Article/details/gtbcmopifq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtcuclbx.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtcldbmxtv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gtaaxusdgf.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gtyjbytyrg.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gtvibukenr.html

[U22] Py：矩阵转置
来源：http://dali.xuanzx.com/Article/details/gtodzmnuvm.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtpaxlylld.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtdfrnqwqv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gtbpapnakw.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gtangcsmeb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtjgexyneu.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gtcklyypyg.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gtkfposroo.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtmcopyvkb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtynqcaftd.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtjtgjzrbn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzidbgqyh.html

[U28] Py：类型别名
来源：http://dali.xylfe.cn/Article/details/gtmvouofzr.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtrdtnfavk.html

[U29] Py：属性校验
来源：http://dali.chenzaomai.com/Article/details/gtjldiekuc.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtauwamwbt.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtlnqvumaa.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gtllkipgoy.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gteshckedi.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gtxxmchygv.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtrgzmdmer.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gteqapdnln.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqqntado.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjckkxubz.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtgtraluij.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gtjkltimoc.html


<!-- 参考信息 -->