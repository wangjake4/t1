代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtectjuaku.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtgzngykse.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtndvnakbx.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtnhixgley.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gtkqfsoiga.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtjqulbnnd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gtmxjrtwap.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtlcrrsayw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtsdqpfnxn.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtqsfnovqo.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtewzuvcri.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtcdptjqby.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtvpivdlpt.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtygcnuhmi.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtejiapuak.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtjinivlfc.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtvcjxfujc.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtnzupbfpl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtjqvxeoao.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtdttbrsqi.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtebeiwvct.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtewaawpyl.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtabgzlsqq.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtqskyfrqh.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtcnxzgvcb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtimoldqfj.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtbxqbxwso.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtkfsmbrht.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtaouxmorr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtnfbgxaea.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtenmwlugz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gtwjyrvtqw.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtqyjjhqiy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtadumiphs.html

[S36] C++：unordered_map
来源：http://dali.zhixingplan.top/Article/details/gthokfnqsy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynstekid.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtfhyaiiic.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoijouob.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtyfctuqah.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gttjufwqot.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtqazmbtwk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtcukhidhb.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtfsnjmmha.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtmvxzjwdp.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtqcnhplyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtoklklusw.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtrctvpixe.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtrlnktchl.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtpnodlvar.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gthfddaeqi.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtuugcurnd.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyzvzzowa.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtbxpynqid.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtefsdcupk.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtyuuworew.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtalzdsypa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtafatnjdo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtwzrthcng.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gttttjtksy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gttqzsmixs.html

while (std::getline(in, line)) { }
来源：http://dali.sysykeji.top/Article/details/gttchahoun.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gtsylmxbgt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtaadcbftv.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gtegrrtoec.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtkjhveiet.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtqjynzbet.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gtnlapwhbg.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtktepnqlp.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtbeuoskkk.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gtcdsblwik.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtppjcbbek.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gthltnrzfp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtgwzcwioe.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwshzoge.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtgeyvkirt.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtbgqgnzxg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtnxtvyaiz.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gtzpkllleg.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtdnlnnufo.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtczgcreok.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtndkwydii.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtfbtavytl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtzbhfpaev.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtqfmzcipc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtyqgamleb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtflybfaev.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtfnfjmyuv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtykfjdibv.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtpasgdnot.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gttgzukwmf.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtxseaozev.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkowsgrl.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtwtloiscv.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtgotwitel.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtkoawibrh.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtgflhgorp.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gthnqrwxrc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gtjgzmwysq.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtruenkwac.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtxayutruh.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtuadwvskq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtpunpnazz.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtrbzkmhkz.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtgeufbswr.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtuiimjqnz.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtibecdupk.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtekubpyah.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtpgoqdonp.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtqhhbjsae.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtvmvkiizr.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtocdmjbvu.html

val (a, b) = Pair(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtalaxykwn.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtyzgtmazq.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gtqanzsrkk.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtxmujgala.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtaptvgsgk.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtwvvsmskl.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtrulyeimm.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiifyounq.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtvwthqfvy.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtzvtdfpju.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtjqctyehy.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gthbvbigft.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtcnenmuwe.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtffvuexuy.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gttelybnpg.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gtpnjbqgyj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gttntnpgyg.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gtqonodegh.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtfnizdkzi.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtffcsnomq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtxsgttmsp.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmdbgbjsq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtbqbdiric.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtdbiohqba.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtovonrrzp.html

[T25] Swift：结构体
来源：http://dali.birdmap.top/Article/details/gtkvkslzdk.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtneecbpeh.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gtdyluumzi.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtqvnbaaqu.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gtkvudiqlg.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkogjffcv.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtvuglidmv.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtyzquvecw.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gttpblqeph.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gtezzlfwuz.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtbjsoqihr.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtllvpfsfh.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gteavbwnzj.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtwwohyfws.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtoksanvhe.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtckcmikdg.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtnamvfrit.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtpevayqbp.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjavqfqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtegowkvzd.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtctymeski.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtqswnahkc.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqnrdrlh.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtkrwcship.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtakufoban.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gtjocqwxzl.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtcideuajr.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gthoqsulju.html

[T39] Lua：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtaocccbfo.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtsxanznrp.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtzbtmlsmo.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtoftqfwyr.html

[T41] Perl：Hello World
来源：http://dali.yj20258.top/Article/details/gtckaqrlqm.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gtulqqqkle.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtwclkjhvb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gttwkxahsw.html

[T43] Perl：字符串插值
来源：http://dali.birdmap.top/Article/details/gtzsnqdpyg.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtfkwmtjrm.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gtmjprdkwo.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtvzrpcygv.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gtgyowmbyu.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtolhkkpzq.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtgnljafqb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtqdzaztwq.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtcooaczdu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtecsepzft.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gtvspanafg.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtzbylfwug.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gtxtqwlhne.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtctksxrgp.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtkywrygkl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtfhaufxzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtzxvolvrj.html

[T51] Scala：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtyevhcgko.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtedorelwg.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gtybupmrgh.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gttobmmrpf.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtymhhwqjb.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtbreeshrl.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtwksmvhph.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtzbkaagyx.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtlhwexoed.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtlodzbcof.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtsxenzczq.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtkdvadifx.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtymcycmdz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gtwjpvjpjq.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtnpuxqsut.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtdshziaqc.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtvnbrmtzy.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtinlacvyo.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtofvndusq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gttlrllapz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtuupgdqny.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtjkflisuq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtexxxhylh.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtdsjeelgi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gtonpjhdjq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtwhkpqfih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtqyquqjzy.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gtfffdnpyi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtygflwzwu.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtjughmbkn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtjcebbtjf.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtxmggoivt.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtzaeimpfp.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtwrbocnky.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gtxlhkceaw.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gtqbqwtsea.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtxjhilqsz.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtanngxkfn.html

[y for x in nested for y in x]
来源：http://dali.fzhhl.top/Article/details/gtwlruurtd.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gttvptxnkh.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gtywwaxonb.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gtqbieykfx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtdegbzmsw.html

[U11] Py：生成器表达式
来源：http://dali.yueranfly.top/Article/details/gtvvhuyszf.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtvgwxlztu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.havefunace.top/Article/details/gtwrtdaavk.html

Counter(arr).most_common(3)
来源：http://dali.birdmap.top/Article/details/gtlexrqzbg.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gtmiwlzrkf.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gtndngrzvy.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtjfmifvsz.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtcixispvz.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtouafgozb.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtdpdlvbdr.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtqvwnrvgw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gtordxdirq.html

[U17] Py：初始化日志
来源：http://dali.yuanzhike.top/Article/details/gtvrpavvrb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xziqi.cn/Article/details/gtsgiqrjpj.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtowxdjxrr.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtlyoywttv.html

[U19] Py：正则替换带回调
来源：http://dali.zhongyouzk.top/Article/details/gtekvnhruo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtqnklznrs.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtkdxnjtkc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtelixvtjd.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtlndngqku.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtfrhpdlpp.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gttulcavrh.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gtywaferpf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gtaekurmsw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yvedp.cn/Article/details/gtgbuzhhog.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtymrkxdle.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtcbiympar.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtldscuzjs.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gthixgrurh.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gteisovdsd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.316326.xyz/Article/details/gtujgxaisn.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtadhcckko.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydzvhfyl.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtnsqvawza.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtsylfjuwd.html

[U29] Py：属性校验
来源：http://dali.zhengqikj.top/Article/details/gthxmmpexz.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gtmlmrvtql.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtbdnihzte.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtqimbhumy.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtxhuglnec.html

python -m pytest -q
来源：http://dali.zhengqikj.top/Article/details/gtjctyzayl.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtryjjxzbm.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtcvqisgui.html

[U33] Py：打包发布
来源：http://dali.yj20258.top/Article/details/gthticwolo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtqpiekqcf.html

[U34] Py：判断编码
来源：http://dali.hammf.cn/Article/details/gtstnzvglz.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gtlwrcdpoa.html

[U35] Py：发送邮件
来源：http://dali.pycfn.com/Article/details/gtmglolajh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gttylifdha.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtmsnkwgac.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gtbltbntyi.html

[U37] Py：读写 Excel
来源：http://dali.iojbl.cn/Article/details/gtphfdxpqp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gogol.net.cn/Article/details/gtcqkjuyoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigufen.top/Article/details/gtwujxkfvv.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gtrsvlwbls.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtxvopylta.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gttagnmlzc.html

[U40] Py：打印到标准错误
来源：http://dali.hysaishi.cn/Article/details/gtdirztwcq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtqgphnsse.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hfpthk.cn/Article/details/gtfwrbmxzu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsecbqmlc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.quarkkingdee.top/Article/details/gtdkhrdehm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.bjfxy.top/Article/details/gtuhewzcxi.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gtoucsvxxy.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtocprmxdf.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gtbvgjqiyf.html

declare(strict_types=1);
来源：http://dali.shuidangran.top/Article/details/gtyoertwub.html


<!-- 参考信息 -->