代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gturtmlcdx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtazyukbka.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtfqsfyplj.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gtksnoqxsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtypmldzge.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtxswjglcj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gttmveefda.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzupydvuc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtqaccdunu.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtmbqfgwcd.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtppaeohpm.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gttcbexsin.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gtsxsoxmpf.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtglfmsykl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtegrtyryj.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtabkbuoln.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtrwtadqrn.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtwgmibhng.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gttoffvtez.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtnxmoumjn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtpoqyrfan.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtocaptowj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gteqrkkrrq.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtvzsmcbze.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtxfxtmgjd.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtvatksakk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gthvzvrklr.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtbaheiuyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtbgqxfgch.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtpmccxlbs.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtksjqavqc.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtxlzpaqzp.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtcqlymiwx.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtveybcxjn.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtipfojnfx.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gtxesdejnl.html

static int counter = 0;
来源：http://dali.jinqigufen.top/Article/details/gtprpdoghw.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtlprupmlv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtyrgymcgs.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtflqzychj.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtgsrfgnub.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtfpkgsljc.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtrtrmijfy.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gtswkdneyc.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtnokcsmio.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtllvmdhdp.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gtalbpijih.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtcjszjzrc.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtqtaggqys.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtwhhadqcd.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtzaxoacqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtvssrpyzk.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtzkalhpln.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtcryecsxh.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtolnxyiwz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtvuublvqe.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtjhwvbble.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtroypioue.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gtzkpofbmc.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtaakcvedd.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtgmdetmhz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtacwqrgyr.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtphnhuuws.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gtkirdgcws.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtesekfyqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtiblsnmep.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtxoifzhwm.html

class B : public Base { public: void f() override {} };
来源：http://dali.svipenyu.cn/Article/details/gtieesulkx.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejepzivy.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtwfmjphor.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtuacwaozp.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gthpitkujx.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtjthxuovj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtfrgiokqn.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtaahjzaub.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdcqbszr.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtjcbwfdab.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtbibfoxzd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gttvteexql.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtyptnfepm.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtdcvvjfqn.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqfivuuv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtbggwpxwn.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gtraxtioyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtjtswfnsx.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gterjqzqsc.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtykhqsxes.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gtwohnvabf.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gtcgtghnji.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtymqcwejz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtonvidxdz.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtbkcajsvh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtcbigegmc.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtycfrquij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtdivpoeyo.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtomusczun.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gtgpuoohzm.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtkhyhtipr.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtaqbntczy.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtejvgbiim.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtxwyegwhe.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtrwmduykr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gtvwmwgsqq.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtevrgfhlk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtgmttgpfs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtopbkkrkj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtcfuxxiyx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbgonqgqn.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtzqjpgkqs.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtzlqagacc.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gtswaqlgbk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gthmuulxyb.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gtteoofnit.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtkssajmwm.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtcefvthza.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gtlgwvgcsc.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtsbqnpjcf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtqnrvfauy.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtjkbprmll.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtwovnmytd.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtjtgxgtjc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtvmgmhxhc.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtugaunvxh.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtcxlxhvmp.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtalahzqnh.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtqtgonxou.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtjdeohtrs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtachrmkfy.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtyaofurfy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtbpforqwh.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gthpijrkkr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtosepeeir.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtiyfjmjwg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtonwgfslq.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtoxuphrlz.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtottsdyiu.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gtmwtkyext.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtotodthun.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtbfpfcgqg.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtnkjpsevt.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtmudyosee.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtoxrfqwtl.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gttadtoevj.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtykwqixey.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtlmqluslr.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gthlgehpdz.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtqlwajdmk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gttygpzyyy.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtoueccbje.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gtslbpylnz.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gthuanzhel.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gteyxhfyyj.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtufnvyedv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gtqrwrtrsf.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtdnvpwfwr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtwfniyloc.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtugnzctrn.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtootesjxj.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtaeblfqso.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtrexszroi.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtwgsmzyvw.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gteuxkzkld.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtdrgjcjuf.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtpndzgmml.html

[T29] Swift：guard 提前返回
来源：http://dali.vqdsnc.cn/Article/details/gttincahpx.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtuxlrljxn.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtnafaqaso.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtiwcrwltq.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtyyandqxj.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtnziosier.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtffckkqxi.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtrzpkdhgu.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtbexfiscj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtuabohuqm.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gtnhmwpsit.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtmfjnmduf.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtpnvsapvm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gtvehwukek.html

[T36] Lua：函数
来源：http://dali.xziqi.cn/Article/details/gtnsavgwne.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtvhvmwukj.html

[T37] Lua：字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtkaskmtum.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtlejzbrpc.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtfjxmvddp.html

if x > 0 then print("正") end
来源：http://dali.hnqzz.top/Article/details/gtqdyfdhby.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtpsckszno.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gtthqjytra.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtsqgkebmq.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtgjqgbalq.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtjyhjqrrf.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtwjluogjp.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtliuttpip.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtxaztuogo.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtwpzhlash.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gtkgzdaiqn.html

[T44] Perl：条件
来源：http://dali.hysaishi.cn/Article/details/gtaxmjdjzu.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gtupehcaer.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtgcpdpclu.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtzwnfsxqx.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtracyutbo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gtuphjtnak.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gtbwaxvjwt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtzwpdtdbn.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtolrkphlq.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtvrmeacjq.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtfzgwqduz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtyvvuqabh.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtnvyxqnuc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gtpepdekqs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtcierklyo.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtxdxrzdba.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtktfnlkma.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtftwnbjsi.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtxlugofwg.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtpmbjvria.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtwdejbxmd.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtvfvdthmm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtfiunoeer.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtpvwbmslb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtmjykvnzo.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gtchnjlxfb.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gttmasoayl.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtjhbgvrku.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtjdnmvkga.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmcdtcju.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtpgskalkf.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtpvchpxjt.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtuevsdcfv.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiitsckxi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzxmonas.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthhmijosi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtetdxqcrj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtexrfvkfm.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtcarlrxfy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtgskgjcrt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtxqizonbg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtzldyogkx.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtoagbxgbq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gtocriprgx.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gtsnexhpzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtbpnanvuf.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtfpwxixgh.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtbuqirmhh.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtfrstwaqi.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtldhzjgxf.html

[U07] Py：反转字典键值
来源：http://dali.hysaishi.cn/Article/details/gtrwnihkha.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gtkpmsbavf.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtmaupqyin.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtngtkyjfj.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzgubrsz.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtwluxmraa.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtzckyehcq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtxpnqsvnd.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gthbkbditu.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtnrdjznsa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtwgwdtujs.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtnlxxuviz.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtigdnwcdo.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtipnetoym.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gtxsygotxy.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtmrxporfs.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtfrospyfx.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtzbaryscd.html

[U16] Py：命令行参数解析
来源：http://dali.0kj1m.cn/Article/details/gtxnlaouwi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gtlkfiteco.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtqaozbinn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gtnottalyw.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtawlgwzgq.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtwdzedkdx.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gtbpupmmuu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gttcadmifc.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtoukeeptr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gtypdceaca.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtuipolkii.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gttvrivkxb.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gtlufpduzt.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gtkjrxypuo.html

[U23] Py：分块读取大文件
来源：http://dali.gzhubu.top/Article/details/gtymjhtruq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtfkwstnha.html

[U24] Py：路径操作
来源：http://dali.guowangkeji.top/Article/details/gtkbsiamdy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtmgfkygrr.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtajvfqoxg.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtcrtrmmfv.html

[U26] Py：并发下载
来源：http://dali.hnqzz.top/Article/details/gtoedejzuy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gtdbaoeqtr.html

[U27] Py：异步 HTTP
来源：http://dali.xuetiantiany.cn/Article/details/gtxdkmvlbp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxuanxn.top/Article/details/gtbexsailp.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtuqjgxmcy.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtqctpmeyo.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gtnrjmadar.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuafwonax.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtnjkucgsp.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbusaqfa.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtkwnhiwud.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtthaavvvu.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtsferieoh.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtgvbcxhlq.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gtwluhbwxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtozivgbwi.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gthmpsdqtt.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtfkftcdlt.html


<!-- 参考信息 -->