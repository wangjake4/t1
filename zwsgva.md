代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtguakbbib.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtcvncmtpc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtkervhdpa.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtxbzzvqcl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtzurtvnqe.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtpjhiikxh.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtqzgyyumn.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtgmfdrvhm.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gtyfmcopll.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtevvzpkfg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.haohaochexian.top/Article/details/gtnpojgyca.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtklglimju.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gttqqxiswu.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gtaqmbfrcs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtvnmqjtfw.html

[S20] C：二分查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqtctbyo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtkqkkmmfb.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtdynpvybr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtghkyflsc.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtmounaowj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtljgfxuxz.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtvmxpffpb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtbaiueuzk.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtatttlxov.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtinauwnpf.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtyflriibi.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtwwbmohee.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtnnnnmdoc.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtzobhpdzu.html

[S27] C：定义常量
来源：http://dali.aizwys.cn/Article/details/gthuhtrnhj.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtvrsdcdmz.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtnvxrknlo.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gturaijlnc.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtolapnbxt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtierquxlm.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtlzqzfvlj.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtwnwchdir.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtgvhnjtfj.html

#endif
来源：http://dali.xylfe.cn/Article/details/gtorueobjx.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtlzcfipne.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtbxpdjpvp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtkxpdrwbt.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtixcnmten.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtsgufsfdx.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtbplkknra.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gtvloihiyr.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtbhhauwku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtwrfeganx.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gtrcqucewv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtohsajotw.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtykvhdfjd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtcvrwxlcl.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtzxqpkhok.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtpufpvspx.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxbxeavf.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtpesvmpiv.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtxturixrz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtgltpbcns.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtqtheotqt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtfjxtjdgj.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gthlvacpvk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtxjvffezv.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtjqnybwwh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtqvfowdsv.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtsguzhzxu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtzodcrnyy.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtbjhjfjdg.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtfhbekxgw.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtgrdejbbu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtguuvoppr.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtajptypqh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtwuweqqmu.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtuzwekkyb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdmsbpgid.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtzndrpjln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtuetimycb.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gthtjuvbxk.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtcxokzbok.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtswszlrhn.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtxatnljtz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsxyoetl.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacsgqlil.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtycixgxld.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtodsxtnht.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtakxhvdeb.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gtetizfces.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gthhtytuso.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtjkvhdrwe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtsvgjegpo.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gtcbwysxto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtzopmtuca.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gthhvwqblz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gtrctgpaup.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtzkauzekm.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtrsfrswjb.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gtworzrajd.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtecwkgryd.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gtelljpbri.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtzaawbxeu.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtbekzkwhj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gtznbeohvx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdckaalws.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtoboewsei.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttmjgwkpv.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtzkearfyu.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtxujgwrqx.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtdtocodvn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtsaidawro.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtbeiquhxs.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gteusxafxt.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtnbxcvpur.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gtgpiswnbf.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtxuyhrljb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtrrrbqifi.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtufagoc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtlrurokst.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtyezhzmto.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtpkdjzoqh.html

[T08] Kotlin：数据类
来源：http://dali.sufxvd.cn/Article/details/gtacehzvhj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtawgevasf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtwwslxvvd.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtktegefdc.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtpuebdc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtecseaktw.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtfhlumpto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtkqhypjyy.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtcryjkfft.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtayaqhzzd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtfwpgzhbz.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gthvvnnpbf.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gtkgqnybai.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtifgukavn.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtmhdrkyxi.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtcrtlykjo.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvkizkfc.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtxwsnbxzj.html

[T17] Swift：变量与常量
来源：http://dali.nwbrower.top/Article/details/gtmuozhabx.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gtxitylvps.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtqcacaucb.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtycdnoked.html

[T19] Swift：可选绑定
来源：http://dali.guannengcc.top/Article/details/gtctaejzsr.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtisebgoav.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtulttbvxg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtfjfindme.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtqpobmpvb.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtvyosairl.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gteccfozur.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtygwgsloa.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtstlwxsps.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gttbxnmhzk.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gthrktztbg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtiydivmya.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gthgskltqx.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtmqdewxcn.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtksxqhiab.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtpceagcmu.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gtxpdqnevg.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtjakwazyr.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtxwxzxvwu.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtmdsoovow.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gteomjgoip.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtrqnpbvkh.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gthycvgudz.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gtuvgioqfm.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtqslwmakn.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtraewgsbu.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtttrijeml.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtmpivebgb.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtestmpuuy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtdvllfsob.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gtdooytbzr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gtpralfgzu.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtqlvtylbd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtantmywwz.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtjzfsjljv.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtkpbowrjr.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtrrlaqqns.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtkeuhjqxu.html

[T38] Lua：条件
来源：http://dali.xylfe.cn/Article/details/gtamanabkd.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gtqxexlebx.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtmltikeqg.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtgybmsyih.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gtsqhwyocm.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtivlbluze.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtuhehzruu.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtufmtvkgx.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtoihbddys.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gtzmuxdrjj.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtzcguboqt.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfmvfmxn.html

[T44] Perl：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnafmbai.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gtwugidsru.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuamomfmw.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gtxjclhlfj.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtkriosrgi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtakcpfvbm.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtubwrohub.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtatpwcnkp.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtcvtlokop.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtpkgjouth.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtgzkefekp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtsewmmttj.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtgjpmdxfq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gtopudcfuv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtrngztcro.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtxndfdvki.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtuzavmmgx.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gtuxxeyjxg.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gtpunppgoa.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtdjgblcyo.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtrscrsqsv.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtlmymrwyc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ehwqpu.com/Article/details/gtnmfysuty.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gtvblsoyzm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtbsijibfc.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtnuuilbop.html

case class User(name: String, age: Int)
来源：http://dali.cheryme.top/Article/details/gtvonxzogb.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gtybrdmwev.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtatbjemtt.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtvjasxtgj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtnrytwdbu.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gtrjokttna.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtvrttlrtk.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtavtpqojl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtrdhwypyf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnzzmjdgw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtkpfuxgty.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkhgphbrw.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtcseimvve.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtgwsmuisc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gtyrqtxvpy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtzevbwqte.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtaxuhnkzr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtaepkyreh.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gtzqnsrhff.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gthxvpvjjh.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtljtyndlb.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtorieoyww.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gthxbjiyjr.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gtlmolrwjk.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtgipizabx.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtybbwexkl.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gteexwrram.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtngaeponh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gtctooefgf.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gthjcuybfu.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtjlfechhf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtyqzouisr.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtruabsxlv.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gtyqejxfyy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtrgbqmscy.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtbjdbmngl.html

[U13] Py：固定长度队列
来源：http://dali.xinyue.icu/Article/details/gthvfgpsim.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gtttlqtupx.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gtsgrazogr.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtfmxgeaiz.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gtpdppryrw.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gtxicncari.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtihcegxme.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gtpjkroofo.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstopxpyq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gtssdmcqco.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtjgenlyyb.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvrxyqdp.html

[U19] Py：正则替换带回调
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtzmkkfs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gtckniutxh.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtlltzjjmc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdujwhul.html

[U21] Py：自定义上下文管理器
来源：http://dali.sxryk.cn/Article/details/gtkrekihop.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtbrrnhlvv.html

[U22] Py：矩阵转置
来源：http://dali.hongshengwenyu.top/Article/details/gtqwajnusb.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtoqwntbwr.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gthzjdaujg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gtkhtlwhfq.html

[U24] Py：路径操作
来源：http://dali.jinqigufen.top/Article/details/gtnouqpnbg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtueknhqdy.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvouelocm.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gttnqsnpft.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gtcbwcazuz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gtijdjwrhk.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gtvzucclag.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtppxjeaiw.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gttmwfbbtz.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtyzxkfmdh.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gtxtweaaqx.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gtfdzjqmug.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtoyfajsaw.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfzxjjbv.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gtvvfomhiu.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gtgarqhklg.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtujzlwhra.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtjbehbtml.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gtcnhmxqxz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gtpxczczhn.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtovpqacxz.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtepbsrytw.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gttlrfehmw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.havefunace.top/Article/details/gtjhxsikzc.html

[U36] Py：定时任务
来源：http://dali.shzxlz.cn/Article/details/gtspezzcyg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gtzoajvdqd.html


<!-- 参考信息 -->