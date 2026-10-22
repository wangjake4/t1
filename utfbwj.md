代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtfroinwhw.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtdekngkvz.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtljrjtqyg.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtjpgyuain.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtklbdzuoz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtcggpxiff.html

fclose(f);
来源：http://dali.birdmap.top/Article/details/gtwxkqpuok.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtnthgtwmb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtrqmpzlix.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtogokwpcs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtswmfsjhv.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtfqbteiyd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtnzcdieux.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrdtlbrw.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gtkiohrhxj.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gtkergikhv.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtogiaiksr.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gthiwaxzpe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtknnmsbyg.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtjrkaokfs.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtqsehtgod.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtssvcyvvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtjpwioaqi.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtoxvovich.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtnnnvjnim.html

[S21] C：字符类别判断
来源：http://dali.ybcxt.top/Article/details/gtztrvcofe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtpajovnhg.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtcagogott.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtnwqcvwsa.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtcumbrjcl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gthuiowlkk.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtartqgehd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtdpcpzhqz.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gthbnplnaj.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtnwnuhqjt.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtrmoiumeg.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtthgxphon.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gteudgdbbe.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gthbknyryo.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtxqiblbqy.html

static int counter = 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgpvvgya.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtlpxayftw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltxqqtja.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtfptcgahk.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtzvxwxsxy.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtslamarok.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtsgnclzmu.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvvxszov.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gthtapurbe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtlirtonhs.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtqmhgsmmd.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtowfxdise.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtypywvduv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtuvoocblk.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gtjfjdwkte.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtmbogzzms.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtzqfoczvk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtlxqbfvbu.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrbieswv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtzrjboxae.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtonnsfusb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtakkmplfr.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtvtfggyzt.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gttptlhilq.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gtettlokvw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtfriwfrbb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtnsmzrnvw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtiibecmcx.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtxhrsupgl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtozwdeggr.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gthjjrgqsa.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtgnnoyabl.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtkfdgomvr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtjmhqtwoj.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtfuxvpmzr.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmpnkmsw.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtchrrzlyg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtdifhgrbd.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtqsxpdbkt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gthiuofuph.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gtqnmvadht.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtdbnhddpp.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtxnlfanib.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtmeyzwros.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtfnnyauuq.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtwyqjrxyl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cdnleiting.top/Article/details/gtlkqzfepn.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtoifjwljk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gttimffrtz.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtnumoothu.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gtedqccxao.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gttbiuvdeg.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtkorjheke.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtpyleeavv.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtbxrkpvak.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtfvkvhojn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtviqzbttp.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtouvhyoly.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoylrevax.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtovyontyi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gthspeldcj.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtiueuvnah.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gtfmvjoker.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtaclnwhgz.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtjyyaopct.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtpxolbhbr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtbxmbfvgw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gtbxofugne.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtigwveken.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttzumbrbo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtdvgvcohx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgoxqgbdq.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtnjqrxons.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtrjmjivxi.html

[T02] Kotlin：变量
来源：http://dali.tian-w.cn/Article/details/gthhelekdk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtrzevvklq.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtznkcodbm.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtazhqryqd.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtoothlmep.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxlatdwu.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gtmnwnfcuz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtgsowapgn.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtbluzlrxo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtruzvkvzm.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtwjefetgh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gtuapgwdhj.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gtkmzwelgj.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtptmohxjl.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtserajscc.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtzniegedd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtodleuuea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtxpqitngw.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtugkfcxgk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtzdtghbvr.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtxbvkssjk.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtimdohmie.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtnkiqidtr.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpfgyvcr.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtcugypunp.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtuilszfap.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtouijwdpf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtatoatzfj.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtwnodelvt.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtghzrzcfr.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtaebbhgks.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtrdtnksuu.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtbxvjozpx.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gthhybvyqj.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtbhmqnsco.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtsyiacucp.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtxznvvqkh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtxnluubkv.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtlbpubjil.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtjgznfpsd.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtyfocilnq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gtlrugtwjl.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtybwtjxda.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtvwtvsndf.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtgoataxbc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtgtrwmgcg.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiuzuufu.html

struct P { var x: Int }
来源：http://dali.daria6918.cn/Article/details/gtsaxojrhc.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtmvsyxmtj.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gtmokcdcbb.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtdlwbotia.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtmaufaszp.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtwnersjgp.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtejhhanbr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtihtxjnlp.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtitzphjik.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtxegatzqr.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtkbvtxqic.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtlonlktoj.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtxlgimmft.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtfnojtoie.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtljxngsdu.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhsgmmfn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtmoboapkg.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtghwnzlpe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtkpbfpklu.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgyhvmfl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtllhnypsa.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtnwtpwpts.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtuyxbobiz.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwpnwuui.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtwiklafjb.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtzhqdjnnk.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtfktvzpzv.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtkjsagqfl.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtedjcfjxg.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtucgiijof.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtcdppednf.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtdoewabhe.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gtwyhomyrk.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtmmtoaddu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtovdclmnj.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtwjpwrywp.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtgvofopov.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gttjmwnxgf.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtwbbkosji.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtudhmidee.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbguodxll.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtyqvubzjw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gttihqievv.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmlmonao.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtqcdxupxs.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gtjhvslfzw.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtnhxzahgu.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtqppdcyvp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtglixnjih.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtzlarcffm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtdohpamao.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gtbktpvobd.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtqcbcajvt.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtvxxqduih.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gtvoihbrpr.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtuuybnaqm.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtondhvygo.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhxljvuv.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtesskqbmy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtrkkdecok.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtddqvknho.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtlouyqstu.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtyegqatbq.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqklzxeje.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtjuloquqo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtgarvbxuj.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtwqulbsqw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtkbwkuycm.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtclwwdxej.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtgzffdkpx.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtcowfioub.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxmuxjyv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttijxttbp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtolismmkl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdfvnbvpj.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtjvvrqwzq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtgzgofwzk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtmshcgyfp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtwsdkxthq.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtdgdfmjzg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtyfdlxdtr.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtnwqahhpf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtyzbrxzjs.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxmhjrpo.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbdretps.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gthtzsawdu.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtcxqltznc.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gttotakfmk.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtjylzxsvp.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtffywhqds.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtyzmjmset.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtfbpztudq.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaluiwru.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gtqwenoasq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtcesunvtj.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gtpzjreftl.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gthfbkdifs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtfhqogrjx.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtkgnfmdaw.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gtcbjocqhm.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gttqbwdixr.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtlixnktuf.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtggtlqazj.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtyfxxeslo.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtglwdwteb.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcancond.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gtymjtjfna.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gtmuviinje.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtpsbznjek.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtidzpaiyh.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtaesrjahq.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258.top/Article/details/gthillqwxu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gtxmbsxriw.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gtrvcbtnyj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtbsapbiov.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gtoafkxlxb.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtfrktwqfb.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gtgoigomtp.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtfdcqaoap.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtbpgbxalg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtzkajwoir.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtzvyqorhx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtcctrciqf.html

[U25] Py：CSV 按字典读
来源：http://dali.hfpthk.cn/Article/details/gttihrvqao.html

csv.DictReader(f)
来源：http://dali.cucudq.cn/Article/details/gtdylcaqnu.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtcjduaxvh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtbbvakbvb.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtaxxdvptu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtdpbtjqim.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtiznpmwkt.html

UserId = int
来源：http://dali.sxryk.cn/Article/details/gtmjbbwatc.html

[U29] Py：属性校验
来源：http://dali.gzhubu.top/Article/details/gtpieeobkm.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gtiriynzrq.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gttiaqgpaj.html

@dataclass(slots=True)
来源：http://dali.zhengqikj.top/Article/details/gtkudmmgmy.html

[U31] Py：单测
来源：http://dali.zhoulong.xyz/Article/details/gtluuccbko.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtqlwfbwwx.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gtoosolnxw.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtncfswloe.html


<!-- 参考信息 -->