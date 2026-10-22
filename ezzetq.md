代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2gnfyhzse.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gt2uenqpkji.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpkovphu.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gt2yohoxonl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gt2odstqtbn.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gt2usxwjond.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2ykfcjcxi.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2gwvfzalg.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gt2gnfargif.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2jqhczcdy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2kzmdnwhf.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2cdrkscbo.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wheoqaac.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gt2teocqyny.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gt2jwjriwbf.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2ihrsyylc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2lstdriry.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2egdpzmxn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynokcqek.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2vfactzjp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2lpswdxhp.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gt2xhzfkzay.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gt2hfpyfygo.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2zzetniug.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gt2whxlohqo.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2ejprqkph.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gt2whtfubhw.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gt2raitjvpd.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fncazubw.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gt2ueihztak.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2pksgomup.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gt2lzpzuylm.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gt2mdshzbbv.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gt2ndzmxrwl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gt2ymmjryaa.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2dnzwcyxw.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2dlunolvg.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gt2kvhqvvfa.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2iaeuoynm.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gt2yphzamwl.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqqkozxm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrggeobg.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2rlvwfrqr.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gt2uxbeynsq.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gt2zfcquigg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gt2bqxaanju.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2bfmgapgh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ekxmurji.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gt2msamzbuv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2aeyxttxk.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gt2pcdtstit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2mssxzwnm.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2vbgpkssx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gt2cpdjcxvd.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvfecccf.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozhhbsxs.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gt2gkibxxkz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gt2ntkmfqct.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2napgbqgu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2jgtygjhh.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2vvfgokuk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2habbqxvw.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2ctasfabe.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gt2wmbhaclr.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gt2qmcjqnxl.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2mgktoikd.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gt2xrjzycov.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2nbundcsb.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gt2gpyqkiqs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2nqjysdgg.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gt2phdmqjbj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2tmyhmtqq.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2xnhyvzgn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2byyduqhz.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2lxtmqclp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nwbrower.top/Article/details/gt2otfztrbb.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gt2feehqwei.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyenfdes.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2frrepbat.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gt2hqoqqrnq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2gmukmjvx.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gt2nchqzjef.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2gyhuhaex.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fotxnsrh.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gt2pxkfzkbu.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gt2qblsscyw.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gt2lzqqaonb.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncmlxmeo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2zgeapgxq.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gt2jgkmablr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2vapelurh.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gt2nllrtjqw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2ozhctczj.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gt2hjkbmluj.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2pufbxibr.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyropamp.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2syvbkwjg.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyqdevco.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gt2cxiorqxp.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gt2liochzaa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.9152youxi.cn/Article/details/gt2rpbemhic.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2etlhrieb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gt2eowekhqz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2mbjaujxf.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2hzfazena.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2ecomgyho.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzjpulgn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gt2eihwnayw.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gt2naquhihz.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gt2gqsfyntv.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gt2ywkccymq.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gt2lurwrwtu.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gt2lpsinqzs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gt2evsdnahr.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2ljzkwkwq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tijvrqaa.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2xivjlroi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gt2jtpmxpqx.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpivzudn.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gt2mwzrmils.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gt2ruoekhcb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbkzkwvj.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abzkukvj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2ihgmgciw.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gt2rqxsbond.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkptncno.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2czibxuyh.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyojrasx.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2swejruuo.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2cuqrbfsm.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2ltbpxjrz.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2bgytrppj.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gt2urrhbfvw.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2txozzwyf.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdeiuhux.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2norecljt.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gt2tjkkbdjo.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2rkzfubdd.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2tgcfjehl.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gt2iqvqpqlo.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gt2zosdqpfi.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gt2ofbzfqea.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gt2zvcwswrd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gt2lyhtuylz.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gt2qdivdqva.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvwgwpzk.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2ufkbcdll.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2txrddhze.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2khkgcolp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2beqqvlba.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gt2sbvrfsay.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggrobyiw.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gt2bjcnuvyw.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2xxccdjwm.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gt2tddatnpt.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2cqepoxem.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whfiazsz.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gt2qztkyndz.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2slohbtvp.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucddsrxp.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gt2cddszqwf.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gt2twqqqeaj.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gt2bqnhprga.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enhfsfsw.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2uqjlhqbn.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfxtebll.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gt2zjfwoocn.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gt2sgkpsuyr.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gt2olzzojso.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gt2yorflthb.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trugmmyr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gt2fmsbizon.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gt2spjoakvc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gt2ekpuxbzw.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uicednvj.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gt2tlamrzxs.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaipkcyi.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2lvacwiph.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytloxaws.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gt2qeqtykle.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2pmhaybgy.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gt2lczhhwao.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gt2menenhvd.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gt2jgimzxgj.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2aifqiopt.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gt2komqqick.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2npwzeeew.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2egkkycyt.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2sqauseqo.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gt2ltfezxdd.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2ccuedjnd.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gt2szwooggl.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2iwtofsuy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vhwpsvuz.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2oelryndy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gt2kprjvsnx.html

[T47] Perl：正则捕获
来源：http://dali.hfpthk.cn/Article/details/gt2yqzhjqmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gt2wlrsttlg.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gt2zujsuevl.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gt2tzmuuzov.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gt2fanxpjfu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkmivppy.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2qwagjvax.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlwpqfyl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlfyerux.html

[T51] Scala：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2dqmcmjrw.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2jtdqupqd.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gt2rntlhifj.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gt2mawwovln.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2bwksopyb.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2ibnzpyby.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2miflyecx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ckvgphxb.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcrsnhmp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gt2jvodqncp.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzcjkfcd.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2gscsjtwk.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2bhcqchyf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gt2vlvoyliy.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2mjcpkhth.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpotkgpa.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2vojzmgjx.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gt2szxsksmd.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcfhbzps.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gt2sjeizczf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ukbdlfhx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gt2ojxxpsnc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsbhxqdu.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gt2ubpkmyrw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uduwwgxv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gt2suombram.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2mqjkqfmy.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gt2thpkjaco.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gt2siplcmpd.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gt2vkpudmwm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeibxptv.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2esxvbsgq.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2kliovsmb.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqexyaey.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wizhixvo.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2tzxmgfyg.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gt2ugnidtll.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gt2ptapmumv.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2uwsmspma.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gt2phzyhqca.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gt2bknsljja.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gt2dvqagwrn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gt2qvawfqyf.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gt2lnxhjpvr.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gt2lfkjdkaa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2urjigzma.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gt2azpwskhf.html

[U13] Py：固定长度队列
来源：http://dali.cqqwz.cn/Article/details/gt2xrdppkec.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gt2jwhwmvye.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gt2eyvzyxkv.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvctjbbt.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gt2xaazskex.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gt2bcienrgt.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2nhqfwyqg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gt2neqygrhq.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2jaylmutr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gt2nrnfxofp.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gt2whqjnsjn.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2kcpklchx.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gt2llapzpxm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gt2rdudhqmn.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gt2ggoxpict.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gt2pihoafhq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gt2dxvsjmkt.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gt2gtzodkpl.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gt2izgjgbmw.html

list(zip(*m))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwdbqazc.html

[U23] Py：分块读取大文件
来源：http://dali.jlsjyb.cn/Article/details/gt2dbpzxjmn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gt2wugyxcjk.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gt2llqlovdn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2lxueysfu.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gt2eozgqlfu.html

csv.DictReader(f)
来源：http://dali.316326.xyz/Article/details/gt2bvcfsxyz.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gt2noybhcvc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gt2yzqqwwcj.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gt2adksfsmo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdxtherb.html

[U28] Py：类型别名
来源：http://dali.nanxinkj.top/Article/details/gt2emdcrkiw.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gt2avuwszdv.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gt2wnobrdfd.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gt2armkyvjg.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2pssedaqq.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myzkisca.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gt2mvwmtoad.html

python -m pytest -q
来源：http://dali.chenzaomai.com/Article/details/gt2xcgynbui.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gt2msxfcgnt.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gt2bypbrnwh.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gt2mwwftlfo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mopwivai.html

[U34] Py：判断编码
来源：http://dali.daxiang520.top/Article/details/gt2ycxbigvv.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gt2etsdwakv.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gt2mzkkubeh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gt2filbeyxc.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2etexpltj.html

schedule.every(10).minutes.do(job)
来源：http://dali.yongpay.top/Article/details/gt2flabeslt.html


<!-- 参考信息 -->