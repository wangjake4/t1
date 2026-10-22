代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnqnqijy.html

[S08] C：动态内存分配与释放
来源：http://dali.ivvv.top/Article/details/gt2ipogidvf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gt2gomeodfo.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2zfjdiffr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2usjjhwyo.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2lqubexfh.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2dckdizzu.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2qmyscbwj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2cunrtchk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gt2easkrkfk.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2urkvqwct.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2xmeecrms.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2glhdmjgy.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gt2qrshowhj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2hwtrpkag.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxxwmfxg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gt2qtzyukma.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blprijpg.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2czzrkisv.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2cmxulsmh.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2vnawseqg.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2vvacssaw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gt2uwothljb.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2uxgegfrr.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2fhpftisu.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2qcheskdb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2bsnfdodk.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gt2arzufcol.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gt2airbaxdm.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gt2bvtctoxp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gt2xhzowvng.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gt2pbbualwm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gt2mjwdbgbm.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gt2jinfadkn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gt2jituwoby.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gt2cqxbltfe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gt2ilrcvcuf.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gt2owoeaefj.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2zpbhfxpm.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gt2bobpdoex.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gt2ieorpoko.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gt2zzawaccn.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2fosriuao.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2pleysubo.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgiencsc.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gt2comhjice.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gt2xdfnpycd.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gt2quhdptfk.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gt2asoygkvm.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2fystfyof.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2vawetvym.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gt2npvddgmn.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gt2habqsvqz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gt2tpssitpk.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yeajczln.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gt2qzoikncd.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gt2eluzehuh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2wbwebbqa.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gt2basuxqmn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gt2jjbkecwt.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2ltxwprlx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2amvqaseu.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gt2wfnsitxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2sqrfbnel.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gt2iygtoysr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gt2xzovtstk.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edueuotq.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gt2khbjjnlu.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2lgnasowv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gt2dsgryjiy.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gt2jbzremvl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gt2zhkwpxzy.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2fcloymjl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gt2syqmmmoj.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqdumdjj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdfnzhwm.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gt2ltuwzvgm.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gt2bdjipyqk.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2lvlrgxjz.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gt2fjdjdgna.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhhvogre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gt2gruqamjt.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2atudejsb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bwfossxv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gt2skikijnz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gt2sbukwkrx.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2uffkuzhe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2raqzlfbz.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwtapase.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2vgilreoo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2xnufpvmt.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gt2ryohzmlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2ddeqiaie.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2ifhfifmi.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2scbcpaqz.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gt2iapdlcqk.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2ifudddck.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gt2fbuqqrtk.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2dizilier.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2uereqjqt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2konncdso.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2dasbfuku.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2trixidit.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2iltvzigv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2puhnspyn.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2rwvpilnd.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzkfvuug.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2kbhdsxje.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gt2uetuipqi.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gt2xtguavwy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gt2dzuqiwvt.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gt2vicqyzqc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2uxaqkjsg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2krzbfljs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.feifeiyinyue.top/Article/details/gt2btjxspba.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2lbjyixjt.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2xxfqnrbd.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2rodfjezy.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2vcmkhbqe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2diliqrjk.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gt2oqfwtjwx.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2jhavbreb.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gt2gsoyixwt.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gt2iadlxdpn.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gt2pkqcugxf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2njzrcpxb.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfjijgqc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2kbmlobop.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2qqymvryr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2tyhrcspq.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gt2ztirhhhv.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2jicqpidj.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gt2dafjzclv.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gt2nraoocva.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gt2zspeywgi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gt2hnenismc.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gt2sjebafhc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwoqjaix.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkeuburj.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2wiancgvx.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gt2bteirxtv.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rxfjrppm.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gt2fwicewhe.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2inmagyjn.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gt2cecypino.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gt2wavaysxj.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gt2unnrydti.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2qwzhovix.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bezqwicz.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2hhlkxpbk.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2aprgmbfd.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqnrcxne.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gt2mmqwbvtr.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gt2yngbynfv.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gt2vqjjriym.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2wzeizyel.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2rhueyzrz.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gt2ofjotrww.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gt2lazqlloc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gt2pjfijing.html

[T23] Swift：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ivuhpoyz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gt2hrduojrk.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gt2chwukxqg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2kttcjqim.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gt2dgeuzfjx.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2xhuszavc.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2bbyhvckz.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gt2vrwylaog.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2gldhbfhq.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gt2edjvldqm.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gt2lelifbrq.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2oqidcdtr.html

[T29] Swift：guard 提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2icufieuf.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gt2supsptcs.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gt2ftkspenv.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhdbmcua.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2lzzdrgun.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxiuqfzl.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2ymezlqwv.html

local a = 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2jelkghci.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gt2flggvbap.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gt2ommttrak.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2umzpckxn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2oinhfjee.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbwyaoac.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2wksxmrzt.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gt2axenhttq.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gt2qbenzerf.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2ojqqmpxc.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gt2kikrvueg.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gt2qkbvvrrs.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gt2idifxqgt.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2jhbpbdhq.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gt2rfuuqusy.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gt2iwkfybfs.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gt2alvepkwd.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2fbykizkc.html

print "Hello\n";
来源：http://dali.fzhhl.top/Article/details/gt2flqpreex.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymqahxiv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpsretrt.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2irsonyyy.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gt2ylunhsdn.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gt2iuldsymk.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gt2ymgwbmey.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gt2lbqqvpcm.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gt2ikkjojuy.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2uxeenvyr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gt2lzygaxgc.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gt2qichzqwv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gt2tjgkwnpz.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2woqziiyv.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gt2hpohyiho.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gt2apuxkfoo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2vqzjqdkq.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2dcmxmmab.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gt2lhmvsfcg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gt2eruitbwm.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2mbcwruil.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2aqvuhnxb.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2bevqazbb.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gt2zwkdyalh.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2mblsxkrg.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvxsorhp.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2cfvqvvei.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2wucdzhzz.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2mdrmdfkv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2epcrdxns.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gt2xucdwafd.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2brppgedj.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2lwumiawo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tklralpl.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gt2qhaojphb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gt2szfmxumy.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2xlvqanax.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gt2yqxhhbrf.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gt2evaauzbt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tryzurfm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dgigswha.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2negftlav.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2snryjbhd.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gt2egdsudmp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gt2sdbfnixr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2ggvkazkq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2khdxysqj.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gt2qopkykmb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gt2fxokudkr.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gt2uordkcgb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gt2avhmravw.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gt2hgzbbpij.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gt2lzkdndep.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gt2qahpkswe.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gt2wrnezkse.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gt2fupgmddg.html

{v: k for k, v in d.items()}
来源：http://dali.sysykeji.top/Article/details/gt2yqzmbihi.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gclmxwvr.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gt2bdtrbnfb.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gt2rezuylwp.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2fepyfdoj.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gt2aaptuiob.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shzxlz.cn/Article/details/gt2mvqdhdqd.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gt2ucwmaqph.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gt2cyrqaqvn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gt2aeyvtxct.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2lcxyqngd.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gt2yaqmuvda.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gt2qmwyftil.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gt2wrossdin.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gt2jyuazgnx.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gt2aifzwdfs.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gt2vugtvzvv.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwbrszfb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gt2etwpaohz.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gt2hdtslply.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gt2zrsvfkao.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gt2tmmsjglr.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiavdhph.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbwgbdvy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gt2tjjqnpew.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gt2sfbadfzu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gt2odhyujpw.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gt2ipwvvidq.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gt2pigwilym.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gt2imgmmaou.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gt2kywmxvcz.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gt2vwrsbayn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gt2icwxaayp.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brsxxkfy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2jedztkbj.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gt2tsgdngiu.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gt2gjcvgqgp.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gt2hivwskyu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daxiang520.top/Article/details/gt2xgqupbfo.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gt2yvhyhthp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gt2lhfuyrse.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gt2tjgljkcf.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gt2kzmkmlcd.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gt2tedmtgnl.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gt2jngfsrpt.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2pfwsqpni.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2djzieceb.html


<!-- 参考信息 -->