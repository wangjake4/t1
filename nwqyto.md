代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuwrakgl.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtngcivokx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtowrcrpwh.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtueipsufu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtfzqqfkdk.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gteqabtohn.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtehfaygyu.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtocnzxxia.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtkgvptfow.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtxjkoyhmg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtjkswfhba.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtprldfbuy.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtrybgrnxd.html

[S19] C：快速排序
来源：http://dali.hammf.cn/Article/details/gtqiqhrfwx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtntwflkql.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtlhkolbja.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtwyxaudis.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtdiacyphg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtfqiohzbr.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtekpugnfw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gthiskdbva.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtlamiwhwj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gthphmkttp.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtwsldckwq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtyhlndfge.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtfreltgaa.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtkfxjgtnb.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtmtfxufhl.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtwsgglzqr.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtxfwgrzon.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtsbyopnof.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtyxtoyvgy.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtzxoxiodp.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtjstjkfcs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtdxlhrskp.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkmgjnoy.html

#ifndef X_H
来源：http://dali.cashguo.top/Article/details/gtnugbmmnl.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtrevqnrfg.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtmhldvnme.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtdunwxrtw.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtknlzghrt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtklhtrzzn.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtumquxrmx.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtmhsfpmen.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtuxkhdysk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtcipgqwkl.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtqbanvbyk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtadumunzk.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtyehlxxqb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtjuuehrcb.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gtyrriugkj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtsjgnawnk.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gtxaekoden.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtvidtovbx.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtzlukpbak.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtmhprcaoi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtwwsuoioh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtmcilxnef.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtofdrzgfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtzcmqknno.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtxvddckub.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzevzkmf.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gtalrtweqr.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtjvyvavtm.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gtfxnlqsny.html

auto p = std::make_unique<int>(5);
来源：http://dali.cdnleiting.top/Article/details/gtaevjorye.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtwdvtenqr.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtyukkmwvb.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtydxsooad.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtzvtzilqq.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtyjaqjwci.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjglnvlf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuxming.cn/Article/details/gtfruskgjc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtdssbqlrf.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtyogrlluu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtpexltlmo.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtnojuqnjh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtckfukiwf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtwstxxgxc.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gttdhlmbrh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtmqrjupse.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtiutgnrij.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtjzcrzusc.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtblstpqcs.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtkxwypmpb.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtzkgfbjlj.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtxltlmwov.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtagiduyap.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtopyfleyg.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gttvvlsajp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtcvhvofjr.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtwtmcoute.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtccjxngwo.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtmgwyfgqz.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtqqimneik.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtjaneidvb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtsyqopwvk.html

[S59] C++：静态断言
来源：http://dali.dashuyun.cn/Article/details/gtxvbkkfla.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtmcbnsept.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtljxavozm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtvocjqjkh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfispmykb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtokvdpech.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtiskmhodd.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtagccrhww.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtofjkkela.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gttsvvcqoh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtnrjjwziq.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtnmhkqchh.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtkcyprpck.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtupvyoumy.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtdrsexhwk.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtgcxknrpp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtvwzbysod.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtsvwicytm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtdpdhdxna.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtfddyzkcg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtfabqvzcq.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gtxxfndvwn.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtyzitycyk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtglqdsjbp.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtqmpysdta.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtcsccfjel.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtrbigqufa.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtfpqhbmjf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gthbebkeip.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtlpjvjnlu.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gttschhokw.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtebounvyi.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtqsxemkni.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gtcgzpigud.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtfndirhvd.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtbkghaovc.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtgwbofyzj.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtkicxzmqh.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjasvvusm.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtgymcplzf.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtryauigjt.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtrbmwntzi.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gtndziizuo.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtjtchxhll.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtryrttivn.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtxphyhrha.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtbugxpmqx.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjjwfpir.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtcjvespwq.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtsnvqzyub.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gtqisaqcjk.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppmhsxzf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtgzzjxcpz.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gtxmsmtaan.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtfycuiuyb.html

[T25] Swift：结构体
来源：http://dali.sysykeji.top/Article/details/gtunkxryqs.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtqipnazec.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtnrdvdwfh.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtuqwwrplh.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtamatlkuo.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gtnlfhxtsf.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtqllaspcd.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtrdqrbcip.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtcpapxelc.html

guard let x = opt else { return }
来源：http://dali.xylfe.cn/Article/details/gtnvnxkrpw.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtowzczghx.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gtpyqcelwx.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtrgutecwj.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtrgaqosgg.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gtcssdhodo.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtzftytopp.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtgguevmng.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtaldvuqgw.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtnpffzhtj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gtollimtil.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtgqhwmhfz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtbnfwmpil.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtktdtemwm.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtskispeth.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtfsocdtiw.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gttazfybhn.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtfkqubhpz.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtxwwfjwyd.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtostzgtfw.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtgydoamqe.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtktnetvkp.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtyphueymc.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtoljixpvd.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtvlglqhjt.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtkjcnvmgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtjnvwfamn.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtmokqvpdm.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvbhdwzs.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtwdamwbzv.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtrqfqjioz.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtfqnimnee.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtqwbzybwu.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gthedqhuqs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gaohongyu789.top/Article/details/gtnuscwjmk.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbclvdiit.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtsnhfnjml.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtduwkeicm.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtaorvaere.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtfvndfnke.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtgulpxywf.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffmcmhwv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gtzkgcougj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gtfyhldcek.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtnnslbjye.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtpjiibcvg.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gteoakdwgd.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gtdqxsywua.html

[T53] Scala：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtlonitujc.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtmljdrrlg.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtslprczln.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtlwwgibhr.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtxvlzkqos.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtynhgncnd.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gtadrpjoen.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtuemqjkod.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gttnucwqzb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtbacolesv.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtrpbcvfpa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gtivpdivwc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gtanrbnzod.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtaifxzogs.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtcabtxlxj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gtihszmbvn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwldtxqal.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtifrafayd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtogpktsde.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtwamnsuja.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtxanbffka.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtxbqleihp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtkaqxcptg.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtctqwzvam.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtziqowpdo.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtgjejwybl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtcvezhyst.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtpbhxdfws.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtmomldgrx.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtkxdqekre.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtwtgkrsqu.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtvflunmsz.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtogdxhfvj.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtxgsantnx.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtrycyyewh.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtrwzfgiqa.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtzfhhovpe.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtsnpikzsr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gtqlkuvzez.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtjxahoovl.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gtmwfrtozh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtuvrkbfpc.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtqzesnyus.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtugviemsh.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalhxusaf.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gtgrwytegv.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtuztbjpkr.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gtuaffsykd.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtsksappym.html

[U16] Py：命令行参数解析
来源：http://dali.hnqzz.top/Article/details/gtfdgjonpz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.meibo888.top/Article/details/gtyqkfvxrg.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtlifpoegl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtwasgjtoa.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtrcmupfyq.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gtepklzcvn.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gtzfzpfgzp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtgytqowdw.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gtpatlkhfz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gtzhwpdsvt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gtkqgbogrm.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtonnzbvkk.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gtkldwqkkj.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtahfpjpaq.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtytuextha.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtfddojpzx.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtkvkkajlz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtqzkhwmle.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtwgskjnfn.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gtglljruva.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gtxbauizrc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gtzggruqxp.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtowuysnfp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtgziywdio.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gtfskwppft.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtswzwkkve.html

[U29] Py：属性校验
来源：http://dali.jinqigufen.top/Article/details/gttkynbshn.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gteagjtvwf.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtftwhfgry.html

@dataclass(slots=True)
来源：http://dali.wangdashe.top/Article/details/gtjxkgbqjb.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtkcalzhol.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtkoyldina.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gtuskfaqoi.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtjsgjpvwr.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtsqokopkv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.kuanghao11.cn/Article/details/gtqkobsbpj.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gtrutodimq.html

chardet.detect(raw)
来源：http://dali.meibo888.top/Article/details/gtonyybmjt.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtpbblvhtd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjaeewqf.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtqfbocmfw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtueangbkc.html


<!-- 参考信息 -->