代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gttsibzaut.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtvhzavtqn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gtbnwaigph.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtqzzpcbrh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtxhrbnwjt.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtkslpwwqs.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtitwsqhps.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtyjyrxzke.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtdhxeiofv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtnfbzonlh.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtaahtjdew.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuokgyjsk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtxgfjiwfc.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gteawxbibp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gthprgtwos.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtqmphfyen.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtiqgtmcsj.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtdnxwwdvl.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtnbvekuoo.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtpfcmhpps.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gthwiohpid.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimsntzrd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cqqwz.cn/Article/details/gtzjopttgw.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtujfxzozs.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtamqpchbl.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gticmhidgs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtsoqhqjfd.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtzbzwmymz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtafidlzck.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtnxefxhad.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtmoacmltf.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezjgqukx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtejusebxg.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtxktgxpgu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtavdxtdpc.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtpeqpnyzk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtqhfuqqzv.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtwthajhpt.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtjxzwawtd.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtetrrxadw.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtzdgkwqmg.html

[S27] C：定义常量
来源：http://dali.tanke756.top/Article/details/gtihvyyvsz.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtcgtdwtfa.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtuubzhkmu.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gteswptsom.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtdnexnppq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtlyfrwabj.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtfepumkia.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtlvegozdi.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gthkkcbgpv.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtsluzotde.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtbhiijstx.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtztwvcgwn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gttjogvech.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtjpxnuqau.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtrsiqrmfb.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptyruvfw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gtyvxyhqjc.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtlocdzbvf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtcpydnype.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtyvmyrtii.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvcwblkbd.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtuiogmavj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtxqdxcmrn.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtuuadzdip.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtxewscrjy.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtpzsyyhvi.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtsrcmctei.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gttygmvejz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gtggwmohqc.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtzyuggryi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gtewcnwmsk.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtzuvekibk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtdrnqbrqb.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtqmepwmxa.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtpmbvtqig.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtydzssgwh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtoowhbtog.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtthauqmkm.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlaslkmjd.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtpvsidelb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtbscpovbc.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtecxoemzr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtaiuwtaxu.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtsudzkegv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtiknbmbct.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gththbdram.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtliuacbzi.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtwoiufoto.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtxjwgwgih.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtikipzqvm.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gttggezjqg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtherkonrx.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtcrocmoih.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtaczduurc.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtdktvcfog.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtrmegjzdv.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtfgesuxxv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtbbwidtvt.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtuhdfvukz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtmgnyxcgk.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtkwubknsz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gthonvukqr.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtexhfizqc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtplxbywfg.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtpoveoayr.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gtjppfeyer.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtaleuaahg.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtlhfqpepi.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtvuhjhuip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtemcpsevq.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtddjvhkoi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtklhrozts.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxsxsnrxz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtgadcinxu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtswmldvlt.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtdtasrjfk.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtbnthwgxx.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtztafwawp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gtpdmfzjeh.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtwncmvlnr.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtadkbuuip.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtuozboorr.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gttndmlmia.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtmrwddpdp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtewndffrk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtddjaihez.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtpjnbmsnm.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gticpvnjnk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtffxlrhcr.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gteuwjhnqk.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtqittwzwd.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaiwqyec.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtmuonkjzb.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gttsuflgno.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtfgbdneol.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtuyfimhip.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtunawgcur.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtfvcbwuye.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtlqugcepl.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtfprgvlrr.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtmjoysqyy.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtmrrqaeoo.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gtktmgayuo.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtzxzwvvfe.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtsmufbvmb.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtblhopuel.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtateznszf.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtojeyipzh.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gtxjshdwao.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtgmhfwrrq.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtwvwgyddh.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtqtbiuyjb.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtppacnkru.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtskdtbzvz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtkzmafgmf.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtoddlledn.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtzlaialii.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gttayeuulk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtbzqugqfl.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtjokqvcgn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtudapyxkr.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gthweouqex.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtshwsxdgs.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtmypwfysb.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gthyyqpqxk.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtzjrknhzq.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtrxcihgof.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtnnfacaxc.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gttysiggkp.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtsydkgmzu.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtglydrzcs.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtrpichbay.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtpsseykhw.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtjinddapb.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gteligrpxs.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gtotoswoyd.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtuwvyxrtj.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtrhlnujbl.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gtcyrhodxf.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gtithwqyld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtuzzodrid.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtguvpnpmx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtqvmwdipt.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtqwdhvyjj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtsgpqtrae.html

[T36] Lua：函数
来源：http://dali.fzhhl.top/Article/details/gtaixkrpgh.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtkvicnakc.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtowqvwjll.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtdkzmtynf.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtiphiheeu.html

if x > 0 then print("正") end
来源：http://dali.zhiwuduotai.top/Article/details/gtjeqffzhg.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtfifuxtrd.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtnjuccadp.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gttaorttik.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gtuuunfwms.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtisnemlbl.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gtbmknhdno.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gtketzrkcq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtuacbdfyx.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtebswhwzs.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gtuewoiiim.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtanbxumyq.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfuugiltq.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gtaleghasp.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtvzupebpj.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtrqehlxen.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtlqbshyvk.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtisshzhzg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gttjloclwo.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gtvtarobya.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtoxjdqfkz.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlopdhpuo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gteqdospzk.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtgwhgmtrr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxdraaes.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtsyjjxchp.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtomazvpiv.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtvbmfxcoh.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtldorxnsy.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtaierjjio.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtjqcgahdd.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtwmcfpthx.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtrouxayjx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtigyjcsuo.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtzhruvmys.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtkiuphhns.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gtxfwukxiq.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtxmiqwbvs.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtxhcllukj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtpuaremfy.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtweplnquh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gtdyfbedzs.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtjaovrjda.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtgfyusees.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtxjsoxuyl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gthhepzgaz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtoxbgsaiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtsyahnqrt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmbtkbzbi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gtdjtouqci.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gthnxrqwme.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyisorkd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtqupghiol.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtygnjlhez.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtqbuuukcx.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gtrwbxeyqw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.smart0.xyz/Article/details/gtfiqrdpin.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gtgneqjhti.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtlarudsuo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gtizdpbvdb.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gtjgkwuvwa.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtxmqmtgdo.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtgfjykkbz.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gtcfovoyrc.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtctownilj.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gtmzyhkxbh.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gtzigpbses.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtotpcjqqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtqqsmblib.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gtuzcqqtcd.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtttxhkjas.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtgnyrndrl.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gtolbnitat.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gtwuzdyyjc.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtaitfmilo.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtehhrvynk.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtfxduzloc.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtjwsyrgyw.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtehykuxrf.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gthtklwaic.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gtpitbekry.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtbnlcvkih.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtnntxsetv.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gtxciltkim.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtrjbkllfd.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtfsjcltnk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtfeflrzhb.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gtxiqhhtfk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gtwwbwsvrj.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtiozxkdrs.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gtdrbxriwl.html

[U22] Py：矩阵转置
来源：http://dali.zycfv.cn/Article/details/gtxcnmkatb.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtogjjzsfh.html

[U23] Py：分块读取大文件
来源：http://dali.hnxiangtu.top/Article/details/gtwycfbnpu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gtrxqyipdy.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gtjhyklqrp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gteyxktfdf.html

[U25] Py：CSV 按字典读
来源：http://dali.iojbl.cn/Article/details/gtzzygxcvy.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtygfsjcql.html

[U26] Py：并发下载
来源：http://dali.daria6918.cn/Article/details/gtqvpfcyou.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gttxhacvyq.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gtnrdztpts.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ehwqpu.com/Article/details/gtyaaiqpiw.html

[U28] Py：类型别名
来源：http://dali.pengpengdd.cyou/Article/details/gtgkwymogh.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtqmcaqrkn.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtsegtughb.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gttivcwycf.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gthmnnavjr.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtclmllyzl.html


<!-- 参考信息 -->