代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtgsbfizro.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtrxrkjyfq.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtayzjbyyv.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gtouqxqfyu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtjnoglkhf.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtkaaegerg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gthbdyntvj.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtorkiyogk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtfyictqyb.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtckwwmmjp.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtkuwbcecr.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtwgvegcrr.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbljmben.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtiunpyshe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtiebapiqu.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtqygiavby.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtyxpeslgc.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtrjiacehl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtjnrldhjj.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gttgywrywq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtfiwxdwht.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtxfzyzehw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtykmltxoe.html

[S22] C：字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtvqnabaww.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gtqvdzbyaw.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtdgvdgwvj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtjbmdcdzq.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtdwwpikei.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtxzcsokga.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtbvwuectq.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtizxwkslg.html

[S26] C：内存清零
来源：http://dali.hnxiangtu.top/Article/details/gtvjvparop.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gttaadbxfr.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gtgovfqnur.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtnmfzylzn.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gticqiglcd.html

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gtgghhppwq.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtoqewsnci.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtwbobgbyf.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpadxuzp.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkhuohqz.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtiuhvbchs.html

#endif
来源：http://dali.cheryme.top/Article/details/gttioxsawp.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtvlxxjlaa.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtoxybqkul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtptlcbxcr.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gtrayldyuj.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gttmershkg.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtvnmjduki.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtmawirapa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtvptexcuy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtinjybwux.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtgpgahrxe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtvolqmjax.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gtzwezjwzl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtzrrbnqim.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtofghtexi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtewkitynp.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtnxulpxkq.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtnqrgtufi.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gteyatkkqr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtbwkjjaij.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtnoieolsv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtuoojbmeu.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtaczexbtj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtzibznvbg.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtifqakbdq.html

class B : public Base { public: void f() override {} };
来源：http://dali.vqdsnc.cn/Article/details/gttlpkxqzz.html

[S43] C++：智能指针
来源：http://dali.yj20258.top/Article/details/gtddnbrmlp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtuzakiqip.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtyitnzitp.html

void inc(int &x) { ++x; }
来源：http://dali.hammf.cn/Article/details/gtelhneera.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtylhvytdv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtfwdpiqgt.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtygzgbqix.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtezrlksbv.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtqqxbiuqf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtghlraate.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgerjsxmf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtafserpwq.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtdosdhlyp.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtdgobtfrk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtshdnjwwh.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtrfqidcby.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrpqglhx.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtrtymeypv.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtnsrivpmz.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtfidrjurw.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtvybsrjqq.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtjqhvstxa.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtpzshnysk.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtfmxbwoqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gtdypsubhv.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtxajllqal.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtgytkaifs.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtexgydidf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtwozrqpxu.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtmrcvxejd.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gtkdvbftvr.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gthbsczdrp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtgfuqiqcz.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtrwebfzya.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtcgfkshqk.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtnkwgcofk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gtdiieeuuw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjjaehnki.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtkxlfyfny.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtaruklrsd.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtwnliciot.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtidesxava.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtyibmtblm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtpyuakowr.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtstkjkblm.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gthgtihegm.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gtvcbavleb.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtugkirlxk.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtngjhavpb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtjnwjwvhx.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gttuzvoptr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtasnzpaye.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtbbzxbsyp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtsuyzozhk.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gthgppgpml.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtnkfrktqe.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtneeuhmki.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtrxtuhxtz.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtxtogihzk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gtvpvmgsic.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtvckqvadx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtofknnlxs.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtbanrjvnd.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtkhfkfepc.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtavmzuake.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtgytslolp.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtpooiuhmj.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtzfuzbghg.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gthkeljffa.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtbkhmodmf.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtigwytsqs.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtinqbrhsl.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtkxwsbbnd.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtxzjrsffc.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtwihxudvb.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjdxxkoe.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gtikcrugxv.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtarvmstpg.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtfjpbpasx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtdufbkoqt.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtttzjmoxe.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gtpbugypaa.html

[T22] Swift：字典
来源：http://dali.mhx1999.top/Article/details/gtjtqltzwd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gthdnvlziw.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gthcmsrqiy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtfvdwxhsh.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtdrrtsobs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtivfjktmn.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtbuigqwnt.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtylsbhwzz.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtqxrcokju.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngtevoia.html

[T27] Swift：错误处理
来源：http://dali.nanxuanxn.top/Article/details/gtsqejfmit.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gtdowkpfuq.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtseizjiwp.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gtwgthghjm.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtlxrtmpop.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtsycwojko.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnzsexey.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtkpplwoiy.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtvmclembc.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtzdilvjjq.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtyedxyesa.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtnffmfleq.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gtojnidcur.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtdgkqftof.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtmxlwidva.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtyornzvky.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gtvaubrvxw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gtkqufqoai.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtfkeqwruw.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtzyteurzu.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtkmqmuydn.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtwrwjlalc.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtmuukszmx.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gtzpcglbas.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtkzclizgr.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gthozunhgm.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtdberfxpo.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtpjsxjbjm.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtlbygknup.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gtcgsolgrp.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtekcizaqh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtigurobpp.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtgwmaaufb.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtoxbqsehv.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtuyasizyw.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlibnoywu.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtyhglirfl.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gttiqbjnkn.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtehealdhl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtsmlnqebv.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtulqhhuhm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtwxmyombp.html

[T48] Perl：正则替换
来源：http://dali.ivvv.top/Article/details/gtpaptoejw.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gttrcalidy.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtpqbqksgg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtwopqjmvn.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtndudkkgi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shangyingyoupin.top/Article/details/gtiddqyrlb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpxqmafn.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gttxnzzrze.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtsvrauebi.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtebemywnh.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtrkbhkkyd.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtnfgztnmz.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtasdnnuvb.html

[T54] Scala：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtilzrxtyn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbavocuq.html

[T55] Scala：集合过滤
来源：http://dali.meibo888.top/Article/details/gtgyhwhcpy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtbbmkvafy.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtceqbpqqz.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtlcizjxhh.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtnuuzybfe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtcwuhpwzo.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gtgyqbbuus.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtusechkde.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtiqsbahso.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtrnmunvtn.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtdimcdumy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtqaszmmot.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfdpxaxvm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtvlbnyttj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzymuhknr.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtahromvka.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuzhbjdi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gtlqfxgkrk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtjzznofrx.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gthonommza.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtptcvxwab.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtljgotjqn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtwvdkbeyv.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gtzqnuuxhi.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtmuqsnfoh.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gtzxsreigk.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gtsmchvozd.html

[U07] Py：反转字典键值
来源：http://dali.hnqzz.top/Article/details/gtmvowabkm.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtijqlmkmi.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gtdhkzicgg.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gtmaeuoptw.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gturelvacu.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gteplcrsor.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gtxnamxose.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtcxgkmygo.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gtcxnilwdk.html

(x * 2 for x in arr)
来源：http://dali.ppjwa.cn/Article/details/gtstgxinfh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gttftaixlt.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtbsxhqerl.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtkhenjnhf.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtgffldthb.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gtuqissdap.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gtsjpcvxli.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gthghlvsqq.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtbyelikub.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoomzzfc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gtmeybklbr.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtefeijyos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gtaqpvfbtw.html

[U18] Py：预编译正则
来源：http://dali.fzhhl.top/Article/details/gtkhdzgprn.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtgwgapsls.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtvhjvtssc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.vqdsnc.cn/Article/details/gtetortffz.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gtveokruzf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtdszivbtn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtjpehwkxl.html

@contextlib.contextmanager
来源：http://dali.zycfv.cn/Article/details/gtofkijrus.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtmqcuqwpv.html

list(zip(*m))
来源：http://dali.snrcjt.cn/Article/details/gtvnjzncaw.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gtwttnuxom.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gtiljvicdo.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gtfqawadud.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtdfaznfwk.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gtytonspvk.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtmmsagdds.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gttecpwsgu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gtehtqxqyq.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfjlavsk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj20258.top/Article/details/gtyvavvipk.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtcurlcrnd.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtvreiitej.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtwznnneed.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtsesqksea.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gtogxwwihh.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtwfeelzju.html

[U31] Py：单测
来源：http://dali.chenzaomai.com/Article/details/gtqwzwrmqw.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gtlabbdetl.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gtcjdcpzjn.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtoonvcsmj.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gtsoicpgfk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tianlin.xyz/Article/details/gtrhonzhhm.html

[U34] Py：判断编码
来源：http://dali.yueranfly.top/Article/details/gtdpulbgvh.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gtmmwdflmv.html


<!-- 参考信息 -->