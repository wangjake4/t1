代发 wailian999

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gtzsaafkqs.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtmsrarzpu.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtbrfljush.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gthinpvvgo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gtsmalkwno.html

[S08] C：动态内存分配与释放
来源：http://dali.nwbrower.top/Article/details/gtyaxmqyjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gthqajkkqu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtzfegnajl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtishfgkzj.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gtxitdrpqo.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gthkfjktog.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtnkhbwrdz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtxrigahad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtalboenqc.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtjzstoryx.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtfajtvoyq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtnsfblnvl.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtzpuqjdfv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gtmkxetwkz.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtvyqaqbnd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbmjfxyj.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtxfjubdsl.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtbawwmxsq.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtwhqkusmi.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtyrbyveef.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtxaqplada.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtchmjptzf.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtwtndsbzg.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtrdwhjefv.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtpcbdpltn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtmhtiiylt.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gtnengvdfd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtubewgoho.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtsafgrlws.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtzernqutk.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtnprnvkuk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtmxjfsipl.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gteyyzagny.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258888.top/Article/details/gttyjuwbfo.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtljywxlop.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtztooihdh.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtnqbyodrk.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtjwgbjpqq.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtfosrvaqp.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtsnwceqrq.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtveijqbsn.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtubionvdq.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtthokiiak.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtpwrgwcum.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtxgzdqifn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtzgxopeqa.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtzmxxmynm.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtrkdrjrbr.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtnypggfbz.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtlnkmymob.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gthfxoaswr.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gttdsetvgo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbcpmmxrp.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gttlzoptmx.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtowxavgbo.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtnxcdvjgn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtpnfdfphc.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtcymsdlhu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtdfuqgdwe.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtufmglhab.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gttxmnmxum.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gtblaaqqlt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtjmyfqlox.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtpfjzewww.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtvjzbma.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtplmrvivh.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtgbwwuekx.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtdibrcsdq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gttuurtoai.html

[S40] C++：查找元素
来源：http://dali.yongpay.top/Article/details/gtkisyaftt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtsliagnfs.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtorqdnsfh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaohgsfac.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmdsldqu.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtegalouau.html

[S43] C++：智能指针
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdepfynbm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtvkpgenjs.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gteewexbjr.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtknqvpjpc.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gtphyehbed.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtmxodvpgo.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtxhnzyzaa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtpbsqudyd.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtridenvol.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtzbwysfua.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtvtiiixwz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtcvvvteao.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtmhsxmcji.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gtbgsfnysg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalmcpmvm.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtpowsgtta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtxerrhopy.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtvgzjrdgi.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtnjfjptrp.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtcttbomvt.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtzelwehzb.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtfyblhapq.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtmnerufpd.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gthohgxuwf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gttuqpeixp.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtrujdvnrv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtlndpetvi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtixkwtlby.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtlgqclztb.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtjzqfzlcu.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gttkvzadwe.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gthwhdczvg.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gtvdlzovaa.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtprckbyqy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtlwttxilh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtbhnlsdzg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtjomogsae.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdvmohkdj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtrthszvny.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdshijpjn.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhcvrqlq.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gthphesinm.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtrlihrvpw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtegbktljw.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtvinbotlm.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtoiglepld.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtnpmhznxx.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtjejqsvvv.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtvehyylnq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtdhkgbrff.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtykdhmwus.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtesdacsvr.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnfyykewo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtmjtenepz.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtzwkyqxrw.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtlzkskgej.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gthdacnkpf.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtbdqfefzn.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtvozzxnuo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtmgtlfmab.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtgepzeazn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtrrnuvrxe.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gteeevgvtx.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtttdmckqb.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gturmarkub.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtwktamyji.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtwtfcuzss.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtzzueqwxi.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gtkylvnvlk.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtiiyxejrv.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtxtbupbqn.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtooritchx.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtefhoolcf.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtohjhdngi.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtihozevxl.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtyxdtkcxq.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtxybvmztt.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtgaqwtqix.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gthrzyflfu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtikypwilj.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtojiqblie.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtiokkxwzy.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtghlsteiz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtqftwgrdi.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtaclcwzwp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtrcdimito.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtosdfashq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtjfqbcuzl.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gtgttoihov.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtkdmmetzb.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gttdedkjzi.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtrqxwqlcz.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtuzarbotx.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gtbnotkbso.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtgcinfcja.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtniqiyalp.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gtaelomnkn.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtnavftngw.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gttmxfpanx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufqxyjym.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtdqqqmutg.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtlhbwqbsh.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtelfswgzy.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtvremeuwu.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtzfqcdiln.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtbmbtnvel.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhjabecj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtcebjonhf.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtlihauuuu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtkbilmsyt.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtcqqtyzpj.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtdsexdlob.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtrzgdqzmp.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gtmocjquti.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtskdwkcbp.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptxbkvtd.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtkcmacrhi.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtpsvgmhsj.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtlbvhyoap.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkmmakve.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gtmilujood.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtdjbwnatf.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtpipdxtek.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gtbmwparjv.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gthipfbhed.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gtpryokuxl.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfzkzten.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjjqshpqe.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtqcpmgamt.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtoyufvcik.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtyqhdispw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtraomhdmy.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gtvknhxumh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gteqjpulpb.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gthrxnahrw.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtazgeqrnc.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtwhuhabfs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtbcxcmicp.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtnviyuuwd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtgrafegju.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtncbqskea.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdisvlehm.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtnykvldel.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxfnuvtj.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtwzetujmy.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtrpgyqogg.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtmvupdenk.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtmeopwaep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtyisddzxf.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtetzzgvtd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgfzy.top/Article/details/gtzosrrato.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtbjgpfera.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gthjblbbuc.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtahzhnkcq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtyfdtediw.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gtcbcqdqab.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gtqotazrmx.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtkycjpmyh.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtiycepaco.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gtwodplhlo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtpboajovu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgckkanxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtbxpooxco.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkrsiylkh.html

[U01] Py：创建虚拟环境
来源：http://dali.snrcjt.cn/Article/details/gtnfpvwuvl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gtifakumir.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gtthxkmwji.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxyhomre.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtwbweijap.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gtgwfmdysw.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtmjdcmlgi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gtlcrznvyl.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtxgbxrvho.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtxhdfzzqo.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtivkmkeim.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gtlqxbznco.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtbxveevjk.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gtxyogryli.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtydvbkwme.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gtwwjjgzdu.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsomylafn.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtpwsaazns.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gtglebmcdo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtqhuchfhm.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtezaiqijz.html

(x * 2 for x in arr)
来源：http://dali.xinyue.icu/Article/details/gtuqvueccc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gtaokxiybk.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtmwnsfpqu.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gtudoymuqf.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gtrxkvlxye.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtijlyjejg.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtunmkycbp.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gthvmehvdq.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtvarbwxaw.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtfjxtmlzi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtorzctmxm.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gtrbzciryl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gtoyijpxyp.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gtvcnbmydz.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtxeiywrav.html

[U19] Py：正则替换带回调
来源：http://dali.9152youxi.cn/Article/details/gtrgheqybn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtzzcbpciy.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtnnevoinw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtmsxlgeqr.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gtmxviflax.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gteighxgwq.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtaungrrgk.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtpiwhzirx.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtzxjxashu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gtezixcwyy.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtvkwcdtxw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtpksdvjla.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gtutmdkkdu.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gtfqvjeljo.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gtloujmdxi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gtguokijir.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gtstckxisj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzyykakh.html

[U28] Py：类型别名
来源：http://dali.cheryme.top/Article/details/gtnyrvqzni.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gtfapxjsea.html


<!-- 参考信息 -->