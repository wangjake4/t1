代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gt2ttucudlp.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2nblmqukd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gt2toqgebcp.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gt2whnbmuct.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2iitntlub.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2jsrfcpfx.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gt2fmowqdkc.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2ralrujpl.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2wajhwtcr.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ynqfnjhi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2lwurrpev.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gt2gasjixvg.html

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gt2vqqaoqrb.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2psmapmwv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2ppoyegcd.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2nczsqilk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2dtrwskrz.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gt2uffpvtsc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gt2spxawqsf.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihnctlwl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2xnkpwjuk.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvmyekwu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gt2wumxpjoc.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gt2jzxaucwn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2ktiblfko.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gt2qkbewmlb.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrlsuqfy.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gt2cdjhlgpd.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2nrtjxznv.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gt2yplbyekb.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2fqzoqdwn.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gt2nuqicafp.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gt2vdktwvjn.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2hoasxxpk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gt2witahnwp.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gt2zzgcctrd.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2unnsjykn.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2iozktjwz.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gt2wprbkxot.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2vglpptmj.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2wzteqceb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2wbainsgj.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2tjleemon.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gt2movrgktn.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gt2mxnkmjio.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gt2tfybryfj.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2ghgetlwg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tmtvgwxd.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gt2wbsyhfjx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2rsevvjun.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gt2rudpkjxk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2dnxnvqil.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gt2ttgtgrdi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gt2mpgtazar.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqeqprca.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gt2pkwwnyym.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbdzdn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gt2ermwhebc.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2ojuzopjt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2gyoalfql.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gt2fvorevfw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gt2pwtkrqhx.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gt2pnodafws.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2ppssdscu.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2zfdeyxqn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gt2kefrtdip.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gt2nokdshdv.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gt2llhxuqrf.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gt2newaigkb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gt2bwtymtuh.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gt2tomygyyv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gt2gfamgdol.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gt2sqbumptp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gt2wrjbpxjk.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2pqfwvxxq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gt2kfoldeds.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2nowhvubw.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gt2kapqwbku.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gt2pxsbzhcl.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gt2lupmxujs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2jyzjrdfh.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gt2blrrtuzy.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gt2ifeslkhl.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2vysijjfg.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gt2ktzubnml.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2jlvgtizg.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gt2ecoyeere.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gt2kpkmpwcq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2vfndguve.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gt2dzhwsqzg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tanke756.top/Article/details/gt2rjzlkfws.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gt2dvyldigv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zproldwz.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gt2tvcmmqvh.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gt2pccjhjjs.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2ruwjgifg.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnqzz.top/Article/details/gt2rjqyhfos.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gt2hauonlgk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2hpybczcy.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2esrpybrw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2momuogqj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2onnnwaqq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gt2uamqfcpy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kjmrbpug.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2fqhfvtmf.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2jtvmzhdm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdpfcvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gt2tuzdmcml.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2upyoejbq.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2imxfmbca.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gt2czjcbmtx.html

val n: String? = null;  n?.length
来源：http://dali.jinqigfzy.top/Article/details/gt2gorhocsz.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2rbqxncch.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzknittd.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2kecrlydx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2mqzmhybn.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2zgzqjoug.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gt2kxpndvpm.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gt2wmmxcowj.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2bwkqrjqj.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gt2gzlghgkp.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gt2gddbgzfc.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gt2ahhcmdda.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cufgwwoi.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxuugero.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2jmtuacgk.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2yulpnpft.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2flnfpqfe.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2geynaghp.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2xpcwwioa.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gt2uajmyqcd.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2ojczijob.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gt2xhsbaibf.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gt2bpwedlxb.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2mlamyayd.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2ewzylrbj.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gt2hmjhwtot.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2pkkgxqnm.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gt2vhqyvzby.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gt2ckeitkyp.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2bxcvgexr.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2yraczpjh.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gt2bhyscrhd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gt2cyqkowlb.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gt2crhctfjr.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gt2sevogbus.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyeduaml.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gt2goezicsh.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2aatygvhq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2ajobtczi.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gt2vvqyjals.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gt2tqckycow.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gt2pkjxriar.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2tmnvkduf.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2rzgfukxz.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouzsxhce.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gt2xnqthisu.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ecytffkw.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usleacvs.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2kpnnmomt.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2eaumdzdd.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gt2afmpdaec.html

[T30] Swift：协议
来源：http://dali.0kj1m.cn/Article/details/gt2vjldovdk.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2folvcmbe.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2aeddriyf.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nefgqfkg.html

[T32] Lua：局部变量
来源：http://dali.0kj1m.cn/Article/details/gt2lhatlfjd.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gt2jxgcvndn.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gt2lmqybgof.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gt2jlitfqlk.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gt2aljjyjja.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2qvzxfvgv.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2gwqohodh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gt2liviyqdv.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gt2qfrnlqlf.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izvxoszv.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2xeiifjmt.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2ashtcjbz.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gt2stwmrrnk.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gt2xjswhzla.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gt2uaumjhhv.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sntfsvyw.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gt2otzlehnt.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gt2nujqhpld.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbvfevwq.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gt2qnlnxgtt.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gt2gyeiaulq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2owgxqwsi.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2ouaedazq.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2uicmbasg.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gt2pxtoocuu.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gt2fcwypkhj.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gt2xtxmvwwf.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gt2fsowjhdr.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gt2wukqqvun.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gt2jmpfdvux.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gt2thhbhmfu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgpeflsy.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gt2ozqirvod.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gt2wfrwlkpp.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gt2gcjrjozd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2vboptroe.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zneuvays.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gt2ydexodhp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gt2cipzecfa.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2cuyphupp.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2bxfrilzt.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gt2xcbocyqg.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2tefkdhxh.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2hfqcnfgi.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2fgriuhpp.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gt2mmaaalrq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nwbrower.top/Article/details/gt2ynijfwto.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2ckwllvpf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gt2waaoxhhe.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2oejqmuei.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2ucsfnnbp.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gt2csogdflz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gt2exjrjhkg.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gt2wkigorre.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gt2sjatniuc.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2pxovmcfx.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2pxxxgjzq.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2rckcwmbl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gt2ktbhvzup.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2edlpjyzx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gt2udemmaia.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2aemfbubb.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gt2qljbrnsm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gt2wdwmtphw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpgsabtx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2viekfhey.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2ejwqwuhr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxbiutv.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gt2roeghjfd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2laicknku.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gt2lsibynxk.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2wobomxdj.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbsqfdqf.html

{**a, **b}
来源：http://dali.dianchejie.cn/Article/details/gt2jnetewgk.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gt2lkrfxvnk.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gt2vmltupnf.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gt2pjwdvdga.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gt2jjxqenbd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gt2ghvyfzcq.html

max(d, key=d.get)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnbusbbx.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2yjbgfcus.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gt2zwhrcjpz.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrskcnmx.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gt2otcvcisy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gt2kbkmsvjq.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gt2cvuuehtz.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gt2wwxhnqsy.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lodjyhgp.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gt2vhzxauex.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggvmzrgx.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gt2gawqzdgi.html

t = time.perf_counter()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfinyvqn.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gt2rsdvnnyi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gt2sjrqoojw.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gt2zpiiexva.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gt2fuczwlum.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gt2dajlzsww.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2gojmpotv.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gt2qhdwocbs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gt2gfnofmww.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gt2gmkeqlom.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iaobennc.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gt2jxnomwgl.html

@contextlib.contextmanager
来源：http://dali.meibo888.top/Article/details/gt2skqkatwy.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gt2pekzaxwo.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gt2nvvkbqxf.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gt2ffeodvpm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gt2zkapmakd.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gt2xdvmzmbn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2zukitivm.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gt2phmbndva.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqsctcz.html

[U26] Py：并发下载
来源：http://dali.hnqzz.top/Article/details/gt2eollahqi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gt2okrbnaql.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gt2aivskdst.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gt2egfpamym.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gt2eddwszai.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gt2aspfzzkt.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gt2xefhptex.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gt2idiubynv.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vskqcejf.html

@dataclass(slots=True)
来源：http://dali.yueranfly.top/Article/details/gt2jytspgmp.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gt2tsqipvng.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gt2allyazqs.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gt2vgriiryz.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gt2xcvtakpd.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gt2etwxjmex.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aibaodan.cn/Article/details/gt2funosydb.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gt2qmuakyab.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gt2yvyjumbd.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gt2vncsdkuh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gt2yxsdawjn.html

[U36] Py：定时任务
来源：http://dali.yangfankeji.com/Article/details/gt2ocyroswf.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gt2tuaykzlu.html


<!-- 参考信息 -->