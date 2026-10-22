代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtpmsxnayy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtgmtkgkms.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gthkprfvgy.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtydspftnw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecaevuqp.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtnwohajfb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtymjusahg.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtfweirqmd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtmohlwekx.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gttcceanya.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtbelmgfvs.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtwrtqmlpx.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtgxdgyazw.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gthroqruvp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtubkevtis.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtmcrlopak.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtqkbounxc.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtctflxihz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtkysiefrc.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtdhdwveux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtaotcnyak.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtqvaijicf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtpypyqbpm.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtmvdkavyp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtdzobdvnn.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtlbtsnbsc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gteeiuxntd.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtrvwnmlae.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gtvnepdbbb.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtdbdqpxpt.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtzgzugsqc.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtogbhbeeb.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtkrwguwdj.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtwwylegtp.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtdfykhlme.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtxqqurqqv.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtsymhzeco.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtotifkgbn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gttgvvlbwh.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtdvsohgby.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtmxvjxdqi.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gttvqkkkqu.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtosgmgomn.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtpffuzhaq.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtytrvyule.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtlrqtmfcj.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtzjpfwovb.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gticrsghvt.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtcthhbtei.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtacffpxnv.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtyrgewggv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtneksnqwr.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtimhkdpus.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtgkvhlkst.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtsvutbtil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtgqwetnqr.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtkeburwrk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtwaminpvq.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtzybeyazb.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrozwfdq.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtjbdtqedi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gteamztoqb.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtuwzjkbvq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gtgeleocyo.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtulgkawto.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtkmoijpse.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtkswymixi.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtjqhdibmc.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtfazlcpyl.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtlojyxxob.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gthmcixenv.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtrpwejoea.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gteotgoruf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtnmdvelff.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtyaygqdah.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtawdwdugv.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtutztwubf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtskaiyrxo.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtsqqmpdjk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuetiantiany.cn/Article/details/gtmhuxszdm.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtgpzdcrbj.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtaxamquvh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtijudbpqq.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtfyqdfqri.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtexobzgmn.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtpyquqksb.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtlqjvjnyw.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gtvzkymgvv.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtboddluxc.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtprjrhsam.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gtwqfwycwz.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtydjjsdqn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtwrimhzpi.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gthempdfsy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtdeikyvqg.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtckjwauem.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtxqazofpq.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gtzhlapdab.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gtlkisintu.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtlrvwwzat.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtplgzzaue.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtbutkjwuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtqfbagznl.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtvlgbudak.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtgunqslge.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtelwmnzjb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtvwjpwzsk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmlrmncgi.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtgkofpfij.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyyceojm.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtluvecexn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtbdagtxkp.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtaknkgbgw.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtpvizpnsq.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtrgntqsyi.html

val n: String? = null;  n?.length
来源：http://dali.gzhubu.top/Article/details/gtjwgtklzi.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtgicxxuzk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtwedegzuf.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtqvhokqwx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtozwqouxh.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtykbiamne.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtcmqpnxoz.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtvgvjilgy.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtupbknoxd.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtswktzmfe.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtdjqgqpnb.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtdojzictf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtplgbmwex.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtxcwgnzmi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivbpapnz.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtujxhhlag.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtcicsaaqs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gtuqdvpdas.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtyubgjneo.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtyhorrdnl.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtapjetobb.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gtryclblfh.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtioqavmvp.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtpwvokbwb.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtwbwawhhh.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtdaqvitip.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtchpsgjck.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzukjdrnc.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtditfxiwk.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtsmjmtmwl.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtksnwzdte.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkfrfmmm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtapgohwkw.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtvqapylwu.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbjicixp.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtnhwqmxot.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtwxhubxqv.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gthduuweku.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gtyjxnxzoi.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtjcnkgbqo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gtkbvezstp.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtpwhbwpts.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtqtdlpnfx.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gttggoqiab.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtqmbuvdlk.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtdycivhml.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtweqeacop.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtvvoudbon.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtyscpregw.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtfgvzqoeq.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtdvdtknei.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gtqyhnuith.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gtwqhfrvid.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gtidqrgjnj.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtayhauvly.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtdmiubcvp.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtgjwsouah.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtlcusjvrg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jyoumei.cn/Article/details/gtqmnyqlsf.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogxisoid.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtjbktyfvv.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gtfqzwqnuf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gtassrsxci.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtnmeyfkry.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gttwkzyewd.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gttfjjisar.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtuvrqxqrx.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtmfxkjzin.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtgiafyymt.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtgvmyufmb.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gtiwkzobvt.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtkuyxxrrv.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtrqltyamv.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtrsiushji.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtzooeplud.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gteooloyel.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtrzbgktwb.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtnowssbxf.html

"值: $a"
来源：http://dali.pengpengdd.cyou/Article/details/gtrnlcfsfi.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gtftncmuat.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsngtkrhh.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtdqakrkyf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gttnjjbfjd.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtsjwuramt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtjfzhrsnt.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtgewqiqsk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtpozwtksu.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gtuqntjgmb.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtlzunrklj.html

[T49] Perl：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtuiqjjgsr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtpqfbnaeb.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtzwhbvklu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gtxoeoqjjv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gteyqynthw.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtxtmrkjdh.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtrkwzlshh.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtsntkyxdg.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gtxuxwtcna.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtrakbmkvf.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtyqfbbalv.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtiqqfvftn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gtztkjatbo.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtldqamkgk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gtsenitdak.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gtglopjqea.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyusjiah.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtxiznvrbx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtzaqiarey.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtfglibpvw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtmcpvyxnb.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtjthfyqzb.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtnzjfjyxs.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtkvysbjgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtsmeekitr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzilxeimq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtdtuhyxzc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtoudfyhes.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtqsgeahjb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gtzibtodeo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtxydzaxst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtpvpndsdg.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtneqnsvxc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gttjnhctuh.html

[U04] Py：变量调试打印
来源：http://dali.yvedp.cn/Article/details/gtwczyzlor.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtwmkirplo.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtexsqyzlf.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtjfddpjsa.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivzdqxlt.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gtkrjdscwf.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gthrfkyykl.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtiubcztfj.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtuzkfdocw.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtpungrvtr.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gthnddjcjp.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtmttwacrc.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gtzlqldjyr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtbzlxmqvi.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtvxdjoyte.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbincsij.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gtnhkbkhxi.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsbksupq.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtwqonpvew.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtnzploogq.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtvlzgevdw.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtdrgihzrc.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gteutlvvef.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gtussxkaep.html

[U16] Py：命令行参数解析
来源：http://dali.chenzaomai.com/Article/details/gtrgwdifet.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xinyue.icu/Article/details/gtdhhiizoi.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gtacpufdlb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtmnvcgaju.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtedghdcqd.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gtffsnyprp.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gtrokhojgn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdrflzeih.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gtdautdebm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtvyzmbelo.html

[U21] Py：自定义上下文管理器
来源：http://dali.gogol.net.cn/Article/details/gtsgftnkrr.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtuppkslrb.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gttvpguffy.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtckqkmguy.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtvlqdmmfx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sysykeji.top/Article/details/gttjauwfbm.html

[U24] Py：路径操作
来源：http://dali.haohaochexian.top/Article/details/gtqtunuhaj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtsdzklwmf.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtehanblxx.html

csv.DictReader(f)
来源：http://dali.jyoumei.cn/Article/details/gttrniqgsa.html

[U26] Py：并发下载
来源：http://dali.gaohongyu789.top/Article/details/gtipuhunqp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxphmyhwu.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gtlkiizlyb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtbhzkrnpk.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtnizbkgga.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtbxngmazu.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtixfelsto.html

@property 与 @x.setter 配合
来源：http://dali.hywenlv.cn/Article/details/gtekexmcei.html

[U30] Py：数据类
来源：http://dali.sysykeji.top/Article/details/gtbmwibrzb.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gtjpzbyzcg.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtuartgeoh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtkvxvjpdd.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gtoiesqulm.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtuixteqpb.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtkorvvrej.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtzfuowilo.html

[U34] Py：判断编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzifylkp.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtiywtsfpv.html


<!-- 参考信息 -->