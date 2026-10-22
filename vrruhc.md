代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2qazffjpc.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gt2yotnhpfc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gt2mdmgducj.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gt2tjcpbeba.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gt2jhmtwklm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnfrcok.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2veplakda.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2qinvhqnw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2ftzkbkmk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2exlhixtf.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbxmdqst.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2oswsyymu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2vucjivro.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gt2mpfhpdcy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2otzzjbkt.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2iugtxvfi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gt2grekcvcw.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gt2rphsrxow.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2rnsptwko.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gt2opijbdyx.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gt2gicxqrqq.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2pvpiokfs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2hutnrhhs.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ooczorbv.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2qcqwcbyy.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njpnbtpw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2qzqqpzyd.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gt2pkbwrrnb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2rjcpmnjs.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbzyhyjv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gt2jpttuxeo.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2lshthgbg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gt2cvzpqwvf.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2dirzvtzt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gt2enupundr.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2oshwxhrx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnvmwhsd.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2jatgtpmt.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gt2ratwmcii.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gt2eockyunb.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gt2hbdnrdtw.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2uuygilxi.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2droitjbb.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gt2ibjhbaev.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gt2yycxvrhy.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gt2izaydbfv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vczmigsg.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gt2eudctahy.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2hqvtkpor.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gt2siamxecx.html

#endif
来源：http://dali.yj202588.top/Article/details/gt2beobzlmh.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2tjuqkcep.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gt2isrqzggf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gt2bsgfmepn.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gt2stgwvith.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gt2dewawhbh.html

[S33] C++：vector 增删
来源：http://dali.hfpthk.cn/Article/details/gt2ravrnqbx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gt2iswgafjy.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gt2jkgqnxou.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gt2hrjvmjme.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gt2bpgpvehx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2tmsunics.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gt2ctqawxkt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2towqypdj.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2zxbcfpdt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2uutxackz.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gt2kutrtpnx.html

std::sort(v.begin(), v.end());
来源：http://dali.svipenyu.cn/Article/details/gt2wmyhqzre.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2hveqilrf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqkgqetv.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2zbhqapsp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2wswruqet.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2hmpcjvgj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gt2knjmjuag.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gt2thaywezu.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigfzy.top/Article/details/gt2kssjdwlx.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2mcsgyxuo.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gt2lnbjqnnw.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2jprotypu.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewnsebcp.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2pudtbbpm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gt2vunelwtc.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2gfibjxkc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2itzkzwrx.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gt2fqqalrvc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aipazgva.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2qaiwskwj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gt2gixefzie.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2mdrilxcs.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2dxbjpfsw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qixhbjea.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gt2exinxgyi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2dfrcbjvd.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gt2ofwayrls.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gt2ojkxndxl.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2dzlowick.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gt2cciklutm.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gt2hljyftlu.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2jgghidyv.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gt2xkwjvmbx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqlcwydn.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gt2bpgrehga.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2ueneidwb.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gt2cwnekvst.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2obpfxwvq.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eupxyugz.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gt2drxjwrzt.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2ydihkkyg.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gt2rrfarlrm.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gt2xsnkkuae.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nctdbhrp.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gt2ifmppigp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2vrgtodpr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2tlxxgxst.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2fwzqlugu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2unagqazh.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2tdsrqgeh.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2pfheievw.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gt2hgdofzdh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gt2jiilgonz.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gt2hzkzzsti.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2atnubanm.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2jlbxydbv.html

val n: String? = null;  n?.length
来源：http://dali.pycfn.com/Article/details/gt2omkuzall.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2aepygeky.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gt2lpmmigwz.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gt2elnwxfpl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2itszwxpt.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2vxvygdnh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecdouxzm.html

[T08] Kotlin：数据类
来源：http://dali.ybcxt.top/Article/details/gt2vwiyauwv.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2ityfuyfk.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehxiudon.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gt2svbfzgxh.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2qypzogte.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2ngzwdady.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajlaqhsl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2aqotwpdo.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gt2agzfyiqa.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2hhcegvpf.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gt2evgiehuy.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gt2biykklps.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gt2ivtrycgn.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2uqojctky.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gt2wbmlkasw.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2fsaidtiz.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2jxmfajyr.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2nxqwregx.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2bxqlqgeg.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2navuqptf.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2lehrsabl.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2jbvlcann.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gt2mqnrqisc.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gt2acmurftg.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2ofvcpmrv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzmdffhc.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gt2zfmkwrna.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2wjfnfirv.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gt2mjjyyaqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2rwbpvgtj.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gt2nvjgvcvg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2esydzjmy.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gt2vihgxbdi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2zwwoesdo.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gt2iqknmuxt.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gt2buqjjtji.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gt2jjnvuspi.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gt2hitxrgxa.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2jmsyvjgf.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gt2yevlicaj.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2rqpieblp.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gt2ybipyzuz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaptprpm.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gt2bzxpalsh.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gt2mkbgudfj.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gt2ucxcxcdc.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2tgpbqtor.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dxronqjw.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2basjqavl.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gt2srluszva.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gt2xkaqzhhy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gt2yaisudzi.html

[T34] Lua：遍历表
来源：http://dali.hfpthk.cn/Article/details/gt2ibuhaems.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gt2mgyhgtfu.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gt2nvaiplyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2qjwxhnav.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gt2rpuephyu.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gt2ijjkmyhg.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2xcsixhhz.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gt2nwvgbzdm.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2fhwlatqj.html

if x > 0 then print("正") end
来源：http://dali.pycfn.com/Article/details/gt2dkqjnsuv.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2kjpashdg.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gt2bfkuugpx.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2bhpbroue.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gt2sbuyccwn.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2mxloivfo.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2huhrrxep.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gt2vhfcregm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfujazfq.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2jvwvhhsf.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmefcqhw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbajnrlq.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gt2igybgqza.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2hditevkn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2yfiduhac.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gt2muphvcqo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ehflmytd.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gt2hdywboja.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gt2devcqgih.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2ngwaoqqi.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gt2bthwpais.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2plcfozav.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2obdezrep.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2eywxvlpl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdurqedy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gt2ocwfnfyz.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2knjysscg.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2hlshyhxm.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gt2qqxprlmz.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2wwgzpsgg.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2cuxpvsmr.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2crbnxvsq.html

[T54] Scala：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2iajkvbzl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ydzc1.top/Article/details/gt2qzqvchpo.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2myyinciz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoufmjzy.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gt2qpoyzphl.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gt2qxacuaac.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gt2uktugdfu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gt2etqxdeuf.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gt2sxtebsjv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceqlctlr.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppbufdnv.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2byyiyoxj.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gt2kpxynjnx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gt2tvejotke.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2aydnmvdd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gt2vcjjopvf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fddgfnla.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gt2ozexdpgo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gt2kpyzcsel.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gt2hxkhvvbl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gt2aczeuvqr.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2fsvuqqjj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gt2yqhsirdv.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gt2eusqceaz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gt2ivzmwavw.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gt2nqccaqxl.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2chxndrbh.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gt2vbfvxnzw.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gt2xvobscut.html

[U07] Py：反转字典键值
来源：http://dali.andypj.xyz/Article/details/gt2gvutrswb.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gt2amyyxoss.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gt2kofbiiaa.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gt2ipbmbzxk.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gt2clpnlyvq.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gt2gwhztazi.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gt2ligxsdsy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gt2vljqxjax.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gt2wyprhats.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gt2poxdrids.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tanke756.top/Article/details/gt2aaqnuedy.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gt2nxhvbtqo.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gt2blnuhmrh.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gt2ggktopvk.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gt2msrqqcdl.html

defaultdict(list)
来源：http://dali.dashuyun.cn/Article/details/gt2qbecnekw.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gt2psvdlvrc.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gt2pjndutsq.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gt2gupiyufu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeqbkmy.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gt2jwbziyqr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gt2nybqbiou.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gt2fyvpjyfm.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2mwmzedux.html

[U19] Py：正则替换带回调
来源：http://dali.9152youxi.cn/Article/details/gt2zlijeuli.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvdtdpi.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2vqgrvtuf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gt2ixcvxxgx.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gt2abwpnram.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbbrrxdu.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gt2pqvrhdfo.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gt2ffcetsak.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gt2zpbkkfgy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gt2btpaeuqo.html

[U24] Py：路径操作
来源：http://dali.sweek.top/Article/details/gt2ouvzujtn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2pyttuxdt.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gt2digbsgce.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gt2oqiueeic.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gt2wfldeuet.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gt2pcedetcu.html

[U27] Py：异步 HTTP
来源：http://dali.9152youxi.cn/Article/details/gt2zdxdspzz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gt2ixlmxabb.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gt2gapcmafc.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gt2ekcexwwh.html

[U29] Py：属性校验
来源：http://dali.zycfv.cn/Article/details/gt2gwvquvph.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnvylgle.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2cdnlenad.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gt2zlqtgigy.html


<!-- 参考信息 -->