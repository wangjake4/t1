代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtavcksafu.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtprdrlkzj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtklktnkzf.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtxklpwqqp.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gtsttawkdm.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtcuvjlyqd.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtnzmfmxmx.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gtacmkujqc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtyjacuepq.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtstnlojdv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtuhiazuqp.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtaxhccvdt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gthuteubff.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtdvlsqbjb.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtklglneho.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtrvbacdlp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtwkcigqmx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gthefucqgi.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtzytipbao.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gtyhdvedye.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvilqpiqq.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhlzcpbc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtlqbkodfh.html

[S14] C：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtekfjivpz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtdauyzuhp.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gtyhkdxglg.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtkkpqeotb.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtbvaxcygn.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtztbftqer.html

[S17] C：安全拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtromaulrb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtexgrbcjs.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtshuipbdz.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gtqmanvfgb.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtsydasgzw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtulgsuxcx.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtzehnuuuu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtbwjrvpge.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtkesdedxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtqddlnxag.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gthzxecgga.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtnfbaescx.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtiogeeont.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwhxphru.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtihmeooud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtkbakhyhy.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtjdxakxbg.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gthbrugnau.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnulzwuml.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtmjzatzft.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtlwenin.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtghsdsdtm.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtbguuariy.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtlqkcnjlw.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtkirdnybs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtejdtmdfl.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtdalqsfpt.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpzvlwtq.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtlkyoyqnq.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtsulnctuh.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gttntatrhy.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtaqgnslmg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvpupydz.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gtcxhvxlrx.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtwjpstafh.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtluombaiv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtrnulcfbr.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfsunebf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfvweciyl.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtxewyeeyh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtkdsubumx.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtdiuoladi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtyxthrivf.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtezzjqbkr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtlwyypvbh.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtmgbdxoes.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtvhdmhxrv.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtzjmbmcnt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtvzhzltva.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnkoxvah.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtqnpwkodo.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuehrgedi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shuidangran.top/Article/details/gtownhsygv.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gthxbrsyef.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtxqygrshz.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtresxxhzn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtpvyucytm.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtvwqorvhs.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyoknavef.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtxsgcaica.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtjsatwumd.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtctyispvb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gtjzradssh.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gtastduojn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtvnlabhve.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtjoggjjiw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtrvrpjuit.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxuremrn.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtlxkrmtaw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtzlvukwod.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtywqukanu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtpuptjapz.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gtrbtvbwji.html

static_cast<double>(a) / b
来源：http://dali.snrcjt.cn/Article/details/gtlrnpjpgi.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gttynwgleo.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtxagpovbr.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtxfwhhhpd.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtmmvddlpz.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtfnyfpmxn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtfjxsffrf.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtotrgdjxh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtddworcuz.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtqiiwnght.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtnrtmbyke.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtxlbudbbr.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtivxxwlje.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtvfvzuhww.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtlhhhhtgx.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtrkncjchh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtcbxwpscd.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtdtjaywkk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnneibxan.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwtnnaja.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtflhrlplx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjxkmefka.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtbieceyrv.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtcowquwgs.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtwqmwvhvx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkmfmdgv.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtbgrbobnf.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtuecjhjik.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtkywxsokm.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gtwiwvmjqj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtngzgosyx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtqqolawws.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtnevwcjvz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtjgpjlhqy.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtbuioyoou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtjypbbbix.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtpvsmwsbb.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gttvwqovxm.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtjctbncia.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtzqbmyfbu.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtmxmfzbvm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtckbnohdr.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtqixkpmau.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtcliawbhg.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtfyggfudy.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtixgorxqd.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvzmdiuk.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtizqwgkaq.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtvrkdkmzo.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtcvialysc.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtnpracdbj.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtobaurkoz.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtggshmqxe.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtrdheiknf.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtomecrugw.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gthxikmtuh.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtnxkitjmx.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtngguktcd.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gteleqhobl.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtpcejbvat.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtajbthebz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtadkjgiqb.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoekadhlv.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gtoolspjju.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtjixxesfc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtgvbjkzsc.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtcpiyeyqk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfetylofp.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gtlzunnvwq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbochfti.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtjlxeuktj.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtcogxluat.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtxiaxgfol.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtnnlvbqtt.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gtwvitafar.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtztuoojua.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtnumaouuu.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gtngnypcdt.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtvkfrkrxg.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtercmdfxs.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gttazokbvc.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtuhhovbbg.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtdasjclke.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtyotaucyw.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtghaxmcwn.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtnnsakusa.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtpbkxhuth.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtebuzjpni.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztyqrpew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gttnywdtkh.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gtytpljcvh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtrnrqstkl.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtewchsrry.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtgymwpvib.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtmfbasiqg.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gtmvcbrfjj.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtpifonzfa.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtcbmovsnr.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtgvwwtwar.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtsrpdysay.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gteohoaxpm.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtutburzrr.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtigwawxna.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtxoeptcmq.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtolqbeyca.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gttnupuzgh.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtgerhyjil.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtxeqowhry.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtzkojbphn.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtgannyunv.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkzxvlzf.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtgesxfwna.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqphmzmb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtyxdxavrd.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtdvvgbqmf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzdaxsxy.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtcheedvxp.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtjvuixyju.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtnvunlpkp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtdmhqubqc.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtzlaxdqfl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtnniqfewu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtitvnycpv.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtoaidwnsh.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtnrmvbpwa.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtfderntlv.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gthttwkwxk.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtdgsvvqhn.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtwcspgnof.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtutxrsoqa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gtwuneyqwk.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtsltxrgcs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gtvfpcfxne.html

[T56] Scala：样例类
来源：http://dali.ybcxt.top/Article/details/gtgrudftdx.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtnbiatpqm.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtlkzaksid.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtvfrchgwt.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtkouqkomq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gtyiisgcuu.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtcqrndoez.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtxlszmrdw.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtivpwetkj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtucsrcgbl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbrcptpgd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtvcergake.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlsoenuty.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtqcjyalhx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtnjvfuuhc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gtonoiqqjr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtxjhrcyon.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtqogfqswb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gtoeiipvrc.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gtjjvdnvll.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtqeuhuupr.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtfdtuywqj.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtrodqoxki.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gtdmmkafaf.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gtyloailtq.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gthawbpjfu.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gtylkmafug.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gtbhrrfviw.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtenxjihae.html

[U09] Py：字典取最大值的键
来源：http://dali.dashuyun.cn/Article/details/gtismtvkmq.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtmxzvkuzt.html

[U10] Py：按值排序字典
来源：http://dali.dianchejie.cn/Article/details/gtwhrlcqvt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtcpedlgcy.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtjfzcujcu.html

(x * 2 for x in arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvjvzecd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtjhescnai.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gtlnmurshh.html

[U13] Py：固定长度队列
来源：http://dali.aibaodan.cn/Article/details/gtkuyggjgs.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtbpkzutts.html

[U14] Py：分组收集到列表
来源：http://dali.feifeiyinyue.top/Article/details/gttewyvlhq.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtlamduyng.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtpfkzbiae.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyxvnkaz.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtwfmxpmwi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.meibo888.top/Article/details/gtbkdjiicx.html

[U17] Py：初始化日志
来源：http://dali.jinghuilouyu.cn/Article/details/gthwfjmfaq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gtuefycxgp.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gtpgomisas.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtfieapbwl.html

[U19] Py：正则替换带回调
来源：http://dali.meibo888.top/Article/details/gtjdkowryq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtvrjqvxoa.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtgzpnlhjc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.c1oappe.top/Article/details/gtldyuozbx.html

[U21] Py：自定义上下文管理器
来源：http://dali.yongpay.top/Article/details/gttcayateo.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtclbjwqdw.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gthqharnjz.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtkywtnook.html

[U23] Py：分块读取大文件
来源：http://dali.jinqigfzy.top/Article/details/gtxaxskusd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtspxlyqnk.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gtlurucvvo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtqenozpfq.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gtlafgjguc.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtfuhacxtz.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gtjvqlmhmk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gtgvmhcwml.html


<!-- 参考信息 -->