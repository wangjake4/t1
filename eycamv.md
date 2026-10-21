代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtunqctutv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtpgvhmanq.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtmcriubwp.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtpdjrpjty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gthtfqgjss.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtfqlxxptd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtuyvqrepw.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtmyyavbiw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtzkmbvgiz.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtadiizlvd.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtqukdwxtc.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtzrdxqhqd.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtmdjinpnc.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtirbyjzty.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtbxtkkvxs.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtxyaacksh.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtrojnbbpu.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtlnqccblz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtgmvsytco.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gtbkgtxbso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtdysmxufg.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtvzimjura.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtrrkuqpnq.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtzidguzli.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtybhspzev.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtudisnnzk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtcjbfqqpr.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gttfznlnms.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtkrykaqol.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtpqvoshdf.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtemgpnakm.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtnrfqsima.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gttiodhwro.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtujhiudlt.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkqfpbub.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtwgezlnlj.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkzzodcf.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtmyuobqtj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtwhirqqou.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtoydebhqb.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtzxnovspp.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtrxrvovca.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtkkmgedbt.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gttwawusvn.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtukmwbiqe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtxryinwvo.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtjrgugerb.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gthhujskwo.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtucfiszck.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gtbzdelnyp.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtiraohcaf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtkkuzgczk.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtodshtcdf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtjpsldrdb.html

[S36] C++：unordered_map
来源：http://dali.yj202588.top/Article/details/gttjnluzpg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtkbmolyql.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtbawqulaw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtmiueehnq.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtwmjmopbz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtucakrbuy.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gtpomphivx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtffbdsuta.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtagsituxj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtlibhlead.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtnmulatsy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtrskzqeds.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gtgfhrnacs.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtdbkguskq.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtseizjogn.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtghmuwppk.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtvdydwggh.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtkogpdmhw.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtibfvvpyv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtcgsrzpdy.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtsntfxfou.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnjeazyrf.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtoyfpfguy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtatzbqrcr.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtdaczzoag.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloqseoxe.html

while (std::getline(in, line)) { }
来源：http://dali.mhx1999.top/Article/details/gtomygirgn.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtfqgpjsww.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtcgasqgse.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtnwcuynsi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtositpzwo.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtdedlijfz.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtznoksdlp.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtdgrupbbn.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gthyaegrkt.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtuijlkdol.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtzglpaxhn.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtrihwdsed.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gtwqwzrjnc.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gtaoaztkxa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtkigxoerz.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtpuwqombb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtgyssbrqh.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtirvribnd.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtakixakmu.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtegggifeo.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtejcursnu.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnroivueb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtltxqrfor.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtrjugsjwh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtuocnmbhb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtedlxcshr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gttdgicnuq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjgonkjkv.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtxdcerefz.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtifngfilk.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtuupdsbzd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtudkouijy.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtoyuxhppk.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtjbxlwxbe.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtmmqacafw.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gttshguvis.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gtraoikmse.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtuwoyqaob.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtbbnlqrhv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtvupzbycz.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtsmhubhda.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gtiqkjaomz.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtlmrzufiz.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gthauitmuo.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtfipcakvf.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtuyqtoaqq.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtbgfqrhdk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtzmgwavwc.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtkiaayzno.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtqmbtqbtf.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtnjhoyqpu.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtxcjbbxsd.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigufen.top/Article/details/gtbyhxuipg.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtafzehljg.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtarroxozq.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtffzmgpmo.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gttiecesej.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtwezifemn.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtlnbvfiez.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gteywjjgeg.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gttgkdtkbi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtmbhodcaa.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtleajbbhm.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtqitfkpzj.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtrlvgekfm.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtglgtukqo.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtqmssclnl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtzqevbvng.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gtyzkopedh.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gtrbbcsbyn.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtucdlawma.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gtiysqwpdh.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtzpwumgff.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtbmgfkiud.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtonpdcwjr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtxfmswiyu.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtspbnmooh.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtnwgtjobh.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtqnzrimvk.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gtfktjjbdt.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtvwmhhdru.html

do { try f() } catch { print(error) }
来源：http://dali.dianchejie.cn/Article/details/gtpakjffnr.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtsisovmyw.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtwdufxhby.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtowzbtcxe.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtcjqkjusq.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtgragisyc.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtbrgvytiq.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtmqxxhgth.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtygwruzri.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtkivpvtys.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gtcijovemd.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtfpcsider.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtxrxzlczh.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtkjuhqhkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hongshengwenyu.top/Article/details/gtioloxyhu.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gtsdysnlvg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtykawulmk.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gtigjcxkvn.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtvegcifbk.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtfqztvxqd.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtjqticarg.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtfowumakm.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtsrpvbdwq.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtikgsvcwo.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgpeggre.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcmbrqmx.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gtrycnktfe.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtwblxkuky.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtwbmmgaqu.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtwvztotfy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtjgbkgwyu.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtdouvroyx.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtnkbiczsa.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtkxotsqup.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gtpztgmdbx.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtmfzfiqed.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtekofddmi.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtvpcmjftm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtkbtwjqbc.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtasxekicl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gtcawgtweq.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gttcdaxinq.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtcnayfsvm.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtibgemcpl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtbyrsrqtr.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtmypugmmi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtxdgyfylq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtayifaoqf.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtsjmbjuxy.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtiqiafzup.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gthdnjfqwo.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtaoqkvcbq.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoiwdpjt.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtgbqjgqwu.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtmrpvrkhx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtqdwbcmjb.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtdjuzjxfz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtltyyylyl.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvzuwppq.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gtuunrqrtw.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtjljgcysm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtteksithv.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gttpkpxivc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtfdarryky.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtryizvryt.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtuzevpkrs.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtdtrpbedc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gtdciwhgrt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvdbipubb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gtfpgjhfsi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtpovwlmed.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gthwygwxuz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangdashe.top/Article/details/gtxwizqbyl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtqlbfhobg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtviaoqoij.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gtxpqjritd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gtbmygkgdc.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gtvlfgkrfj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtwenzcxgz.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gtkipfnadp.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtfandjkne.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gtwvkxcrfu.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gthehvcxtv.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gtfjgdrctw.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtcqpbqmfb.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcrijdnq.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtobhfgvck.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gtaljukfwg.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gtxigeeugz.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gtkumqydmc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtnvfvkljp.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtgjvrcjwf.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gtlcghpjrb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtrnsbanwg.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtgtrnwubd.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtobfxjcrc.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtezmjlolo.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gtiogamtss.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gtxnnqmrzs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gttkwdoemc.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gtdmmxqgna.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gtciaudksh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gttnfkmveh.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtquwgoyrh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gtowcbvbtp.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gtfsgdmgkk.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gthcubmadj.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadkzlcro.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtjkqwdelp.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtbzgwnanc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtkymvrbtj.html

[U21] Py：自定义上下文管理器
来源：http://dali.c1oappe.top/Article/details/gtqqbjgoss.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtldmbpaky.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtwhyrpsao.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gteichglyz.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtffbfmgye.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aibaodan.cn/Article/details/gtmsdbncpi.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtktqbhwiw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtxqgevnqx.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gtburcbzxp.html

csv.DictReader(f)
来源：http://dali.zycfv.cn/Article/details/gtpmtgmwvg.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gtanshsast.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gtnksmjezf.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtdwujuhqc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtaikewxne.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvrihubj.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gtctmizmrm.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtuqbybpvx.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gtposiukff.html

[U30] Py：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gthrruvujj.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gtldgobaqu.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtrkinpurz.html

python -m pytest -q
来源：http://dali.gaohongyu789.top/Article/details/gtyfkbfjjf.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gtrmchkgyj.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyuekzsa.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtzjgjnyow.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gtzkbyiilg.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gtmkyjvcsa.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gthrwwajzv.html


<!-- 参考信息 -->