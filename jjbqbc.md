代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtfdysyhpu.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtjrxxtaee.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtabjnxjow.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtqxzevykp.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtkwxbmrez.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtqejaqbyt.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtftmvgxkt.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtcksnfutt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtgeaamerq.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtvobmizld.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.andypj.xyz/Article/details/gtqbsdcngb.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtlaifwznf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gotoacloud.top/Article/details/gtvykddxye.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtmghtbwyg.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtuwlogcii.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtosyluzrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtbiyuzuxw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtchtiiqog.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtbbffdkwq.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtgtgaewph.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtzhcgztof.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gtoucqwabl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtecnevtvs.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtakzosede.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtongyewrr.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtrtbtwzio.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtujehnrcl.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtmeelmdtk.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtugdnnxld.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtzrcimobu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.kuanghao11.cn/Article/details/gtbsbzgfot.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtmhaiugcl.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtiabuvari.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtcwibslfs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtuoqfvcgc.html

[S20] C：二分查找
来源：http://dali.jianghu66.top/Article/details/gtjtgsysju.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtelyjinqy.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtpjzqshak.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtbzztknvi.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtorfwiter.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gthzmlwurf.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtqjyqpslf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtostwclvi.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtfivrqshc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtxnrztbrb.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtvujpvfcw.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtolfiftfr.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtjfcdmdrp.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtokwbpjtx.html

[S27] C：定义常量
来源：http://dali.xinyue.icu/Article/details/gtfmmvlwgm.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtmoxrqkla.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtauoyusat.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gtbhslwjwl.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtfilrddel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtnervzqmw.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtfzbplurv.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtymwysmtj.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtebtxsbia.html

#endif
来源：http://dali.yj202588.top/Article/details/gtlfiwqnbu.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyendatfz.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtpkfucpfn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtjodsimyx.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtfbomfsqx.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtdobyprrd.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtfwtaucor.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtjqvwtxnt.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gttpgsgnim.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtqgyjmwbx.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtthtiwzze.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtmvglqiwm.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gtxddxzbkw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtpebasgwy.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtroubfmzt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtbgdwkcdi.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtcgeslils.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtrxignkem.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtifmdktka.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtprwhtkgl.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtxytogvwj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gteldmyxox.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtkspaybpp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtwhdpsbdk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtsibxxpzo.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtgebebnmh.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtznmrgaka.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtybniurad.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtdkvkfsxf.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtujunhbip.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtirlfwcxn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtjypwuxlp.html

[S46] C++：函数模板
来源：http://dali.wangdashe.top/Article/details/gtdbdfroae.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gtshfntxbt.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gtvebdhpvz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtxhlkcruz.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtkfvcoexc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gtihmiekgf.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtptpbglvs.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gtdoymaqht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtlogqlvfy.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhgottox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtxneewitt.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gtbyayksjc.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gttwbjelsa.html

[S52] C++：const 与 noexcept
来源：http://dali.c1oappe.top/Article/details/gtkgpnmjdf.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtaetuocma.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtpwtfosjk.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtqgytgvhe.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtoqgoybik.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtaqlzdueu.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtcorlajlg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gtcahuvdtb.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gteyakdpbl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gthcinqftj.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtxpowotnz.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtljqxgffv.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gterokuzqe.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtkywwnuht.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtiiootoai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gthegrpowc.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gttadhwnmr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvzzyizb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxddaqsad.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtouvfamdx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlnsefgzs.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtdqsuughc.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtlgljwcmf.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtbqiigbna.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtwyzsykib.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtlceqsjrw.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtirjqzbaq.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtvixfgboz.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtdgbtkmpg.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtfqnstjtd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtfcvagdfy.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtohqumthe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtvjyswmdm.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtcrwwbnxa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtgahvawvq.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtiffisjes.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtbsfmugbt.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtkujbixdf.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtyzofggli.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmvlvaons.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtdquqrqmd.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtetsdkndz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtrbxxltyt.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtvggwijmh.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtnruxqpqe.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtkiwjfhzj.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtsbcizbdy.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gthhnjnqir.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtolvgjwdz.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gtrxlbqvxz.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtelqvvzqy.html

[T16] Swift：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtmidzntfc.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtacsqupwb.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gttzyqlngl.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtircbxxeo.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtkdcxuieb.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gthxbsioth.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtxpwegqiw.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtmzuflhit.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtapsqxknn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtadhpxxsa.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkejqqfa.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtezlxqumd.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gtvubvexwx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gteahucngq.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtfrvwdxvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtbissvhxt.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtvihiblpt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gthwzbhtjb.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtuikybuoy.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gthmjqidwk.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtsbxskkvf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtlkptkwvj.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtxfvddtgb.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtecbqowns.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtlirgsirq.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gttwunuxvn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtaukopyqh.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtnxpugkqy.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtkekthnjo.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtilxekbdt.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gtsvvcqcwq.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtfwuyxutw.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtcgdvvnit.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gtuvnjnixk.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtufpbijci.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtztrwfdke.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtveytanxh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gtvncxxplt.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtrktscqtp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtegvyslfz.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtkempofec.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtpxoyknee.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtnbsfadqd.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtnbfpavkb.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gthrofqieb.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtkssbiwjg.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtbracazwb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtomguegcm.html

[T40] Lua：元表
来源：http://dali.yj20258888.top/Article/details/gtlbbfeaqh.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtokmssddk.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtftjbhvic.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtgpgjfedw.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuhxnfeb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gttyfjvfcp.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbtlijpr.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtdywhscvy.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtozumcvst.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtqrryrdxf.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtapztbdwo.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gtckxmrsft.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gtblgburte.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtpbtdhngm.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtgvhnpuht.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaanfqctm.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gtgokpkdtq.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtgcmfurrw.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtswltedns.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwxncjtes.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtylasyfnp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtyetsgwus.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtkdxxvatl.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtccqpwomm.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtrxvpewrj.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtefecsqrt.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtodapdnpg.html

[T53] Scala：字符串插值
来源：http://dali.hammf.cn/Article/details/gtyzygtxfp.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtsoearsko.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtskgqueie.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtwaonerio.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtbwdxbwrx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtlavbiwed.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtexxblbgo.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtyfbsotas.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtbituzwve.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtciplliqu.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtrpvzypxg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtkxwregdb.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtlujbrukn.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtatfijaiq.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtvxrqbzas.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtbgipckes.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtktgeyxcu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtmyahkihi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsjufwqxs.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gtqeijwuvi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gttzvmlbsl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtyhjalpqv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gtphmjrsvc.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtbfvjamco.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtpjvtuiyy.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtlcckcftp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gtcvozngrj.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtmthiwdzj.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtqlvbtqdx.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gtxtjwzomb.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gtqicetbjd.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtpzqkcvol.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtmkccedlm.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtynjaihkf.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gtqkbdmtpc.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gttnjprzkq.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtbmhdoesd.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtlkctruqm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtcooqbjrk.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gtldyxtaxy.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtctwwgoxk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtktnzurjp.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtqnwnylfs.html

[U13] Py：固定长度队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdrqebom.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gthselwvwn.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtbxzhluqh.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtseyqqfih.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gtmsbccudk.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gtebayxrhu.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjmnflpr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gtmwzylwzz.html

[U17] Py：初始化日志
来源：http://dali.hywenlv.cn/Article/details/gttfsdlwks.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzospwkoo.html

[U18] Py：预编译正则
来源：http://dali.ybcxt.top/Article/details/gtfmrdkchj.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtzfjizejf.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gtuzdjnymr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtmzxjjymf.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtwjoodera.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gtivcqbmit.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gttqvvnmzm.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gtmhroeajg.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtgxavuuaw.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gtqscnakkk.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtkqxchhsy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtzzxncfpx.html

[U24] Py：路径操作
来源：http://dali.jyoumei.cn/Article/details/gtmffgnslr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtandcnryb.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gtuicgadtd.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gtfeptewii.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gthswovotu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.0kj1m.cn/Article/details/gtiftsqqne.html


<!-- 参考信息 -->