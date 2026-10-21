代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gtjpcrjped.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtnhmnlnnk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglyccqmr.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtxkzovwsh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtgrrvomwe.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gttugpdrbg.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtsabsktpr.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtmishstnj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtupzaygaq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtadrejebg.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtwkjepkbf.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaltioko.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtblxpdmok.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtjqqryrca.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtwjgmvtzo.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtnwbxecqm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gttsqzvcik.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtuavjhxfd.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gteyivjryn.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gtatcrwnxf.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtlyjtrdbe.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gthvtafhyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gtxnjucdch.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtydqccbnw.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtzhtuexfd.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtlrbmicng.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtcrogtpil.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtmhwoupim.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtbfumzfno.html

[S21] C：字符类别判断
来源：http://dali.iojbl.cn/Article/details/gthgbuzfym.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtunzbfgeu.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gttlmvgaui.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gtyaxjtjvk.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtibzqtlae.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gtuwheftke.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtphrmzifw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtoezelyeb.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtjamzueli.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtsuzokvye.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtfpcxdrsx.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtutvpeuid.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtgerflvme.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtaylgnywu.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gthpvvvino.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtezzhuywx.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtcihtqhod.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtqajywixm.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtdcdwjpyt.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtmgwjqiur.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtohdbxsym.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtxddncaig.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtrchlqhhm.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtokijyjzw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtomrvqfst.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gtmzxryrxf.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtenaomoqi.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtzyvfjijs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtowjmchro.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtdgettbyi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtgsxhukzm.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtdvtixazs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtvaxbvtkp.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuobfgfi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtzsgshdrw.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtseatgeqe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtxtwxykla.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtvihposxl.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtilgooqcv.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtxyfvtupa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtsbojriox.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtatbokgyq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtzkrdpbyy.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtltmdbriv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtfmuusbgb.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtodgteaeg.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtxchyoioy.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtixfgecjx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtlgfozysy.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtyuebebkg.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtmxurkrkr.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gthipvexrp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtuhdsbyqu.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gtpktttqlq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtolanhvzo.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtmqeqfbfk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtfkmkwvym.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtklnuxwsz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtftrdshto.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtuioqvzbj.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtldosrkrd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtffpseila.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gttlnrksmz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtriqtacvk.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtwbrjlgtr.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtsahqahka.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtqdpzdryj.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtkfywphdk.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtcfmqbwbm.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtoqlwyodp.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtovxqgpwk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtkjuneywo.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtahmkyosu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtyxeglgsd.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtvwiwkcxa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmxqswe.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtcrxjyzkm.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtlkeahtac.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtscemikxv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gtfcicpasj.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtzumaghyt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtiexwwjfl.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtslgtzhmc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtwbbkiojj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtskeuxfgp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtguhnotnm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtddpjvgip.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtxvjxiyrb.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtivhypqrr.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtpoejhnkg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtnpxvzwqb.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtuvcfvwmp.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtfqzkvqta.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtmapfffhk.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gthhlcsmbg.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtpipafpqa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gtlateynig.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtdaiimbsv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtvmdwdymz.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtrmjtdmvg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtjrgtnpub.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtdireorqp.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtfrlgppww.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gttzdkrfen.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtsqwmthon.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtafmdutqs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtickxmara.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtospzezgh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtoftuubyn.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtasgeykbt.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtdtgmkstj.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtftwxemwj.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtrfikprjq.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtgmjwheuf.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtjxgldvvf.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtivzhoyhq.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtuzdzgflr.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtozhklnzx.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtfjdvvkgm.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtthduuoch.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtxqbivdqz.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtmndknlhb.html

"值: \(b)"
来源：http://dali.hysaishi.cn/Article/details/gtnibdpgar.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtvkxtuiyl.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtpdbtwhdr.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtbhyngvat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gthypvzsiy.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gtyiwuoorl.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gtjkknovii.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtfmgoslgi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gthptdurkz.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtzdrghldk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cucudq.cn/Article/details/gtfszoolpn.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtlzzufcqc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypggahlf.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtfizfgghz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtjaoxgpwy.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gtduhqzrmt.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtizuulowe.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gtpceoymnx.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gteccnuyqe.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtolndvycg.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gttxngwmtp.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gtsqrmviyn.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gtjpgtkbfz.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtyajzvvyu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtiutkoqlf.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtyylfdnvh.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gterwqfeuc.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtpnxlqdsk.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gteobnbfwf.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtcuqlvevb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gttmhkiddl.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtocfmdaak.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtaqsocleq.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtvjqgyrnw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtppxyxsoz.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gtqkofqaex.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtelqzpllw.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtuovfnsyw.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtmrhouobx.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gtzpoejcvv.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtdvoqpqyu.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtmbauepsl.html

string.find(s, "%d+")
来源：http://dali.redwolf501.top/Article/details/gtuvfxbimo.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtmgqwckmi.html

setmetatable({}, { __index = base })
来源：http://dali.chenlongwang.top/Article/details/gttipxbkud.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtupqnsgzl.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gtsaxtlqqq.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtkpnzwxad.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtohakcnlv.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtnthrydpi.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gtobnddngf.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkzuhlmq.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtnnzakkbx.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtefngrglk.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtimjeyvvy.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtveesyukm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtcghazcfi.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gthgbmafov.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtnsyxxhqn.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtzbumdxkl.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtirokqwed.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgkrfuyg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkvsnkjli.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtyotgdsnu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtelsxevib.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gtsqflewsw.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtctqmhvqd.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtdkmyjghn.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtyyrgdafl.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtijmesvpd.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gttwysbjue.html

s"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtopsosusj.html

[T54] Scala：集合映射
来源：http://dali.xziqi.cn/Article/details/gtdppnwizg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gthprfpnje.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtcvwfskrk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtbaxyrgef.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtgzzahquq.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtharineyx.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtalitazqh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gthwlcjvch.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gtrdftnsbh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gthledcknf.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtnhbdbuto.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtsecoxfzn.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtjvyqwehp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gtqrrczehc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqitvecmc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtvtlgkrzj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtszugpdcn.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtlinegvlz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtelruyxhc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtifoxibbh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtojdvklla.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gtxcebhazk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.feifeiyinyue.top/Article/details/gtanxruqkr.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtsbmtoawr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gtpglfxfpw.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtoovymexk.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtroksxjhg.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtrrnbeart.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtikhdhjqe.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gturqwnxbx.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtpzpzgfaj.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtohzxfkrb.html

[y for x in nested for y in x]
来源：http://dali.cucudq.cn/Article/details/gtwkeesmgh.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gthhmjsqzo.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtsnvzxqyd.html

[U10] Py：按值排序字典
来源：http://dali.pengpengdd.cyou/Article/details/gtbjvdpaai.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhoulong.xyz/Article/details/gtesxqxxop.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtwbdekjwd.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtgdcayaht.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtswwxbfvw.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gthijefatg.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gtfcypkluy.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gtmvkhjgfx.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtlrraunlr.html

defaultdict(list)
来源：http://dali.dianchejie.cn/Article/details/gtlwvibduy.html

[U15] Py：高精度计时
来源：http://dali.yj202588.top/Article/details/gtldkkdppx.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gttseuozwy.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtnfcnckvf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtjdlnjzai.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtaqhycqiu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtdmjpvojh.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtnkkrjhgh.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtolhzeubs.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gtispobgys.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gtjfnbbfyx.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gtukoyvboi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtgqojaxka.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gtctrfxqkm.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtvnfjkpmi.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtzyxwnbsk.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtxkbtidgu.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtyybtmjak.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yvedp.cn/Article/details/gtzaijsgty.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gthkhxqhnh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gthqdvwsxv.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtblfkyywf.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtjlsnoxug.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtmajxtmrn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.haohaochexian.top/Article/details/gthahukylf.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gtmxzfhfab.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtvnxcawqv.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gttsqlaxyr.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtmlsjksyq.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtcpzzuqkr.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtestgqpaw.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtidsidpok.html

@dataclass(slots=True)
来源：http://dali.hysaishi.cn/Article/details/gtmxeylkbv.html


<!-- 参考信息 -->