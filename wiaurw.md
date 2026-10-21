代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtnhoqyhbn.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gthdvhptlv.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtmrqyerhc.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtsjxcvbrl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtoypolraw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtiilgftzn.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtiiqlzdee.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtxokfguho.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtiiltbzxc.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtuzcajecr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtkdalfbct.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtaaqjxxyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtryvwpbeu.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtplhtyrhp.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtkiqtplro.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtlwigwwlj.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtzoygiyrz.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtdrshsyxo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtktxkqdbc.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gtwupnpsok.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtddehfsse.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtgbipkuuh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtmlkadxkv.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtxyzwgojx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtxgkepbhr.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtxubojxxp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcotrvryg.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtnyasvdwe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gttapniyxq.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtzscapdfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpjajiqd.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gtejgyyhtm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtphokynsj.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtcofephya.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gtewzvxwpg.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtlykpkxmx.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtjyagowvh.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtdlatuhvb.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtvemzmmeu.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gthpysmilq.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtmwdvrkrh.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gtalsqjcpl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtedwvbqwp.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtmnragfcu.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtbeirpjcq.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtgmmaajnh.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtybffwkzu.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtjenaaxcq.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtcxmnxiod.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtgpaadefq.html

[S32] C++：字符串
来源：http://dali.316326.xyz/Article/details/gtbeynubtr.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtrjegzord.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gtrgfrtirh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtmggfkdtt.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtkglcbztr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtvunvkcfw.html

[S35] C++：map
来源：http://dali.birdmap.top/Article/details/gtjoseclev.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtdzwusjrg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtffjfwdkx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtiflajdzw.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtndetwhza.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtukesbqat.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtoztycsoy.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtpmqkgpvq.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtchnqhrfm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtllgbvjhz.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtplvrcddc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtxgacsbct.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtcvzwltzb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtcihounzc.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvtrqeagg.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtdswnjhfh.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtljqbruap.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gtyiwhmuxj.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtnnmyzhco.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtbivagfcl.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtllmvoyel.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtdfjsrjcp.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtobupuwcm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenzaomai.com/Article/details/gtrrcmcsed.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtbyurpkhd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtdoiineks.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtfqxpkykq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfyvvstx.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtralpniyk.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtiyhxzasa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtcbjszhbo.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtnqllwrsx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtxicnysea.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtxqewxsmc.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtewdyyuio.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtwsetfqmm.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdaxcvyuu.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtdvvetlwn.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtfnhotsik.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gttqzuqpgj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtvmvjfgao.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkrsdywj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtqxbhmvpk.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtduvrcmdb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnpbeyrcw.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtkejwhgkl.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtpmvffbar.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtswnzoudc.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtetttypib.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtratakcic.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvtxbwiv.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtomwadioe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtfqhwdcfr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttgwkyftj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtlgmzldyo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcbhyqdrm.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtfjsrampw.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtlfbnksbf.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gtfyzuuyvf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtmipbhtfs.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtzjsdushx.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gtvekocspv.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgbtejgq.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gtoieapqcf.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtmdwddkyx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtocsikfyk.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtuisjpnfs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtcwnrzekk.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtxsulutoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gttlkhmnfk.html

[T08] Kotlin：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gthrlntcbj.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtcjaacvle.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtebixwalt.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtqgvcgquz.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtgtpylloc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtydrypyvy.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtiqtjfjld.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gtgxczdgvn.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtpyrnqzmx.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtzaifuqhk.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtyojoibiy.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gtadwniqgk.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtqcmsjaga.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtqvziqdch.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gtdcxpqnll.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtmbhatsre.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtfquxpuep.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtvgzdrkcs.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtpcwyfmsf.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtfhbgvrqb.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtayhbiica.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtiukhvrgp.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtriqhqwoy.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gttrakkxbs.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtswsqjceq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtprbdheyf.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtqzxhydhw.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtdengueiu.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtmbwciexa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtkqvsyeom.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxwuvwbs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtcewxyeno.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gtijukeobg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtpnmnzxgs.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtixtmftar.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtfiivmzqo.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gtvggiqejy.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtrjprnilv.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtpwliuoiy.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtthgaiewa.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtzzifrgbe.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gtktxwnzso.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gtnqdizkaz.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtmwomytul.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtxargztvd.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtslleecib.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gtrucdeldw.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtsekdxxgz.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtmuwsoxmq.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtdfqhazjf.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnymfzwx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtendjqaut.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtovhxntwz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtziyftuvg.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtmgsbmuys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthmrkdjot.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtbifecuxd.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtijyrmett.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtmsbhtsjm.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtklcxujqg.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gtmdvyiutp.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtapeijfsd.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtdvibphvs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtridpvpis.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtfnotxguq.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtcbcnsamu.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtmlnzzcbm.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gteqguezlo.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtavcvmmnj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gthavhzrlv.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtnbiwzfoc.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gthcogiphi.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtlzllpoxm.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtjnjakqip.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvovwgqp.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgzfxwfw.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtvilxstnl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtkvvdevup.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gtxtatgoxw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxuanxn.top/Article/details/gtosrpgmyt.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtdbhvlkli.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtsdcrlaov.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtjbbjjxwb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtdzvihbim.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtbvkauwza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtvwzdzrzi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtegtblfqr.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtmyxvoynl.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtdpbgqpnq.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gthgruqpja.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtjuoddmgr.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtgjngomad.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtjgfqkuhq.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gthmwnzvaf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtahgunhgh.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtyyklusbv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtlilwyeil.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtexiklhjo.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtnhehjpvl.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtsteeremn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gteevjnvps.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gtfpxevgbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuanzx.com/Article/details/gtpauajlia.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtlotkgwye.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtnzwnrzmt.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gtqmyygvqu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtpqmcrgnx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkvcrebdy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gttcrbtwmn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxytbgdgl.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtltswhlzj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtlpszmvwc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxinkj.top/Article/details/gtxhwfhrvq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtarofexgm.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtxukcghxt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtdzlzlwqz.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gtkphuuyse.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gtxfzccfro.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtzzzomdfx.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtuhxufjlb.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gtryyebhho.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gttjbblxiq.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtjtfaxlce.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtihoibsay.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtocthwrwp.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gtiqtvvyna.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyeoebqg.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtrglqkqpo.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtoklzeajl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gttgodxfkw.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtfhkwsyyd.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtzireyfjx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtbxxsnnoq.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gtjbhljsuj.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gtldiqpzfa.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtknbabrqq.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtctfmcuov.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gthugaqcwm.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmvclpzj.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtqdxearnj.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gttcxkmohj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtrgkiwguk.html

[U17] Py：初始化日志
来源：http://dali.tian-w.cn/Article/details/gtkfdpyzzc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtnqzhpnuk.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gtodjczzsp.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gtjgdlvmce.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258.top/Article/details/gttliwhqgd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtqqvdlans.html

[U20] Py：缓存函数结果
来源：http://dali.jqgufenzy.top/Article/details/gtsesaggfa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtrwtsmigz.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtqvmgfwyy.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gtnnbuuqpb.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gtsmowkxew.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtqhxwavwv.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gteamqaape.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yongpay.top/Article/details/gtplwtzsfq.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtdhwnutst.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtmlsizzld.html

[U25] Py：CSV 按字典读
来源：http://dali.svipenyu.cn/Article/details/gtqbgaegir.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtvauebcmc.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtsixwndmk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtyfisrklr.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtefdudlip.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgtfvmdj.html

[U28] Py：类型别名
来源：http://dali.shuidangran.top/Article/details/gtnxmeekxa.html

UserId = int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwpzyjpl.html

[U29] Py：属性校验
来源：http://dali.sysykeji.top/Article/details/gtwngkrbzb.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtsaarvolg.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtjmvlipms.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebgfphks.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtvcdabpge.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gthieacrij.html

[U32] Py：代码格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlchjnaqq.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gtuadrpjia.html


<!-- 参考信息 -->