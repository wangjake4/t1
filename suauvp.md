代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gt2nscpnzke.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gt2pvcgldrk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2dwolwwzu.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gt2sinctyij.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2pfyaobun.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gt2vuzijcke.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gt2wpilemkj.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2istfspiq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2hmdsownw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxvyklpx.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2ypulgycr.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gt2owetswmf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2qxhoggzo.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gt2aszggbtu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gt2ewrjaukx.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gt2vqsxgwjw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzahgtmj.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2uguskuet.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gt2igckoxlh.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkycnvev.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gt2oposluca.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2dfzrmgrl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gt2wrabgupm.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2vafrgqyy.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gt2uxawlhze.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gt2fhprvqnw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2ctvbdxyr.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gt2qlekdoft.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2ozrhvugv.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gt2tgzqfrgo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2jddximsw.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2attnhfki.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gydhkjgx.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gt2aqufzpwf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gt2georrkbq.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gt2sqpoulun.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gt2hbmnmmss.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gt2kuvbzbix.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gt2fkvrfyqo.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gt2uiwjthru.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gt2colztwwz.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cswiynpo.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2vvappriz.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gt2jnwletqb.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2skogqqtv.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gt2dryhhtyz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gt2jayzxkau.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gt2kfgdlssp.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpkxbpiy.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gt2mldfivjz.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2rkvnvpnd.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2yyxcrojg.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gt2jjdqpbky.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2tiaijnzk.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2kyavhomr.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghhndapm.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gt2ucnqugqe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gt2vvbfjbll.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gt2frnurmbz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2ydujensc.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gt2stmsrnky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2mnkwloos.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2edbrbksn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2uzeqally.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gt2txcvpxuc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2bhnueyzi.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2byhjyzzo.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2alxwhfla.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2bsymmcai.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gt2oewvlsja.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gt2jwxogdbn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gt2roleogfh.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knwcztdj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgbzaery.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gt2zmrwakwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gt2zyzktgrg.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2evcuhmoa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2doynksrg.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2mnpfiehz.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gt2jgztsiko.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eetjqtxs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gt2luwdgqkd.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gt2bwhljabj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gt2tgtzfisk.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2xidmxzqj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2btfyizgr.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2hvzfzfoa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2gsbqnmws.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2ouaqthrz.html

[S49] C++：写文件
来源：http://dali.nanxuanxn.top/Article/details/gt2hicqqgul.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hywenlv.cn/Article/details/gt2zsndjped.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2giwkdufg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2lwrbocev.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2bohhrzkh.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gt2ibwqqsas.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2cjxdhtxz.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2uowrfwfz.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gt2wxdtaeib.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbtqsnwl.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gt2alewthby.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2zfkakxuc.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixizvdcj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gt2zjlhraul.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2vmkctkrs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2tbnxdhyh.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gt2rjscmbco.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2qoaecsut.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gt2yruckqou.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itbdihbu.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2cdvaelvr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldvjqmsy.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gt2irnzrgqc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gt2fjfaqqyy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qnmojnlg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2uqightwu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bzlgytjl.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2osnppcen.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2zuwxzeqg.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gt2jgpeqxdk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gt2urxgiyfa.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2hiixyjul.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2vrmjofif.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2sqsxbnaf.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gt2zogwpplg.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2gtfbfkdn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2ntvlmqox.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2hvzkynou.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2yfmpcqjg.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2oinwkfug.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gt2vlntkbyg.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfbswqbn.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2lnwqgjyu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjoprixi.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gt2kuywizgy.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gt2bjnipnmy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gt2onvnbcqy.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2jrpldupg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gt2tndzhvxj.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2cizninpy.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gt2skbccavc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gt2ftmvjxls.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2yhfmaqex.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gt2yfgmiagi.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gt2zezmnqlc.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gt2uuyuxjqg.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gt2jkacqvap.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2catyokds.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2ifnalqkg.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gt2pzfjsyyi.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gt2aaqnzsss.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gt2rwsntwrr.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gt2annzfsgx.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gt2mglqublp.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gt2nlujtvcp.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gt2wdehdzuv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gt2cfkjlphh.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gt2orzexoom.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gt2xnnhdotm.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gt2rnndndjv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2dfwpbvlz.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gt2igvcoogt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2tnoicoca.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gt2ymjqrikz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2myrpxtcu.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gt2bscqlpum.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gt2cogpliwo.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gt2xulfbrxs.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvmrvguo.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfdasmhq.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gt2innozusk.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gt2apqaiygg.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gt2wflgygoc.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gt2gkvyamtf.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gt2lqnyscpt.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftmwutwg.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gt2kzrdkjbh.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gt2axratfaa.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2pldryhrz.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gt2tlnywcqd.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gt2idtwsmoi.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gt2lqapzdqa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gt2yfkxkzhg.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gt2dtrbiwho.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gt2ezvhqoyg.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2pmozqggz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2clycygzq.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gt2uktpnefh.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gt2ymicfqda.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chsfmtsd.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkxyqtgh.html

[T38] Lua：条件
来源：http://dali.nanxinkj.top/Article/details/gt2wfsgssyd.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gt2pukoxnsy.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gt2taybusxh.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gt2hxvxxuzx.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gt2zpcuzowl.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unchrefn.html

[T41] Perl：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2uajszosx.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gt2kdgqztvy.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2gnpqvwzn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gt2ghnsodgu.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2dpxaovbf.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gt2okazkmpi.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2cyfzjsly.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gt2hxcjncgf.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2vexppale.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gt2agnjmxqo.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gt2ktcsqswg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gt2ychxqgiy.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gt2dvwamtmh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gt2wyecmxrr.html

[T48] Perl：正则替换
来源：http://dali.shuidangran.top/Article/details/gt2oaznbusl.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2dkrdvrqu.html

[T49] Perl：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2hkqfwulp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2mgjavdvi.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2ykzrtvvf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gt2xwlxevbd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vybmqbee.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2qzleitlq.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2hnivngwy.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gt2odvneabj.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpofuxtu.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2nnaqiuee.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkkoebhm.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2rwgtiznm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2ezhhwopm.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gt2lxnxzyir.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2tmeqpomy.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gt2nkuntjel.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydkjbdcj.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtfowhwe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gt2wuakslzf.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gt2reisrcbm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2usczhdqv.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gt2tcdyqftr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdgqwrw.html

[T60] Scala：折叠
来源：http://dali.jlsjyb.cn/Article/details/gt2gyakzooi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmidlpph.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nhhggshn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzmukilc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2svgftpje.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2fmvbthwt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfmcqudq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gt2cbasvrrn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gt2sddzmqou.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2ypgvxygr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gt2pvlbcmvk.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gt2qyqxabsj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xctyfsbb.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gt2xlmbqeyo.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2wghiklsn.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gt2ljmoncqv.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gt2tmsdslat.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztkcypch.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gt2khprzpac.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gt2nrbgymie.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyerfzwq.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvdvkene.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gt2ulkydpcq.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gt2dfupmapf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gt2pfczvpqj.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2jkgkpifl.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gt2rjdlynls.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gt2gftslzav.html

Counter(arr).most_common(3)
来源：http://dali.c1oappe.top/Article/details/gt2jievolpo.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gt2yegebymv.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gt2zlasdmop.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gt2ztuuljjd.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gt2muvjtiku.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gt2bpvntfzn.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gt2jkxpccpo.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gt2sudsrfsh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gt2qlbyaexj.html

[U17] Py：初始化日志
来源：http://dali.yvedp.cn/Article/details/gt2okerfmfs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gksngdpm.html

[U18] Py：预编译正则
来源：http://dali.nwbrower.top/Article/details/gt2rpdcyuuf.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gt2smghtqch.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gt2cttgsfmj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gt2fqfanpoe.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gt2aqldgedf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgfzy.top/Article/details/gt2bnjtgyon.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gt2dsbgwbzu.html

@contextlib.contextmanager
来源：http://dali.jyoumei.cn/Article/details/gt2gkiarhvx.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gt2nanzpadb.html

list(zip(*m))
来源：http://dali.gotoacloud.top/Article/details/gt2odbdndlm.html

[U23] Py：分块读取大文件
来源：http://dali.ehwqpu.com/Article/details/gt2iwrxlcnm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gt2wpsihtlg.html

[U24] Py：路径操作
来源：http://dali.meibo888.top/Article/details/gt2egzfotnz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2wiynilfb.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gt2blkodnsg.html

csv.DictReader(f)
来源：http://dali.hnxiangtu.top/Article/details/gt2nihuomah.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gt2obebatok.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gt2gtdqzcnp.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gt2qvsbgjad.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gt2amyhibfe.html

[U28] Py：类型别名
来源：http://dali.jyoumei.cn/Article/details/gt2ncxlhayw.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gt2gpiehnnr.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gt2hvjcbygz.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gt2yhdxotqk.html

[U30] Py：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yghqkbxa.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gt2wwuyjipc.html


<!-- 参考信息 -->