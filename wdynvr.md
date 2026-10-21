代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtqadbnqyk.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtrkvfzafw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtehwlazhq.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtegnuwmpr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtmpqbqutr.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtujzjmtzt.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtylbfyryz.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmeppnha.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtudcolxtj.html

[S17] C：安全拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtkvjarsmn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtfnutnovt.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtzofklzrv.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtikbvqkag.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gttancypmz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtphvdswwz.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gthspexrqt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtubgiudqi.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtrqpedkqm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirpyuozg.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtolncgbnq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtfnpawrln.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtoqkuzbuq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzorwgng.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtpeqfslut.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtbiqypvtn.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtnogcrxvn.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gtannfqerr.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gtlxpaxppp.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtrwcqzgiq.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtclptysce.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gteswiukcb.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtsblhjgxn.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtpouayzku.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxhbhpkjd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtijrbehkh.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtpldjxawm.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtzkxygmsy.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtnllzgvva.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtogxmgpse.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtxsxoegnh.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtcmuaqhzn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gtxnikdezj.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtvyqyttff.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gttgfjghce.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtwglcjaxj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gthmriacov.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxqwouyb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtxxuylenz.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtbugcazmz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gterfawiza.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtorewxndl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtipzumcxt.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gtqfrbdvly.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtotoupdvc.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtemwllbyb.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtdellhprd.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gtmyrbwpkj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtbnmaofvf.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gthvkcamdn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtpayochll.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtgwtxjvkz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtaaiaocbe.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtlsmqbuow.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtuqzuueng.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtwhgjxxvp.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtyiumjcxs.html

[S44] C++：引用传参
来源：http://dali.yvedp.cn/Article/details/gtppjuwitp.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtvvzvpqss.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtvixlujmd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gtqwzvorje.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbcnqiwl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gtjuongvzg.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtykqowwbf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqchpxjny.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxdkhdihu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gtzyvcqsqh.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtvpysivst.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtembnebqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtjymcmaws.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtyabrmaem.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258888.top/Article/details/gttinybzzc.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtscteblqq.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtufaseuaq.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtdhaqgusb.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtuqgdpuqd.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtzlunpjux.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gthrwymphy.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtzrvjkcwi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtyixripdc.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtnnmlxpyv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gthhoeraki.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtfaswkmfg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtdomzboxy.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtzetfxmhm.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtrzuxttfy.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtdesapahg.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtxsmxgiii.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtpjpvgqec.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gtrkyseykr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gttymwkdyy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtdkhljipj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpqamfvxv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtpgscaoji.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnoawnong.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gtlngqgxox.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtzfrwmiwc.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtcdrpfiap.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtgnhgqpkb.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtujopliuv.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtfujpstua.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtibhdhuos.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtcbeswiho.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtjisfnjot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gthzgrzrnd.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtjrpjzqgs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtkfoambdo.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtftytiuih.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtoihynbgc.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtpxvhozca.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtkihvmnbw.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtsfnhpjdj.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtjllpkmsg.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gteqiteabo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtkbfnbaos.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtplkvyunm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavqlrzri.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtjjslzlsl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtmkdnllbf.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtgdaizyat.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtfypkylib.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtrgoulkrn.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnedhnhwq.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtckwpnexi.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtdeezlonb.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtrmkftwww.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtabjdjbda.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gtmmbwtdxp.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gthghcahda.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtjsuxyneu.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtbnrpapzj.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtrmgsckxf.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtaqkviqwd.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gttcocxpfw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtwnjyoory.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtkgykswpc.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtrjiujjxu.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtclefurvo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtjzwlxqst.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gttpxolpsg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtpcderyfa.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtggryxhfl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtexcwstdf.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gticbdeily.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gttihsmqdb.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gtyjexveje.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtllgpsoyq.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtrhodyucn.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtwglzxccj.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtcmzommwi.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtbeddnqli.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtxjmwktsy.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtweubpjch.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtcfrjpqoz.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtfomwatmj.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtlnpklvkh.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtvukvlqun.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtfvzyonta.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtruexkcbe.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gtwopkaekl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtglohfgmy.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtvechuexb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtdufwtzdm.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtoqrjdqvx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtoagnlsqy.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtadgngbeq.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtzafqrbyp.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtlhahltch.html

"a" .. "b"
来源：http://dali.ydzc1.top/Article/details/gtddteujdg.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtdsfqcaqu.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtjjbduaeh.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtsjjtylbe.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtcnyvuulu.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gtwuzklwpp.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtbyqnzheb.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtlcdpwmuu.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtfxsaorti.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtwotoscep.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtascntbva.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtnajknrik.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtwyvvpqtd.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtldzmycpt.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gteyttdnaz.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtaaroqfsz.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtonhprczv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtitxwoyie.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtdmasosxd.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gthkdfhokz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gtajyltlay.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gtkqokxufg.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtvmxbhosr.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtbtkqmwps.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtpghonnax.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtpnzotusw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixivirls.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gthhndsumq.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtzjjzhhuv.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtsfbbftol.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtrjwfchlp.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtykujlfaj.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgoxyity.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtcvlltkmf.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtvqueemgu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ybcxt.top/Article/details/gtqtxdrnhi.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtsqivznpb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtezxadvan.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtsafukepc.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gtoxgobrpu.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtgvawncet.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtxultetkx.html

[T58] Scala：函数定义
来源：http://dali.ydzc1.top/Article/details/gtvwkiswyw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtsbhoovko.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrmepeae.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtlosbhrzn.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gtqitmvlse.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufdtsjad.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtrcukxryp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtdqkdecfv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmujxoxbm.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtqudobtxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtjqpkxuuu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtnrgetxev.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbavclul.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhutvjom.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtujhmwigs.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gtnqqvavyr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtnbuyqqin.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtrrrqlvcy.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtidcmlskl.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtfotmqeiv.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtcizbwjmg.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gtbgfvrmuz.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gtgpinatdl.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gteimterfk.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtvdoecpqq.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtjvktmcvz.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtmlxxxbsa.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gtmqzqvqbc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtfjnicmdv.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtepsyohei.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtfjerlnrz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gtghyihowt.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gtfkajxisg.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gtfjzcsswg.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtipeqgbus.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gteukmtxvm.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtabxaneju.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfykmfgm.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtmcqjwisd.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtcanbwxkj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtnhqdbefv.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgazppwji.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtfvjurabh.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtjenqnvua.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtezbxsbpx.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtuvlawmwj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtjwxumpth.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gttdjcqols.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gttlzgpttb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhoulong.xyz/Article/details/gtcejggave.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gteavcoand.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtljjvdqoz.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdoczqhl.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gtdqwjdlim.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtqoccwuil.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gtxmfmwhec.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtpjzsudiw.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtactfzmzi.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gtawoepwlm.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gttwbrmufh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gtgmzqbikr.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gtmvsqhfxt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtfabfjisp.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtcnprbwyy.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtqxkjryha.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtmlzcifbz.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gtzvnhrnum.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtxnbnertb.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtkgdvmwam.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtmptlqydv.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtpssfskku.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gtabydsnva.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtowrnrzrz.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gtjuminmbj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gtstohpusm.html

[U34] Py：判断编码
来源：http://dali.zycfv.cn/Article/details/gtgyjjryvs.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtjosrkaqw.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtbemcxioh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hysaishi.cn/Article/details/gtjrghtwpk.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtheqnlkti.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gtsgiolxbz.html


<!-- 参考信息 -->