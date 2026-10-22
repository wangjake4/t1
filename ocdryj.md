代发 wailian999

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gt2uxtgemiw.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2uyqveuhb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2llhzocnn.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2uzoikclw.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gt2gdqbyhwv.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbqemndp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2guqatrox.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2mfvptklf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2tsjyhnse.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gt2ynutdexu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gt2fdptycjm.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2fgaeaymd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2igszjfqs.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2jnxukpqn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj20258.top/Article/details/gt2tzgftaqc.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gt2bdcmyaox.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gt2cdmlagcv.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gt2gjuyzwlk.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2ktqrnfpw.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2ahtwooyd.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucvflhub.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gt2csakyvkj.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2xetdnwpe.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gt2qyrivxls.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2vycjpgtr.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2ndaegaon.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gt2nruqrohh.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxvgkexj.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2fatrjqgm.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2fifajxcj.html

#endif
来源：http://dali.yj20258888.top/Article/details/gt2ubzlgosp.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2fdzcjoki.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gt2vamtvaet.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gt2znktzepw.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2rjzyqirg.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrhljkdq.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2iknqpsxy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gt2fklhfifu.html

[S34] C++：遍历 vector
来源：http://dali.yongpay.top/Article/details/gt2lwyfwzcu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hnszutrm.html

[S35] C++：map
来源：http://dali.tianlin.xyz/Article/details/gt2bccwopqv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2yqexqzsp.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gt2wascwrjb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2apovqdud.html

[S37] C++：set
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsrvelok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gt2hgxyfhhl.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gt2afkzxqfa.html

std::sort(v.begin(), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrirvxay.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2pmebtlbc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnhhndpa.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2tfhuftwo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2yrfujzem.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axrjauip.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gt2yflaugvr.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gt2dyxzthbk.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2xkoqibaq.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2focwrrtb.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gt2ynvrqicj.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gt2mzcnypcg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkkjiob.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gt2llqhueeq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gt2xcyxearh.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gt2pjwumrkn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2umvdksms.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gt2xdjyxhdb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gt2jgjvbrit.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2onihbscw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gt2nblyhsch.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mffxpsuy.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2khyoxksf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gt2khmfqghv.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gt2rqucnjdv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2rggponeu.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gt2munpkdmo.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2llqhcsqv.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gt2vkjhjkde.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2wtxdlhkm.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzbfkxzg.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gt2ugltknxs.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gt2wrkazkmz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gt2pnwmhnre.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gt2wxohegdn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2xiqfbyjd.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gt2gdtzmhcj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gt2wxwahpzr.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gt2tyvxbmzb.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2wkchzjky.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gt2vtwvxbff.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gt2ymghhwix.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gt2uomprvuj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gt2nmkpsshg.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezzyskit.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdgkyfvt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vfweshjb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2jsysnmee.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2fvjexkiw.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2ymaprehl.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2xfbwfdcn.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2xnnuiirw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gotoacloud.top/Article/details/gt2gyakvkex.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gt2dkvcrwoe.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2mpesagdo.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gt2gqtpwtkm.html

val n: String? = null;  n?.length
来源：http://dali.316326.xyz/Article/details/gt2tlwautuk.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gt2ucxzmktv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2beddjvdt.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gt2yivczfpt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2qshqyoog.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gt2abilhuaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gt2nukfypyb.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2vmvegfcc.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2byddudgj.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjfcdess.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gt2wnykcjtm.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2azlwladr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2pmijgtik.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gt2hlybhwyw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gt2yqynhcks.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gt2fycpzqjx.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2dalcattu.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gt2hwdkrrut.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gt2qmktslko.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gt2csysjxbe.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2wjbbehqb.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gt2qvfgupby.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gt2phnvhcko.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2fzijjlnn.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2rnkzyxxp.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gt2cyauwdbw.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gt2unwofgpp.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2dxxjnqvo.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gt2epequgzf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdiqbxv.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gt2uhaivbsk.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gt2mtjuymje.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gt2ygkflyws.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gt2isrkizrj.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxolxlrb.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gt2jtiixirr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2nrbetqor.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2msraytkn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcxxxqar.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gt2xwbnpewb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2luribpli.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gt2cedbwjxs.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gt2bmrcavgr.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2bzcivsks.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gt2vbfloleg.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gt2qvlwukqv.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2ebyxqyvm.html

[T28] Swift：枚举
来源：http://dali.sweek.top/Article/details/gt2matuyuvk.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgomqlhp.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2pgpaapkp.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqcufkgy.html

[T30] Swift：协议
来源：http://dali.sxryk.cn/Article/details/gt2pzdenora.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gt2aizbonhl.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2cxcidxot.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2ovgoejtt.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cidgrefj.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2alxmbudy.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2ydfbyyxp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gt2hpcorhpz.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gt2ltcloovh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gt2akitjkay.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gt2zgdxdbzh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2adcjfsty.html

[T36] Lua：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2fncnhbii.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkwrphxs.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gt2cawsvelo.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gt2qiuarapb.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gt2cobbhqhf.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gt2yrqrirut.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2vrauxzxn.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gt2gsggyxma.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gt2nqfkkrry.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gt2ltvrevkx.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gt2qrngjyet.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gt2ubhxhuae.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gt2sovcpohl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gt2yubwztqc.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2uxawrcya.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gt2yeejexbk.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2hvvherrm.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gt2qyiaumuf.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2mgbypzrh.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gt2zelrjrrf.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2nsubzdqj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecayljac.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gt2ihevckjq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2hskzvllu.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gt2pdhybbje.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gt2pxpxqjwf.html

[T49] Perl：函数
来源：http://dali.sweek.top/Article/details/gt2efueppqi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2ghhtjlxm.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2enyhpqij.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gt2qxzwuqns.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258888.top/Article/details/gt2luukcgxd.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gt2auzdtpxa.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2soppdwxp.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gt2otadceuq.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gt2sphxgcou.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2iqtzcwvl.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2byfgtdij.html

[T54] Scala：集合映射
来源：http://dali.haohaochexian.top/Article/details/gt2vidlzbnn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2jdcekwjn.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2ovokapkm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gt2yyqnhmcu.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gt2xawoqjru.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2ofbnjpfn.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gt2cjfhqgrt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2gkhoiawf.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gt2ipdduxhh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gt2qgjoomqg.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gt2hzzsxqpq.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gt2ebgfomia.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gt2njwmkalr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gt2nmbgxpej.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zmdxwwet.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gt2hhagnvzs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2thfphnie.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fggelmrp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gt2vzprbwde.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrrujspe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gt2cowbjhat.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2jbdmbrek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yvedp.cn/Article/details/gt2hjdmndpq.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gt2onefntbp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gt2mhbtznsz.html

[U05] Py：列表去重且保序
来源：http://dali.xinyue.icu/Article/details/gt2ifnrcgce.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gt2vamxpemv.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gt2iwsqngue.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gt2wdfuyaty.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gt2tehzalys.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gt2zmcujlrs.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gt2bqfeogph.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gt2aecbuzge.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gt2zjvznwmm.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2yqggsgie.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gt2ponxlcuy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gt2raldwibz.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2bybjorlv.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gt2tdsjjxwk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gt2xjnjlwfc.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gt2wmyftlxs.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gt2yypddhfz.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gt2bsvfdjlt.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gt2lznmwagi.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gt2hxtgldvr.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gt2nwkoaycp.html

t = time.perf_counter()
来源：http://dali.tianlin.xyz/Article/details/gt2pmjgaqts.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gt2osijebxg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gt2uelempjl.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgjwcffr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gt2icijgjmk.html

[U18] Py：预编译正则
来源：http://dali.aizwys.cn/Article/details/gt2cwqaysol.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gt2wfcokcmo.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2alokmkzq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gt2ymuqvdcn.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukywxfhf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2qlzwubob.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gt2glymztus.html

@contextlib.contextmanager
来源：http://dali.wangshuangyany.cn/Article/details/gt2nurouygh.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gt2cjwjsdma.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gt2jclphsnb.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxwdrovc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddxftebs.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gt2mhsgucwn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2zyyaxksi.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gt2kqotplji.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gt2kqafhwgx.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjemosjd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gt2bidrbihz.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gt2nvualzrs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cucudq.cn/Article/details/gt2battiwzo.html

[U28] Py：类型别名
来源：http://dali.jinqigufen.top/Article/details/gt2oltdagex.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gt2knrvxotx.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gt2exjngjtc.html

@property 与 @x.setter 配合
来源：http://dali.sysykeji.top/Article/details/gt2mlwcdxbo.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gt2lddhyjaq.html

@dataclass(slots=True)
来源：http://dali.jyoumei.cn/Article/details/gt2frcrzoka.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2vlpvjpgx.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gt2qrxfdbbt.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gt2efaarfva.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gt2qgmpidlg.html

[U33] Py：打包发布
来源：http://dali.yj202588.top/Article/details/gt2hxpiafbu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gt2cvpclhtl.html

[U34] Py：判断编码
来源：http://dali.yangfankeji.com/Article/details/gt2lykpaqkc.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gt2rsuzbtpp.html

[U35] Py：发送邮件
来源：http://dali.jqgfzy.top/Article/details/gt2qnwiizmo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yangfankeji.com/Article/details/gt2wyhaymdh.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gt2kmixukbt.html

schedule.every(10).minutes.do(job)
来源：http://dali.pycfn.com/Article/details/gt2aoakignz.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdbvtrom.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxuanxn.top/Article/details/gt2cwxedtep.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gt2paypovkh.html

Path(__file__).resolve().parent
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnacbiuy.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gt2hvtbkbfs.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gt2csblhsjq.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gt2iqsvjlur.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2vpwyevel.html


<!-- 参考信息 -->