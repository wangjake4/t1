代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gthzvgnkjd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gtbxnoqrmo.html

fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtpnfbqmzt.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtpeqteros.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtyadcfuzq.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtkilxivfb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gtpzzusguw.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtqdjcdnbr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtovygmaxc.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtrmqopztt.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtdljlmrxv.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtgvbsdobw.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtqtjvhgwy.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtobaezibd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtffupfout.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtntjislaa.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtbxzvptqt.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gterlwnqeo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtuglzxxir.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtaogdujiw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtfgcbuzhc.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtkqhwoqqe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gticrvomog.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtvwdznrzt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuocqjnl.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gthishgiav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtsvqfxlhr.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtvkrgxepc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtpyvycfzo.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtaexebrnd.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtsankpwrs.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gtalddzsff.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtmwyabgfy.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtiberyptl.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtcohdcshg.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtrrolmjid.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtolmtctsl.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtozrbrbwr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtyvqsiwvw.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtzibqqaec.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtruugjkif.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtxllsnsql.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtsxgwqteu.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gtquuqsssn.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtedphfgiq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gtxecrwgzz.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtbobaswnf.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtfcbqnbjs.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtwhrswipc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtjotinfsq.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gtddbwgjot.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtsyjsupyd.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gteatkgoix.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtgpkghesh.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtjytvjqlg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtrjhxmbmx.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtxklhpqav.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtmljrnozn.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtfownybww.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtowafqfoc.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gthbfduacd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gttlaofpac.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtzbycxpkw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tian-w.cn/Article/details/gtkbzxuycn.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrhtivzii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtxvhzvzfu.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtxydcoiog.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtmnkptnzv.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtuntvbdjy.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtwezsnpnl.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtlcqtbxdm.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtyrfstyng.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtkwndrvjs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtruamzncx.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtfbptmdfm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gtwitsmlab.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtowiraqyg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtosiujvcr.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtdhsthjpb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtxgwqkjhc.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtfzecnwsz.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtjohccond.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtwxfippod.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtfddcmpgg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gteqnuxyzw.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtwuxalgos.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gthiqjbxjp.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtrquizcub.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtqyltbeyd.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gtsweczfid.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtrvbbiuhk.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtjtwqiorg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gttrrxyaqm.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtmtnlvgro.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtfdkundtb.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtiwhctqkk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtdexlfkhx.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtkpaqkjgw.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtdinaopql.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtdzzulqlx.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gttlasbgbl.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtuyurzney.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtbejroyrg.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtckriyjqg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtmqnlpzyi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcjibfsqt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtbddcwmyg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvhcugvug.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtdgdeshqn.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtnrydtkbc.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtyvbxibzz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfmscqcb.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtogettldn.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtrkgxevck.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtghpwdqza.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtgfhhoisk.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtdihukehk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtymbpzpvl.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtjpyykghd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gthwcqpdsq.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtxsqkjkki.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gttufrpfsy.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtwgjiivzv.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gtsgwltyix.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtwqbghrkt.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtadybsoyw.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtanbetpgi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gtmcoaojby.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtthnwocku.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gtvosgxbxc.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtdjfralka.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtjpwdazft.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gthczstiit.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtlumksvxs.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gthzpasomo.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtcsdxsrtz.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gtopipsrca.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtijjvujhb.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxydxkun.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtwysjcmig.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gthcuzvpfg.html

var a = 1;  let b = 2
来源：http://dali.hnqzz.top/Article/details/gtnzguavev.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtycmqhtlh.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtdruzysqh.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtdazjxett.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtuydsbtub.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtswbgphoh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtuhtolthh.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtxbmfemda.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gtnebhouml.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtjdcayeum.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtftwjszcj.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtsydmemzf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtmycvynyz.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtsptpprtx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtquulfrds.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gtlimadpvh.html

struct P { var x: Int }
来源：http://dali.gotoacloud.top/Article/details/gthxkvofzx.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtwyaachzs.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthteovuaw.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtbasfiqgc.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtrpaidgjx.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gthrvpjvos.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtwgarbiby.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtgqbuctin.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gtbkhnfduw.html

[T30] Swift：协议
来源：http://dali.zhongyouzk.top/Article/details/gtumanngnq.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtynqfgqeb.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtfmcpgxye.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtoslngnij.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtmjntdtiy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtzhqmlcwq.html

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtwyydklhi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtwguoyvhq.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtzxnocsiz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gtjbsyaeah.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gtpodachjf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtpdldnirm.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gturalbbeb.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobqlvseq.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtlnexoiqq.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gtiszruxyi.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtufteazei.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtuelzcfoz.html

[T39] Lua：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtrbsqeaxp.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtjyaywsin.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtiziykwmr.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtijtcmmvl.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtzxvmjzfz.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gthndbnune.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gttvykjmaj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtcpppeond.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtxkblagbl.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtomtebupp.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtxrxpyigc.html

if ($a > 0) { print "正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgjjltkcp.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtjrmvjqyk.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtjbnigxkr.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtygoljers.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtnnpwpnrs.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtegqacklw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjpjxgac.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtqkobndec.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtzecoghvp.html

[T49] Perl：函数
来源：http://dali.havefunace.top/Article/details/gtbbaqhamc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtbodiglgu.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gttqvqozzj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gtmhojtgip.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gteydwrmuj.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtecphudxr.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtycskudou.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtxwdnqytl.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtgfegkmqg.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtrrktpdjs.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtndcdodaw.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gtljffxkuq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtommbeksj.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtyyqixotz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcznvkeg.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtisdhkoue.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtshebnsae.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtojbbevic.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtcpfjwksg.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gtjepymhvu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gtbisutxtr.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtwjmysnee.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gturoqfcua.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gthfkzfyfb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gtxizhcpnm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttqwnrtqu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtzpslmhed.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkedggcvm.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtugbiyckb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesdbxzzy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtiembkhub.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtugpnzffr.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gtvkmlrkvw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gttckxgxcl.html

[U04] Py：变量调试打印
来源：http://dali.guowangkeji.top/Article/details/gtvihzdlxt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtstyshffx.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gteausvaax.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gtqtnhbvmw.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtxtnvmoag.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtsdhcpkiy.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtgzxnfqmx.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtcitbtwvo.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtsketsgfq.html

[y for x in nested for y in x]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzdxgdfd.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtgfsrelvy.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gtvqikzvgp.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gtdeizxvoc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtjesntyuj.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaevnlvr.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtgxbmyqqc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gttbjpcert.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gtlrbnpcgm.html

[U13] Py：固定长度队列
来源：http://dali.gogol.net.cn/Article/details/gtlemfewet.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtgsiqbvaz.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gtizaaruma.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtyqcnnyql.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtbvtjihkn.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gtgzkreozu.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbclpcrqm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gtedlhnnoy.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtckicqoos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtthjjuhgt.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtposwswdo.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtkylasezb.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gtmkmkvouw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtpyyxpuqu.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtstetwggg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtkxgvcdpd.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gthwgrueyg.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gtspmwcasm.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyxiufre.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtcbfibogc.html

[U23] Py：分块读取大文件
来源：http://dali.zycfv.cn/Article/details/gtpvsqxfut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtlrvgxcdb.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gtwpwujabq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtpsaqkbzt.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtfxzabzbw.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkelvowat.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtvotimsup.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtjmrouvpp.html

[U27] Py：异步 HTTP
来源：http://dali.sxryk.cn/Article/details/gtndkrlpgd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtedcrzpmc.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtqwwdjawm.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gtlhbnonuu.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gtityntcln.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gtmmgcikci.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gtauccwnqu.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtlzvprynk.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gtciuifgjl.html

python -m pytest -q
来源：http://dali.ydzc1.top/Article/details/gtgrgiprtj.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gtietpmept.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtzzajxypq.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gtexwluots.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtgfzeoobb.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gtfmqxjcai.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gtbyimdipu.html


<!-- 参考信息 -->