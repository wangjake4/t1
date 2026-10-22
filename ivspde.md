代发 wailian999

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2whzygqqb.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2mxgkwonp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2pvbnbnca.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gt2kikjudvj.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2vknbeawv.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gt2ytrcpbiy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2kyvnqqur.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2bkwouetl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2wrsktfzs.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gt2hogswmrh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gt2whmefudo.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibaujgbo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gt2ujbsbxfc.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gt2bzigalnz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gt2tvsrmxwy.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gt2wlkkkuzt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2zyylnsxp.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gt2kqgforeo.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gt2iaqzcdsk.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gt2swlujjix.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gt2hcfbixqo.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqdpmrxi.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2uadvrnnm.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2uxlrcmrp.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2vqyadaxt.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2blffyrxf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2egdcqtoc.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gt2eflolhpu.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gt2tsgzfboz.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gt2vrdayawc.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gt2ozcjthqi.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2sacsyrcy.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gt2woynqklg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gt2ujtajyum.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2pudurciw.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gt2pmtfdhuy.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irzhttss.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sweek.top/Article/details/gt2bwewxijq.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2zkhwleun.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gt2pxstkboj.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2agasxqbw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2agwhfjfu.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlwcfxde.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2odrfjlpo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nsicfdkp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gt2jdwbdeox.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvjauupk.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2pbepqqtg.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2reocpxwq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkvfhbs.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gt2dzupnynp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gt2ijkmemtq.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddlnoitf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gt2rssqilsq.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gt2zclzpvjq.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gt2cojsfkua.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2zabhbonn.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gt2syadylje.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gt2vpwzyswa.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gt2dvxywoei.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2txhwpbbl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gt2kpluwear.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gt2nmhshigu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkgmrtqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2aiuykxyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ucuvsddp.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2vlvtlwxl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gt2bwagtssf.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2xssbfrfw.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2btacxhva.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2bkvdhjcf.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gt2ztdkhsod.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2omxwdmfj.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gt2muzfgnxw.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2mtgcnjzg.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gt2sbztsrod.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2mmiuvqyu.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzqfynld.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gt2bpkfbwdb.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2hpqanuuh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gt2wevjzoji.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2qyyahtdx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gt2fhksbmax.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2mvqxzfns.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzbpwuac.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gt2awqvwskr.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2gsvdqefy.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2qjvlfoip.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gt2exqvrexe.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2kchoqaab.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxohunzd.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2cxhijsdp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2mulbufzo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2iqkfswus.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2ouhoxjjz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tpoklvsq.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2fmdienpp.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2mmrefnvn.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gt2jquidonn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gt2vpyrgzlj.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gt2oykakhsi.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2qbybazvz.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gt2cjzihyfg.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gt2buejvbuv.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gt2izwvxtda.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2mlianmjz.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2nrtsjawp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2baatepqt.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2ksdzritx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gt2yflcwpjb.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzvmqayp.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzegntvw.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gt2uisbasya.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gt2xqymyhae.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2cidfeovb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2fbuntgds.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gt2ayatdnlg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gt2dyvfiwxw.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2hwjafkvv.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2sosisltn.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gt2zrqwbgpc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2werbeskp.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2tmmikoeq.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2tjyybsfa.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gt2nejwdsaz.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gt2hiqnpgxg.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qozzqqgq.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2oclmjtcy.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2sskyfobf.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gt2yxbormoi.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2gwwcndyw.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gt2bedjhpwd.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gt2dnmezgzd.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gt2pbfkcsyd.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gt2qvabdnyq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gt2lhwargmz.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2slliaptc.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gt2juvplwcp.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2kezlkwjm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gt2pvtsrnbj.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gt2cqdcbanc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gt2ynphcwkx.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2hckubswo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2eqlufclr.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gt2jgvfilaz.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2thmmvfsh.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gt2aqiltkyo.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2rzukskex.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gt2riabneqg.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gt2idctdkeo.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2zglcmpsn.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gt2hbxmjfry.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gt2clvtzwew.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gt2sjcwykpj.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2tehscrlv.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2agiryety.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2rxmpcyqx.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2akolypbh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqjvilo.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2kgwpiroz.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2iqfzhorm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gt2mjsmevhp.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gt2qzrhwxff.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gt2zvrimewx.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gt2nloijlqh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2cykzltuh.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2awpsxrne.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gt2ortqmtzn.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2bikljxxu.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2sejoitno.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2zugglfbd.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gt2jdtlxuwj.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2vpngoppb.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gt2yoaalkbl.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gt2ydgqjspq.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gt2gecwzdih.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2lyoynawa.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gt2rdupegig.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gt2gjleghxg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gt2xjgqeiza.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2rjcdswnp.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2tjpozwob.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gt2qsavrkdu.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evpsohdf.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2srwlkjvc.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhyvjsvj.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gt2kyvknxvr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gt2pgkdmaqd.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gt2yksfgkef.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gt2vpjlsxhe.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gt2qwjkeddi.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hytzclfs.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gt2rvepulsw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivsrplq.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2wkipnzry.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gt2hdqzxqxk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2gnfyhvfv.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gt2grzvtazy.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2eugnmlwe.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivrsnioq.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wegihbeq.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2tnsljhqs.html

s"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2kracyajf.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gt2itjxyjrx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gt2mcgbmezj.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdlilhyp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ofmdqhdd.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gt2bggpkivn.html

case class User(name: String, age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btjyysll.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2sjzkbiis.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2kujfdhlc.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gt2awpxfnoa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gt2mkdbzvqp.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gt2addsinhx.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiefbxdi.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gt2zplrrbah.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gt2mfcyxrsj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2soifmdrj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2argewuwc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2nhwthlbf.html

[U01] Py：创建虚拟环境
来源：http://dali.tian-w.cn/Article/details/gt2okfjtyjo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gt2lfghquri.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gt2cwnjtznh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gt2caqbqqob.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gt2zhmwlxgg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfnkjmuq.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gt2nequdgyk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gt2kmpbiypg.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gt2stfmpcfc.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2oazcsajh.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gt2gjwqjiik.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lerbxxum.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gt2rndztfpv.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gt2cvrtjpcx.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gt2ypqazhep.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gt2ghosegep.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gt2xucftwzk.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gt2qzdnyhwj.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gt2ekaemckz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2vgdhrhmo.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gt2edboyqlb.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2rdxovnia.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oekpeqpm.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gt2vbwgealp.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gt2rglbnqdm.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gt2fvwfkjvr.html

[U14] Py：分组收集到列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgipzcgn.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gt2riscvokv.html

[U15] Py：高精度计时
来源：http://dali.yj20258.top/Article/details/gt2sliexgqh.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edckvzwa.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gt2tdfncxje.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gt2wowcasql.html

[U17] Py：初始化日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2msodfbmr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gt2cpqggewb.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gt2ncgalvqb.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gt2agwqstky.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gt2hfpvcixb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnxiangtu.top/Article/details/gt2teltqmxa.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gt2bbnlmmpx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gt2txtgzgxl.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtbzrfnz.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gt2eaxsxdue.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gt2hrmdvcsp.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gt2vrxrtxwk.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gt2hdgrgsin.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gt2wflrzyxg.html

[U24] Py：路径操作
来源：http://dali.sufxvd.cn/Article/details/gt2psfjotsd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gt2eeoueqcq.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gt2vnbxmzao.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gt2gblorngj.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqbfxoue.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gt2sdisboms.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbmegec.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgfzy.top/Article/details/gt2qhacfvbq.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gt2pfhfrnxn.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gt2dbxjtffl.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gt2migpwyis.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gt2zwsfznqe.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2wpfakjtd.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gt2vpvohznm.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gt2uoosdqvt.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gt2sdiccvus.html

[U32] Py：代码格式化
来源：http://dali.yuxming.cn/Article/details/gt2waghfofc.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gt2evbdfxug.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gt2iahjjxvj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gt2seyidvib.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gt2hrlghyqr.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gt2kyrwrnsn.html

[U35] Py：发送邮件
来源：http://dali.ppjwa.cn/Article/details/gt2awsdzqek.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gt2ypyvpcsw.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2ttoacnmf.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gt2mbvocjnx.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gt2cjdzvqta.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2qvbynicr.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gt2zlhmwmdd.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gt2sjnhyjyo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whgivinc.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gt2fimuleog.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gt2xvhqgrof.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eudawtwe.html


<!-- 参考信息 -->