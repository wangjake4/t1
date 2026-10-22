代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gt2vjusqouq.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2xdzqvset.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2gsloixol.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2zzinmbfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gt2lrhsfkhy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gt2kqrzxlmi.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gt2difbciyx.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2lualwwef.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gt2pfpgbayy.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldeggorw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gt2jvtssoni.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2wkekjdsi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2uulodlzd.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2oicwfjoo.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2szzdqztz.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gt2mlldvgrd.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2uosygwqx.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2cguhuhxm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gt2xufmxaae.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2fmijvavo.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgrsuigo.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gt2gufwybzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2bfmeubkk.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gt2qmmqpifw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2mkakxygc.html

[S21] C：字符类别判断
来源：http://dali.birdmap.top/Article/details/gt2fupisfvx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2ekvsnxeo.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2veriyfkx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2efwtyoqf.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gt2qozuugty.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2hodreekl.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gt2hvxbhqhi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gt2zieotzct.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2gapojybw.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gt2zavjulxn.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fixabzhp.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gt2yekosbzq.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gt2tnbxcgqa.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2zepfcxnb.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gt2tdrtvyqf.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofusqmxt.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gt2sycgwxuv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2fumbpzzs.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gt2dxjmsupw.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gt2omrrfsio.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gt2fjoqhoca.html

#endif
来源：http://dali.yj202588.top/Article/details/gt2hznmeuvp.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2azllyxaz.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gt2rpadobat.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2mwinfdve.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gt2ibushgye.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gt2wdqeywcg.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2ufukskti.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2iszqgobc.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2qaatfgwa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ygduksox.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gt2kdrbsgzn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2gnwlswac.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2gfoxjtkh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2abnnamvb.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2loguxwve.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zutajest.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2aolivfra.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2ntpzaxhy.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gt2hkllydca.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gt2esaxkvex.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gt2cgqqofac.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gt2mpbhgbzg.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2oliyrazw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gt2zbbktmga.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gt2difukdxy.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gt2zirzgyhd.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2mblsnxqb.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gt2hfxgsbaj.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cygdsucl.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gt2dwzzcajr.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2nbpneikm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgibabgr.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2vzxoybpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbsishic.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecjiqwya.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gt2ntceydns.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghnmbnxv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvqxhygn.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gt2flkrhavr.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbcocevk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2rdtsinie.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2ukqawhdq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2vfpttfgc.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2lclpsfin.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gt2zgqxnkzx.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gt2aphneklv.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2zamdhlsm.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2fgnsywmt.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gt2xhbtpezq.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2viibmftc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gt2lxtvucat.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2pakrlynq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gt2qsearfjo.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2jlafoetz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2cbgxmifi.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gt2xadatpug.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2ygykjhqt.html

[S58] C++：命名空间
来源：http://dali.shzxlz.cn/Article/details/gt2lletlqmo.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2noniolsi.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gt2hqzbaqvh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ivvv.top/Article/details/gt2kclrugzo.html

[S60] C++：遍历并删除元素
来源：http://dali.jiagoushi.top/Article/details/gt2wqlonwas.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2tsxngnya.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2gcgynubl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2yzrypvqq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2owggbyop.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2lfymidkd.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2qrbtlnnc.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbfnvxia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gt2pvptjpel.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2avhqpazz.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2lyvyyemj.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gt2ldnqmgom.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gt2eqmvbiqj.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gt2venhqvql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gt2tdxvtnrt.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2mththqlx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2rocdbeyh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2cpgbtekg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcocrczg.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gt2ctkcxssn.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gt2orxlabtj.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2tyzroxfz.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gt2rnrejlmh.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gt2aerbneou.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gt2inlqgmkz.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gt2czlfyger.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifkxvaxy.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gt2xuztscth.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2whldyzuu.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gt2mzczgfgt.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdwnqsdy.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gt2sagiwgmj.html

for (i in 1..10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2zczaeuvs.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gt2gjtifzbx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kroxsmpc.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2hxgxhvxw.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2kqllyrve.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2azjbonfm.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2pwistcnl.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2xcrwhorq.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gt2fjgeamao.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2dhmyndme.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waotwuad.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpgbdpvi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gt2jfsjbwfy.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2dpxvjxfi.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vubrsnid.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gt2kueqrhro.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2dxllafws.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2cksugptr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2eqcgjhiz.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2njolrwpo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2ibegxhcy.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2xasofzua.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gt2zundcbrr.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gt2trnmgrfs.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gt2ogofvoag.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zholhbxj.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gt2nofaituk.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gt2kfjvsllk.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlofvgvu.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gt2clchcidm.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vahlhcnr.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gt2rofqydzy.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gt2gsokjtln.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2rmvqbwuj.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2clnrjupz.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2afrbehay.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gt2ukzqzvhj.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2eojeqkwm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gt2duebkmpl.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2xiplqjrj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gt2etvasfwp.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gt2kwyidfci.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gt2zninmsvd.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2zupllvzg.html

function add(a, b) return a + b end
来源：http://dali.gotoacloud.top/Article/details/gt2auofckfj.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gt2woilzvww.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gt2evazxfye.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gt2btykdsme.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsaslxdq.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gt2ifwnucha.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gt2izpqzeiq.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gt2zisxaeyc.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gt2rkozapde.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2evwgkaur.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gt2mrwcitlt.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2mxynaxvb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gt2zvgtrnyj.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdooxibn.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gt2tqbgsuzk.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gt2dvjamcsk.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gt2bdirvalp.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gt2rkzldhyl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2raqudywt.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gt2vxxizyok.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2inkgoyfn.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2sbzjhbat.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gt2otxegdwj.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gt2wzacwjin.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gt2szzwthak.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gt2umtexoot.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2meywlbct.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttenfzcm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gt2ctzpupqr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2adbpljmi.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gt2noefsyuu.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2gmyvccqn.html

[T52] Scala：变量
来源：http://dali.yj202588.top/Article/details/gt2ezpzocwh.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gt2rvxggcmv.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2akfshmff.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2iarlupvh.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2sajvwyjz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2pkvryrgm.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtdpuxbk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlzfoevh.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gt2angneogx.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2sjtftgrw.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2olvhgfet.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gt2cklrzumh.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gt2itdjdxxi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gt2bjbdvmgx.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gt2bbmayalp.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2hbllqour.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gt2pnskwbvq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2ougjavig.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2sgiwsgyz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2lynuibai.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2tzhbtugg.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258.top/Article/details/gt2orrtogtj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gt2vcnghnzq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gt2cipgwqnr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2alvwlrml.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gt2nnjhondp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gt2ykvtobgc.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gt2fmaxetzc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hzctwtju.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gt2qmrgwkwa.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2tkwhkxme.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gt2gkdxejws.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuickmlm.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gt2gijkrktn.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gt2ngcghaan.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gt2anhlekgi.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2uewwkkfp.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2pnnmtnlj.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmfuatup.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gt2pdpiqmnr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2oteataqw.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2vkygvrir.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gt2cwctjzol.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gt2mqocqijb.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2toitjihu.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxscnnhe.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lydxvyqe.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gt2dkimglbx.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gt2cmoqzvtx.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gt2gqqdaacp.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gt2gtphmlnn.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayghyarh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gt2jzvfnuwc.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2othaaxzb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gt2snsdxxjt.html

[U18] Py：预编译正则
来源：http://dali.jinqigfzy.top/Article/details/gt2cxtsiltn.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2rxbufuyo.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gt2vhebjkhf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gt2gkgcuhhr.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gt2lbsaxqwh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gt2kgttkmbi.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2gngvdgyz.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gt2muaxpldc.html

[U22] Py：矩阵转置
来源：http://dali.hnqzz.top/Article/details/gt2hufclstx.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gt2rlyjktie.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gt2hjgccqxw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gt2vynsphdx.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gt2injkwkjg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gt2mhauxkxa.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gt2xvvxixbz.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gt2ohtpqemh.html

[U26] Py：并发下载
来源：http://dali.ppjwa.cn/Article/details/gt2ugpfivcw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gt2jnewateq.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gt2whlqqivp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gt2uasxiotn.html

[U28] Py：类型别名
来源：http://dali.aibaodan.cn/Article/details/gt2rckzktmb.html

UserId = int
来源：http://dali.tian-w.cn/Article/details/gt2wytkjclo.html

[U29] Py：属性校验
来源：http://dali.zhongyouzk.top/Article/details/gt2ounhxyuv.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gt2uwkmkull.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynctikye.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gt2sztpinff.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gt2xaliroxr.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gt2mdzwvsrb.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gt2ldldgsta.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gt2yxsvlrtx.html


<!-- 参考信息 -->