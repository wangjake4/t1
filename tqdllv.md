代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gt2tbenxzps.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2begnwcbh.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2kjfhrzft.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2tfqunjtg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2ouqezwiz.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gt2gbjaabxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgmqdfnr.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gt2ofheqkya.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gt2dzfrajrw.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gt2nqyuhmmo.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuptqeeb.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqyxrejf.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gt2ixrkorvg.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2vltyjbcf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoglqfzy.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2oqrevrxb.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gt2dzcyvxnk.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2gmwqhuvw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2iynabbbw.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdowwram.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2gqerylsp.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkqvtsml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2ymsrkicf.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2nyqcjvtp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2votqrwfv.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gt2rboxnajl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2shlngkrw.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2paliauqw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gt2swjzceib.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2xdyrczqv.html

memcpy(dst, src, n);
来源：http://dali.hongshengwenyu.top/Article/details/gt2arruqwzb.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gt2tuuimkog.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gt2qsxfyzwf.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gt2gfzrkwcx.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2eahuanlo.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gt2rhcwhtir.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gt2igoowzpw.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2fsduimbu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2uezedcpm.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gt2zfsjdrpv.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gt2yrfpcozb.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssqfdwiu.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gt2rkupewga.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2swztyxlv.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2lmgspscj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xylfe.cn/Article/details/gt2ofsfmpno.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2tlgsrdbu.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gt2nrwbdfzt.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gt2gnegvkfk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2dujddeew.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gt2ixgeslak.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gt2mqcexqtg.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gt2yeznvtvh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2yrxbkvgw.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gt2ihibkwko.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2bfqadoqm.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2nsvwttet.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2melikqui.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2ctbwevae.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mflpmvzy.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gt2exfwbund.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gt2zovbafbo.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2retlucab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2phyoophz.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gt2lwnpekhn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2nxipwgnr.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2bjhodojy.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gt2hkfnjwjr.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2zpdqjrat.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqiwyomn.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gt2ptxdcokh.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gt2yqowfevi.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgepiscr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gt2uwptpoqy.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gt2tqndmzhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gt2pnevmidv.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2zxwycnvm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gt2ntmqztfs.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2pkwmwcst.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gt2scgdvnnx.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2cezrzyud.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2yfalbwii.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2axipaavn.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gt2chmcyoex.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2viapwlqo.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2xwoyotoj.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2oirsodrr.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gt2vktggexd.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gt2tuswiexe.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gt2zlmtylrs.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgvqgcib.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gt2bpwueusn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ddpdqxhg.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gt2srxzpgxb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2jczwyqib.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gt2lufdtlmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gt2fudwzles.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gt2jnfovayp.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2drhgjtai.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmzpdswv.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gt2eurzriyg.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2zyitslno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gt2juvjmyxd.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gt2twquqily.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gt2jtsdiebx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2cutobqdi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2nkomytuh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sngtnguy.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gt2mglyledp.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2ksxzyhce.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gt2hfrestoe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2ewwmnyev.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gt2hswyuuiy.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2frsmwwyk.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gt2fltvxfxh.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2ofrjdpey.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2xsousnho.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gt2yakmhzxr.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2puxdably.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2wvsxlaer.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2qiuofqaz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2eddmfmlw.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2okvhuxfi.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvkuprpb.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gt2xafmofwh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2svgrpsvl.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gt2ttanlvns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gt2zdndnwjv.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2gibqvjje.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2onxccaez.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2gqkniocf.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2mwevstnj.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gt2uewymxfd.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gt2euurvhuo.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrunblvc.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2saxzdwwb.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glekjfde.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkjprsmj.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2crhnkyew.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2aclezgfh.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gt2zbiezqvy.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gt2tonmkxxm.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2ejgvftxd.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gt2pfxokaxh.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2hkbgxaph.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gt2lpmwibib.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmgshyrg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gt2smbvsakc.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gt2xqrcfxfw.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gt2tmlfchrj.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2ouhqfxwl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gt2ixkgubnw.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gt2tsitsgmb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2btalwtup.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gt2mwoftucz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2bmifrcku.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gt2xvycppsb.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2psxecuvr.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gt2iziixdcc.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2jimqfuer.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2kopelomt.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gt2kkkiokhv.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gt2ykgxszcj.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gt2ftvexpcq.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gt2jvmtyckb.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gt2rflzgfih.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gt2wvmywldi.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gt2wheewpwe.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2fowpevgv.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2cdvvkngm.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2vompbtgj.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2cgxbbsqh.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gt2obvqyzce.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2eskmittx.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gt2buvyrvrv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gt2gvdbvrgn.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gt2xwfkdqpo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2ctfmfmfp.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gt2kshrpnme.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gt2kiqsiyeh.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2icgojuuy.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2abritpqu.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gt2iqnsmusx.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gt2ecxmgdar.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2tfqtpubo.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gt2qycepjnt.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gt2ccqzclzk.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2agrfokjh.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2ddhphsyn.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2prxsyvbo.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gt2outoeyxc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gt2ncplsayn.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2lhudpvyt.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gt2rfjdvnms.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gt2psczgzrv.html

if ($a > 0) { print "正"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2edwnmxkf.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyqfmbeo.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gt2isvsalaj.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gt2noivaheh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gt2qimpvbpw.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gt2wdcblnjc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gt2kgnyfpba.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2evygbecb.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gt2pcbyekjp.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gt2qoyaglkf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2hziqrhjo.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2xhqvwzmz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjpuzzno.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2ysumrzwr.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2mekshgkp.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2euspkdnd.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2nmwmgioc.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gt2rxmglqwu.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2auwthueo.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2gfqbtgjo.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtrqzirz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gt2ywgifsxt.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gt2pxpwjvkf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvevctyd.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gt2ijgbnjvk.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2ufwordbo.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2xpfnptiy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2syixhjfk.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gt2gfxcgnhm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hetdkrbt.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gt2yjfaqptx.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2jfzhjzdh.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gt2vpfrqcez.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gt2zjppcztr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ptpjuixg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2pgdjbrmz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2bmaolmlf.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2ydmpnzdm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gt2esnrayga.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2takibcop.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gt2ttlkwavr.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gt2gzesplpo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gt2tmgpkfjc.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gt2awkvajda.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gt2pldizfrh.html

[U05] Py：列表去重且保序
来源：http://dali.yj202588.top/Article/details/gt2jgttqvne.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gt2abocszml.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gt2nekjprva.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gt2unlnhxnp.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gt2nmwfqoua.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gt2kjwqzzbe.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gt2esjybvaw.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gt2qsufsana.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gt2vaqrmxgf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2psbzysre.html

[U10] Py：按值排序字典
来源：http://dali.daxiang520.top/Article/details/gt2hmdeuwys.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cashguo.top/Article/details/gt2umgaevhn.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gt2krsnwjhe.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gt2pcnktmhp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cqqwz.cn/Article/details/gt2oyfvxepb.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gt2qprvbmds.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2dqjgoomg.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvvsehwe.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gt2honkuych.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gt2yeifqgqr.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gt2wkkppyig.html

t = time.perf_counter()
来源：http://dali.cucudq.cn/Article/details/gt2ybuddlmx.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2kosylbbo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gt2elninmxu.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gt2xlexvbgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gt2mpsvowgd.html

[U18] Py：预编译正则
来源：http://dali.fengsongda.top/Article/details/gt2njshqrwu.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gt2aicmskuj.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gt2jelsfnpx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gt2xysifllj.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gt2cpppckny.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziiulqkv.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gt2uyyxtmhx.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gt2cycbexsn.html

[U22] Py：矩阵转置
来源：http://dali.pycfn.com/Article/details/gt2uhrrdpnh.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gt2llonqtcj.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gt2wrzsnogo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gt2lsrpzklc.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gt2wwqwbgmz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2tpnpuvtv.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gt2zbyhqiip.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gt2wpmmbfsh.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gt2dbpykbqg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gt2exqwtjfd.html

[U27] Py：异步 HTTP
来源：http://dali.yangfankeji.com/Article/details/gt2rtjiyvwm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emyxnqrn.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gt2dovjezwz.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gt2gzheavar.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gt2wapyxjwa.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlxmryus.html

[U30] Py：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2hjlnzagc.html

@dataclass(slots=True)
来源：http://dali.daxiang520.top/Article/details/gt2dygbkueq.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjdxuija.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gt2caawlczq.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gt2gykjgexg.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gt2ggdtfzkd.html

[U33] Py：打包发布
来源：http://dali.yuxming.cn/Article/details/gt2udvmygsk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2epdphgzi.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gt2ezqsretl.html

chardet.detect(raw)
来源：http://dali.bjfxy.top/Article/details/gt2fppnpsfb.html


<!-- 参考信息 -->