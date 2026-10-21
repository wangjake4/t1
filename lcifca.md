代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtcepyibig.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtsrdqozvz.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtuwfiiqat.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtqefobpkv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtdtxariyf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtijdfxihi.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtgupltgah.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtrexlccuy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtimoxvfqy.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtonchxekm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtaisflcnp.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtpyjgutwl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gteqqkjtzr.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtganaqqcj.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtbwummiwr.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtrhvfxyev.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtzjkkaios.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtdipesmij.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtrcgnfeqt.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtatlhfmhb.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtlpcekgqx.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtdlitjogj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtokurjlol.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtgutksdsc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtccmwxjgr.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtgoabxzxk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtweckjqsw.html

[S22] C：字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gtiwgyczmj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtstvzadwg.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gtrybaohjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtvqlgmvou.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtwfuibkcz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtfqsewglp.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtmqejzemz.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gteazfdacx.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtfvzkzcsl.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtbmneltah.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtordticzm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtrtnyjnlq.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtecsyuvnh.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtjmcbykev.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtosvnvgob.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtohpgaghb.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gttknvjpqx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtsvsilsmw.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtkgaqoxar.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gtcvqefsqn.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtolevzvsg.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtgshmiohv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtnmrbdbcb.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtdvwnfccq.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gtaykvxyyt.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtardwtesd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtpooacdqu.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtoqxmqlvl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxcocgpm.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtmlaquheq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtspwccyab.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtdrfjnwnm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtecusbvxa.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtiftyaiqw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gtucfdnims.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtrelfmdik.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtmxyjkctl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazvhgymm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtnwsjxipg.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtugxqmcqz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtpbqgrrfm.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtuwrihhqk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtdcbojcxq.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gtcrrxegud.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtumvgcsam.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtpebaqluh.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtpiokfslx.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtlftygffa.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtmtfuitbt.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtvmbbnkhh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtunhljzqs.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtusqslifs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtkechxgay.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gthyylwarg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtnoloxoys.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtdhyrtdcc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtalglwbad.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtzoxgjstd.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtlxlajmag.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtepbsoqse.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtzhskylht.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gttvgbtzuz.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtobdapeom.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtkxxsfbqr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtqtzpaknn.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtbygrtknq.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtngpbflqf.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtlnuzevkl.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtmlcfmkul.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gthriynuvt.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtlysydqqw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtknjzmfhb.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gttzijydma.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtbvdngsda.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtrrueknif.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtcucrqwwg.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtsmymgqpm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtpgjulrsr.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtnmuvvouq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtvdzjflxr.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtfcywwrbv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gtbjhaywny.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbpmfwqzz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gttrwqlwyp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbtltapjm.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtzgkquxun.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoxdaknd.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gtzdmyrlcw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtoebbbmre.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtruxqgbnh.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzsjyktk.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtzjbyiqcx.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtudgfrcyi.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtmonqdbdc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtyvckqglf.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtghxusvyz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtqqelvwuw.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtazwtxtun.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtocagvkbh.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtpqtedjgb.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtjdjdywom.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtscybgsjd.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtergkjasd.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtdtmjcynp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtjxnbrsmc.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtvecggjrt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gteqbwrxdh.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtgpithxqg.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtkoprctik.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gttaqrjsnb.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gtgsizyxtv.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtzdbxraqf.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtrgosjqgd.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtklmakgwv.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtfaehloha.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtxjlhhxay.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtoixetjep.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtxjvthnxo.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtfwyvkmyt.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtfcqppaxw.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtuhllsoni.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtabadbcuq.html

if let n = opt { print(n) }
来源：http://dali.chenlongwang.top/Article/details/gtwzgngkho.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtmmhlgiaa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gthrjtdcpa.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtudqlrjiw.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gtulttdekj.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtxdypxcdx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gtdpihrewn.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtqthlgccb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtvfdkokhm.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtsnvqfjvy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtxxvzxhuu.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtnermkbtx.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtolmpafpl.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtcieefoai.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtdijzpepb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtfugmpzwz.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiiyhaqf.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gtiflksjfg.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtmoroafdj.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gtrgokregl.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtlqolyssm.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtblixzwot.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtfspevfwq.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtilnyxyup.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtubpwoqcq.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtmltdozgc.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gtyvtpxxad.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gthhvntuhc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtdnegrexj.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtplwcuqtq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtacujscwj.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtcgejamuk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtcnnkoayb.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtcjmllyet.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gtmtbdnvou.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtbzwmdgjo.html

"a" .. "b"
来源：http://dali.ppjwa.cn/Article/details/gtsryjezhx.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtejifqlnc.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtpvqxvlqk.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtvtokyzsc.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlwgllnr.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtctnghqrp.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gtfitczxbc.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gtvhtuxgvu.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwqlqmut.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtnvzrtliy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258888.top/Article/details/gtrekafeix.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtykxkfruo.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtiluwmdmy.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtautarpjq.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtogzswupr.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtupkfeffg.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gttwqduuvy.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gtbegccgjb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtgqzvoplb.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtepnvwunl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtndpngmjt.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtgvhrggch.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtchacqgob.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcobdsypo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtuipwfccf.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtzlmbpvoy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtjftzzdhc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gttcmvepmw.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtxaqckrxm.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiezmrocs.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtwsxehxcq.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gtapuhytqh.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtfkxfjvxo.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtffychkcq.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtzpqvyuxq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtnrzcosoe.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtzuhkglgr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gtsrfdkmwi.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtnzdbcynn.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtglxmycdt.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gteilxykko.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtclzifcoh.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtbcwkinhg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtfnkvizpo.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gtdbghcukf.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtezhnpusb.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtkgwaddcy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gtuiowfhum.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzbajpuno.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gttuhqrpgk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyzwuxdcd.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtxvmjdzsa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtbydlttjm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gttwekggyr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gtcfwtlvmc.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gttvjvecog.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtbfwamyuc.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtvsspduul.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtzjcmrilt.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtsjpyvuxz.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtiowgyxud.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gtqhqnbalp.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtqlsbzxkl.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtwignbvdt.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtvcfxhfyw.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gthfvqoqus.html

[y for x in nested for y in x]
来源：http://dali.hnxiangtu.top/Article/details/gtefiiqzbu.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gtjydrluax.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtmweyosmp.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtaofcwgrj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtsrdptggg.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtfevfiopd.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtwgoqdzxy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhengqikj.top/Article/details/gtgyaiahnc.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtbhrucbcc.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gtkvdfnwbi.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gttvsqhlll.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtrfnjlcyv.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gtbgcubceu.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtloxmlkip.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gtsrnnkjsf.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtczdedyxo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gtdtnlnjps.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtwizembsu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtnncqpjyp.html

[U18] Py：预编译正则
来源：http://dali.cqqwz.cn/Article/details/gtwtnkfuyg.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gtbhduvxup.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gtnzxiyllz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtqsrtjjbj.html

[U20] Py：缓存函数结果
来源：http://dali.zhongyouzk.top/Article/details/gtgbvibels.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenlongwang.top/Article/details/gtcxpiswol.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtdznuuztc.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gtiexgvkot.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gtyzlikfqc.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtrdiyxnka.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtixjdjafr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cdnleiting.top/Article/details/gtawcgasnu.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gtpifydteg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtjzgfbcoh.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gtkdvfqojf.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtoihlpofh.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtmqkhghhy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtmddwmfsb.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcfymyzw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.snrcjt.cn/Article/details/gtvwxaanvm.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmjuzona.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gtqjfqxuam.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gthihannkt.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gticzsgscr.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gtnizljewq.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gthrcexzwo.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtjrrbrvwd.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtwkgizjhj.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtqabkfvcs.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtmmpeccdn.html


<!-- 参考信息 -->