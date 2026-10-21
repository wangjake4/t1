代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtwiekxyiq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtqvffdgyb.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtxmwpdtvi.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtcyzabxvw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtulgulwtg.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtnhjndlem.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtuicpvzah.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtmtntvwib.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtolhjhcem.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtjevdnddh.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtmovmgzaq.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtxrecmqto.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdvbjwlz.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtqsqbgszk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtdfemfdxg.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtkmiogcad.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtokubbmth.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtiojwlfrj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtxrupzaiw.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtntoeqvtb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnndldcii.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtvwruttnt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtigegkyit.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtuqbonyti.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gthfzucqqr.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtfelquzdy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtjfeeajlh.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtljtryawy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtycmxfzjp.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gtvczdwwve.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtbmpubtlr.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gthqpkuria.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtclarmgnd.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtiwpsxhlg.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtvtpffhbg.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtcclmjinw.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtzvhzwrol.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfgrdlnfi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtkjgehzhf.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gthzulevpr.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtzvmhzrwf.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gttxncfmxi.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtxinffgec.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gthqbunrgf.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbljjbfu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhvalcma.html

[S32] C++：字符串
来源：http://dali.daxiang520.top/Article/details/gtjnlvspzm.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtjjuhukwz.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtefqjxhfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gttofycklp.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtgmochwjo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtnpmmnksw.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtxixhkfcl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtqnrxtgrt.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtdkvraior.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtvnihuytb.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gtorwiscgq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtgbvlpsli.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtdlhtbhfa.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gthrgadcye.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtvzibfilg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtoafcqxhh.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtzyssumqf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtnltjklmj.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtekozcast.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtzcmghmqv.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtcykxfhqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtnrqhihgy.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtbmjjnkie.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtoqipiieu.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtxlfnxyls.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gtrrwdgjtx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtstszkomj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtvzslwxen.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtovxlwfhf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtfxjwbuyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtbodtpvcs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtfyttpixk.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtdbqgtuur.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtmtyofdhu.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtklauuail.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtkrpghkfs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtyyzibedg.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtzleuvxxs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtwfezfhri.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtuikiouil.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtmpjflywx.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gtuxsdfatq.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtdbhxcqjq.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtfafoabll.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gtneetmphp.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtpyypilgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqewywgq.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtmqhnofzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtioashrwc.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtmntqnicj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtzhjxnvid.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtinafismg.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtupurosfn.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtfatgmijy.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtdgrfxpgk.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtcyhhlcmo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtossotkmd.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtxysudbbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtgxpyowtq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkadcavkq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtwpbagpav.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdvbidmab.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtoxtgpsta.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtzgxeqjml.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtdalromfn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtpqgzlcrs.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtvranjfhf.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtmeymnmie.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtykuwydhv.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtvexochlp.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gttybihvyf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangdashe.top/Article/details/gtjqddoaco.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtpsypdtik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtgdpmkzws.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtgvfgbftv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gtoyuyiybi.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtzyezzyqz.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtidnnwmtx.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtkbngpmsv.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtmdjwlidb.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtsirfhoqb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtuzjgadts.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtjdcatjpe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtxxcdvswt.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtdoynchog.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtrmfktwhg.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtqfiwjopk.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gtrqiwgoid.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtwkmtkurp.html

for (i in 1..10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtfydxjtek.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtouyehoxc.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtojcezqci.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtdahckrtz.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtycegweiz.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtdrnqanaa.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gtoaivxxlw.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtkpdjqzpi.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtvamkdige.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtkmfudwxm.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtjaspyccq.html

[T20] Swift：数组操作
来源：http://dali.hongshengwenyu.top/Article/details/gtalxucsfp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtjgtsaajt.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtyzxlohgh.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtsfufbwzi.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtdgsfxkra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtoyxhhjhl.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtqytczdkq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtmhxkyofg.html

[T24] Swift：闭包
来源：http://dali.yongpay.top/Article/details/gtcpxgjhow.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtdwwmdcnu.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gttsykebfl.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gthocpzkwq.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gttozjezhl.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtbmdlhxto.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtpttefgta.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtddqedmls.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtmxquepol.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtgaexprub.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gtdxqyiers.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gtxxeopjvb.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjrdjymx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjtgpjsi.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtikgzvaux.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtukitzkdk.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtldbgnsdo.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gtcvxogosh.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtdsiouxvr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtyagdqaig.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtuyymfpox.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtnljtyqgk.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gteutnoech.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtuitjnlel.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtyjshywef.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gtsejsgney.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gttddjfwja.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gthzcsdvit.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtenmugktv.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtrdkxdhzn.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtulkxcueg.html

string.find(s, "%d+")
来源：http://dali.jinqigfzy.top/Article/details/gtzjxtpvzh.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gtikmgulwp.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtzgwnlaim.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtwibcjzta.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtqssptzys.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtaituvkwf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtwntsxzhp.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtpgmrfbvf.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gtytqafbqp.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gtnafdsmoq.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gtewuvpvnh.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtajftelvw.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlmiatesg.html

[T46] Perl：哈希操作
来源：http://dali.yvedp.cn/Article/details/gtctxvscqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtufnvbxbj.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gtgdonhpaf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoooghsu.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtkphtgvmf.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtgcxwuvxr.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtztejosru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtrkotheqc.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwmlsufph.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtrhyocckx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jianghu66.top/Article/details/gtmyeftefo.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtagqbnlxe.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtyzatunrd.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtkseqdnmy.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtrrkifgoe.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gthkwvyozl.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtydnzscvc.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gttqrvrotm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtrhxzmbfp.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnotberyz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzvtpxxk.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtzasmrcdv.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gthhbndimr.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtqsdlmoso.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtxktwyelp.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gtgzdvqcbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gtnhnvrtaw.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtigtzavgx.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtfkmrlvad.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtxxdyedks.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gtcaampufi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtphslkvzv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtscbyzloz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvdisvns.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtmqrfiuxu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtwwktfauj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gtwyymbcmt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtorjnffjd.html

[U03] Py：加载 .env 配置
来源：http://dali.hfpthk.cn/Article/details/gtscbndxkf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gthdqrubhc.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtxeesdrrz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtoamuvxvu.html

[U05] Py：列表去重且保序
来源：http://dali.hnxiangtu.top/Article/details/gtqytpmuip.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtuwkuzzbm.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtawfuwsth.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtogsrgtjf.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gthuellzej.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsidxrpp.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtxqgvnnek.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtkkxrmszj.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtazublqub.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtuaqpafgp.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtuldtdapr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gtgvkhgqjc.html

[U11] Py：生成器表达式
来源：http://dali.xinyue.icu/Article/details/gtqbynnylp.html

(x * 2 for x in arr)
来源：http://dali.daria6918.cn/Article/details/gtwzikxbaz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtccznygwh.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvvluquv.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gtdxutydgo.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtellvnjqx.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtkgremhdn.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtjoxwtjtr.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtshkibmke.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtlrgochza.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtdwsbvngc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtyvnxwuiy.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtkkkjybqc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtvlgktdwt.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtapcdfblb.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtenewlqjb.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtmhehqedo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gtsqfqigeb.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtknrpaovl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cdnleiting.top/Article/details/gtvvqidcor.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gtzohsgchd.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtwguuuuxc.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gttqpttecd.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtsmpxnvbm.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gtwlkyshsx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gtfstmbked.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gtteuoccjy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtoeoungtn.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtixmvhoek.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gtsxygwabg.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gtmmpwewio.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gtzsoazstm.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258.top/Article/details/gtpfchaora.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gtoxfatxly.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gttuliciuu.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gthrtobuos.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtcyoppafp.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gtkryrkkih.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtedmbqdlg.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtrxhuvkjx.html

[U31] Py：单测
来源：http://dali.nwbrower.top/Article/details/gtpwpcdkbs.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gtekaoqasd.html

[U32] Py：代码格式化
来源：http://dali.sxryk.cn/Article/details/gtgbazjjbb.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtqcnyevdo.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gtwxzyueua.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gtglyhttcz.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gtdasessqq.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gtrhwgqmog.html


<!-- 参考信息 -->