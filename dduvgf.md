代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtrdqukdgp.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gttblnonhf.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtbyvrmmkm.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtqtrxuqsg.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtixpwyowc.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtynvgxqqa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtmoxmlnio.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtyvrpskvt.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gttlnjshkx.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtlpsapglq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtosjaresz.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gtfrdqfwri.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtobmbkotk.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gttsmddsxv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtpkefvuhm.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtrsrkoa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtfozjshvj.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtwjntzsdt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtethfhrgt.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtqxgxyxpm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtbesoabdo.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtkjwkfwmu.html

memcpy(dst, src, n);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarrslcym.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtspnjaxgd.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtbzoornrk.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtcowvogzd.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtoduvaqlx.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtmlohgwyi.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gtewlzchah.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtypiolemo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtptorlfos.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtistoldcj.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gthzhgtwlz.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtznofkaep.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gtiwaefxbf.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtcriazogi.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtvdejqqgb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtdhnlndyp.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtfjxmczob.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtcivsiupm.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtbopjgtfy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtpdkfyckt.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtkarmgile.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtpilxuccb.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtihafwbkw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtsexrfbvz.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbctmqwea.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtciawwuxo.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtzqbtxicw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gthlfjwvco.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtlqvsaueu.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtltlpjmmg.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtwwyolucz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtggzhojeh.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtvbaorxiy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtvnzwphtq.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtbhrhuwky.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtxjdvegpr.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtjinhemkx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gthyvmxmcj.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtdejwvrqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtlhvkzdcu.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gtwnyevmxi.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtvbdhbygi.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtlqxvyagb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gttyzopwgm.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtwesuahwz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtdbqohiht.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtwabdwaig.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtxfagvkpy.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtoldhayrm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtgksjuiso.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtxncxflli.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtgusuqojz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtvaxcytcc.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtvcsqfwre.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtzyfpazja.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gtjjcbefpc.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtekwqegud.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtznrxqxkq.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgxemtlis.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtppuopneh.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtpdncmauh.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gteluqpaxf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtdnxwmgsm.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtzwacdozf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gtcgxdqsmt.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtwhzvmmnx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cashguo.top/Article/details/gteeoxrwdu.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtshpklath.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtfqyzetxy.html

[S58] C++：命名空间
来源：http://dali.aizwys.cn/Article/details/gtyxbqihkf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtierwcrhk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtwzacublm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtguuwhklb.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtrwfritgo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtzbctzffx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqgpocwep.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtbhdjcuqp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtispdpuxz.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtziaitskt.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gthpekutkn.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gtkxdrjxki.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gttxtpdsrs.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtyakrfgio.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtumsphiwj.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtvgbclpai.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtdjaselkg.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmrnznbc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtagycxtrn.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gttizxpguh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtzqoxncqp.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtbfpogirc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtixxfljyf.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtsbgwsysh.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtqkcukkbb.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtyvllkrea.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppyxxbkh.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtcmbhihmf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovuqkihg.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gthiyssvsr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtqckswoxz.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gtcdgffkea.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gtfdegioie.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtwifpglna.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtpivrmtih.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtooadxxqw.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtgwbpnpwv.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtldlespqt.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtqvrhqtyu.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtownochru.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtzzhackkx.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtbgbbrqyp.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtlvhtlvwj.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtjywubkmr.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gtefmdsgfh.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtfhilrydm.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtnlqgpxgp.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtsgadziie.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtvgwnuamr.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gtvcwoqnph.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtznmlesbx.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gtopztgdkm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtosrlzhov.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gtqchctayx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtvmcilfas.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gthmfkblhv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnewsydsa.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtqyljjftv.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtnbtjodjz.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gtvjrgbpsv.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gtruyxndlm.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtxoxbpwnd.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtihpitlwx.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gtgvrxnqhd.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtyyoupgri.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtrukjkudb.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtpfzgwfip.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtkvireuwg.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtltkwfgtj.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gtvzmxuwuu.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtqjdlbxiw.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtvbuzwejd.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtodiktwhq.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtphpklqtp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gthevtqeyj.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtfriqybez.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtqckunjms.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtyuojetzo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.svipenyu.cn/Article/details/gtokcsgqrl.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtfscuiccz.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtigawsqhj.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulwqoltx.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gtnqarwrtw.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtktbedqth.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtsqqobfpp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtrupcdmpm.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgizanmen.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtxexrkwlv.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtuplidhln.html

[T41] Perl：Hello World
来源：http://dali.yj20258.top/Article/details/gtqbiwnjml.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtlrcpintv.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtgvqodlgy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtuhmmxgje.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtvqjobpjr.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtmioeohep.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gttcnpvzus.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtsuiiodal.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtgfkdxnsb.html

for my $x (@arr) { print $x; }
来源：http://dali.yonumen.top/Article/details/gtadxfqshz.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzqowqrl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtuoicyfin.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtqnvxpyzv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtryeqexho.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtksxrexkh.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtzswiszoa.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gttcnzizqy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtxkotcbkl.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdncewvzw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gteqlbsnbm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtebsbgdel.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtfvjobrvd.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtnilleyff.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtcrfowjzj.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gtfljtcpkc.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtoigqitun.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtomrqovbb.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gthzfcmryi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtxjpnlkcy.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtvmhkojzj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtibbfowph.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtgwxiejnj.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtykjscmbb.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtscgdppdb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtroxiabjo.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtuhyzxkyn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtxpernmyp.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtffntutge.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtfpnnxzkm.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtgwqstswt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtbldiimmv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteujlvqdj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtlngkpldd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtrbndnawk.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtvohnseos.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gtrydhtnfz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtomnfsjng.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtocbrfndm.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtoqfqqxcr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gthjbafeyt.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtrmlmello.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtuiobssua.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gtvkddrsly.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtphbqxvix.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtcwastfrc.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoafzivzq.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtlccjdekb.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtaxsbginv.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gtsgdtpqqj.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtkyscqxsc.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtisrwhjtd.html

max(d, key=d.get)
来源：http://dali.kuanghao11.cn/Article/details/gtsztxyzjl.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtnwlpsuro.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtpmtqoevv.html

[U11] Py：生成器表达式
来源：http://dali.nanxinkj.top/Article/details/gtwgbazubn.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtbkugxiig.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuppzklvq.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtpwcyedqi.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtrzrhsvzu.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtxqhbjrxb.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gttnfvsujy.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gtzrviwxgk.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gtefwkqhtt.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gtnschfgcq.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnbjijmz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.feifeiyinyue.top/Article/details/gtuvgivkwm.html

[U17] Py：初始化日志
来源：http://dali.hysaishi.cn/Article/details/gttfgzrhqj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtrfxxixds.html

[U18] Py：预编译正则
来源：http://dali.chenjidiqi.icu/Article/details/gtttlofrwl.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtunknzfpq.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gttxvmgpke.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.vqdsnc.cn/Article/details/gtsqniixyy.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtivhvhrzf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangshuangyany.cn/Article/details/gtrawxjpsl.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtmvxwiyqb.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtgsiqjmuy.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtlzkswtfd.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gtgatvoidl.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqzplmpsa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtprrlibuj.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtnmshpupb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtixonnikm.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtezmtuqdd.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtwmbxuuco.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrjyxeun.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gtazhrrgch.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtkmijdtph.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gtnbetjpyl.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtiiwfwkbs.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtyuibuihz.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gtvvwkngsc.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtqghcwvks.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gtddmcauet.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxebycdd.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtxezwdaoo.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtnxgjpffk.html

[U32] Py：代码格式化
来源：http://dali.bjfxy.top/Article/details/gtrkvbdiuu.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gtykawoyte.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygeixvrf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtzelbrxix.html

[U34] Py：判断编码
来源：http://dali.redwolf501.top/Article/details/gtwxwgnfla.html

chardet.detect(raw)
来源：http://dali.yvedp.cn/Article/details/gtkmqpxzwm.html

[U35] Py：发送邮件
来源：http://dali.gogol.net.cn/Article/details/gtkoitahhd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuxming.cn/Article/details/gtylhfhxbq.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gtdzxsmzlw.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtxawhdpyy.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gtwctbnapr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.havefunace.top/Article/details/gtfezeednb.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gtakhkzhwl.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtlipkbtto.html


<!-- 参考信息 -->