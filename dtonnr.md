代发 wailian999

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpffeplnv.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gteoldopbh.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtlyjemzaq.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtdcpwwxqe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gttlycrhfe.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtzlkweqda.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gtxinmigtm.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gtqkzmdgrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtdjzjumax.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtwctcizzw.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtrbfoacfu.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtiticugxf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gtqcsylmdq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtoslkjmzc.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtaqyaetjh.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtxpuexifg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtomwpfnkl.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtthhdfuih.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gthlcdhidh.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtrdxwvotr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtvspzbkgy.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtajewudks.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtppmlrync.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtdjzpjpbh.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtzjzgnycg.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrildbmrv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gtcuaxwczu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtgslpxwjd.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtergwwoce.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtkigtsdcd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtdxkirtea.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtgyhvglxk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtkgtutnyg.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtsxxewsdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtfoxmsgca.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtlckhsdve.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gtttotbmpn.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtaqkqqbci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtbadavgka.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtmybhfhok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtyddksvvt.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtzzbbuddd.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtbmqpwncl.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgpuccn.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtcpvylskx.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gtrdfackxm.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtgqbrhpzx.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjqtomut.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtzseheqlg.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtzvxdikwb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtytboxkgx.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gtwpxoclyh.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gttrtxrxbx.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtwcyasxbm.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtrxicvhge.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtugwdkles.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtasbybcnc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtqhsmlmfw.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtapdmtgcx.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtsccegtow.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtjjqmaxpo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gthumvotmm.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtkxdyptmm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtknpvxnhm.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepakbrnj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtgzcubjjg.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtemwbxlue.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtcghvqkss.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltayouzt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtrsuiuzsj.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpjpabti.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtjmsgqbxs.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtwludgvsh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gtybrxtorj.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtktzwtelb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtpffqrvdy.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gttqzjflla.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtjbpfdhhl.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtvpjssson.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtejtpjzhc.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtuevalbzm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtanofnjnn.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtbeuxpzkh.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtaqxugjue.html

[S45] C++：lambda
来源：http://dali.gzhubu.top/Article/details/gtcrvogara.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtgpyqelqj.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gttbkroweb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gthmwequlq.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtipaexsun.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtzxwnomru.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gtiinhwbca.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqshrwnir.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtozpstoiq.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gttnbipntj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtlulyuuhj.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gtctfbwdop.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtflvenhhd.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtpcjhpqkp.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtyqlzplyc.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gthejsksmc.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtlnxxtqal.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gtsytlbmoq.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtedcqnzmw.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtkyakbwwy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtlefrxgmb.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtqmxowbto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gthodutaap.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxjdeyou.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtovupyvrg.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtgvsaavqy.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtgagfadyu.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtzomgeuof.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gturbokebv.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtjpamywmm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtpedwxnrs.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtbuujltoy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtjkjocrhz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmldfgsng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtbjrtsbtu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwbzpoigx.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtbsfbyoxn.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtzykesnea.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtwmisytyp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtedlmnkzs.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtjskvayjh.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtbadwekdp.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpoqmwxd.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gttjcfzflp.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gtffrtwodu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtpprgdrze.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtwfrvqpqp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtbbhswejl.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtyflswcul.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtnpeawsrq.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygslqrjt.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtavudqwag.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtgxxnuqns.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gthvhtxnkp.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtkrdwczdf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gtxwkoikck.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtuejkhsvr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtxgsnixtx.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtfyoisomc.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtgjqeadpv.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtahunyoyw.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtdjcbpkzk.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtkynxappf.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtypzhaqww.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtrmwgfnod.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gthnstbmqn.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtblpyzlec.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtxnotjhnd.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtwthdlsta.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtirvwayga.html

[T18] Swift：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtkoevhxao.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtxrlnqpuc.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gteewbbuzv.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gttqkpfmvy.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtbvnnyslq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gtmutgguzs.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtlntqeqjk.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtatpzapct.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtxjbvdgvj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtoekmeyuj.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtwdpngmba.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtwcgmtrbo.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtiozjzyyf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtasdgkbrx.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gtfwqyzkrx.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gtgkrmhyop.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gtnnaepmcv.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gtqatnegbl.html

[T27] Swift：错误处理
来源：http://dali.mhx1999.top/Article/details/gttwnhjwto.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtqajrcsqg.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gthhptyumv.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtnugddazd.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtagaohpoe.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtcomuyggi.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gtzyrwakif.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtznegyjhq.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtnhuyunpj.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtxobglziy.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtkypgnllx.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gtlgxriwby.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtsukoeqle.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ybcxt.top/Article/details/gtxvzkafff.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtqpszbuno.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtjickpejg.html

[T35] Lua：字典表
来源：http://dali.chenzaomai.com/Article/details/gtgmzqamhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtupeezugp.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gtcucpclqv.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtwbktskzo.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtipslpqyq.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtddcgfwoo.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gtesyqabgo.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtjsmohklz.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtaxdgrolk.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtshmedxhv.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtjphpewsx.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmbejqjd.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtkbhobhdz.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtgnolcgnz.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gtnsemhuqr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtuwfoewuv.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtmxfoteql.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuainmajl.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtmicuuxba.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtikhemxlx.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtisneebhh.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtxblehami.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtbpmahxor.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtvtvedyko.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtdwhgofun.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtnmmisggc.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtsgfddgka.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtaealqjqf.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtdotnqtjk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtdyugmevo.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgabssde.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gthqxudsuu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtzvcpqbuj.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtnkssisey.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtpzedsent.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtgkyndwrn.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gtcagmdsuo.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtcuxocmjf.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gttvokvpfa.html

[T54] Scala：集合映射
来源：http://dali.yuxming.cn/Article/details/gtmydnbkyk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtduphbrdi.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtzetocein.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtxqcevyoc.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtrjmczwhk.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtmpbbxeiz.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtjwoxtwqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtajkfocuf.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtwsijqxqp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnciiwhc.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtvryrffsh.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtpuvudsil.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtqjtqodjb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtfhhyjobx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqzzdcpiu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gttcuafzkg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsebxwfwx.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gtvpyywlhv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtdgpdapqw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtgqywbqno.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtghwpayon.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gtwjjpxdfh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtttyqvvem.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtaetgaofg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtjlzzovge.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtjyccfjpw.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gttizqkdha.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtwlbahpkq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtupwjnapj.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtqzzksaka.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gtswsavztm.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtfoszxrgh.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gtnhvmeozw.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtlmrztobx.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtaamwxndn.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtvrveyogk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gtujidjrza.html

[U11] Py：生成器表达式
来源：http://dali.316326.xyz/Article/details/gthqtgknrb.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtyhbxnqdo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtjxwvkojd.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtpcwzuhgz.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gtbcenabxx.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gtputjchyz.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtahnktreb.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtktptdpvc.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gtmezbrdrs.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtxqntukpb.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtjrndoitc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtaqctxwbf.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtctywkefe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtphhahcmi.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtlzvzxbvx.html

pat = re.compile(r"\d+")
来源：http://dali.shuidangran.top/Article/details/gtjaoesdbb.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtvpmmpkfs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gttzacskve.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gtxtznegdm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gtpdkdozxj.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtiezmszyc.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtjqmtaoeq.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtlvgdcmkw.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtzrmonwda.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtbwuuisul.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gtdhtmmrec.html

[U24] Py：路径操作
来源：http://dali.tian-w.cn/Article/details/gtxeegyifv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtggddqafr.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtwndpbnbe.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gtroqzhttv.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gtplzalutd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.birdmap.top/Article/details/gtgykujbqq.html

[U27] Py：异步 HTTP
来源：http://dali.xziqi.cn/Article/details/gtbnsqhuvf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gtxjhlaafn.html

[U28] Py：类型别名
来源：http://dali.ivvv.top/Article/details/gtnfnvdpdl.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlmhlncq.html


<!-- 参考信息 -->