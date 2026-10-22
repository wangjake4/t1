代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgvpauvf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtmfvkkmrm.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtfmcyatrk.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtfjvsoalt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtwlqiwdqj.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtprmcvedb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtbjslghde.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gthqmoymkn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gthtgbnobx.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gtwkpzowqi.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gttuyrzqfy.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gttxzpucov.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gthvvqehkc.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtukcqpobn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gttmcnznfs.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gtsliyxcql.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtqncnckvy.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtukoplaic.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtpxflpezr.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtbpkdfnbu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtmqsaikcz.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtqvbnilvy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtgndrjjjo.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gthhdvsawd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdndqfpkb.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtpolfbwbf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtcfbcfuul.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtidvqbmwm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtfzlabppd.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtidcurvqe.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtfyjsjhms.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtnmsiamri.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtglsffecq.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtzakallye.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtbirtczlu.html

[S28] C：静态变量
来源：http://dali.sysykeji.top/Article/details/gtzoyxcpdv.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtefgdecxr.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtchcomrjm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtadpiklyf.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtfdqliswl.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtxyatdbxl.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtwnyldgac.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtqplpmdfn.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtnuvgpvdc.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtgdojjvdq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtuulesrkd.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtaxpenild.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtxdvwxwth.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtmaorvzpr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtpfvwotcq.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtcmkgtlkh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gtvmplgwss.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtgbhnumoe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtdcjnqean.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtqolrdecl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtwahuxukg.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtrmxpqoza.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtlceajscw.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtrltxlxqe.html

std::sort(v.begin(), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtucapfwly.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjerqxax.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtusyugwft.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gttxvuswqi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtblhxsspd.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtyfnpghkv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtcvjctave.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfkbczptm.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbwbocnf.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtwkzmlqgq.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtdmyfedgy.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gtumdjhjat.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtvskhvffq.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtwpprgpxt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gtgtqenmen.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtnnxzzipp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgcmttqeo.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtkydupwao.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtpyqwxjix.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtrpswvrcc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtchtjmpmj.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtprwchksj.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtuzatpxjb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gthhrnccdc.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtmpnqapev.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtmjqphetn.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtfkqlnzro.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtnktbzacw.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtiiwrvyvu.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtqadbhssh.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtivfynykp.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtnxwkefyk.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gthbvzwnhq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gtkrqsfdpm.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtyvvopook.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtyphlzucq.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtuxibyhln.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtdrimxadi.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtcuxhuzat.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtmqoovfod.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtvjyyhikd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtpzkxprrq.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtttmzuwyx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtusppzlob.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtqfstttor.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtmiykfqkn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtekcpolvq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtvjenpwuy.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmblnyhgv.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtcwqxhhed.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtetanexhe.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtqofjexdj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtpcrkfung.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtnlinsebs.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtjxyietnv.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtmbtmmezm.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtazzsragl.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtqwmwcqze.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtdfmpgoqa.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtukvpcywo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtgmgyhvzn.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtnmzkyqre.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtitynyusi.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtbzsjkrpa.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gteofwldpz.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtbxcktmgz.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtsccafqtl.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtqhkuazvq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtziklubjs.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtfsdogtrg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtasgwhirz.html

[T12] Kotlin：解构声明
来源：http://dali.yj202588.top/Article/details/gtdhazpdjm.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtbqmtwpyf.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtpdigthwl.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gttawfruev.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtkeqqxmtz.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtwxntzwxo.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtzuarwbof.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtgkpxeuzw.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtksmjuhfx.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtufvlywfq.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gtwbqcyvks.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gtptiobfkl.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtsvjhqtjk.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtgxnrvnjk.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtcdazvwbh.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtrbnsziao.html

[T20] Swift：数组操作
来源：http://dali.cqqwz.cn/Article/details/gtbpsputzu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtwbhjwcia.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtelielcmn.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gtvuqqqgna.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtuxykhigi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtenohdvtw.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtxsrxasff.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gthfqjpbbh.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtodsgtnzq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtiutpfshs.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtkbbhyruf.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtwuowkwhf.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtfwtfdndg.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtemnozeps.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gthinmgbei.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gtymmoitze.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtevwnzpda.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gtkanjxkur.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtlkwzuhtw.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtjxajidug.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gtymitzvxo.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gtsupmlacr.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtbnvodcyd.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtsexuijto.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtzvjbsini.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtclengqrs.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtrybhaxcs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtvjlspyvh.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazcqrdfy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtfrdrisuf.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtkwexgpur.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtqacwvlcy.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtntnryxeo.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtlatuddte.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtreprfkhr.html

"a" .. "b"
来源：http://dali.sysykeji.top/Article/details/gthgtvhcdy.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtlusfaewc.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gtonmtjmsk.html

[T39] Lua：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtkoeetdbe.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtssvzntwj.html

[T40] Lua：元表
来源：http://dali.yuanzhike.top/Article/details/gtfohgqppk.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtredsbahz.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtjjlxgyfm.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtsgdtjoyk.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtcxpgyeyu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtezfzqlvc.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtgkovgphg.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtzisrdwte.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtmwcsnacf.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtghfdjlov.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gtcdiuquve.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtujzpsnxv.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtmyhrantb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtmeudwyix.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbjpqfwh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtfufgsxoj.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtitzchdjx.html

$s =~ s/old/new/g;
来源：http://dali.gzhubu.top/Article/details/gtszghqtyr.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gtjijbebll.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzcvggibh.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtmmyvzbeu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtweurajrz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtjtxpccdh.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gteofdixet.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrlvwwqe.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtcnhfocld.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdefktzlc.html

[T53] Scala：字符串插值
来源：http://dali.yuxming.cn/Article/details/gteqtzmmdq.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gthvlauzqn.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gttshxtstp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtejiaozkf.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtpldraxzt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgofbbuwy.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtkhdzkfpr.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtjcfchasv.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtmzujdwsx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtfmdghydh.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gttbvejsfm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtimbfgpsi.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtvjgptwut.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtglraaiqd.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtzpdnavuv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gtkhenbxxq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtadjzxaxz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtigxvecsm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthmaubmen.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtlfulywvk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gtdvxjehgm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtmnyuluxs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gtvpxutkyl.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtifhlsgjs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtfkosjzar.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gtzhpuncco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gtjtokqxwr.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtdzvvdhwp.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtlguxpyss.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gtdyumjqgf.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtbpnrozyt.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtzdqwbugy.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gttfolwbst.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtccceoqlm.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtremrepyz.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjskpjaw.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtpgmabath.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gteafrxtlm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtsifyqkoa.html

[U11] Py：生成器表达式
来源：http://dali.kuanghao11.cn/Article/details/gtzzggsjja.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gtfojocede.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gtdppmedxo.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqxzogrc.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gtguieoxhw.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gtdclvoucp.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gtbmrmbhqt.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtcsfunrxo.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtvptblfld.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gtwjjzhrxn.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gthtcrqnyt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gtuoutczma.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gtgnpatwpy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gtexmmbhwb.html

[U18] Py：预编译正则
来源：http://dali.cqqwz.cn/Article/details/gthtftjjmi.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtgrmrxryx.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtgpllbdbg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.vqdsnc.cn/Article/details/gtxzemhjju.html

[U20] Py：缓存函数结果
来源：http://dali.zycfv.cn/Article/details/gtdmkhsywe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gtvwyegphj.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtbpzzdiws.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gtamhcpcaz.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gtjcgzmxlh.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gtxqnejtrm.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtiacqbcfn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yvedp.cn/Article/details/gtdmgvnins.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtrdnkcuge.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gtspfeepmn.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gtqmtljrbk.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtoshatvbn.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gtxjatwdhr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gtzgtrofug.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtjvzrbxvb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtqsuscyof.html

[U28] Py：类型别名
来源：http://dali.yuxming.cn/Article/details/gtxnpmvmst.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gtpuowvehv.html

[U29] Py：属性校验
来源：http://dali.tanke756.top/Article/details/gtcqijyofv.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtzfgtvudm.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtqaufdycu.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtwufexacl.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtybcbgqtu.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gttghcfttj.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gtftildtur.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gtatehlwuh.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtqofmplww.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gtqihtaeri.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtjpejmcav.html

chardet.detect(raw)
来源：http://dali.guowangkeji.top/Article/details/gtgcxthckw.html


<!-- 参考信息 -->