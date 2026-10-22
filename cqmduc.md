代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtkzpcjftl.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtawcitdcd.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtlikkdtka.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtjyrwjt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtladnlftd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtexlpawth.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjftafufj.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gttnxypybz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtnuzwxdnx.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtrdjbyenu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtwikohzip.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gtevfkhcze.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtjzbymtsp.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtfkethnns.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gtfumhszax.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtoblvzcxl.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtagwcsgij.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtblzxjycs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtetkffkuv.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtaldwoaiy.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtosaduuhv.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaqmmeph.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtqjexbqnq.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtmsskhpyd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtyxsypqnm.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gtpkvkukis.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtnokpnyql.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtxwfbgoos.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtowyhvesd.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtaqxcluri.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtsfxurgvi.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtzszwsdfg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtrwwckcnt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtmftwntvk.html

memcpy(dst, src, n);
来源：http://dali.hywenlv.cn/Article/details/gtzufwhusz.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtvpozehrw.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtnwxgeffg.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gtccbxfphz.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtywkwpmnj.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtmqtdznwc.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtgdkhyehw.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvkvvvvo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtxyqrwcts.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtotaxvoil.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtvuoyzrfc.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtladnhoij.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtnsseuaqg.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtilierwuo.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtkcxhkgwg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gttxilywap.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtoyqzdvyt.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtmukjqdjl.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gthztzbydg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtlqsivjtf.html

[S34] C++：遍历 vector
来源：http://dali.tian-w.cn/Article/details/gtkxvkwcth.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtybsdleqs.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtjayfjqgs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtzdhsresc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtpdudswgh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtkkhwuvff.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtdppfbrjz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtqvvvwvuw.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtpxsjjjbc.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtmrnkzkbd.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtgyrcawan.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtbsdzdgdf.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtfyxxlbct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gttbauzsqt.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtzhtaoudr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtcshbhbfr.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtcjlpwnfp.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gtlzcdoqre.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtdbverlwe.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtwmmbxdpc.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtyiyfiiig.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtgvdooply.html

[S45] C++：lambda
来源：http://dali.chenjidiqi.icu/Article/details/gttdyeilwk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtpllushyf.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptjtyjzz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtuyfrfwgw.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtrsxktkej.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtwaitjgpd.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtnpfodqts.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtunrxvdni.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtpgtdodbu.html

[S49] C++：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmdlvpumz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxuanxn.top/Article/details/gtughbgijg.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtuejhuvdk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gttkebsfqb.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmczpzjq.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtkjzcxzee.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gttxsxodmn.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtaolxpcss.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtjlekaarw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtqamfigdu.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtishnuakb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtzojkvkfi.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtdfoeiayu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gtzkryutap.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtslaayuns.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtlozlnlth.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtwpqwejxk.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtiawstjue.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtogwgqgvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtqlhhkzdx.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokgbjmzp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnqeulwh.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtsctghlne.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtrftdmxtd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtiidztemp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtetorvcxs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtslbxndev.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtlvrrrzqt.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtrpkbjazy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtcoqfiydl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuybhppmd.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtwsniwzwc.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtucnrauzu.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gttfawyztx.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztoehoin.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiduiiki.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtwnsjqljg.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtiinztsxl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtbwegzmpr.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtserphyua.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtlagjtigx.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtdqyrvnyr.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtmwcwylkb.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gteoqtzzoe.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gtesyydkfq.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzlozfdnw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gtaixpzkum.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtiijbnkhq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gthkvoblxt.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtwlpzjscs.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtzyrzlfar.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gttzkasdia.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwkjgbwu.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtytihdtue.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtxrrulvbk.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtoxdqutuu.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtuyrgqnua.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtfltqxkxe.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtxewawdfr.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gtyaxqrfoa.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtczjgfdet.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhypyoac.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtxagseruq.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtseaguhqy.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtkytmxpmd.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtaoeztshl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszbphdxd.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrscxrhn.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gttiyvrrtx.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gtfcfqtfvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtsrookhkk.html

[T23] Swift：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtdqoedrog.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gthupgsgih.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtnneidwrq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtgkznizjq.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtjyzesxon.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtuvzrmoqb.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtjxhritxl.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtwlmrjvhi.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtvjoeyecm.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqpjvstj.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtxpmqzbag.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtpcmjwhhr.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtpkaqlgln.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtamletybx.html

[T30] Swift：协议
来源：http://dali.pycfn.com/Article/details/gtnfajoeji.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtgamvtgip.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtkoxtsdsr.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtshkryvla.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzztlopw.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtqqxgyvel.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtksjfnmit.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtecmcsznv.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtxfvkinzr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtswelikxh.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtkpmzvblu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtigqmndgy.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtepuzljlx.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gttnycmrke.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtrgxathna.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtppqlpmhw.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtxmcdvndk.html

if x > 0 then print("正") end
来源：http://dali.kuanghao11.cn/Article/details/gthfrkyyiy.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gtrknzfhra.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gttsggsanb.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtcqpfrzbo.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtoblemiks.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtqokrmhdm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gthnfsfaek.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtdjqereev.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gteyanlymx.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtfdhdzlfa.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gtambamoik.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gttwsuknlx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtoycvbebc.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtudaiqjdz.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtbojemvca.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbratnjv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtioeczigb.html

[T47] Perl：正则捕获
来源：http://dali.hfpthk.cn/Article/details/gtbvnphmmk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gtzuqcyslb.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgpzjnhh.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtdblmqgbl.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtybdsfnug.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtojxxhejp.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtfiyuxzlg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gtmkcgyqpm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtomscvnzg.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtnmtcqvue.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtwmibfevv.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gteypyvonb.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtbbamgfha.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtaiossmqh.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtcqtincqy.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtgsuzuzne.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtcgnibsza.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzugdcpsx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtnzpdtbyh.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtsinueybk.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtljwmxukg.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtfdnxtwoy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtqfbiddeh.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylbbbwya.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shuidangran.top/Article/details/gtegeeacoo.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gtgqvwndny.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gttfqhdkvs.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtgwlqwncp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtfxqdbfaw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzdrooso.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtxhqasdfp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfqhqdckj.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gtftzbiztk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtqbostfca.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtdjglqoyz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtvdyithvy.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtqomyfosm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gteylcolej.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcwkzdbw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtdediptxm.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gtwjtykgsk.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtasyarvak.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtbubupiof.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gttvrlxouj.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtfyazizil.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtwgnsjyfk.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtgkuquupj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtvfzunkko.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gtdieufihz.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtglmudunq.html

[U10] Py：按值排序字典
来源：http://dali.hysaishi.cn/Article/details/gtlupfmxpc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gtvbsvkyuu.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtdnrmlgjl.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtmgpyjwqc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtmkoqkezp.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gtjtrhhrbv.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtwoiqpwfi.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtpzigaiuy.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtphdegyey.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gtcenttcsz.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpunfqnvi.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtawxsmrlf.html

[U16] Py：命令行参数解析
来源：http://dali.shzxlz.cn/Article/details/gtdjtwhqgc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gthazebywt.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtmiagnvpp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyowpvld.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gtdtbredsx.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtosfhlson.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gtajmoowsp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cqqwz.cn/Article/details/gtyussrnim.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtmkcmugoh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszrmxcwt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtdhchvzfu.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtalmooxkv.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gtbgjlrggd.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gtnxwwuqcv.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtmbpxqnln.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsglghalp.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gttbskyccf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtifkstxwk.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtiykiygdq.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtpayajime.html

[U26] Py：并发下载
来源：http://dali.zdqjudy.top/Article/details/gtybwawaoe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gtuibrjqty.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtsxfwsvva.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtkerjflna.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gtgkwsxtst.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtuflmfbhj.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtdpzkvyqw.html

@property 与 @x.setter 配合
来源：http://dali.hysaishi.cn/Article/details/gtfxrvkyqb.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gtdnpnhndz.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gtynislznq.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gtubzjzxyf.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtomqvkpdg.html

[U32] Py：代码格式化
来源：http://dali.nanxuanxn.top/Article/details/gtoyvqyjbd.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtuzfoowji.html


<!-- 参考信息 -->