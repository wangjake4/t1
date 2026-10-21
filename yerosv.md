代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gtwvqarozz.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtqfbjzezi.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gttnjnhblm.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtuiqammzr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtxoudcusd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtzlhwyzmk.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gthrnvgnkz.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtuoxhitxy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gteawubkmd.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtvtduixac.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtidbjrxgx.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtjgkwdnan.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtfmtgrxiq.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtmqukvcnu.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtwpprimfx.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtsusowhzl.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtyvldkraj.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtuxheleod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtqaeyumga.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkrjqkvp.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtfbeqfyjf.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtwlfuungt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtnllbakaq.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gtbfocyrnc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtaauvazko.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtubefkybt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtdkxtrfqv.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtxfjctgzg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gtfsbuiocn.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtnefucvfa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwiscjcp.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtmkogysgr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtfoqpedoa.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtvojouqyh.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtclmmnfrb.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtxsyxcnwb.html

memset(a, 0, sizeof a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaoafuvy.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtmzcstyul.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqihvsktx.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtjdkyrmfh.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtcivdvrls.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtwgeqdjzz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gttdxvuqdy.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtwnaiflia.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtknihoncu.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtghqyowyu.html

#endif
来源：http://dali.ivvv.top/Article/details/gtbuofujry.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gtitqucrcs.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtdyozettf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtgspyqrcg.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtzbejzmor.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtvgkxosri.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtpmqtmzcq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtigzipfly.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gtjunpwtcq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtekyekfvt.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gteinphftj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtsnrkmtaf.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfdbdikz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtqbbuawqd.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtaquzinkl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtchexwnsn.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gterwbssyy.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtmpggkjfy.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtddldpyjq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yueranfly.top/Article/details/gtbmgtfiud.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtwgmmkmrm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gthcvqiuwm.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtupewyazi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhiwuduotai.top/Article/details/gtocziifzi.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjgqjxed.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtjqgrqkcw.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtqdsswuhs.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gttejbhaxq.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtmtlzecxg.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtroaazbvw.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtybokxrvj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtguprytsi.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtjujrfxzz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtwzqoqckq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gttematagk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtyusypfnw.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtjgxoympk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxgayvua.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtrsfgisbv.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtszhxwojg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gtsknlooaj.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtneihavos.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtxrmjkksc.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtepqtnowq.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtaernyjgi.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtfurzhwmu.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gttsggaqka.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtieopkwgy.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvruaqdrw.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtphlqaqjm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtlolmcdhk.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gtejynqirh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtatqgcyvr.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtmkeeusac.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gthejyaanq.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtfmmosyyx.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gttmryefrl.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gtllopdwxk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtfrikkjap.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gtfqxqabct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtclzmzywk.html

[S60] C++：遍历并删除元素
来源：http://dali.shuidangran.top/Article/details/gtrlicpjex.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtcmqvqktt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthiehscdc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtqgsomdfy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuqivwdmt.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtshdusuqu.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtmwxbfeml.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtzozcjhjy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtrpfdvswd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqxynpvp.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtzphqwxlk.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtxsipzwda.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdqqppvv.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtncbwcgne.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtrkrhqqnp.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtebrpjoyd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtuthblccu.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtrfgaktvl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtcqehmter.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtbqmplawt.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtctgmslqs.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtduiilrlt.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtvpelyuih.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdupbnxzd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtfnnlvwhu.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtctbgoecw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtthywaaca.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqphjlvs.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gttezjruvw.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtbmahjfsj.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtenwmpolq.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtanrxalju.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwztgurbw.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gthkheiegv.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtlgcqhnrs.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtsycreisa.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtomjwjmuh.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtzgiubpsz.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtelvuntfm.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtnocumkhg.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtngdlfxmc.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtvdmrshro.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtfxctcdmv.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gtliqevyiy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtamzboijc.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gtlkfdzvhs.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gtulfroeop.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtlnrttucq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gtmkcqgtdu.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtanlmbgse.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gttjejboiw.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtbttbbgcg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gtrytavcjy.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gthrdrojqo.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtieqassvo.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtyxplmbwn.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtnbuazbwj.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtlvnlerlu.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtoljfmztb.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gttrpdixgt.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtdbejqrhv.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gtzwtczrsj.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtbunigwkl.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtbnkpoexz.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtqvcpmzty.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtfxsjxvze.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtdtirsjjp.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gteaeutkfn.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtdiajxkic.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtfbscmims.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtsogjqvhv.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gttkjzmhwk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtoqfdogez.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtgopvciln.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtxkmkbpuh.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtsnceubkx.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtxqxumoif.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtzsxbklgp.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gttovlhbna.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtoatccqxe.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gttowbjoxo.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gthwnrtyxb.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gteffyzwhu.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gteryksotn.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtxfehvrzr.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtybdahavf.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gtwpijifjp.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtptmkspda.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtrdkxhsmg.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtncoqnnvi.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gtyyyiumjn.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtrwohglkf.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbjenmqx.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvptazciw.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gtfpnknjbp.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtqsjwpupd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcenlevwo.html

[T47] Perl：正则捕获
来源：http://dali.gotoacloud.top/Article/details/gtmtdzhsqu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtuxvdbbui.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gthhxoufum.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtzjulcdvz.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtdvpaaoet.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtgsrapftl.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtxjoyrsci.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyehdwix.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtywiqxbbk.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtxsiwzpgi.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtoyvuqwyl.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtsrpilexo.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtqqbrhapp.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtlkyatuug.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtqesymhrj.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtetjzrwbl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtmnmybtlu.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtpmbpkgyx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gtviumjcjm.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtpwxbloqw.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtngyunfuc.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtiodbctiq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtyvomqyrn.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgzirins.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtigxrxcqd.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtemqcwoft.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gtfrqmwyjh.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtpcjobwdk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtytylteze.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtheazxbkj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtxytyewqn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlfmxjfzx.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gthybltshk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtmqplnqtl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtbdbxijdy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtnumgowbq.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtmiimioab.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtepazmifd.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtekpdzffa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtvpylwlrr.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtkdefrlkc.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtgjpbqirx.html

[U06] Py：合并两个字典
来源：http://dali.daxiang520.top/Article/details/gtxiirzikf.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtellgoygr.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtriycxogv.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtftsvtvob.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtyzvkzcrx.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gtdbunslas.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtlriqisat.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gtupnsylrc.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtcxdtdxed.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtkspqadkh.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gtozlfoeek.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtejjncxix.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gtftzcuver.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gtvgvuijtm.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gtelkfhhlt.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gttvpwzcjt.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gtghewgaph.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtmiunjttb.html

[U15] Py：高精度计时
来源：http://dali.iojbl.cn/Article/details/gtgylrmove.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtflrcvycg.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtlgmbojsk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtlddacsjf.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtboteottf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtgmetufzk.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtfvfalwlw.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtqjngqmld.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtiyrvqfzr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtikfbtyix.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtrklpjzix.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtimbsfirt.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtokaexcog.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtaurkfiwq.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gtoqcaxiza.html

list(zip(*m))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzipycaw.html

[U23] Py：分块读取大文件
来源：http://dali.316326.xyz/Article/details/gtrwrmisqu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gtfzqguuko.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtynfaabrl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtyrmwvetj.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtiqzpzslb.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gtwhyltmim.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gthhnalksz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gtrjhdhlcs.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gttroylauc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gtzwsepqcx.html

[U28] Py：类型别名
来源：http://dali.ehwqpu.com/Article/details/gtuaivakih.html

UserId = int
来源：http://dali.yongpay.top/Article/details/gtusodwrac.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtglvskvkw.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtspvipnrs.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtjstyvanh.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gtemlsqhqv.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtyszrbwdo.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gttlwbsncx.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gtizlwmcio.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtjoszyzle.html


<!-- 参考信息 -->