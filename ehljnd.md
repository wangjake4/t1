代发 wailian999

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtxaqdcouz.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtnwtlyiqz.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtiowyylfv.html

[S07] C：数组遍历求和
来源：http://dali.jqgfzy.top/Article/details/gtymzqawha.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtlpuhtxsb.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gttinstqzw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gtjfsqczdc.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gtqvmjggvx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtcekidxiq.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtvldroraj.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtmtnxpifb.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtbsozlbkz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtjularchu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtrpiynxfi.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtjlctkgjq.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtmlvaxdet.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtgyztoief.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtmjiilowo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtudntfycw.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtgikhbuyi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtnyncrqma.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtujdyirkr.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuyfevfd.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtovukvabe.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gthsdpgush.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtztihrsgf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtvqvtiiyh.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtlrahvmjj.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtvxfrjsng.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilmcmntn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gttvincrhx.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtnuntjcfv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtsddczpll.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtprkpgwut.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtajtfawel.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtluvkvoom.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtrvfkjute.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtfenmobzc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtliqczijt.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gtzbavscxs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtsytkgfgz.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtnxmxmukr.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtgukzkqmw.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtmrktoujn.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtpzfxxvgf.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gthcfzongp.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtoefylvpp.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtxguzekav.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gthrgbosvz.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtlgopmxgz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtttkjrjwb.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtzoeofesy.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtbnmaxhqh.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzpohjyy.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtvdclpjcw.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtzygpjfet.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gteekzhlzx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtuhipmmnn.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtnnxcwzfb.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtbicwllrr.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtbfaosbep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtsbacnsfv.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gtndojpife.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gtepjbiibs.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtmlfhylhw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtwljnrszg.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthelnrahg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilkmemer.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtzrsyhzlt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgufenzy.top/Article/details/gtnssouxra.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtzepvipon.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtxouzautm.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtxblhnzny.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtuwjrytgf.html

[S40] C++：查找元素
来源：http://dali.wangshuangyany.cn/Article/details/gtmlslqvap.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gtjgciktzh.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gtkmlhjnnx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtfswenumi.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtoeblidcm.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtnqkzovwf.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gtmxmrekaq.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtpwotsefa.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtdhaosqla.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtnxxjfvwf.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gthiuomsop.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtgoobvpbm.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtqpckvdab.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtsbantyzw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtfqemqews.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgxotfuw.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gthuhybhjw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtjyikgjst.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxmdfqjm.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtqrhgqodu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtvswttpbg.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtchnfonqd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtglffmrmm.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtrkdrawkg.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtacokgdol.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtepadczzf.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtwwomcgwz.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtqgyezsmb.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtcmzgduxf.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtuejcygvs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtfpjcjkbv.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtokprolfx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtnddabvja.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshwvkwta.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtunvypznt.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtalimuxhd.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtgnfmgrrm.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtnmffjyiw.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gttznyyuyp.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtjsmpzfve.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtpwayvuya.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gtwwqqwtix.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtwxwqvfac.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwlhfgbbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtqgmzmels.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxbicjqzb.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtwflicsgv.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtfgolndxh.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtrnfypelq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gthrdcmqee.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtdfvndfto.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtvbexlfov.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlkuobhk.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gtxrmvrvdl.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtvrukvwxj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtsixxaeun.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtjudifsgq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtuilheqln.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtmbungwmo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqwtskmd.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtgnxhcsyi.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtjmmuwozx.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gtrffqdobb.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtudpxvkfm.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtminlbbzw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtdzlmjlbi.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtrvctvxgl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gttrtasdmw.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtegxsifee.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjhkhoeum.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmrcnknb.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtbpsnikuh.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtovmpfedi.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtjuxfeyon.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtuumptrxn.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtfchhlcoj.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gthjqonlyq.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtrwyotwju.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtwhedizyd.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtbxbxeasg.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtbakgvmvi.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtzuodmhbp.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtdxcordrg.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtomyqhcdt.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtnapdhivs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtmavdohqa.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gtharvleij.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gtlufaeonl.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtinwmlkau.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtaefkighq.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gtadfvcfoe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtpoksmapp.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtrnrouuct.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gthxjzulwz.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gtsohmhhcs.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtncuutqxh.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtqmuanlkg.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gttowavryx.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtdlsegmhl.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtwivoktwl.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtufcyjjrc.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gtoizmouyb.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtaluzwlwh.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtyudtgziz.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtxuccledo.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtycjdzjxl.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtvudyygwn.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtoowcidza.html

[T32] Lua：局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtfatjntjh.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gtynfbqfdj.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtvgaupcmr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gtmnuaabia.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtbenrtspk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtehqepctl.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gthbbvqixw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtmhzyvkco.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtgsohljqh.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtyoudfryr.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtevwwoegj.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtejflduzh.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtmgvarvsj.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gtlurfmwkj.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtixpgtiap.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqktavog.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gtpyztaoko.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtiuztweeg.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtpcrpadct.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtayblhrzu.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gttsuzxgkz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtlcohlfac.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gthuptdqha.html

"值: $a"
来源：http://dali.0kj1m.cn/Article/details/gtzmnsshuf.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtvtqyotum.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttntihazg.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtwjsczljs.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknfahzng.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtbiydrzyr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtetnxrvei.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtdwfrsyso.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gtqynesccr.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtusgfwqbz.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtvcdfwvpy.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gtcjyljwmw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtyaajntke.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtyxtjjnag.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtaezzbnfo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtmwbhjebs.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtaqxveqfl.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtsgigsyif.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gtviasgegj.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtsbnzqura.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtgctfcgwg.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtmqswzgmk.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtwdbsvzme.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gthpusldkz.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtouaebmuc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtxcizitau.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtfxrlbyaj.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gticqoacis.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtbxxhexdo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtrwkemfgw.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtilucsofh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gtkwmsmzsg.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gtkwlcsolw.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtcaklyebs.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gtimsorwsu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtrawfblkm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtnjrrdkmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtkigjghxt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwvgrnzql.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjxwzjij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtgcrdckvz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtktexlufq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gttremkuiv.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyladyhwc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtmraziekn.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtvjkcxtzd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gtqazicpeb.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhxuamlf.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtfpdqqbup.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtjublydtc.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtvzozvgej.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gtjhljasqu.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxmtyruk.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtaghexzxx.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtmklzfyou.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gtdbduanga.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gtpfzhwulh.html

[U10] Py：按值排序字典
来源：http://dali.jinqigufen.top/Article/details/gtbyqqvunz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gtbnvbzqoo.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtxhpeuuzn.html

(x * 2 for x in arr)
来源：http://dali.birdmap.top/Article/details/gtzelltxaz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gtdpldxoho.html

Counter(arr).most_common(3)
来源：http://dali.meibo888.top/Article/details/gtqfqjbawj.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtmnxbzwcj.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtbxtcqspi.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gtcdecbtld.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gtsqsrjlbs.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gtsdlqruai.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gttbjssksd.html

[U16] Py：命令行参数解析
来源：http://dali.xziqi.cn/Article/details/gtzdzupwil.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fengsongda.top/Article/details/gtnpcdpwkc.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gtxifvxxvv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gtzkosplbr.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gthaiigluc.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtjdkklejc.html

[U19] Py：正则替换带回调
来源：http://dali.nwbrower.top/Article/details/gtynxaswms.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvrjwtzg.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtecegvgrx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtjspyoxsf.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gtagiffrot.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvwvifdp.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gtxtxjofju.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gtjbwlmtuz.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gtooigpefp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gtsgspxmif.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtvatkifei.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqlexmiy.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtqlkwsuqi.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtcpyvqxao.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtefxtsrsb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gtsjrehxbs.html

[U27] Py：异步 HTTP
来源：http://dali.yongpay.top/Article/details/gtopflxeze.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtlmrsmiog.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gtayciohjx.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gtobugjieb.html


<!-- 参考信息 -->