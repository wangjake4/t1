代发 wailian999

int main(int argc, char **argv)
来源：http://dali.iojbl.cn/Article/details/gt2xlbwvcip.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gt2iylywjnr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tttuulbx.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2acyfddrc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2abtzewij.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2augnkxxy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gt2ftblgxgx.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2zcqsbaii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssjdtrzt.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2loanajzx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gt2lnrkgwlu.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gt2qwqczhlw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gt2exhehcqy.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gt2qujajsyu.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2quvekshr.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gt2cbnrjkax.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2vsxmhkoz.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gt2fyhqeqtu.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2rafbdxdz.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2ypkkpsjc.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilwasppb.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gt2bmbnwaiz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gt2jxthllpg.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2qdwbwcsu.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gt2zqvkvvgy.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gt2xogltgpy.html

#endif
来源：http://dali.wangdashe.top/Article/details/gt2ypaoijqv.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ezsesbil.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2qftujmfn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gt2xxluyllo.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erryoppj.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gt2itrjyfyo.html

[S33] C++：vector 增删
来源：http://dali.shuidangran.top/Article/details/gt2nxhxbimz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2hwwtspga.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gt2ckpxrgcn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2tmqteriz.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gt2fujqgzrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2gstcbfxl.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gt2qbayhqmh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2zxcvwiom.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iriofihk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2rsjnpcst.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gt2pjxizzuk.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2ruhkjkzx.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2znsflxve.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsebbrof.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gt2ljpclmfx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gt2vylopfkl.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2cdksyugd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gt2oyzllwng.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2xnrbvgec.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gt2zdhzhenc.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2ieziyiei.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gt2lbuikpuy.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gt2vqlbhedw.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eeftsokk.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2ixqwqnwh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gt2bflbmwyw.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gt2wkimswxt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qijsbjae.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gt2sipwzlhx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gt2inorvnyv.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2hgbdzyvz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2seuoptex.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gt2cfkoffoq.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2nuufbqmb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gt2gfscpsda.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gt2mwwkpmtz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkjngwat.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zifnudej.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgypbvas.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqahelr.html

int size() const noexcept { return n_; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gzvdunyt.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2eapgmbqx.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gt2mgljfgtf.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gt2achnzxwh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gt2qjeonhrc.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2rezyzhlq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gt2rolgdpni.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gt2jlekyzzf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2bnqpusfs.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2znqzkfwg.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gt2hivaptax.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gt2wdoejbhh.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gt2dydlypph.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2myslhpte.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gt2qfwdtvui.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gt2cxsaedmc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gt2fstqsybl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yajhgewb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gt2fxsiunlz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xbuzjxuh.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2jhdbbtno.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2ozfbgjik.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2hmrpxbwa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2hqaagfap.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gt2wytwmyty.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gt2exkkxwyp.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2acoffsib.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gt2tpdnmwed.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2ecrqisde.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2jkuqpufu.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gt2ytrmgjcm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snxrytuj.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2glguvite.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gt2qqrwvawh.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbsyifvo.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2nvxexxkv.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2dbjuzfrv.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gt2sztyzjyr.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2omkpgusi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gt2fmljwvdk.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gt2hvqhwabn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gt2ovabmwxs.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpzxzjlt.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2imrknssb.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gt2rxkfkwea.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gt2gzopztcy.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2nenzwgwc.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2mgnnhzcw.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2hkcixljd.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndlsftpf.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2bcsyxuqo.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2wokogwnf.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2byyfiqcz.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2amqyccve.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2dvjqoeyr.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2bglxucmy.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gt2kolzofqg.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gt2umxtyhir.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gt2yiiddpdm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2eochpsjg.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnzcpuvw.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2cngtpiyv.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmdbfllm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gt2ssvcojzt.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2oqrkfgwd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2vdgldflu.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gt2ipnyfzpa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfcifqsf.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2eaplsyim.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gt2qbutriua.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gt2kovjzpqn.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gt2damznfbp.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2odqfyuwy.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gt2zkoadxkb.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2mraxmcqr.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gt2wwletaut.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gt2zcnrfuzh.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gt2mnktbszy.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gt2wbdkansr.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2ipvrezbx.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2supecwjf.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2vklnwyqi.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxylqqvp.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2oaugoepi.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gt2dnpfmlxh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2mspwcixx.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gt2qwdtzxsa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gt2fzuksevw.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2zqibpkmn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gt2jwfzclut.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2mecvbejx.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gt2cffkobnp.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2ntzziyur.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gt2nmtserek.html

[T38] Lua：条件
来源：http://dali.hnxiangtu.top/Article/details/gt2fnxlqpgs.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gt2liefutcd.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gt2gvjdcphe.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2awsushlj.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gt2muuincvz.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gt2tnvqcbcp.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2chuampiz.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2awcvmtgd.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gt2repmeddn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj20258.top/Article/details/gt2dngxjkkn.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2tlmkyuil.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2ubzksivb.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gt2lrwguuzz.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gt2kqipgnfd.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gt2zueejpln.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gt2woybmtkm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qyivggwp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gt2echoxrmh.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2gmxqxqyz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gt2egrxazhh.html

[T48] Perl：正则替换
来源：http://dali.zhongyouzk.top/Article/details/gt2hlqcpmnb.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gt2qozmqepk.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gt2bltmzzmw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2wzsunidi.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2giimnvny.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gt2pfwnmgds.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2aeurjvfa.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gt2xepfiepz.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2wcitynet.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gt2mxzfrrlt.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2tvslwlsx.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2krhmvuqw.html

s"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2adqodknn.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2bhtaowcz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gt2rnobpgbo.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gt2vawmxcsq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2stdulznm.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gt2yhaxulyb.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2tsxkydsu.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2rqtsivwq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gt2uhhxdhpp.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gt2cknciuaf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2lrdjfupr.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2kybwkvdr.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2gaunubsw.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gt2tjipafmz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gt2slyomjpg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2zhdbjpjk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2hpvhuyir.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2hwaajrel.html

[U01] Py：创建虚拟环境
来源：http://dali.yj20258888.top/Article/details/gt2bicyiriu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gt2kfnxacrp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gt2sasekifq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gt2tydhjkei.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gt2dmwszgub.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmswydil.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gt2hxtgxdib.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2ftaybaey.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbfvxcu.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gt2felupkmo.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2qoyvnqof.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gt2tskjunie.html

[U07] Py：反转字典键值
来源：http://dali.jqgufenzy.top/Article/details/gt2eoqlynsc.html

{v: k for k, v in d.items()}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffmsrnvq.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gt2cwlbfvqz.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2zgpowddi.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gt2oeweyvlm.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gt2snezhomu.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gt2gxsqnlqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gt2olydivyb.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jebzlvza.html

(x * 2 for x in arr)
来源：http://dali.shuidangran.top/Article/details/gt2ivgnenoc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2omeajyai.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2lininwwv.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gt2xcoltbtf.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gt2jfdzcrzd.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gt2ondgqtdv.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gt2wrqumbml.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gt2xjgpplgi.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gt2fbvcbosu.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gt2dfnzkofd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gt2dglkvzsq.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwvcldfm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gt2nsjbhcfq.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gt2excsgeac.html

pat = re.compile(r"\d+")
来源：http://dali.cashguo.top/Article/details/gt2quxzlfii.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gt2cgqvkyed.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gt2tofiszmi.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gt2wgyjxucv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gt2kfazyrkp.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gt2uxxdovmx.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gt2jrmxpawl.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gt2tlvqudng.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2vpzjcpln.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2fezeffzc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gt2yufcnpms.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gt2wxoqneix.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2gcoxvzfc.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigufen.top/Article/details/gt2yztzsnqz.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gioxulrf.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gt2xiunnjvv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gt2mrphakrw.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gt2exjrcmek.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gt2hylxauho.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gt2hgrqwesf.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gt2bhtrwrcj.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gt2sfmkrkxb.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gt2jtjejbxk.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2nvtjybsr.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gt2qetqodpt.html

[U31] Py：单测
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vetjzupg.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gt2fpfeidcq.html

[U32] Py：代码格式化
来源：http://dali.yvedp.cn/Article/details/gt2xxudxoqw.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gt2crveemih.html

[U33] Py：打包发布
来源：http://dali.zhixingplan.top/Article/details/gt2ynglnoag.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2kdqqnvzl.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gt2ipvqrpxl.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gt2wyqbepcx.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gt2rhojaiwa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gt2zfsaxfuz.html

[U36] Py：定时任务
来源：http://dali.yongpay.top/Article/details/gt2rjovqjvr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gt2mdbenqbz.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gt2vnhtsfku.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tian-w.cn/Article/details/gt2vbnwkxpx.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gt2jfzvxoaj.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gt2bspithhw.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gt2ytmdpifl.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gt2jfuaqiwl.html

[U40] Py：打印到标准错误
来源：http://dali.9152youxi.cn/Article/details/gt2dwxtctrz.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2oaebjybq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2cpigzztz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gt2axhzgngq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tianlin.xyz/Article/details/gt2zjhiqnbl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dianchejie.cn/Article/details/gt2gxrubiwq.html


<!-- 参考信息 -->