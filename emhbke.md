代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gt2oibdqdxe.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gt2veajjcze.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gt2yhqkxfke.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgevvtbq.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gt2rezmcgad.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2knymdbnx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gt2ewowxfdb.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2dqhebpfu.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gt2pihlbbji.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxtkkbrh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2xmcactdp.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gt2pcwvtjoh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2wqjidgeb.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gt2xjpiyqbz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gt2nuaucgdl.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gt2mbhfpylv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2wxplahvj.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gt2fzmjzfok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2yrtdcnam.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2llltinzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2fdoudhpf.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gt2xyhdawud.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2dtrnxtrv.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilxhbllm.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2gavixxtq.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2fmutxtkk.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2fwppdamk.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gt2vjkqfzfb.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gt2hsnikfnp.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zplwbnox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2gpmlwsen.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gt2xduoehao.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gt2jazjzqvn.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gt2fzvtzeqo.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2cynmwxbv.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2jnhqgcrs.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gt2iriwxkjv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gt2iarhxomm.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gt2bfjrvxeo.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2hhlewium.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gt2bkdixseb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gt2lmbxjeco.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2twreubvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2fogybxho.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2kfnynjsc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2nhlfjedd.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gt2zzlocypp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2mcelszvf.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2zcfpxnyc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uykkeaqh.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2llggsqdw.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2ruryrnyp.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gt2fvpdxfev.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gt2mtiqiofn.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gt2mpekdzzj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2rxndwajj.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gt2ltzmutuu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnatillo.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2mexrxjef.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2xtcmgncn.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2cdrpvela.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2obbltaop.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gt2znqfjfiu.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gt2rkryigrh.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2tvdqakta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gt2xlzpellm.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2wpcthlyy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gt2sdkedixk.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2phtohwkh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gt2mtmxryns.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2vdjcqvae.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gt2hbcmsuzc.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gt2hdqdzwzy.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2dydewdrk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gt2wwymfyho.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gt2mihywdsg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2pomlzmto.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2dfcndmpf.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gt2wulbejrc.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2bpmpyqyp.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rrrbwebb.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2wawhbsrf.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gt2hobkrqnw.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gt2mdampanq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gt2bghimnxn.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gt2ilxxhqgl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gt2supwigfi.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gt2dhkabrip.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gt2twjvxcjg.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gt2buanfatc.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2rvhmxwhs.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gt2iujetilz.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2wdbcprbl.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2eweexpze.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gt2eufrkxdj.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhwmheqo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gt2tihgityy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efbhmkvy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gt2vhnwyknu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckloxlri.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2rmvdsawq.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2bowydbje.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gt2ouwtkegw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gt2wpfhjbmn.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gt2etdhdqtb.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gt2ufgyqpbn.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2vyittkdl.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2oqecyejb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2jzujkner.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2wfxacxxz.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2nqfrdeif.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2cmizlzml.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyabpftl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2jbelajeu.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gt2xmvcjjed.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvwqztne.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gt2cclopkgj.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdscckbp.html

[T10] Kotlin：默认参数
来源：http://dali.redwolf501.top/Article/details/gt2upnxrmam.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gt2vyloniic.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gt2zdrgqiwo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2ljnnfhdi.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2kkyfrggn.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2sfkjqkts.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gt2aptgklel.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gt2ufibkclc.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gt2wmoyolum.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2mrdovsgr.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gt2zbgdvala.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2jecqonoy.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2qsfybnnp.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gt2qsxeeind.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gt2kjwemiqn.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gt2wfwmossc.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2wmhgewug.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2hglmhwjm.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gt2sowaxieh.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2guplkksh.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2haeuqzqb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2tefeongb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtghimyn.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2tqcogtch.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxnrkkze.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gt2zqijajee.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnafbsqk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2lbfkneeh.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gt2ompjerax.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2wwronemu.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgkoteuj.html

struct P { var x: Int }
来源：http://dali.ybcxt.top/Article/details/gt2takxphyv.html

[T26] Swift：类与重写
来源：http://dali.ybcxt.top/Article/details/gt2ywbpwhhy.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gt2nmbvincl.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2obyzwgsg.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2slmagtij.html

[T28] Swift：枚举
来源：http://dali.wangdashe.top/Article/details/gt2oldqhsnx.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2gqmksjro.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gt2fnvrveza.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2tozwvpej.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gt2dixtkqrf.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjshfjhx.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2ipngdlfi.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gt2hkmhjqjk.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2lvgiqrtd.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gt2vfkknfhb.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2viztwjdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gt2nfxgimil.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gt2chdhcqsi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gt2ecneypgl.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gt2arsyywxp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gt2ttmdtsuc.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gt2sossbyfn.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gt2octgwkjt.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2yikbgerf.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gt2qrcpffyy.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gt2erfcirli.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2snfgnujg.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2nngpbzfv.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gt2lrcjjlsg.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2wroqcaoc.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewyyzsre.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2wazakztr.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ceuptkkv.html

[T42] Perl：变量类型
来源：http://dali.jlsjyb.cn/Article/details/gt2jifenpba.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gt2tepbtipv.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2mpuaqnrv.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nligdbvl.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gt2mickjtog.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gt2wejhtusy.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gt2wyrtszid.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2ajbsutxl.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gt2azjtzyfp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gt2efdhnquh.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gt2khhxhetv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2euzutepm.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gt2ntklghmf.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gt2wwavzjke.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gt2zxmncpfk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2tcbomsjj.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2dabtfvcx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gt2kjgsslaj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gt2vvmxmhen.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gt2ghzimnim.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2zrflfoht.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2enxvskkx.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gt2fiozcdnd.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2zuwbmbfi.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2tcqallba.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2xocvqtld.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gt2pnxtmorw.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2wjilerkb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gt2anocmslo.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gt2wdzeejun.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2adtqkzyl.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2qdtiabsx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2rrosznja.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gt2imwkmhna.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gt2dbuabxyf.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gt2ekvikyra.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj202588.top/Article/details/gt2hvyzhkmi.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gt2cxvujcpk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2xheqpkgt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cqcjqlws.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2zjlbojcx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2iwqulihy.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gt2azfwdxtf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gt2gohujttg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqswefva.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2ncdqstak.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gt2pxkwhojx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gt2udwuklet.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gt2jsispidr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2vyuqqmtv.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gt2klkjwknw.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2ifanmasi.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2axixsnbh.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gt2iacrddry.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2klfixluh.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2cxzoodhd.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gt2swxyeoyl.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gt2abpxrhvh.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gt2ysihglyw.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gt2fvraaoou.html

[U10] Py：按值排序字典
来源：http://dali.aibaodan.cn/Article/details/gt2qqbfoaee.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gt2euzoclml.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gt2jqgcjyfg.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2zfbziwhg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gt2zrtqznyz.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2ktepspfu.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2rcexlpvc.html

deque(maxlen=10)
来源：http://dali.tanke756.top/Article/details/gt2bkcnihkd.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gt2tywivnce.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2zajwiwui.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gt2uunucucz.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gt2rfrjfoyo.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2zxxxbhuf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gt2qotnvfxz.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gt2dopxygdy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gt2vjkobzvy.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gt2ifqwuipa.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2rwilbxky.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gt2xcmbybsa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gt2ycidpobb.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gt2nvzexhuj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gt2pxgltfuc.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gt2kkwusiaf.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gt2uaxukfdq.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjlodiju.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gt2wrszabtv.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gt2ycgibwqi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gt2kblntunw.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjffsmxy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2drylvqaw.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gt2qidvxgjr.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gt2uglysrnb.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvqoqtdh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gt2xfxtyvqn.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gt2freyptbl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gt2qcryyvic.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gt2nptvxjwu.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gt2pfldfcud.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gt2vemvphsa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlfabvy.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gt2rewgutdm.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfojlvtl.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gt2qfrocwzb.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gt2lxinhgai.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2dqeardgd.html

ruff format . && ruff check --fix .
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isqeqssm.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gt2qidtomle.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gt2dbexxwqm.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gt2mlwewzyq.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gt2zhiaqwzl.html

[U35] Py：发送邮件
来源：http://dali.jqgufenzy.top/Article/details/gt2hbykdpgp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gt2fcyfdkab.html

[U36] Py：定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2zuklxcop.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gt2btmgcisu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzjgogg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqugobtf.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcqumnrc.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gt2bhxcudvu.html


<!-- 参考信息 -->