代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtactylcvq.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtcsmtkyqe.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtrxoaxlcx.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtffgbkqih.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gtjtgozalk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtiuwfktid.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtytuuopri.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtvmpchnxh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtwilbzpef.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtfoorpqfw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtsvpmubri.html

[S14] C：枚举
来源：http://dali.yonumen.top/Article/details/gtgkxmwavi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtqqhhurzx.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtxuoannlg.html

(double) a / b
来源：http://dali.tianlin.xyz/Article/details/gtmbwhwqqn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtknowivjg.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtxcrxvemh.html

[S17] C：安全拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtbrwyuxua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gticngehbs.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtsnkpigmz.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gtkgooiqpi.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtuprundrs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtvvzillbb.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gtmabaywet.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtbbjhxfmr.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gtmchjkwgj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtjsabwsix.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtvjvrcsam.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtozgytpok.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtcnuxtuas.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtrcjvnjeb.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtxmgmkpri.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtevfoqtyg.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtycrajrwd.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtawqmaaod.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gtojjfllon.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtrfxiiguk.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtgxrduaal.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtuuaxpcud.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvzktqtdk.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtockhobgw.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtralsinle.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtqnahtbsu.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gthvhlsjcr.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtjsxayyzn.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtupkrnqef.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtshxdavtk.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtnazfvckq.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gttdxllvxj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtmaybbdxy.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gtpowhjyzj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtfvqzdsug.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwynsndno.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gthebuvrol.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwqmtbiw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gttzzklnjp.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtwzwezbql.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtgaiuuklz.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtjyvmyhyv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtrrvkvsid.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtypvdpswr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtceqrcwhx.html

[S38] C++：排序
来源：http://dali.guannengcc.top/Article/details/gtuhskilzp.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gtsnqczuhi.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtgmovkyht.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtxlwnrgic.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gteokmxydy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtutfkpqhd.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtodxycyxn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gthbxpbwai.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gtajelxoqp.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtsbajykey.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtzyombxmb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmhvghzr.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtcqbdrnof.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteremaloy.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtggtfmiep.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtozcdtlul.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtawhkjsgz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtdblkux.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtnunuupee.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258888.top/Article/details/gtwygebmzi.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtpitckqny.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtllkzjcvh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtsuupozgi.html

[S49] C++：写文件
来源：http://dali.yangfankeji.com/Article/details/gtgsncyytr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gtqrkqhpyy.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtzenhvqkz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtfoupupxu.html

[S51] C++：显式类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtaxkczwgn.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtwdoruhyf.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gtecgedzvd.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtwczcklaj.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtvzftpokg.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtximjfuqc.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gttevdefjk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtwchzhuiz.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrtiketb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtsjpsdqce.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtyuzfswxo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gthhlbczvc.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtctdwxbmd.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gtxwxdkuop.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtibhbtuxl.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtkxwilews.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtwvhfothh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtxtsczoio.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtvepdcwbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtytavbzcu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtioeqensq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtnzpeiylb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmjoepwvp.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtxvfpsgzp.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtvgrxnrym.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtqlrrgqsz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtkgkqmdmn.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gtuouihzue.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtsfofmxyb.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gttezjccoe.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtftovimpj.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtzrinamev.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtwjrvjgdi.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gthgeaeoqg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtxrvqprjd.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gtuukblois.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtbpnpitit.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtsegpodwy.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gteekdpdwm.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gthqsamvtv.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtnfwpqmtv.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtcosdsdlj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gttpgitojk.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtkcfgmchl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtvuvmqwuh.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtacclevqy.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtckydodvh.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtgsepmaxi.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtuczotmqg.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtwmgudxhw.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtjhtvuqrz.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gtsnjfhnxz.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtnnjydzft.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtxokyztsx.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtgicmyrro.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtevtmnxor.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtdbleywnl.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtwpgataaz.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtyqyddupz.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtzwizzlyf.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtcviohiag.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsyaeble.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gtsldtqvnq.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtxjsuucrn.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtoodgqpvb.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtllfbjsmz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtruuldjbx.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtwmzqliqf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtvaghqxhy.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtapqjuicu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtrkdeqnem.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtbwouwcmx.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtiepdazyx.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtwrsrlpyp.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtnkgfzgij.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gtlsacemiw.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtwcrdbzxv.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtswecixxr.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtbsklkrlh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtftuxxlot.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtbktxyequ.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtntrcwklb.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gthgnpvihv.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtvdrlyygj.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtqmeieqhh.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtjxvmxyvb.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gtwmexculd.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtgjaauupj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gtpdiqrnat.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtpebomzqp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gteoquioiv.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtblftnvta.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtyrtajmla.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gtnisdmyjg.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtsrwrptwr.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtgglxjgpk.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtjvyuggbz.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gteqgqqdvz.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtxasnofyp.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtfldsrbtw.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtpcmwkvtg.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtnbsoinxj.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtxynigzhq.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtlqdzaunc.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gtjvlagaua.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtkfswwvrm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtvlxbjgfd.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gteqcpekjh.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtpuwqiort.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagvfvdqw.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbkyvutrl.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtkvgefmmj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykxgajrv.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtbofkknpf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtwqrgygat.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtsoedhytv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsbuqwlq.html

[T48] Perl：正则替换
来源：http://dali.meibo888.top/Article/details/gtkyshvcam.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtmxjqrtdm.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gtmldradqe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtghuafxwd.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtudroixnp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gtoawrkrzm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtjixphtdh.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtmlomhkri.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtagihjdoz.html

[T52] Scala：变量
来源：http://dali.zhoulong.xyz/Article/details/gtjwcxvvtv.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtfxdsbtyp.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtlvjerove.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtjumuxvwq.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtcrcjpskm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gtlyxrnhiw.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtsfoznwwb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gtaittnmqd.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gthgusfllr.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gttpxgfdcm.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtoxusvjju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtkywblltz.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gtsfmwdfqc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtkuudqids.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtxipfhaan.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gttygspxke.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtviffxbza.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gtoulqljui.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzudsixgi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtpiwxijbe.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvzuzfvpc.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtsjticted.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gtynjiprlp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtyrvpqvij.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gtaajsfxxy.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtmdtpwcjg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtdmwxlpgi.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtgikeoirj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzekuxpb.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtirtmwofr.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtefomswkd.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtxirdfrpk.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtucsqwgcd.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gtsushdwvh.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gtqksvvudk.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gtkqaydlni.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtsqqnyhsp.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtfnqtjwvf.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtplruoydq.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gtlykzvngk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtqqzkbxre.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtczgcctcm.html

(x * 2 for x in arr)
来源：http://dali.hfpthk.cn/Article/details/gtzrjtmzxn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gtrqdyhxqh.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtwaigxyha.html

[U13] Py：固定长度队列
来源：http://dali.guannengcc.top/Article/details/gtqxtkkngf.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtcqbkinhe.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmmlgqvl.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtcrrltfde.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtxcjcyobf.html

t = time.perf_counter()
来源：http://dali.xziqi.cn/Article/details/gtgsekkbpi.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtbaquwemb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtxzxhfqmg.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevswwwms.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtangaqlvn.html

[U18] Py：预编译正则
来源：http://dali.c1oappe.top/Article/details/gtlvldakbd.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gtbtdujgpn.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtsgclhblu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtouppqiff.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtmpdwmpuw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtgpsbesiz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsljwgyn.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtwyaajpza.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gtxatdnclz.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtsvsdfnzt.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gtvfqswtsz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gtwtloreaw.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gtrzzwdeyx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtbiowaaom.html

[U25] Py：CSV 按字典读
来源：http://dali.tianlin.xyz/Article/details/gtjqmxkpbi.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtosjrswxk.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gtfuehlffx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gtbwjczkrv.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtjisrmvpt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtizrsccwi.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gttumszkbp.html

UserId = int
来源：http://dali.zhengqikj.top/Article/details/gtcvlztrzp.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gtriryetyw.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtcfiddhsc.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gtksvngmme.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtitligigx.html

[U31] Py：单测
来源：http://dali.sweek.top/Article/details/gtxcyhajgi.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gtprbtzuyn.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gtmkazmxja.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gtbljxjlrg.html


<!-- 参考信息 -->