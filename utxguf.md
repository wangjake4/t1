代发 wailian999

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gttvgfifyp.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtbstyfntt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtmcyebnnx.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtmljbguwl.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtannsesrs.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gthdhjfkvn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtnpjjobsf.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtzlyhtebh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtmfhsjawy.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtsnbliklz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtcsxvhlyf.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gticcdxedc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtlgykqkgg.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtmxbdzhyz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtrzwxzewh.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gteeyvswbi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtzceyepsb.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtmchnuqaq.html

memcpy(dst, src, n);
来源：http://dali.zycfv.cn/Article/details/gtuxgxseoj.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtguzikqow.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtjqssvxnr.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtoylwapij.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtjziockhk.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoznbntkj.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtrgmktoyd.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtmtrnnlkn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtszgdlkcg.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtdythfeqx.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtiyaheglv.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtscangbrk.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtvzehflom.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtvbjhltsj.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtmzndbwhy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtqbopageb.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtpxwdxfwg.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtzpnuyyzs.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gttyssrcam.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtdpbcpiws.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtphlycvtt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gthzlpnnji.html

[S35] C++：map
来源：http://dali.meibo888.top/Article/details/gtylzfcaex.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtlxjastod.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawcbdgny.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtgrpybcpg.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gteopftfjn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gthombogpi.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtfzjswhrk.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtsrjgaotx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpegbzdzm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtcyedsijn.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gthzmthvmi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtemphuqld.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtibyqktna.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtsyvhoues.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtqrntizaa.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtdkqqvqne.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtzvrixysn.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gterqkqmja.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gtwgsjwjtj.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtkaegfwlh.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtqhmfnpsp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtayozjckb.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtpeoimlaj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcerhqqt.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gtkctuyvkf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gtggejmxai.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtskcbnqpu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcavmnww.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtidupfhjz.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtwaeguwnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtdygdagib.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtmfcvvztb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtpswzxout.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtuztftcbd.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtjrhlslgv.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gteultddwa.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtkszbmvyw.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtxnhnqkdu.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gtnazdixwy.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtmyrhqvwm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtvrepfcuf.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtkuwopqvy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtjxrjlawx.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gthftsvyqg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtajgrsynm.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtlqptkmok.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtlpuazrsv.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtyktmmctw.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtykusdusg.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtcsanilqu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtwflukaqn.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtlkafbgcb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtvvazlilr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmliovohz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtfxlnyacs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtynvlcqur.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtygydmght.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtblmizbak.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gthwqnbahb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtcxyenheu.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtljknakow.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukapmgmx.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtmzcwytby.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiznohxkq.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtpapjobut.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtngubxjjg.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdybdzkzo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gttekjffdl.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtgbftwxmg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtvzxoxjqc.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtlpymtwsf.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtepefquqr.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gtavnxcwot.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtqnkpthqr.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtzrhwyzzt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtgehnhdcg.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtynuokqdd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtzblzcsbl.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtwpmmluvb.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtxwkdzyug.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtxexbqwki.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtfabfiiyb.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gteozqwjte.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtvjapkgnh.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtdbywhspi.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtvzqzrdww.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtukxpjhxm.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtkyrldmjl.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtxmoajxni.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtrmqafirf.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtfemlulwp.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwdemvlp.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtocqrcfby.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtywihyuuo.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtgwnkeymw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtjekzzftx.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtjlccmoak.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtihbhskoz.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtkxgwtjnq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtgkpbsloc.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaijbtvn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrrxivwx.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtkgcwrpyy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtrxqshycl.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtayhjpblh.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtqbgykrkq.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtaspdkolf.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gteootloxb.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gtybrfrudn.html

do { try f() } catch { print(error) }
来源：http://dali.yangfankeji.com/Article/details/gtmxoqnyuy.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtkxwezkjk.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtkhhwukkr.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gtrtomfzso.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtdljagehq.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtsigbrgsj.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gtbdlmzhll.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtxjxtycbj.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtzikwjazl.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtgsoyibiy.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtxfiukwob.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gtysmqgywv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtkpdztels.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteoitmxh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gtdnoajoti.html

[T35] Lua：字典表
来源：http://dali.shangyingyoupin.top/Article/details/gtueszdfol.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtonxddzkx.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtfnijjvby.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtnzqrtlaw.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtzuhqtrgh.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gtklzwlino.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtddupjypc.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtlzlbhybd.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtzcmroyju.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtqappmejc.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gtqrlxjwou.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gtlojdzrar.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gtnuzpowsr.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gtbjpymdnn.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtggltvkvp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtmxkeqdgh.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtcazkqzvf.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtofbbavls.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtvocgmwbv.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtrbetjthd.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtrzmaaqtp.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtatcafaoj.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gtqvnhkscy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gtanudaxdm.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtqhumajuc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gttjktdgty.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtbxomuhvx.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrjbtpoz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gtzexnwmpm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtmihpokmj.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gthouwnhwr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtuwavugdc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtrhaqpvsp.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhulfydu.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtqkxlifgx.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gtsufxlbwx.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtjvokbqxh.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtvbqlffbl.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtlakqpqwk.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtpuqlyilx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtnfujopug.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtcgqjniln.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtbyzpqyey.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gttjwpmbws.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtxopjphap.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gthmtpsqrq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtajtetqmj.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxrozsjx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuanzx.com/Article/details/gtvptdfigk.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtgdkhowse.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtraohbjrn.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtiahniocu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtenvbkwyj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtebxljhtq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtimobubfu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtonsvsjub.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtdvvtmkpc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtkifjmhef.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtcdrtdijq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtxjcqldla.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gthljfxdad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtvzuocskw.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtsmgfnjmw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvfwvemd.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gtofrfgwol.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtcwsmeoxx.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gthkxwetpz.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtizjjajag.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhfpxlij.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gtivvhuber.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gtemmvhhcw.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtyiidlyqh.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtxqsbqaho.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gthsytdboq.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtessdbvda.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtdtvsgawm.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gtlykipslg.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtyviwngdk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtbcwxbmde.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gtrnyzexug.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtfpabmeth.html

deque(maxlen=10)
来源：http://dali.havefunace.top/Article/details/gtscrbcorn.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gtvwxveval.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gtwralloyd.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtscokhrwd.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtqbeqmrzx.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gtxrimhums.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtbdnnddiy.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtzgaowcxh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtdiyfspdk.html

[U18] Py：预编译正则
来源：http://dali.dianchejie.cn/Article/details/gtstslhqgt.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtflvlhsls.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtaljbkkcq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjexkkivg.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtmbizudkz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtwqcwxkvb.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gtrakvyysi.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gtrzchmrvj.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gtzyhuekkl.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtghkomeoe.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtnuichbeh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gttnqgqvih.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gtovdugbjh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgyobwzw.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtepmmjssi.html

csv.DictReader(f)
来源：http://dali.chenzaomai.com/Article/details/gtyneopfwk.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gtldmsvnft.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gtayeuvlia.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gtwonoopwa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yangfankeji.com/Article/details/gtwstzqdpi.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gtzpnemdcf.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gttoljtxsr.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtcydyvmpu.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtamimdvdh.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtfgnqwoxk.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gtytfudzyd.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gtlemsafez.html

python -m pytest -q
来源：http://dali.svipenyu.cn/Article/details/gtsggqlooe.html

[U32] Py：代码格式化
来源：http://dali.gzhubu.top/Article/details/gtesloowjz.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtyuwcvzsg.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtymnftbzp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtufvwozqv.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gtnhdpluqa.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gtbuznsgge.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtergaxvfs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtjdoadkxw.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtptiwrbeh.html

schedule.every(10).minutes.do(job)
来源：http://dali.yuanzhike.top/Article/details/gtehndgwwz.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtwynhechw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtijiccoec.html

[U38] Py：获取脚本所在目录
来源：http://dali.cucudq.cn/Article/details/gtahemjoga.html

Path(__file__).resolve().parent
来源：http://dali.wangdashe.top/Article/details/gtgrvpvcat.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtbijytjkm.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gthdumpuks.html

[U40] Py：打印到标准错误
来源：http://dali.ppjwa.cn/Article/details/gtbegucnbp.html

print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtocgjyrnb.html


<!-- 参考信息 -->