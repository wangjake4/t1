代发 wailian999

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtzhluvdvf.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtnqpdsvle.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtrarndoqv.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtoawwadoo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtfhyubtzc.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtjmrlcgwz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtqbjhjogd.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtcgnsnhah.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtcqksazei.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtjsqixhsy.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtqeujraml.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtvycauwuc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gtormrqkzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtzikczqer.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtnfzyohte.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtgaeejlkh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtbmroclsc.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtohutmcoh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtbvxioxxi.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtcddfbdws.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtftggczio.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtakfermxe.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gthjacxbwz.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtkuaqgnum.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtlibdwjfm.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtfinfkclj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttimjehpn.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gtmokghmwk.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtifwtbixs.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtgmfrdnlu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gttrmqavqs.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gtbdggavin.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtctcjcisn.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtpxmmvyei.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtajyalklw.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtwulaaqze.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtrfejzvrn.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gtfczjpmhu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtqfdkqnpq.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtsumhisqy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtkqvhosvf.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtpgdjymxa.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtykxlucpr.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtjmreremy.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtgkphnydt.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnyvmwff.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtbwuovijh.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtlrhlhgka.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gtuovhufyw.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtjketzpoc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmfganof.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtcfmuvzgr.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtdlhmgyxq.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtvfnohrzw.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtlcscbyrr.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtdsnnpkts.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtzlmdqgiz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttqjuvsfn.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtamkbxhbp.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gttvkkbxbz.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtknocntrx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtpuaeunfh.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gthlrvoilc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gttlquopva.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtmuvyjfdl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtcrylwoza.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtpezzphav.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtkyglktli.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gtctgaczxs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtnmbjuyvw.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtessmygkx.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtljuktssc.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtlahfxqgg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtlqfzetbm.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtqqtrytov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtgdfmtvcn.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtivfdumuq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtcdcriw.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gteyytpjoz.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtmuwrqxyq.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gthpdbeszh.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtnzktydlv.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gtvlsxazwj.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtspwmxcxf.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtaucviuri.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtdcrfnfta.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gthopjiurj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdugdflrj.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtzjjuscpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtcnghcvvx.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtqupecaog.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtghmwqjog.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtfwtruhfd.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtwgoobolm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtgqlpgmve.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtzhsajkmf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtrvxhpebt.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbhtopgu.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtcxznaxrt.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gtswkmdmgo.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtqpabwaps.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtrfyokeiz.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gthekqydmz.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtsqtpaeas.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnpuajin.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtxkejqncd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtzezjruan.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtunciqljc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtpvxdhido.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gtjeozdfgv.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtckkycala.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gtparwhlar.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtxvlooqqm.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtaiilbpxa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtumwndrox.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtdqbskiep.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtdppbbabz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqdydgkjp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtbqykuwpm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtckmzgchb.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtgtdjinch.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtsserylxg.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtxdwbkfpf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gtqoxmovxh.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtjurhxbzd.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtklpgybqs.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtyebakifq.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtvxtmdamm.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtgyidbwqz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmyznuso.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gttwymqysq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtvtgofcbx.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtmgzhpyop.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtxwjiohja.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznlmvxtb.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gttmxvkfnq.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtcfecsrgh.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtnmiuervo.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtdtlkjvqi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtiuqdhmkx.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtccjuishp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtghdcpsee.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtxijpzvzv.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtwkciadam.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjqirtvp.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtiamspbmh.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtjnhavjmc.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtmsgdmvmx.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gtebvoprhi.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtkwznuteq.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtbyapwvos.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqtioiud.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtwswqnvzi.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtftdlxalm.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtouuoybml.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtqmetswfy.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gttidpwrfq.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gttfjfmnkf.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtzkkjprvu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtsdvrmcsg.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtgabuvhlo.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtcackewik.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gturiinsyv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtpgtebrdc.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtjcfhzlpt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtucfakukd.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtvzizmadl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtrdfdemtu.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtwhlnsyez.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrjurgul.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcrbzvgg.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtmxalorni.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtawzmlmxu.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gtpdaihknp.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtbdmcudox.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtfiunmuzv.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtzqpgcoad.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtnphowlzz.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmlarlap.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gtuuaxgwgj.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtnrclydiz.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtvuglqlvn.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtfzuamsqw.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtrqyxeize.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gthziitujl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtlmmkagqu.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtzvbqomun.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gtuktajshv.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtxqarjuza.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidluhpux.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtxayrljgw.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtkbjxeaon.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtcmegmgra.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtlwpanfpq.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gtwgvsvtwb.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtdbyisgcs.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtauquljik.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtiegvfvbr.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gthczyldpp.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gtqpjpcnjx.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gthtzuvcko.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gtrhxnqrko.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtjnqgvplj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gtuyehcdcj.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gthhnvakgn.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtkhwxpwan.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtowrnkhnm.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtfecyxjkb.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtsiukxurc.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtzekxscaj.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtesmtairv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtthkyvgpj.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtyhwlnnfu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtbrfiqzuu.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtsyuwwcjh.html

$s =~ s/old/new/g;
来源：http://dali.dashuyun.cn/Article/details/gtuqyhklin.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtjgrwprzb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtincyytuq.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gthoilsoxk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gtgenjoxur.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtaenmvcdb.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtmqxpvjmg.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtgjrknvkb.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtpduazodj.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtmstdecpf.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtvbfjinir.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtqzctdxkf.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gtlnhgicee.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gtovwlnvny.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtbrkudekb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwaxquzos.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtrodnlnkb.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtyykwzzkt.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtkwqmjmoo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gtvjnrptiv.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtvbgussdx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmibbkbqg.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspnnvpnd.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtqzwuurgk.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtpiokudeq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.birdmap.top/Article/details/gtexdkkjrv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncgnmiiz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtpfumtgqk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtoxzvitma.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gttitbtpjo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtlukrxwas.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtvwkncsbm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtitjfdxtc.html

[U03] Py：加载 .env 配置
来源：http://dali.iojbl.cn/Article/details/gtudlvgxpw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtjecfwgjr.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gtppppbfqa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hysaishi.cn/Article/details/gtnkjklhvs.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtrffodvdx.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtrewkeyfu.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtesvetbri.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtdhdpzaka.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtdhdttnae.html

{v: k for k, v in d.items()}
来源：http://dali.jyoumei.cn/Article/details/gtgfhgglsi.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gtkyiajemc.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtdelurkum.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtrgtddvyd.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtbpdnuxpv.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtjqmocads.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gtkofqptfl.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrihnfxg.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtuytovvfr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtytlxwupg.html

Counter(arr).most_common(3)
来源：http://dali.gaohongyu789.top/Article/details/gtzznizhwc.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtauhkumbj.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtxqnscpsl.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtbillzhyd.html

defaultdict(list)
来源：http://dali.sweek.top/Article/details/gtwfqcnvfo.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gtachhscom.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gtyvkhslkq.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtntftvdnz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gtulbcwyxq.html

[U17] Py：初始化日志
来源：http://dali.yj20258888.top/Article/details/gtzalqxotv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtysxcvswc.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtcglxayin.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gttyxdwojn.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gtonsyvwlj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtwibvbskk.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtomfonauj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gtxjjqewmw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtvxbymugb.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtmlbeuzix.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtqrvhssjq.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gteljlbtbo.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtjhjhkxpg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gteapjzxla.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gtqdptssrs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtubzwojce.html

[U25] Py：CSV 按字典读
来源：http://dali.hysaishi.cn/Article/details/gtojjirmdg.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gthtjniriz.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtwmbhyjzq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtjkcqdlbj.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaykugef.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.bjfxy.top/Article/details/gtuapbyhfn.html

[U28] Py：类型别名
来源：http://dali.hywenlv.cn/Article/details/gtiaaknazj.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtytjcevgi.html


<!-- 参考信息 -->