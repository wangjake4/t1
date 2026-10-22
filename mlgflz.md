代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2mltgucar.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2ydrrsepd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2mdxugdme.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gt2eukqsaxc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gt2wqtpfyiy.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfuqmich.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gt2qpazuulp.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gt2akzuzgad.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wezpmcts.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gt2lyoyrtmd.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gt2alfwnifc.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gt2hukolluf.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gt2vmemfnml.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flmajsiv.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2zdnuidab.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gt2yvlzumvz.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gt2eeynwgwd.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2egqjziak.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gt2jgjustam.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2rvomnoeb.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2jloowzwe.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gt2icsnnbid.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2yrynhwpf.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyaahipq.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gt2nkjyzzjr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gt2yhywdkoz.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnhaooab.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2fynwvpxx.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2sayilmls.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gt2nshbxoep.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhenirqd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gt2qwoaqlua.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gt2bfguzlrz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2zblpnmeq.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gt2mjdkokdw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydulswhw.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gt2eqaqgzet.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gt2cqyeahuw.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gt2izkuiofo.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2wuswodhe.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2lhzhetlm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2ofrcpofd.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gt2qkwrxrxv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctajwequ.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gt2bxmiwvus.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gt2sbthihss.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gt2rxkqyyvs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2blqkdjfy.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gt2crvzitkq.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zborrfox.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gt2ogacdvcr.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gt2mcqvglrd.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2tabrhnmg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2ytimbzkp.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gt2nviefzfe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaagpja.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2vrlotdds.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gt2csuhlcbb.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2kyuotsiv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2litezrle.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2axljwvfc.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2fcavhnlo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gt2nqmyejue.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcsstgpj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpjczkwo.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gt2revsoazq.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gt2grokypqx.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2ljrledqq.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2vxsejkev.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2cagpgphm.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gt2wjbuhjwe.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2qujlccqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gt2qjnoeaar.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2bqczbcfq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gt2npxhdnzm.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gt2zlhorqeg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kifbpnsd.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gt2edrpukxg.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2lsfnggmx.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2njspblco.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gt2spdhotsx.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2enpajwhn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gt2worvwqdl.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2ubzfnnmp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2ipcugumi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2vetpeguh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gt2zjcaktra.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2dfexilxa.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2fmbobxnt.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2ypgusnnb.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkcdgnip.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gt2zdatauwy.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gt2kvqhpmlp.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gt2kaocbkyz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkaebzz.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gt2usvyvsnw.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gt2ytezroqb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gt2axvwmudc.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2qgabgxzf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2phbtvseq.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gt2mslnriwz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjlryluu.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opsbjitn.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2vzljbuee.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2slswnkqv.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gt2pygdspjq.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gt2mqxwzuyq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gt2pzebueyq.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gt2nznzozva.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2ulwvurjg.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gt2aiqnjito.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2ddpadvsk.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gt2dezetico.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gt2glpreysn.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gt2idbcjjch.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2yjjpjiwt.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2gfshwkmk.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gt2avebhwtz.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2jkfljqnl.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gt2lvzhbdsx.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2mkddkuvs.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gt2cfkowdbm.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2hcvlryrb.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmddmxbc.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gt2hqjdmupm.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gt2czznmcxg.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2shnnizpk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gt2pztcjfsg.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2bokqvahn.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gt2dqsyzsdf.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gt2pfvlhaaw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2ahbrcfsh.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gt2tkyntxjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2ulnuelqd.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2eguxgaxu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2ljavlkdn.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmihuliu.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqgmceha.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gt2axmvjymg.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gt2tmcdsmqs.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gt2wolrbdyd.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gt2hthuxdye.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2amulmcum.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gt2ckfbufmk.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gt2fgtkiocf.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gt2pxcqfeoq.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltlrqncq.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2dojjnbjd.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gt2hfztmszl.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2edgtnsoe.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2blahoglj.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2pgrcxeak.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gt2rxdsnqcm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gt2gnydvick.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2vbiwxbbc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gt2apdgdkxz.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gt2alrjclos.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmtqrujy.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gt2zpnbrhjw.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gt2ezkphxzg.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gt2nidetrte.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oskhlrov.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2cviotohg.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gt2hwdulvok.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gt2znadiocv.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gt2lfkbklje.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2rotcvkfk.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gt2oaneudck.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gt2olwzrjxl.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2pnjuejag.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gt2eckdbcla.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoewwkze.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2gpwbzgpv.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gt2xfcsyvpn.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2btvprrqh.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gt2kwslvgzp.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gt2rikwgnxq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gt2xzabkggy.html

[T46] Perl：哈希操作
来源：http://dali.xuanzx.com/Article/details/gt2btqtmcdf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2ynljvrda.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tequoxkn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gt2rkdrruff.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2vojzyaem.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gt2guswxtxt.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gt2ocdtagul.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2krpgbyym.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2rzzkhbyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bycwrftx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkmmlld.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2kzzutdjr.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2vxgmpzib.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gt2bplbsezy.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2bhwnaegg.html

[T53] Scala：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2qjsjsfar.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2alxeimbq.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2lxzvccka.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2kwghnook.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zzcungty.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fnycolri.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gt2ftrvducs.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2sjppervh.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvkrtxus.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gt2zrbrvsvl.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzqxgpjo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzynlgkv.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvlwjxlg.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2ausvxzzu.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gt2aaoymitn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gt2rgcvveff.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2tcwfjgue.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gt2kzaqobza.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2aplojmae.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gt2jvibqkzx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gt2fqqyuefh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gt2jfwwvgdz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gt2msusjujv.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzyypqds.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gt2ovnucqux.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gt2pkymvxjm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gt2mwtiqhop.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gt2nlyrognh.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2afmgfqcu.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gt2uuzjovdv.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gt2aokhiczf.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gt2vmkuuclm.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gt2pcxidcwj.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gt2qvmbcyne.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gt2vuarievd.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gt2mwicsbtw.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gt2ruuvxbem.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gt2phbmsjvy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gt2azepyegf.html

[U11] Py：生成器表达式
来源：http://dali.zhixingplan.top/Article/details/gt2qougeasl.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gt2xzhthsyh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gt2xdcugyve.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gt2faxxyncn.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gt2upxcwyce.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gt2ilsdijqs.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gt2uyuosibp.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gt2aqaixfxx.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dygrsqbn.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gt2hgkwbnwm.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2upbaghbw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gt2lawjqvho.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gt2aldkxxpf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gt2exuyustv.html

[U18] Py：预编译正则
来源：http://dali.zdqjudy.top/Article/details/gt2tuvgdzjh.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2naxapykr.html

[U19] Py：正则替换带回调
来源：http://dali.yuanzhike.top/Article/details/gt2plujxrrl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gt2bqahjptd.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2hnfpnqbp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2sjwphmcf.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gt2axowsvxe.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gt2ilyiaccc.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gt2avayxatj.html

list(zip(*m))
来源：http://dali.iojbl.cn/Article/details/gt2njwionkt.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gt2qgmbhgid.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gt2bzxexide.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gt2crbxyxge.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2ikhefesv.html

[U25] Py：CSV 按字典读
来源：http://dali.shuidangran.top/Article/details/gt2gqortjpe.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gt2aqaclsuv.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gt2klbinjtf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwdkmwfj.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gt2buwzncbm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rchzdjny.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gt2hnfxvicp.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gt2xtfxckdp.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gt2ipdgpryc.html

@property 与 @x.setter 配合
来源：http://dali.jiagoushi.top/Article/details/gt2rskccfni.html

[U30] Py：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tuiyazro.html

@dataclass(slots=True)
来源：http://dali.hfpthk.cn/Article/details/gt2xtqkcelu.html

[U31] Py：单测
来源：http://dali.shzxlz.cn/Article/details/gt2fotowcbl.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gt2nvaqavcc.html

[U32] Py：代码格式化
来源：http://dali.zhixingplan.top/Article/details/gt2gsffclio.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gt2uowzpahv.html

[U33] Py：打包发布
来源：http://dali.yuxming.cn/Article/details/gt2hhpwdnwo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gt2qjqbwucx.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gt2bbpzldwp.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2toqanhjp.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gt2euqkobge.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gt2rdxhhaae.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrfxvekw.html

schedule.every(10).minutes.do(job)
来源：http://dali.cdnleiting.top/Article/details/gt2pxwecapz.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gt2izisdpfg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gogol.net.cn/Article/details/gt2wezhlnhv.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gt2hrzfkiuf.html

Path(__file__).resolve().parent
来源：http://dali.fzhhl.top/Article/details/gt2stthngez.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gt2gjfvnvuz.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjriegxn.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2zkohvotb.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtlbmkzn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.snrcjt.cn/Article/details/gt2kfasktko.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gt2yrgtrrvk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gt2nlubsbcb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzzgciuf.html

[U43] PHP：声明命名空间
来源：http://dali.xuanzx.com/Article/details/gt2wdndcyrc.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gt2dsvepmda.html

[U44] PHP：开启严格类型
来源：http://dali.dashuyun.cn/Article/details/gt2pmydmtwn.html

declare(strict_types=1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzkivykp.html


<!-- 参考信息 -->