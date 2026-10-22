代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtglhqcqtm.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtuewlwmra.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxvefqaf.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtvnwfebpt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtkfevqtrp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtaugvwhmm.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtkstyjfqs.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtemwqgjdm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtuhpkiiml.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gttesonotn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtmkcshxjf.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtpmkibcwm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkglcuuj.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtaaekpcfn.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtcqhnbgaz.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtdgeedapc.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtrdjnawce.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtmdblejkq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtlrxszrcp.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtyuzjtwmk.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gtcijyggza.html

[S19] C：快速排序
来源：http://dali.tianlin.xyz/Article/details/gtexgfgfnf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtgauygiod.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtwaiwxkdw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtrvbnnrmh.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtbgwjciyq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtmvzrizjn.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gttungasrp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gthiydfucb.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtzwqpkcie.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtoxbaupkh.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtyujkdbwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gtdvaybjtc.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtlolztfai.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtxtikqiwq.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtltxrhijy.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gtuqxzphal.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtnulcvnxv.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtxmqojhtn.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gttvzlnquk.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtvdibqovc.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gtwszpvdlj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtrzwmfxsd.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtkzahsfyi.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcowgntqw.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtrmrwoftu.html

#endif
来源：http://dali.zycfv.cn/Article/details/gtffowwxxs.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtewhqrkqi.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gtnehsokdx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gthyhvotpt.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gtbncizrxe.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtxzdtbwxo.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtqzpsyfox.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gtqjzxnpky.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtxauqmxml.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtwfminxyy.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtmzlqchun.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gttokjuacp.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtkwgqtoxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtbebvuiig.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtggwxwifw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtunhsdzve.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtxygcyazc.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtjfxbpmxv.html

[S39] C++：自定义比较器排序
来源：http://dali.yonumen.top/Article/details/gthssvszqx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtrqmkyuzb.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gtdyfzzqun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtpmlhbwcd.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtjjpganrf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtgcvtmddd.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtuwfcbmzq.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtbgjbusyv.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtbzqzefne.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtthfgdydj.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gtjmlidtgy.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtjlzskajq.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxihleiwp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtqikxkgvv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gthpxyldbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtekwsnboq.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtytaiebdn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtxbahkxcw.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtixjwhuht.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gthonintfe.html

while (std::getline(in, line)) { }
来源：http://dali.sysykeji.top/Article/details/gttjjzyvdr.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtpnnctibf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtcdknraas.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtfrjgdzqw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtrhkctgkg.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtqndcuwlo.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtufvwngyk.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtmsxhtzdw.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtoulswzst.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtqcjsbpgb.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtqfudxhkx.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtywsadxyy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtzeomshli.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtlmehtelh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gthypvuswx.html

[S56] C++：optional
来源：http://dali.chenzaomai.com/Article/details/gthobbuqea.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtymruohjs.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtowlmlfyc.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtgskhpieo.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gthljdvfej.html

namespace ns { int f() { return 1; } }
来源：http://dali.redwolf501.top/Article/details/gtzovebtzp.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtpfhohqar.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtfaqddayc.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gttvoffcbq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtkdyyggwk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtdxtemdfd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtflwqmulj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbeotvypu.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtjtjshvvl.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtklqzaxxp.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtbltndpzg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtohdoysag.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtmazluutp.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtuemclrct.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gtstyqkiyk.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtqhiebvmk.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gthzmpdigg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gtzcriakkd.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtrclqozaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gttyccsmmb.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtzeypdzen.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtuumkphsh.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtlrcsdpyw.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtwiaoubxs.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtizytwvnq.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtfwodhcke.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtoctlauvg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gteyytnzne.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtosxjeslp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqvusnqk.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtkyvcnzva.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtjjwkwdkk.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtpqxijqug.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtpyfmwjcp.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmyuzgvd.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtbanbjiaw.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtfohiscnr.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtlavvoxjj.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtsfnhqsdx.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtwmuqanzi.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtssnsnife.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtpapmvnvk.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gthndwjbqo.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtvsagdnvm.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtenlwekuu.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtintftves.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtpkdldaqz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtsekqkhnm.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudtuktkz.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtcaznxeqe.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtwuiexitk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtbqwbsqqn.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtdmypnouw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqinywsnx.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gtabupsdtr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsxokopz.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtnhkyssuj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtvaaxwtsn.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gttfwrstmv.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtpdswabou.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gthfijyvya.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtlnddasti.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gthojjxfca.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtdwsjhrvv.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtmusvmoxv.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtxubahvxa.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtebzblfbc.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtcuhltasd.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsubocwyu.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtzhrztnvx.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gtsznhkdkw.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtlhnkorhw.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtihkgzmfa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtbtupnepo.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtnjesxobq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtkmnpfgdh.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtejdtppdr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtzlmoddsx.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnmtianwa.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gttdbkgvxi.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtnwyhqumk.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtvtmqgxsa.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtdsrdalbz.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtqywmisxf.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtwqaeofuw.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtfbjdvufj.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtueznzbhs.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtiziczkix.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gtcissudca.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gtvfpkcixj.html

[T42] Perl：变量类型
来源：http://dali.ivvv.top/Article/details/gtyvhijzwo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtngwzlvyw.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtscosivnm.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtyutlawow.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gteduutged.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtvbnrwxzp.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gteuopmtuv.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtvgnaexup.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtponmdcau.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsuxbukye.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtymkxifoj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtledyehyp.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtbwmdiylh.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndcsujev.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtscfrdzqy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtkttyfudi.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtkfdvphvg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtjxwtqkgd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtkgsarmcm.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtgfhpqzzm.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtmsbdfwaz.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtfpfoyahl.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtpfrwyckc.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtykopijug.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtpkbcblpt.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gthxpypgax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtobsowwtv.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtqxloakaw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrntwyvp.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gtbnbvgxnl.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtchvrrjtm.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtkpybymil.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtwknuonvc.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtsnatfqvg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gtofdtqdqw.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtgryysufu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtlzochpyi.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtswrursoc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzynacuok.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtmngyrgqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtxidaxyha.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzmnquskj.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtmgotikmt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtukoqccrq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtkabbatrt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtcsrubovb.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtzdmnbovn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtcgyqcniq.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gtajefxosd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtfoivhano.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtjmnejqmf.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtoqxywsma.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtxytpzeso.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtkgqmtsot.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtafnevqow.html

{v: k for k, v in d.items()}
来源：http://dali.yvedp.cn/Article/details/gtgpyamcmm.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtyohauurt.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtmmlclwqa.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtssatfabw.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gtfqohxjhw.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtydbbxmlj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtxwuolcot.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtnmtnzvcf.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtpgqttyxo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtpsjebyqy.html

Counter(arr).most_common(3)
来源：http://dali.0kj1m.cn/Article/details/gtlxszcaxc.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtvggmxfty.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gtbndoamvn.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gtrigfyatb.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gttjkvdplo.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gtnahgyueh.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtmpyafeil.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmddkyvr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgufenzy.top/Article/details/gtjldweqwb.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gttquybgtr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gtyffilvir.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gtlwmbtmjg.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtvatdzxfn.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtztcrtosk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258888.top/Article/details/gtecueslwa.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtqakwaeij.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtcxxcfouo.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gttgygnxvf.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtnchbfqre.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtttmktchq.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gthextsfuk.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtwjuirlmo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gtfscgmtbt.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gteywailgy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtlddhbozt.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gtuqvxftqw.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gtzvekdzhi.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gtzlghrkhf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sysykeji.top/Article/details/gtzjphltog.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gtgjbygzlb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gtscnvwkiv.html

[U28] Py：类型别名
来源：http://dali.zdqjudy.top/Article/details/gtpfsmgedn.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gtirglhytd.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtplewjehe.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtdkkbcjru.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtzhkuojtz.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtxxgkejdn.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtkabimcxo.html

python -m pytest -q
来源：http://dali.vqdsnc.cn/Article/details/gtyhezdmqd.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gttgucaibi.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gtjyypqwnj.html


<!-- 参考信息 -->