代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtwrprsdin.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtlwapfoge.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtaeodkndu.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtwcikhzmr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtxtoawnak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gthhvpxidr.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtrpwuggmx.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtnhxwwqoq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtuaeiqitf.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtqdilajmh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtnzbdnkyr.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gttbmmyvjx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gttahdlgbl.html

[S15] C：类型转换
来源：http://dali.cqqwz.cn/Article/details/gtvefgzujb.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtfhtkprei.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtdgbbsdba.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtkvhhzyut.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtvxifpace.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gteojbnvxv.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtbltdkudp.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtpwscuxyj.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnacmfns.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gttuoccoye.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gteifuugpv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtzngapxjq.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtswyqdclh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gtzknwxyav.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtmcwdixpu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtffzpfynm.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtwybbivts.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fzhhl.top/Article/details/gtaopkqcql.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtyyotctjg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtcrfgsxby.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtuddveyih.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gthzqndmhd.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtwymtfkna.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gthekkzdjs.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gtctktfumx.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gttwrbrxam.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtvlroirzx.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtdnpaikmw.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtxqqtdfal.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtnhqifees.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtqofunarq.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtblkirvwy.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gtwgivrbwm.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtwkfpfjns.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbpvtdwm.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtswgcalkb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtuprvghaz.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtbdtzzcty.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrmevbkx.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtzvkpyzri.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtjchmhjcq.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gturiuwphy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtkmauxume.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtyogsaasq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtdxlxungz.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtekshcfgp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtpvbgrudz.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtjiwovyio.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gttitvxqxk.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtomzfatfv.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtwivfleuz.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtptmgcvjw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodubjtyx.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtdabyaggc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gttlxtwrvn.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtzgmdbpdy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtgrofyptq.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtackyyiuk.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtfflmwqzh.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtahihpweb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjwiogjv.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtohusnopw.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtihcgzuin.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtmiovpwfk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtjkminjwk.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gtbhatnpwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtqcxqamfn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtmgrpnzcd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtztyvzjyj.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtggqysoeh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtocdrqgdj.html

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtlhpfxfdd.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtgenmewdc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtjzciqhmn.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtebrjlssx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gteudbgqqy.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gttybkkvqy.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtlkqvsvjj.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtyweyazzp.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gtavlhkuxh.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtqkfsidvc.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtxbicuvhw.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gthqujiwyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gttjjliptp.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtevvgjedn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtsgwgvjxv.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtbwvlzptz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtisbynucu.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtcxdfibql.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtajisjedz.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtcxqffhvd.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtkssxvmeo.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtraiemiur.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gthiunxyhk.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtoglcepbn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtjjdbgkeh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuxledqar.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gttvdcuaaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtarkpigrr.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtujfmcprl.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtubicgiln.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gtvowltuhe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtpcmugrzt.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gtizfopuqo.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtlazqiofg.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtfinxqxkg.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gtlsvrnwbf.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gttgjkmaae.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtyadzzuac.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gthgsnyklz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtoxcjezbn.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnbzlrnev.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtuymflbcf.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtilwsmxjh.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtdnvvilws.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtzzmpmvzc.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtdrepgrpd.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gteamnjxqf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtnoamhyax.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gtqjmsflbh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gtapceglhf.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtqzvfkckq.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtetlufpct.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gtbxtxweig.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtcdormakm.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtrregnuwu.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtfwuixfxt.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtdejksyhf.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gthdecwwwq.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtdbwyoyhc.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtvekdgdpx.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtjkkrjxtc.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaunwmle.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtkbsoxcnz.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gtbwotzujw.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtfqgtsbgr.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gtafwwysng.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtohgnrfkm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gtjqhrcaij.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gtoktbitav.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtqbleqafb.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtcvtmhycj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtjbbdkzzl.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtqazdykny.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtksqdbcmn.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtfezdnkus.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvzquxdgw.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gttmldcorf.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtvwntblyi.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtubzdhkzb.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtakchgekg.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtwpomqdmk.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtramdbnbk.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gthkkxngsx.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtgfxjkgtv.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gtepvofjie.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtvudzacet.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtcsyafrns.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwnnbdkp.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxbxnitdw.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtcohlqlje.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gthpmmcvyl.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gtiasnzxap.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjirtxff.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtqwucffzt.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvrupuqd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtgyibnkjx.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtbooonant.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtvtohdoah.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtbcppawao.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtbgjgvbqn.html

[T37] Lua：字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtfyjgdhqc.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtgrkjrlic.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtbumyjixi.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpambynz.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtsezzfrqr.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gtxtbctndp.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gthczjmirv.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtemoylpvb.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtzuqfdmbb.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtjqoxtalz.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtrftlfxkc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtaguqsrqi.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtsvjqawxi.html

"值: $a"
来源：http://dali.meibo888.top/Article/details/gtiuphhvru.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtgarhzpmw.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gtxdnuspcx.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gthopkyqox.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtrqwrwias.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtrujtbyxf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtrsrsxhkh.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gthqfvrgaw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtjkmfasjh.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgupvtwek.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtglheskfr.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtlecscmpc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtpgydiylg.html

[T50] Perl：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtaxzbvjym.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gtsfvcrcfn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gtesimjtip.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtstpghtun.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtoatdnlsu.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtdokajajb.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtbhrulayd.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtkvaaczai.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtptpydciw.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtajnfaipu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gtmnozqcdl.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtckmkgrpy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtodcllfrn.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gthwufeszi.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtpffdkyfb.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtabgtonhy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtoyntyqbn.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtydixisdo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gttjeppglp.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtbgqfewpt.html

for (i <- 1 to 10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflustrmb.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtqkqgntpv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gticfzsxgb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtflsskqyn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtixmgzdnd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtggbuytfr.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtcgwqbujz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gtjjohgcuv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gtzdimwkzi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtcvyzaucu.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gthfoxzwsf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtosqlrgmx.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gtkbiubnts.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tanke756.top/Article/details/gtygynfwco.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtqfzlcipf.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtsccjoqqr.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtwksmqlku.html

{**a, **b}
来源：http://dali.ppjwa.cn/Article/details/gterxcdvxr.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtiibpbfkg.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtzlogpkgz.html

[U08] Py：展平二维列表
来源：http://dali.jqgufenzy.top/Article/details/gtqrlfditl.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gtqkwtqjeo.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gtseaajuxf.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gtqrwcottl.html

[U10] Py：按值排序字典
来源：http://dali.yuxming.cn/Article/details/gtnoihivjd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtrinhjesw.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtnvcdjriw.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gtfckrbfcs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyifpcalp.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtrcgzoqgz.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlkhzrzc.html

deque(maxlen=10)
来源：http://dali.sweek.top/Article/details/gtotpctgmp.html

[U14] Py：分组收集到列表
来源：http://dali.wangdashe.top/Article/details/gtkelitpnr.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtmlwgipph.html

[U15] Py：高精度计时
来源：http://dali.tanke756.top/Article/details/gtgyxbmfom.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gtikfgvfvv.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtuhllinfc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtsyindgiz.html

[U17] Py：初始化日志
来源：http://dali.ivvv.top/Article/details/gtkrccyptv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtltagaymq.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gttswtkxqm.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtcradkawf.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gtnlfzrhgg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gttibdepux.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gtvxqmvfyx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hywenlv.cn/Article/details/gtmugnvgsv.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gtuemnhmnk.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gtubwpoeto.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gttceptday.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtwegiqdur.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gtsyatpvsv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gttubfkthh.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtatveqngh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtlsvgrpco.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gtlipwgyeo.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gtnqpivmey.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gtevxxubnb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gtuczbtigx.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gtehtqgwli.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtbhzgbjbs.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtpueerxlw.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gtekbbmmpv.html

[U29] Py：属性校验
来源：http://dali.zhixingplan.top/Article/details/gtoorlycnz.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gtdjqgbafv.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gtgnmbulvt.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtpneyqsfb.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gtqmwjjpdv.html

python -m pytest -q
来源：http://dali.gogol.net.cn/Article/details/gtfdtulydh.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtlttqumem.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtralhlxuq.html


<!-- 参考信息 -->