代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtecvakgln.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtxgkrtdur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gthsqfdkfy.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtripfzzyd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtsgrtkjoo.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtgiouolgt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtumozzijw.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtkcbepkaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtdggrvvqk.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtpbgrhvpx.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtztffiwom.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtmxancjjo.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtecvqyzvz.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtxsfdbtpj.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gttboadasi.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtmkhwssov.html

static int counter = 0;
来源：http://dali.shzxlz.cn/Article/details/gtrcffqcvi.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtrgvslxxd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzrrmtfa.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtfjetaamd.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsojcifzs.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gthzznnpcs.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gtzrybeypm.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtriaoxhnq.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhuzokpv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtrgmbtpkz.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gteelplspy.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtjjjeggce.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gtmpcqpiaw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtljxkpnsr.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtvitaucxk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtyqrqphie.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtagidldzb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtpelkbfyw.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbpmnyza.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtebqidzht.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtodnbowwc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtkqxxyaon.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtzvxvhmrz.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gttseefqwd.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gteamjcoux.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtpskmuwgy.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gthjmxwuae.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtqeynvjrf.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtcglopmjz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpulptfo.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gthduvkino.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtrpdfsatp.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtdluqzjbp.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtfxbehjzn.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtsnctyvqo.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtdkvbvaul.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtqvhgfmus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuxming.cn/Article/details/gttcwdzpif.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtghnmfsoo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtigswjudm.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtiffdxver.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtiddvwwad.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtuhqyckdj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtnqccjpdj.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtcwilwhob.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtuvggatel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtisosdhmb.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtukdvbhks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtgdlezqpi.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtggsuvuwz.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtcctwfnup.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gtxybzcmjh.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtqlcnxxuv.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtkbbjxaez.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtwkioorpi.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gtntdlelpu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtkijwhzzi.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gtgqpnwghq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjagjauur.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtkyqilttv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtiaewcdhj.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtdgdchyij.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtvrhxkrqh.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxfpbdmz.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxddscgkz.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtnojqobqh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtglocbhlz.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtuqjbikya.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtwcyaucld.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlqcbowof.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtsdzyjrtp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxnjyrnow.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtojldzdgx.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtrluedghl.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtbgvuedlj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtwaiwfsct.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtxqkwurov.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtffwobwsu.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtfuhnxxuu.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gthufmkzns.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtbpgpuwjg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtkwdulptc.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtrlplkcsr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtjuqqnpjk.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtufrclocd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtshojdnvj.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gthkdmsuzf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtyuorsncq.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gttqcykurz.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsxljueh.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtxdccckka.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtlnijnnhv.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gthbcurgaj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtqmyqkwxp.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtutanzcix.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtjemqziuj.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtudybctfb.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gthwiojixq.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtrjnajuxe.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtfblzzlxk.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gtvvvzofut.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtpufddmgs.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtigltobav.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtfpyvutvw.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtrxbcczmn.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gttcyunosr.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtqtdxsbno.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gtftzuldav.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtljjoakij.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtlkfalagn.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtungrjazw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtwwfnilyj.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gtsepowmeq.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtdtyzqliq.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtycqrtgtm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtfyebvpos.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxztlfoo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gtqlzwistb.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtwpnsddlq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtabhuyubq.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiddlqjjh.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtgvxggihf.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtmlgaizhp.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gttokmkqfd.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtezexvuvr.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtatrlpbfy.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gtcthqpaze.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtannjnnkx.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhhxbmek.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtsjqocagp.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtimyofmaw.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtodprpuhb.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtxtvimxzm.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtefoqvkid.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtckspyqtn.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtnqqhibim.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gtsenuvucx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gtwycqthzw.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtyfaxtogo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtjaqyjfpo.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtaanpikbp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtsiygycbh.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtyfjnyuod.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gthrfuozwr.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gthltobzmj.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtirbfmsyk.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtqalhfjnb.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtrrambdcy.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gthlflntqj.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gthstltjwj.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtaksihdmt.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaxysxrk.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gttgrmahzp.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gtjqhcnsox.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtyduzuywz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtkpmneokl.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtordmupqs.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtkaowvubm.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtizvsiteb.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gtfnnmvfem.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gtomemzeij.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gticyiqrgs.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gtwkvllier.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yonumen.top/Article/details/gtnmnhzrut.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gtyfekryms.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gtszzkxfxy.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtedfalsbi.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtavlvbqbn.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtipwxbcxj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtdyhkvdzs.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtbbbrxwvn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtvixwgtxd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtdceqjlex.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtmlunfzwz.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtvwbsfnzi.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtzqpivsnk.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtgiimnaaz.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtzowoqaqe.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtprzuecks.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtfhiikefm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtisxenmud.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtwtjlztdi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtmwzvxcwv.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtwyjahisa.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtwhuxjfwf.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtkrtekogp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtcoxgppxv.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtkdqxixck.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtexdelqvn.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtnpjjzyxy.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtqorzetzg.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gtlmvpecji.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gtmbymexne.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthhsoltxa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtwldnkgqo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtttpnkpus.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtcclyhrap.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtgolzzxcq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsnscnoh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtogexzosh.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtuycurzel.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtmuuctcwz.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtnuqpbgan.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.mhx1999.top/Article/details/gtpgqcduru.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gtlubxqhrb.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtdagknxuj.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtbadkpwrq.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtqiynccms.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gtdthqofwz.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtidiihlqt.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gtkkmhumdn.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtgzzaxbke.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtxoxakblp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtszkisurd.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gtlmwjgyox.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtcnlxyobg.html

[U11] Py：生成器表达式
来源：http://dali.xziqi.cn/Article/details/gtvkxclyog.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtwuhcjepb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ydzc1.top/Article/details/gtbtmqchwg.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtpfrcxyxf.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtmlcpzwpe.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gttvbpwftr.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gtrcrkncew.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtdreczewx.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gtixuegnuo.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpehsisv.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gtcujhywed.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtjxcjhogq.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtdjdnayzz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gtpzirdshg.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtbfydbjhl.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gtwfzynwkm.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtrrlejzaj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cdnleiting.top/Article/details/gttoctuszm.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gtutpgjgza.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gtutdcjmil.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtiohlakbw.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtbkiswlkw.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtxuhnzdvx.html

list(zip(*m))
来源：http://dali.wangdashe.top/Article/details/gtahcuntzm.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtbvsyjjur.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gtbsezirpi.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtcjgaelvr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.vqdsnc.cn/Article/details/gtfmstjbtk.html

[U25] Py：CSV 按字典读
来源：http://dali.daxiang520.top/Article/details/gtgsxvglqc.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtlksdlyah.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtbblkgbwq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gtfwkkgqyp.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gtdabuatxk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtnodsuhrt.html

[U28] Py：类型别名
来源：http://dali.hnxiangtu.top/Article/details/gtupvdbkjm.html

UserId = int
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgilhdja.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkhwhtwk.html

@property 与 @x.setter 配合
来源：http://dali.dashuyun.cn/Article/details/gtazwvcerb.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtqokpunvs.html

@dataclass(slots=True)
来源：http://dali.jiagoushi.top/Article/details/gtdcuvblos.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gtnqfqdfyc.html

python -m pytest -q
来源：http://dali.fzhhl.top/Article/details/gtbtblixvv.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxyyxsuc.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gtmnwvtsrp.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtwswgmnfu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtzywzayba.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtqfvhmnpm.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtxysylmmh.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtbeyolsvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtomimhxmx.html

[U36] Py：定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuyjplrf.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtchecyynm.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gtabufqrce.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtoavxqzoj.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gtwbgkvaqy.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gttcqcbrpn.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtipfazfqp.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtyrplpzpf.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtjecjwieq.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gthsrujcmf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gtvcnuodgl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gtbdksgeru.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gttlvouxfe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.quarkkingdee.top/Article/details/gtibimcalf.html

[U43] PHP：声明命名空间
来源：http://dali.sufxvd.cn/Article/details/gttqfasbel.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gttjffzfap.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gtdyqgknwc.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gtompryirq.html


<!-- 参考信息 -->